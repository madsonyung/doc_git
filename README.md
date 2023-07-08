# COMANDOS GIT
## documentação dos primeiros comandos do git visto em sala de aula

## ERROS:
erro de usuário

## adicionar o seu nome no projeto
````
git config --global user.name "<seu_nome>" 

````
##  adicionar o seu email no projeto
````
git config --global user.email "<seu_email>"

````
##  ele inicia o arquivo "/.git" para controlar a pasta
````
git init:
````
##  Responsavel por validar os arquivos modificados dentro do projeto.
##  ele mostra os arquivos modificados em vermelho
##  ele mostra os arquivos adicionados em verde pelo "git add"
##  (ele exibe os arquivos que não foram adicionados ao projeto)
````
git status: 
````
##  Responsavel por colocar o arquivo modificado em uma área segura
##  (adiciona os arquivos em vermelho que aparece no git status.)
````
git add: 
````
##  ele é responsavel por criar uma nova versão do projeto
##  com as referencias do criador.
````
git commit -n "<texto_da_modificação>": 
````

 ##  limpa a tela do terminal.
````
Ctrl+L:
````
 ##  validar os meus comentarios e modificacoes.
````
git log:
````
##   o "-b" cria uma nova branch
````
git checkout -b <nome_da_branch> :
````
##  muda de branch
````
git checkout <nome_da_branch>: 
````
##  mostra as branchs existentes
````
git branch: 
````
##   Adiciona a branch atual o conteudo de outra branch
````
git merge <nome_da_branch>:
````
## deleta uma branch existente
git branch - d <nome_da_branch>
##  exibe todas alterações feitas no projeto
````
gitk: 
````
##   baixa todo o projeto do repositorio para sua maquina.
````
git clone "url repositorio" :
````
##  sobe todas as alterações para o github.
````
git push: 
````
##   ele puxa as alterações do repositorio.
````
git pull:

````

##  possiveis ERROS 403:

gerenciador de credenciais / credenciais do windows / remover quem estiver credenciado
