# Instalando o <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white"/>
- [Link com os downloads](https://git-scm.com/downloads)

## Alguns comandos mais utilizados do <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>

#### Configurar o Git:
- `git config`  é a função conveniente usada para definir valores de configuração do Git em projetos de nível global ou local.

- Configuração Local: 
~~~
git config --local [user.name](http://user.name) "Seu nome aqui"
~~~
~~~
git config --local user.email "Seu email aqui"
~~~

- Configuração Global:

~~~
git config --global user.name <Seu nome aqui>
~~~
~~~
git config --global user.email <Seu email aqui>
~~~

##
#### `git init` 
- Cria um novo repositório do Git.
- Ele pode ser usado para converter um projeto existente e não versionado em um repositório do Git ou inicializar um novo repositório vazio.
##
#### `git status`
- Comando utilizado para obter um resumo de quais arquivos têm alterações que são preparadas para o próximo commit.
##

#### `git clone`
- Utilizado para clonar um repositório local ou remoto.
##
#### `git add .`
- Adiciona modificações ou inclusões do arquivo no diretório local, preparando ele para ser entregue ao servidor remoto para a mesma aplicação que está sincronizada na máquina local.
##
#### `git commit -m "comentario"`
- Utilizado após o git add, serve para realizar um comentário em uma modificação ou inclusão feita.
- A flag -m indica que vamos adicionar uma mensagem para aquele commit.
##
#### `git push`
- Usado para enviar o conteúdo do repositório local para um repositório remoto.
##
#### `git pull`
- Usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais.
