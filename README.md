# doc_git
documento com os primeiros comandos git

ERROS:

git config --global user.name "<seu_nome>" adiciona o seu nome no projeto
git config --global user.email "<seu_email>" adiciona o seu email no projeto



git init: ele inicia o arquivo "/.git" para controlar a pasta

git status: Responsavel por validar os arquivos modificados dentro do projeto.
(ele exibe os arquivos que não foram adicionados ao projeto)

git add: Responsavel por colocar o arquivo modificado em uma área segura
(adiciona os arquivos em vermelho que aparece no git status.)

git commit -n "<texto_da_modificação>": ele é responsavel por criar uma nova versão do projeto
com as referencias do criador.




Ctrl+L: limpa a tela do terminal.

git log: validar os mesus comentarios e modificacoes.

git checkout -b <nome_da_branch> : o "-b" cria uma nova branch

git checkout <nome_da_branch>: muda de branch

git branch: mostra as branchs existentes

git merge <nome_da_branch>: Adiciona a branch atual o conteudo de outra branch

gitk: exibe todas alterações feitas no projeto
