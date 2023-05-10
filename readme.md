## Entity name: Car 

## Table name: Cars

## Table columns:

- id | BIGINT , PK, AI, NOTNULL, UNIQUE, INDEX
- chassis number | TINYINT, NOTNULL, UNIQUE, INDEX
- license plate | VARCHAR(10), UNIQUE, NOTNULL
- car manufacturer |  VARCHAR(30), NULLABLE, INDEX
- model | VARCHAR(20), NULLABLE
- engine | VARCHAR(10), NULLABLE
- fuel | VARCHAR(10), NULLABLE, INDEX
- price | INT, NULLABLE, INDEX
- year | YEAR, NULLABLE
- car images | VARCHAR(300), NULLABLE
- car kms | INT, NULLABLE, INDEX
- seller | VARCHAR(15), NULLABLE
- year of listing | YEAR, NOTNULL
- listing title | VARCHAR(40), NOTNULL
- car body | VARCHAR(10), NULLABLE
- gear type| VARCHAR(10), NULLABLE
- seat number | TINYINT , NULLABLE
- doors number | TINYINT, NULLABLE
- power | VARCHAR(30), NULLABLE
- engine size | VARCHAR(10), NULLABLE
- cilinder | TINYINT, NULLABLE    