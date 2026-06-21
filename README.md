## Comandos Git explicados

### git init
Cria um repositório Git na pasta atual.

### git status
Mostra o estado dos arquivos: modificados, adicionados ou pendentes.

### git add .
Adiciona todas as alterações para o próximo commit.

### git add nome-do-arquivo
Adiciona apenas um arquivo específico.

### git commit -m "mensagem"
Salva uma versão do projeto com uma mensagem explicando a mudança.

### git log
Mostra o histórico de commits.

### git remote -v
Mostra o repositório remoto conectado ao GitHub.

### git remote add origin LINK
Conecta seu projeto local ao repositório do GitHub.

### git branch
Lista as branches do projeto.

### git branch -M main
Renomeia a branch atual para `main`.

### git push -u origin main
Envia o projeto para o GitHub pela primeira vez.

### git push
Envia novos commits para o GitHub.

### git pull
Baixa atualizações do GitHub para seu computador.

### git clone LINK
Baixa um repositório do GitHub para seu computador.

### git checkout -b nome-da-branch
Cria e entra em uma nova branch.

### git switch -c nome-da-branch
Também cria e entra em uma nova branch.

### git checkout main
Volta para a branch `main`.

### git switch main
Também volta para a branch `main`.

### git merge nome-da-branch
Junta as alterações de uma branch na branch atual.

### git diff
Mostra exatamente o que foi alterado nos arquivos.

### git restore nome-do-arquivo
Desfaz alterações de um arquivo antes do commit.

### git reset
Remove arquivos da área de preparação, mas mantém as alterações.

### git reset --hard
Desfaz alterações e volta ao último commit. Use com cuidado.

### git rm nome-do-arquivo
Remove um arquivo do projeto e do Git.

### git mv antigo novo
Renomeia ou move um arquivo.

### git config --global user.name "Seu Nome"
Configura seu nome no Git.

### git config --global user.email "seuemail@email.com"
Configura seu e-mail no Git.

### git config --list
Mostra as configurações atuais do Git.