# Database: Used Cars

## Table: available_cars

- id SMALLINT PK AI NOTNULL UNIQUE
- manufacturer VARCHAR(50) NOTNULL
- model VARCHAR(50) NOTNULL
- fuel VARCHAR(30) NOTNULL
- engine VARCHAR(50) NOTNULL
- kw SMALLINT NULL
- gearshift VARCHAR(70) NULL 
- year YEAR NOTNULL
- km MEDIUMINT NULL
- price DECIMAL(9,2) NOTNULL
- colour VARCHAR(70) NULL 
- next_car_inspection DATE NULL
- warranty TEXT NOTNULL
- door_number TINYINT NULL
- seat_number TINYINT NULL
- optionals TEXT NULL
- photobook_url VARCHAR(255) UNIQUE NULL

