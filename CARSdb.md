## Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB_NAME: dealer

Table name: cars

- id | INT or BIGINT | PK(primary key) | AI (autoincrement) | U (unique) | NOTNULL |
- brand | NOTNULL | VARCHAR(10) |
- name | NOTNULL | VARCHAR(10) |
- model_year | NULL | YEAR
- power_unit_type | NOTNULL | VARCHAR(10) |
- fuel | NOTNULL | VARCHAR(8) 
- engine_capacity | NOTNULL |
- horsepower | NOTNULL | MEDIUMINT
- trunk_capacity | NOTNULL |
- gearbox | NOTNULL | VARCHAR(10)
- seat_number | NOTNULL | 
- drive_type (rear/front/AWD) | NOTNULL |



| id  | brand   | name | model_year | power_unit_type | fuel   | engine_capacity | horsepower | trunk_capacity | gearbox   | seat_number | drive_type |
| --- | ------- | ---- | ---------- | --------------- | ------ | --------------- | ---------- | -------------- | --------- | ----------- | ---------- |
| 1   | Peugeot | 308  | 2022       | termico         | diesel | 1.5 liter       | 130        | 450            | automatic | 5           | front      |
| 2   |         |
|     |         |