# Tutorial de Instalação do Git no Windows

O Git é um sistema de controle de versão amplamente utilizado para rastrear alterações em arquivos e coordenar o trabalho entre várias pessoas. Este tutorial vai guiá-lo através do processo de instalação do Git no Windows.

## Passo 1: Baixar o Instalador do Git

1. **Acesse o site oficial do Git:**
   - Abra o seu navegador e vá para [https://git-scm.com/](https://git-scm.com/).

2. **Baixe o instalador:**
   - Na página inicial, você verá uma opção para baixar o Git para Windows. Clique no botão **"Download for Windows"**.
   - O download deve começar automaticamente. Se não iniciar, clique no link manualmente.

## Passo 2: Executar o Instalador

1. **Localize o instalador:**
   - Após o download, vá até a pasta onde o arquivo foi salvo.

2. **Execute o instalador:**
   - Dê um duplo clique no arquivo baixado para iniciar o processo de instalação.

## Passo 3: Configurar a Instalação

1. **Aceitar a Licença:**
   - Na primeira tela, leia a licença do Git e, se concordar, clique em **"Next"**.

2. **Escolher o Local de Instalação:**
   - Na próxima tela, você pode escolher o diretório onde o Git será instalado. O local padrão é geralmente adequado, mas você pode alterá-lo se necessário. Clique em **"Next"**.

3. **Selecionar Componentes:**
   - Na tela de seleção de componentes, você pode escolher quais componentes deseja instalar. Para a maioria dos usuários, as opções padrão são suficientes. Clique em **"Next"**.

4. **Escolher o Editor Padrão:**
   - Você será solicitado a escolher um editor de texto padrão para o Git. O padrão é o Vim, mas você pode escolher outro editor como o Notepad++ ou o Visual Studio Code. Clique em **"Next"**.

5. **Ajustar o PATH:**
   - Na tela de ajuste do PATH, escolha a opção **"Git from the command line and also from 3rd-party software"**. Isso permitirá que você use o Git tanto no terminal quanto em ferramentas de terceiros. Clique em **"Next"**.

6. **Escolher o Transporte HTTPS:**
   - Na tela de escolha do transporte HTTPS, selecione a opção **"Use the OpenSSL library"**. Isso permitirá que o Git use o protocolo HTTPS para se conectar a repositórios remotos. Clique em **"Next"**.

7. **Configurar o Final de Linha:**
   - Na tela de configuração do final de linha, escolha a opção **"Checkout Windows-style, commit Unix-style line endings"**. Isso é recomendado para a maioria dos usuários do Windows. Clique em **"Next"**.

8. **Configurar o Terminal:**
   - Na tela de configuração do terminal, escolha **"Use MinTTY (the default terminal of MSYS2)"**. Isso fornecerá uma experiência de terminal mais moderna. Clique em **"Next"**.

9. **Configurar Opções Extras:**
   - Na tela de opções extras, você pode deixar as opções padrão marcadas. Clique em **"Next"**.

10. **Instalar:**
    - Finalmente, clique em **"Install"** para iniciar a instalação. O processo pode levar alguns minutos.

## Passo 4: Verificar a Instalação

1. **Abrir o Git Bash:**
   - Após a instalação, você pode abrir o Git Bash clicando no ícone do Git Bash no menu Iniciar.

2. **Verificar a Versão do Git:**
   - No terminal do Git Bash, digite o seguinte comando para verificar se o Git foi instalado corretamente:
     ```bash
     git --version
     ```

## Passo 5: Configurar o Git

1. **Configurar o Nome e Email:**
   - Antes de começar a usar o Git, você deve configurar seu nome e endereço de email. No Git Bash, execute os seguintes comandos:
     ```bash
     git config --global user.name "Seu Nome"
     git config --global user.email "seu.email@example.com"
     ```

2. **Verificar as Configurações:**
   - Você pode verificar suas configurações com o seguinte comando:
     ```bash
     git config --list
     ```

## Conclusão

Parabéns! Você acabou de instalar e configurar o Git no seu sistema Windows. Agora você está pronto para começar a usar o Git para controlar versões dos seus projetos. Para aprender mais sobre como usar o Git, você pode consultar a documentação oficial ou tutoriais online.

Boa codificação! 🚀