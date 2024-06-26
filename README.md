
# DIO | Resumos de GIT e GITHUB

Repositório para armazenar resumos de GIT e GITHUB da plataforma de ensino [DIO](https://www.dio.me/)

## 📚 Documentação
- [Documentação GIT](https://git-scm.com/docs)
- [documentação GITHUB](https://docs.github.com/)

## 💻 Comandos do GIT

| Comando </>| Para que serve 🔍|
|---------|----------------|
|git inint|Transforma a pasta em um diretório git|
|git clone|Clona o repositório do github para um diretório|
|git add|adiciona para preparação do commit|
|git commit|Salva as alterações|
|git pull|Puxa as alterações do repositório remoto|
|git push|Empurra as alterações salvas do 'git commit'|
|git remote add origin "link"|Conecta o diretório com um repositório git (origin é o nome padrão)|
|git status|Mostra os status do diretório git|
|git reflog|Mostra o históricocompleto de operações no repositório|
|git log|Mostra o histórico de commits|
|git restore|restaura as mudanças de um diretório git para o ultimo commit|
|git commit --amend -m|Edita a mensagem do ultimo commit|
|git checkout -b "branch"|Cria outra branch|
|git checkout "branch"|Vai para a branch direcionada|
|git merge "branch"|Mescla a branch que estou com a sinalizada|
|git branch|Lista as branchs|
|git branch -v|Mostra o ultimo commit de cada branch|
|git branch -d "branch"|deleta a branch|
|git fetch|= git pull - git merge|
|git diff "branch" origin/"branch"|Ve as diferenças entre a branch de um diretório local com a de um repositório remoto|
|git clone "url do repo" --branch "branch" --single-branch|clona de um repositorio remoto apenas uma branch|
|m -rf .git|Usar caso começar com o repositorio errado|
#
### Git reset
Deixa as alterações em stage, ou seja, em preparação pro commit (git add)
```
$ git reset soft <id do commit>
```
#
Deixa as alterações apenas no diretório
```
$ git reset mixed <id do commit>
```
#
Apaga o commit inteiro
```
$ git reset hard <id do commit>
```
#

### Git stash
- Caso não acabei uma funcionalidade em uma branch e preciso arrumar outra sem commitar esta

Adiciona a lista stash as alterações fora do commit:
```
$ git stash
```
#
Lista a stash:
```
$ git stash list
```
#
Aplica ao codigo as modificações e continua armazenando no stash:
```
$ git stash apply
```
#
Aplica ao codigo as modificações e apaga do stash:
```
$ git pop
```