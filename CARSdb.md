## Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB_NAME: dealer

Table name: cars

- id | INT or BIGINT | PK(primary key) | AI (autoincrement) | U (unique) | NOTNULL |
- brand | NOTNULL | VARCHAR(10) |
- name | NOTNULL | VARCHAR(10) |
- model year | NULL | YEAR
- power unit type | NOTNULL | VARCHAR(10) |
- fuel | NOTNULL | VARCHAR(8) 
- engine capacity | NOTNULL |
- horsepower | NOTNULL | MEDIUMINT
- trunk capacity | NOTNULL |
- gearbox | NOTNULL | VARCHAR(10)
- seat number | NOTNULL | 
- drive type (rear/front/AWD) | NOTNULL |



| id  | brand   | name | model year | power unit type | fuel   | engine capacity | horsepower | trunk capacity | gearbox   | seat number | drive type |
| --- | ------- | ---- | ---------- | --------------- | ------ | --------------- | ---------- | -------------- | --------- | ----------- | ---------- |
| 1   | Peugeot | 308  | 2022       | termico         | diesel | 1.5 liter       | 130        | 450            | automatic | 5           | front      |
| 2   |         |
|     |         |