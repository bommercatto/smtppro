# Aschroder SMTPPro
v1.4.3


## Introdução

Módulo para envio dos emails do sistema com autenticação SMTP


## Instalação

###Usando Modgit (recomendado)

    modgit add aschroder_smtppro git@github.com:bommercatto/smtppro.git


## Configuração

Para configurar o módulo, basta acessar o painel de administração e ir em **Sistema** > **Configuração** > **Avançado** > **Sistema** e seguir os passos:


 - Na seção **SMTP Pro Email General Settings**:

    - **Choose extension option**: Habilita o módulo utilizando a opção selecionada

    - **Use Store Email Addresses for Reply-to**: O email da loja é utilizado no campo Reply-To dos emails

    - **Development Mode options**: Opções para testes de desenvolvimento

    - **Log all messages**: Salva todas os emails enviados no banco de dados, podendo ser acessado em Sistema > Ferramenta > Email Log

    - **Run Self Test**: Envia um email de teste para verificar as configurações


 - Na seção **SMTP Pro Email Google Apps/Gmail Settings** (Somente se for usar SMTP do Gmail):

    - **Endereço de Email**: Endereço de email de autenticação

    - **Senha**: Senha de autenticação


 - Na seção **SMTP Pro Email SMTP Settings** (Somente se for usar SMTP próprio)

    - **Authentication**: Tipo da autenticação SMTP (Padrão: Entrar)

    - **Login de Acesso**: Usuário de autenticação SMTP

    - **Senha**: Senha de autenticação SMTP

    - **Servidor**: Servidor SMTP

    - **Porta**: Porta do servidor SMTP (25 - Sem encriptação, 587 - TLS - 465 SSL)

    - **SSL Security**: Tipo de segurança do servidor SMTP (De acordo com a porta selecionada)


 - Na seção **SMTP Pro Email Amazon SES Settings** (Somente se for usar SES da Amazon, também pode ser feito por SMTP comum):

    - **Access Key**: Chave de acesso fornecida pela Amazon

    - **Secret Key**: Chave secreta fornecida pela Amazon