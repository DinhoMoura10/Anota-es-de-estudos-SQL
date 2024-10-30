# SQL Study Repository

Este repositório contém scripts e exemplos para estudo de SQL.

## Conteúdo

- **Banco de Dados e Tabelas**
  - Criação e manipulação de bancos de dados e tabelas.
  - Definição de chaves primárias e estrangeiras.
  - Exemplo de tabelas autorelacionadas.

- **Inserções de Dados**
  - Exemplos de `INSERT` em massa.
  - Bulk insert usando arquivos de texto.

- **Consultas e Joins**
  - Exemplos de `SELECT` com `JOIN`.
  - Uso de `LEFT JOIN` para combinar tabelas.

- **Modificações de Dados**
  - Atualização e exclusão de registros.
  - Exemplos de `DELETE` onde campos são `NULL`.

- **Funções Agregadas**
  - Uso de `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`.
  

Exemplos de GROUP BY, HAVING.

sql

Copiar
SELECT Departamento, COUNT(*) FROM NomeDaTabela GROUP BY Departamento;
SELECT Departamento, AVG(Salario) FROM NomeDaTabela GROUP BY Departamento HAVING AVG(Salario) > 5000;
Transações

Exemplos de BEGIN TRANSACTION, COMMIT, ROLLBACK.

sql

Copiar
BEGIN TRANSACTION;
UPDATE NomeDaTabela SET Salario = Salario * 1.1 WHERE Departamento = 'TI';



