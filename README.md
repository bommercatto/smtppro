# Aschroder SMTPPro
v1.4.3


## Introdução

Módulo para envio dos emails do sistema com autenticação SMTP


## Instalação

###Usando Modgit (recomendado)

    modgit add aschroder_smtppro git@github.com:bommercatto/smtppro.git


## Configuração

Para configurar o módulo, basta acessar o painel de administração e ir em **Sistema** > **Configuração** > **Avançado** > **Sistema** e seguir os passos:


 - Na seção **SMTP Pro Email - Configurações Gerais**:

    - **Selecione a opção da extensão**: Habilita o módulo utilizando a opção selecionada

    - **Usar Endereço de Email da Loja para Reply-To**: O email da loja é utilizado no campo Reply-To dos emails

    - **Opções de Desenvolvimento**: Opções para testes de desenvolvimento

    - **Salvar log de todas as mensagens**: Salva todas os emails enviados no banco de dados, podendo ser acessado em Sistema > Ferramenta > Email Log

    - **Executar Teste**: Envia um email de teste para verificar as configurações


 - Na seção **SMTP Pro Email - Configurações Google Apps/Gmail** (Somente se for usar SMTP do Gmail):

    - **Endereço de Email**: Endereço de email de autenticação

    - **Senha**: Senha de autenticação


 - Na seção **SMTP Pro Email - Configurações SMTP** (Somente se for usar SMTP próprio)

    - **Autenticação**: Tipo da autenticação SMTP (Padrão: Entrar)

    - **Usuário**: Usuário de autenticação SMTP

    - **Senha**: Senha de autenticação SMTP

    - **Servidor**: Servidor SMTP

    - **Porta**: Porta do servidor SMTP (25 - Sem encriptação, 587 - TLS - 465 SSL)

    - **Segurança SSL**: Tipo de segurança do servidor SMTP (De acordo com a porta selecionada)


 - Na seção **SMTP Pro Email - Configurações Amazon SES** (Experimental. Somente se for usar SES da Amazon, também pode ser feito por SMTP comum):

    - **Chave de Acesso**: Chave de acesso fornecida pela Amazon

    - **Chave Secreta**: Chave secreta fornecida pela Amazon