# AUTO

| colonna           | tipo            | attributi                   |
| ----------------- | --------------- | --------------------------- |
| id                | BIGINT          | PRIMARY_KEY, AUTO_INCREMENT |
| targa             | CHAR(10)        | NOT NULL, UNIQUE            |
| modello           | VARCHAR(50)     | NOT NULL                    |
| marchio           | VARCHAR(50)     | NOT NULL                    |
| cilindrata        | SMALLINT        | NULL                        |
| cavalli           | SMALLINT        | NULL                        |
| porte             | TINYINT(1)      | NULL                        |
| proprietari       | TINYINT(1)      | NULL                        |
| condizione (A-Z)  | CHAR(1)         | NULL                        |
| chilometri        | MEDIUMINT       | NULL                        |
| tipologia         | VARCHAR(25)     | NOT NULL                    |
| garanzia          | BOOL/TINYINT(1) | NULL                        |
| inizio_produzione | DATE            | NULL                        |
| fine_produzione   | DATE            | NULL                        |
| data_arrivo       | DATE            | NOT NULL                    |
| trazione          | CHAR(3)         | NULL                        |
| prezzo            | FLOAT(7,2)      | NULL                        |
| posti             | TINYINT(1)      | NULL                        |
| peso              | SMALLINT        | NULL                        |
| alimentazione     | VARCHAR(10)     | NULL                        |
| cambio            | VARCHAR(10)     | NULL                        |
| marce             | TINYINT(1)      | NULL                        |
| omologazione      | VARCHAR(10)     | NULL                        |
| foto              | VARCHAR         | NULL                        |
| descrizione       | VARCHAR         | NULL                        |
