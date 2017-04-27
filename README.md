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

```$ git config --global user.name "Otávio Landim"```

```$ git config --global user.email otavio.landim@gmail.com```

#### Criando um arquivo .txt para versionarmos:

Antes de criarmos o arquivo, crie um diretório chamado ```help-git/``` com um arquivo ```help-git.txt```

Criando o diretório e o arquivo .txt (para criar o arquivo dentro do diretório, acesse-o com o comando ```cd help-git/```:

```$ mkdir help-git/```

```$ touch help-git.txt```

Edite o arquivo ```help-git.txt``` e adicione algum conteúdo:
Por exemplo: "Olá, GIT!"

#### Criando um repositório (local):

Acesse o diretório ```help-git/``` e digite o comando, pronto! (esse diretório agora é um repositório GIT):

``` $ git init ```

![Logo img git init](Macbook/Usuários/otaviolandim/Imagens/Captura de Tela 2017-04-19 às 08.30.58.png)

#### Rastreando arquivos:

O que aconteceu com o arquivo ```help-git.txt``` que tinhamos adicionado?

Você pode executar o comando ```$ git status``` e verificar a situação dos arquivos.

Para que o arquivo seja rastreado, devemos executar:

```$ git add <nome_do_arquivo>```

Ou seja:

```$ git add help-git.txt```

Caso, tenha mais de um arquivo no seu diretório para rastrear, basta executar o seguinte comando: ```$ git add .```

#### Gravando o arquivo (commit):

```$ git commit -m "Arquivo inicial"```

```-m``` : Caso não informe a opção -m, será aberto um editor de texto para informar.

#### Adicionando e gravando o arquivo:

Para adicionar e gravar (commit) em um único comando, basta digitar: 

```$ git commit -am "Mensagem do commit"```

```-a``` : Adiciona o arquivo (add) na área de stage.
```-m``` : Mensagem do commit.

#### Verificar histórico das alterações (repositório):

```$ git log```: Exibe o log de todos os commits.

```$ git log -n 2```: Exibe um resumo dos últimos 2 commits.

```$ git log --oneline```: Exibe um resumo do log de todos os commits.

```$ git log --stat```: Exibe um resumo dos arquivos alterados, mostrando a quantidade de linhas adicionadas e removidas. 

#### Exibir e revisar a modificaçao alterada:

```$ git diff```

#### Exibir as mudanças feitas de um commit até outro commit:

```$ git diff <id_commit_1>..<id_commit_2>```

Por exemplo:

```$ git diff <84237ce>..<8bb05de>```

#### Mover ou Renomear arquivos

```$ git mv teste1.html index.html```

#### Criando o repositório remoto (linha de comando):

```$ git init --bare help-git.git```

#### Listar repositório remoto:

```$ git remote -v```

#### Alterando o nome do repositório remoto:

```$ git remote rename <nome_antigo> <nome_atual>```

#### Alterando URL do repositório remoto:

```$ git remote set-url <nome_servidor> <nova_url>```

#### Enviando alteracoes para o repositório remoto:

```$ git push <nome_servidor> <branch>```

Por exemplo:

```$ git push origin master```

#### Apontando seu projeto: (GitHub)

```$ git remote add origin <url.git>```

 Por exemplo:

 ```$ git remote add origin https://github.com/otaviolandim/help-git.git```

#### Enviando as alterações para o repositório remoto:

```$ git push origin master```

#### Baixando um repositório (clone):
 
```$ git clone <nome_do_branch>```

Por exemplo:

```$ git clone https://github.com/otaviolandim/help-git.git/```
