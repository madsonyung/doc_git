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

##  `git init`: Inicialize um novo repositório Git.
   Exemplo:
   ```
   git init
   ```

##  `git clone <URL>`: Clone um repositório remoto para o seu computador.
   Exemplo:
   ```
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

##  `git add <arquivo>`: Adicione um arquivo ao índice (staging area) para ser commitado.
   Exemplo:
   ```
   git add arquivo.txt
   ```

##  `git commit -m "Mensagem do commit"`: Realize um commit com uma mensagem descritiva.
   Exemplo:
   ```
   git commit -m "Adiciona arquivo de exemplo"
   ```

##  `git status`: Exiba o status dos arquivos no repositório.
   Exemplo:
   ```
   git status
   ```

##  `git log`: Mostre o histórico de commits.
   Exemplo:
   ```
   git log
   ```

##  `git branch`: Liste todas as branches no repositório.
   Exemplo:
   ```
   git branch
   ```

##  `git branch <nome_da_branch>`: Crie uma nova branch.
   Exemplo:
   ```
   git branch nova-feature
   ```

##  `git checkout <nome_da_branch>`: Mude para a branch especificada.
   Exemplo:
   ```
   git checkout nova-feature
   ```

##  `git merge <nome_da_branch>`: Realize a mesclagem de uma branch em outra.
    Exemplo (estando na branch principal):
    ```
    git merge nova-feature
    ```

##  `git pull`: Puxa as alterações do repositório remoto para a branch atual.
   Exemplo (estando na branch principal):
   ```
   git pull origin master
   ```

##  `git push`: Envia commits locais para o repositório remoto.
   Exemplo (para enviar a branch atual para o repositório remoto):
   ```
   git push origin nome-da-branch
   ```

##  `git reset --hard HEAD~1`: Desfaz o último commit e descarta todas as alterações.
   Exemplo:
   ```
   git reset --hard HEAD~1
   ```

##  `git stash`: Armazena temporariamente as alterações não commitadas.
   Exemplo:
   ```
   git stash save "Trabalho em andamento"
   ```

##  `git stash pop`: Aplica as alterações do stash de volta ao diretório de trabalho.
   Exemplo:
   ```
   git stash pop
   ```

##  `git log --oneline --graph --decorate --all`: Mostra um histórico gráfico de todas as branches.
   Exemplo:
   ```
   git log --oneline --graph --decorate --all
   ```

##  `git clean -n`: Mostra quais arquivos não rastreados seriam removidos.
   Exemplo:
   ```
   git clean -n
   ```

##  `git clean -f`: Remove os arquivos não rastreados.
   Exemplo:
   ```
   git clean -f
   ```

##  possiveis ERROS 403:

gerenciador de credenciais / credenciais do windows / remover quem estiver credenciado
