Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

# Database second hand cars

## Entity name: Car

## Table Name: cars

## Table columns:

- id | BIGINT, PK, AI, NN, UNIQUE, INDEX
- model | VARCHAR(100), NOTNULL, INDEX
- brand | VARCHAR(100), NULL, INDEX
- year | YEAR, NULL, INDEX
- acquisition_date | DATA, NULL
- color | VARCHAR(20), NULL, INDEX
- mileage | MEDIUMINT
- fuel_type | VARCHAR(100), DEFAULT(BENZ), INDEX
- engine-size | SMALLINT, NULL
- car_change_type | VARCHAR(20)
- doors | VARCHAR(1)
- original_price | DECIMAL(9, 2), NULL
- selling_price | DECIMAL (9, 2), NULL
- fullname_of_seller | VARCHAR(200), NULL
- condition | VARCHAR(10)
- GPS (boolean) | TINYINT(1) DEAFAULT (0)
- Parking sensors (boolean) | TINYINT(1) DEAFULT (0)
- Air condition (boolean ) | TINYINT(1)DEFAULT (1)
- Airbags (boolean) | TINYINT(1) DEFAULT (1)
- photo_path | VARCHAR(255), NULL
- damages_notes | TEXT, NULL
