# Teste de Sql

Uma empresa no ramo alimentício tem a necessidade de armazenar em banco de dados as informações de seus processos seletivos e seus respectivos candidatos.

- Por ser uma empresa de nível nacional, a empresa possui diversas filiais pelo brasil inteiro. Todas as empresas do grupo deverão ser amazenadas com as seguintes informações: Razão Social, CNPJ, Estado, Cidade

- Todo mês são criadas vagas de emprego, essas vagas também deverão ser armazenadas. Cada vaga pertence à uma das empresas do grupo. 
As vagas deverão ser armazenadas com as seguintes informações: Título da Vaga, Data de Criação, Empresa, Status (Ativo ou Inativo).

- Cada candidato poderá participar de UMA ou MAIS vagas. Além disso também deverá ser armazenado a data de inscrição do candidato na vaga

- As informações que deverão ser armazenadas dos candidatos são: Nome, Email, Telefone, Data de Nascimento, Cidade e Estado 
 

Considerando o cenário hipotético acima, crie um banco de dados Mysql, crie alguns registros de teste para popular o banco, exporte toda a estrutura com o conteúdo inserido e adicione o arquivo .sql em seu projeto git.

Com o banco de dados criado você vai precisar escrever 3 consultas sql para gerar os seguintes relatórios:



- Relatório de todos os candidatos em ordem alfabética.
Campos: Nome, Email e Idade.

- Relatórios das vagas criadas nos últimos 6 meses, com a quantidade de candidatos que se inscreveram em cada uma. 
Campos: Título da Vaga, Data de Criação e Quantidade de Candidatos inscritos.

- Relatórios das vagas ativas de todas as empresas do estado do Rio de Janeiro
Campos: Título da Vaga, Nome da Empresa e Data de Criação da Vaga.
