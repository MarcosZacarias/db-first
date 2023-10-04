| COLONNA             | TIPO        | ATTRIBUTI             |
| ------------------- | ----------- | --------------------- |
| id                  | bigInt      | PRIMARY KEY, A_I      |
| marca               | varchar(50) | NOT NULL              |
| modello             | varchar(50) | NOT NULL              |
| carburante          | varchar(50) | NOT NULL              |
| km                  | FLOAT(8,2)  | NULL, UNSINGNED       |
| cilindrata          | FLOAT(6,2)  | NULL, UNSINGNED       |
| data_produzione     | YEAR        | NOT NULL              |
| data_di_acquisto    | DATE        | NULL                  |
| data_di_vendita     | DATE        | NULL                  |
| condizioni          | TINYINT     | UNSINGNED,DEFAULT(10) |
| luogo_di_produzione | VARCHAR     | NOT NULL              |
| colore              | VARCHAR     | NULL                  |
| tipologia           | VARCHAR     | NULL                  |
| prezzo_vendita      | FLOAT(8,2)  | NULL, UNSINGNED       |
| prezzo_netto        | FLOAT(8,2)  | NULL, UNSINGNED       |
| prezzo_di_acquisto  | FLOAT(8,2)  | NOT NULL, UNSINGNED   |
| porte               | TINYINT(1)  | UNSINGNED             |
| posti               | TINYINT(2)  | UNSINGNED             |
| ricondizionata      | TINYINT(1)  | DEFAULT(0)            |
