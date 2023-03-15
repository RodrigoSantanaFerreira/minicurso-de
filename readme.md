# Mini Curso de Engenharia de Dados

### Para rodar a aplicação de ingestão faça:
- Navegue até o diretório **ingestion**
- Faça download do dataset no link: https://dados.gov.br/dados/conjuntos-dados/vendas-do-tesouro-direto1
- Provisione o RDS PostgreSQL na AWS conforme abordado em aula.
- Crie um banco de dados, por exemplo: db
- Instale as bibliotecas usando o arquivo requirements.txt exemplo:
    <code> pip install -r requirements.txt<code>
- Configure a aplicação app-ingestion.py com o nome da tabela a ser criada, exemplo: tb_venda_tesouro.
- Edite variável db_string com o endpoint do RDS na AWS.