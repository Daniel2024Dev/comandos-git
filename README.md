# comandos-git

1. **Configurando o Git**:
   - `git config --global user.name`: Define o nome de usuário global do Git.
   - `git config --global user.email`: Define o endereço de e-mail global do Git.
   - `git config --list`: Lista as configurações do Git.

2. **Criando um novo repositório**:
   - `echo "# " >> README.md`: Cria um novo arquivo README.md.
   - `git init`: Inicializa um novo repositório Git.
   - `git add README.md`: Adiciona o arquivo README.md ao índice.
   - `git add .`: Adiciona todos os arquivos ao índice.
   - `git commit -m "first commit"`: Confirma as alterações no repositório com uma mensagem.
   - `git branch -M main`: Renomeia a branch padrão para "main".
   - `git remote add origin https://github.com/...`: Adiciona um repositório remoto.
   - `git push -u origin main`: Empurra o repositório local para o repositório remoto no GitHub.

3. **Versionamento do código**:
   - `git add .`: Adiciona todas as alterações ao índice.
   - `git status`: Exibe o status das alterações.
   - `git commit -m "descrição"`: Confirma as alterações com uma mensagem.
   - `git push origin main`: Empurra as alterações confirmadas para o repositório remoto.

4. **Nova ramificação (branch)**:
   - `git checkout -b "nome_da_nova_branch"`: Cria e muda para uma nova branch.
   - `git add .`, `git status`, `git commit -m "descrição"`, `git push origin nome_branch`: Adiciona, confirma e empurra as alterações na nova branch.

5. **Alternando entre branches**:
   - `git checkout branch_desejada`: Muda para a branch desejada.

6. **Unindo uma branch com a branch principal (main)**:
   - `git checkout main`: Muda para a branch principal.
   - `git merge branch_desejada`: Mescla a branch desejada com a principal.
   - `git push origin main`: Empurra as alterações mescladas para o repositório remoto.

7. **Baixando código do GitHub**:
   - `git clone link do repositório`: Clona um repositório do GitHub para o diretório local.
   - `git pull`: Atualiza o repositório local com as alterações do repositório remoto.

8. **Enviar alteração feita**:
   - "Open pull request": No GitHub, abre um pull request para mesclar alterações em uma branch com outra.

