# Mini Curso de Engenharia de Dados

### Para rodar a aplicação de ingestão faça:
- Faça download do dataset no link: https://dados.gov.br/dados/conjuntos-dados/vendas-do-tesouro-direto1
- Provisione o RDS PostgreSQL na AWS conforme abordado em aula.
- Crie um banco de dados, por exemplo: db
- Instale as bibliotecas usando o arquivo requirements.txt exemplo:
    `pip install -r /path/to/requirements.txt`
- Configure a aplicação app-ingestion.py com o nome da tabela a ser criada, exemplo: tb_venda_tesouro.
- Edite variável db_string com o endpoint do RDS na AWS.