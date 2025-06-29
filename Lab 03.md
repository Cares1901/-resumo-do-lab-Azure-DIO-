# Lab 03 - Instância de Banco de Dados na Azure

Para criar um novo banco de dados para a sua instância no portal do Azure, siga estas etapas:

1. Serviços >> Instância Gerenciada de SQL >> criar.
2. Defina Assinatura, nome do grupo de recursos, região. 
3. Após o preenchimento e escolha dos campos obrigatórios, basta revisar e criar.

4. Criar uma Instância de Azure SQL Database
No portal, busque por “SQL Database” na barra de pesquisa.
Clique em “+ Criar” ou “Criar SQL Database”.

5. Defina os campos: nome do banco de dados, servidor, computação+armazenamento, segurança.

# Computação + Armazenamento
Plano padrão: Uso geral ou Desenvolvimento/Teste - Servidorless para economizar custo (paga por uso).

# Segurança
Pode deixar o Azure Defender para SQL desativado se for ambiente de teste.
Pode habilitar Autenticação do Active Directory para ambiente de produção.

6. Clique em Revisar + Criar >> Aguarde a validação >> Criar.

7. Acessar e Configurar o Servidor de Banco
Após a criação: Ir para o recurso >> Configurações do servidor >> Firewalls e redes virtuais >>
Adicionar o seu IP atual >> Salvar.

A configuração 7, Serve para acessar o banco de dados.
