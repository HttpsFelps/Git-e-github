
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
|git remote add origin <link>|Conecta o diretório com um repositório git (origin é o nome padrão)|
|git status|Mostra os status do diretório git|
|git reflog|Mostra o históricocompleto de operações no repositório|
|git log|Mostra o histórico de commits|
|git restore|restaura as mudanças de um diretório git para o ultimo commit|
|git commit --amend -m|Edita a mensagem do ultimo commit|
|m -rf .git|Usar caso começar com o repositorio errado|

#### Git reset
Deixa as alterações em stage, ou seja, em preparação pro commit (git add)
```
$ git reset soft <id do commit>
```
Deixa as alterações apenas no diretório
```
$ git reset mixed <id do commit>
```
Apaga o commit inteiro
```
$ git reset hard <id do commit>
```
