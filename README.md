# Estudo-de-Logica-Com-Python.
Repositório de Estudo de Logica de Programação Com Python.

## Git e GitHub.

### Roteiro passo a passo: do básico ao avançado.

### Introdução.

### 1. Criando sua conta no GitHub.
    .Acesse github.com e clique em 'Sign up'.
    .Informe nome de usuário, e-mail válido e senha.
    .Confirme o e-mail cadastrado.
    .Acesse o painel inicial do GitHub.
[ x ] 1. Realizado com sucesso.

### 2. Configurando o Git no computador.
    .Baixe e instale Git em https://git-scm.com/downloads.
    .Configure o nome e e-mail no terminal:
    .`git config --global user.name 'Seu Nome'`
    .`git config --global user.email 'seuemail@exemplo.com'`
    .Verifique com `git --version`.
[ x ] 2. Realizado com sucesso.

### 3. Criando um repositório com README.
    .Clique em 'New Repository'.
    .Defina um nome (ex: meu-projeto).
    .Marque 'Add a README file'.
    .Clique em 'Create repository'.
[ x ] 3. Realizado com sucesso.

### 4. Clonando o repositório.
    .No repositório, clique em 'Code > HTTPS' e copie o link.
    .Crie uma pasta onde ira querer clonar o repositorio.
    .Abra a pasta com o terminal.
    .No terminal: `git clone https://github.com/usuario/meu-projeto.git`.
    .Para saber se relamente foi criado dar um "ls" ou "ls -l" ou "git status" ou "git remote -v".
    .Para abrir o editor no terminal;"code ."
[ x ] 4. Realizado com sucesso.

### 5. Editando o README.md.
    .O README.md é escrito em Markdown.
    .Edite pelo site (ícone ✏■) ou no VS Code.
    .Para abrir VS Code para edição basta apertar ( . ) do teclado tendo selecionado o repositorio desejado.
    .Ou abrindo pelo terminal basta estar com o terminal aberto na basta digitar "code .".
    .Exemplo de conteúdo: Meu Projeto Este é um projeto de exemplo. - Feito com ❤■.
[ x ] 5. Realizado com sucesso.

### 6. Trabalhando com Branches.
    .Criar nova branch: `git checkout -b minha-branch`.
    .Ver branches existentes: `git branch`.
    .Enviar branch: `git push -u origin minha-branch`.
[ x ] 6. Realizado com sucesso.

### 7. Pull Requests (PR).
    .Faça alterações em uma branch.
    .Envie para o GitHub.
    .Clique em 'Pull Request > New Pull Request'.
    .Descreva as mudanças e envie para revisão.
[ x ] 7. Realizado com sucesso.

### 8. Issues (relatar problemas).
    .Clique em 'Issues > New Issue'.
    .Descreva problema ou sugestão.
    .Adicione labels (bug, enhancement, etc.).
[ x ] 8. Realizado com sucesso.

### 9. Projetos (Kanban).
    .Clique em 'Projects > New Project'.
    .Organize tarefas em colunas (To Do, Doing, Done).
[ x ] 9. Realizado com sucesso.

### 10. Wiki.
    .Use a aba 'Wiki' para documentações maiores.
    .Clique em 'Create the first page'.
[ x ] 10. Realizado com sucesso.    

### 11. Convidar colaboradores.
    .Vá em 'Settings > Collaborators'.
    .Clique em 'Add people' e insira o usuário.
    .Defina permissões (read, write, admin).
[ x ] 11. Realizado com sucesso.

### 12. Segurança.
    .Use autenticação de 2 fatores (2FA).
    .Ative Dependabot para alertas de segurança.
    .Defina regras de proteção de branch.

### 13. Criando Tokens de Acesso.
    .Vá em 'Settings > Developer Settings > Personal Access Tokens'.
    .Clique em 'Generate new token'.
    .Defina permissões e copie o token gerado.

### 14. Commit e Push de Alterações.
    .Adicionar arquivos: `git add .`.
    .Salvar commit: `git commit -m 'mensagem'`.
    .Enviar para GitHub: `git push origin minha-branch`.

### 15. VS Code com Git/GitHub.
    .Instale Visual Studio Code.
    .Extensão recomendada: GitHub Pull Requests and Issues.
    .Gerencie commits, branches e PRs direto do editor.

### 16. GitHub Copilot.
    .Extensão paga que sugere código com IA.
    .Instale no VS Code.
    .Ajuda a acelerar a escrita de código.

### 17. Extensões Úteis.
    .GitLens → histórico detalhado de commits.
    .Prettier → formatação automática.
    .GitHub Actions → automação de deploy/testes.

### 18. Outras funções.
    .Fork → cópia de repositórios de terceiros.
    .Stars → marcar favoritos.
    .Releases → criar versões do projeto.
    .Actions → CI/CD.