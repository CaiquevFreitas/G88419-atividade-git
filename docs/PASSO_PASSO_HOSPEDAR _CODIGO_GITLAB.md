1. Criar uma conta no GitLab
Se ainda não tem uma conta, acesse GitLab e cadastre-se.

2. Criar um novo repositório (projeto)
Após fazer login, clique em "New project" (Novo projeto).
Escolha "Create blank project" (Criar projeto em branco).
Defina:
Project name: Nome do repositório.
Visibility: Se será público ou privado.
Clique em "Create project".

3. Instalar o Git (se necessário)
Se o Git não estiver instalado, instale:

Windows: Baixe aqui e instale.
Linux: Execute no terminal:
sh
Copiar
Editar
sudo apt install git  # Ubuntu/Debian
sudo dnf install git  # Fedora
sudo pacman -S git    # Arch
Mac: Instale com Homebrew:
sh
Copiar
Editar
brew install git

4. Configurar o Git no seu computador
No terminal, configure seu usuário:

sh
Copiar
Editar
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"