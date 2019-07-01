# Curso deComandos DML: Manipulação de dados com MySQL
![](https://www.alura.com.br/assets/api/share/curso-mysql-dml-manipulacao-de-dados.png)

> Conteúdo

#### :gem: Manipulação de dados
#### :gem: Entidades de banco de dados
#### :gem: Modelagem
#### :gem: Incluir dados por linha de comando, em lotes, de outros bancos.
#### :gem: Alterando dados de um banco ou em lotes.
#### :gem: Excluir dados.
#### :gem: Transações
#### :gem: Trigger


###  Modelagem do banco de dados
* Download e instalação do banco de dados Mysql e Mysql Workbench.(Developer Default).
* Criar o banco de dados e as entidades (Banco de dados, esquema, tabela).
* Entidade básica de um banco de dados é uma tabela.
* Uma tabela é semelhante a uma planilha de Excel.
* Campos são colunas e registros são as linhas.
* Chave primária uma ou mais colunas que não possuem registros repetidos.
* Chave estrangeira ligação entre campos de tabelas do mesmo tipo(tabela pai e tabela filho).
* Tabela filho tem que ter um registro associado na tabela pai.
* ÌndiceS facilitam a busca por elementos(Integridade Relacional) 
* No Mysql esquema = banco de dados.
* Views uma tabela lógica feita através de uma consulta.
* Consulta
* Stored Procedures - Programas estruturados para operações complexas (Não respeitam o padrão ANSI).
* Trigger são regras que são executadas quando algo é feito no banco.(Gatilhos).
* unsigned para não trabalhar com valores negativos.
* Tipo de dado float ou double, bit(binário)
* Zerofill Preenche com zeros os espaços.
* Auto_increment - Sequencia auto incrementada.
* out of range - Valores maiores que o tipo suporta.
* Campos de data (date,datetime,timestamp,time,year).
* Campos de string (char, varchar, binary, varbinary, blob, text).
* Enum - lista Pré definida.
* set e collate - Conjunto de caracteres - utf8.
* Spacial - (Geometry, point, lifestring,polygon).
* Projeto de banco de dados.
* Modelo Entidade Relacionamento(Análise de requisitos, modelagem)
* Modelo conceitual (Diagrama entidade e Relacionamento).
* Diagrama viram esquemas de tabelas.
* Ferramentas case facilitam a construção do banco.

### Criando a estrutura do banco de dados
* DBA o profissional responável por administrar o banco de dados.

### Incluindo dados nas tabelas.
* Aprendemos a incluir dados em uma tabela, através de comando;
* Vimos a inclusão de vários registros em um único comando;
* Foi mostrado como incluir dados na tabela através de um assistente;
* Mostramos como incluir dados usando um arquivo externo.

### Alterando e excluindo dados existentes nas tabelas
* Alterar e excluir dados de uma tabela, através de comando ou em lotes;
* Vimos que podemos alterar ou excluir todos os dados de uma tabela;
* O que é uma transação e como podemos desfazer modificações efetuadas anteriormente na base de dados.

###  Auto incremento, padrões e Triggers






