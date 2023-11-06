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

1. `git init`: Inicialize um novo repositório Git.
   Exemplo:
   ```
   git init
   ```

2. `git clone <URL>`: Clone um repositório remoto para o seu computador.
   Exemplo:
   ```
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

3. `git add <arquivo>`: Adicione um arquivo ao índice (staging area) para ser commitado.
   Exemplo:
   ```
   git add arquivo.txt
   ```

4. `git commit -m "Mensagem do commit"`: Realize um commit com uma mensagem descritiva.
   Exemplo:
   ```
   git commit -m "Adiciona arquivo de exemplo"
   ```

5. `git status`: Exiba o status dos arquivos no repositório.
   Exemplo:
   ```
   git status
   ```

6. `git log`: Mostre o histórico de commits.
   Exemplo:
   ```
   git log
   ```

7. `git branch`: Liste todas as branches no repositório.
   Exemplo:
   ```
   git branch
   ```

8. `git branch <nome_da_branch>`: Crie uma nova branch.
   Exemplo:
   ```
   git branch nova-feature
   ```

9. `git checkout <nome_da_branch>`: Mude para a branch especificada.
   Exemplo:
   ```
   git checkout nova-feature
   ```

10. `git merge <nome_da_branch>`: Realize a mesclagem de uma branch em outra.
    Exemplo (estando na branch principal):
    ```
    git merge nova-feature
    ```

##  possiveis ERROS 403:

gerenciador de credenciais / credenciais do windows / remover quem estiver credenciado
