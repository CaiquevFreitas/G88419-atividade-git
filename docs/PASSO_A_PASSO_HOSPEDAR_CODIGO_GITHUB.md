Passo a Passo para Hospedar o Código no GitHub

1. Criar um Repositório no GitHub
Acessar o GitHub:

Vá para o site do GitHub e faça login com sua conta.
Criar um Novo Repositório:

Clique no ícone de "+" no canto superior direito da página e selecione New repository.
Escolha um nome para o seu repositório. Você pode nomeá-lo de acordo com seu projeto (ex: meu-repositorio, projeto-git, etc.).
Não marque a opção Initialize this repository with a README, pois vamos adicionar o arquivo README mais tarde.
Escolha se o repositório será público ou privado:
Se for privado, lembre-se de adicionar o professor massilva como colaborador.
Clique em Create repository para criar o repositório vazio.

2. Conectar o Repositório Local ao GitHub
Copiar o URL do Repositório:

Após criar o repositório no GitHub, o GitHub vai exibir o link para o repositório remoto. Será algo assim:
arduino
Copiar
https://github.com/SEU_USUARIO/MEU_REPOSITORIO.git
Dica: Substitua SEU_USUARIO pelo seu nome de usuário no GitHub e MEU_REPOSITORIO pelo nome que você deu ao repositório.
Adicionar o Repositório Remoto no Terminal:

Abra o VSCode ou o terminal no diretório do seu repositório local (onde está o código que você deseja enviar para o GitHub).
Execute o comando para adicionar o repositório remoto:
bash
Copiar
git remote add origin https://github.com/SEU_USUARIO/MEU_REPOSITORIO.git
Verificar a Conexão Remota:

Para verificar se a conexão foi feita corretamente, execute o comando:
bash
Copiar
git remote -v

3. Realizar o Primeiro Commit
Adicionar os Arquivos ao Git:

Se você já tem os arquivos prontos no diretório do seu projeto, adicione-os ao repositório local com o comando:
bash
Copiar
git add .
Fazer o Commit das Alterações:

Agora, faça o commit para salvar as alterações localmente:
bash
Copiar
git commit -m "Primeiro commit - Adicionando os arquivos iniciais"

4. Subir o Código para o GitHub
Fazer o Push para o GitHub:

Após o commit, envie suas alterações para o repositório remoto no GitHub com o comando:
bash
Copiar
git push -u origin master
Nota: Se o seu repositório utiliza o branch main em vez de master (o que é comum para repositórios novos), o comando será:
bash
Copiar
git push -u origin main
Verificar no GitHub:

Após o comando push, acesse o seu repositório no GitHub e verifique se os arquivos foram carregados corretamente.

5. Compartilhar o Repositório com os Integrantes e o Professor
Repositório Público: Se o repositório for público, basta compartilhar o link do repositório com os membros da equipe e o professor.
Repositório Privado: Se o repositório for privado, será necessário adicionar os membros da equipe e o professor como colaboradores. Para isso:
Acesse as Configurações do repositório.
Selecione Manage access.
Clique em Invite a collaborator e adicione o usuário massilva.

6. Confirmar a Atualização e Compartilhar o Link
Após garantir que tudo foi feito corretamente no repositório GitHub, compartilhe o link do repositório no Classroom (ou conforme as instruções do professor).
Dicas Finais:
Commits pequenos e frequentes: Certifique-se de fazer commits pequenos para facilitar o acompanhamento das alterações.
Mensagens de commit: As mensagens de commit devem ser claras e descrever o que foi feito, como: "Adicionando arquivo README", "Corrigindo erro no código", etc.
Organize seu repositório: Quando necessário, crie pastas e organize os arquivos do seu projeto para facilitar a navegação.
