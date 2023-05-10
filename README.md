Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

# Database second hand cars

## Entity name: Car

## Table Name: cars

## Table columns:

- id | BIGINT, PK, AI, NN, UNIQUE, INDEX
- model | VARCHAR(100), NOTNULL, INDEX
- brand | VARCHAR(100), NULLABLE, INDEX
- year | YEAR, NULLABLE, INDEX
- acquisition_date | DATA, NULLABLE
- color | VARCHAR(20), NULLABLE, INDEX
- mileage | MEDIUMINT
- fuel_type | VARCHAR(100), DEFAULT(BENZ), INDEX
- engine-size | SMALLINT, NULLABLE
- car_change_type | VARCHAR(20)
- doors | VARCHAR(1)
- original_price | DECIMAL(9, 2), NULLABLE
- selling_price | DECIMAL (9, 2), NULLABLE
- fullname_of_seller | VARCHAR(200), NULLABLE
- condition | VARCHAR(10)
- GPS (boolean) | TINYINT(1) DEAFAULT (0)
- Parking sensors (boolean) | TINYINT(1) DEAFULT (0)
- Air condition (boolean ) | TINYINT(1)DEFAULT (1)
- Airbags (boolean) | TINYINT(1) DEFAULT (1)
- photo_path | VARCHAR(255), NULLABLE
- damages_notes | TEXT, NULLABLE
