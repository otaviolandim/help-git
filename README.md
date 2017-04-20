# Git, help-me! :)

#### Instalando e configurando o Git:

#### Windows:
https://git-for-windows.github.io/

#### Mac:
https://code.google.com/archive/p/git-osx-installer/downloads

#### Linux: 
https://git-scm.com/download/linux

#### Configurações básicas:

Para configurar seu nome e e-mail no Git, execute os comandos abaixo:

```
$ git config --global user.name "Otávio Landim"
$ git config --global user.email otavio.landim@gmail.com

```
#### Criando um arquivo .txt para versionarmos:

Antes de criarmos o arquivo, crie um diretório chamado ```help-git/``` com um arquivo ```help-git.txt```

Criando o diretório e o arquivo .txt (para criar o arquivo dentro do diretório, acesse-o com o comando ```cd help-git/```:

```
$ mkdir help-git/
$ touch help-git.txt

```
Edite o arquivo ```help-git.txt``` e adicione algum conteúdo:
Por exemplo: "Olá, GIT!"

#### Criando um repositório (local):

Acesse o diretório ```help-git/``` e digite o comando, pronto! (esse diretório agora é um repositório GIT):

```
$ git init
 
```

#### Rastreando arquivos:

O que aconteceu com o arquivo ```help-git.txt``` que tinhamos adicionado?

Você pode executar o comando ```$ git status``` e verificar a situação dos arquivos.

#### Clonando um repositório:
 
```
$ git clone <NOME_DO_BRANCH>

```
