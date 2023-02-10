Vi chiediamo di immaginare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario!

| COLONNA                 | TYPE         | INDICE      | ATTRIBUTI                      |
| ----------------------- | ------------ | ----------- | ------------------------------ |
| ID                      | INT          | PRIMARY KAY | UNIQUE, AUTOINCEMENT, NOT NULL |
| TARGA                   | VARCHAR(6)   | ---         | NOT NULL                       |
| MARCA                   | VARCHAR(150) | ---         | NOT NULL                       |
| MODELLO                 | VARCHAR(150) | ---         | NOT NULL                       |
| ANNO PRODUZIONE         | SMALLINT     | ---         | NOT NULL                       |
| ANNO IMMATRICOLAZIONE   | SMALLINT     | ---         | NOT NULL                       |
| KM PERCORSI             | INT          | ---         | NOT NULL                       |
| ALIMENTAZIONE           | VARCHAR(50)  | ---         | NOT NULL                       |
| ACCESSORI E/O DOCUMENTI | VARCHAR(255) | ---         | NOT NULL, DEFAULT(0)           |
| NUMERO TELAIO           | VARCHAR(150) | ---         | NOT NULL                       |
| SEGNI PARTICOLARI       | VARCHAR(255) | ---         | NOT NULL, DEFAULT(0)           |
| COLORE                  | VARCHAR(150) | ---         | NULL                           |
| PAESE DI PROVENIENZA    | VARCHAR(50)  | ---         | NOT NULL                       |
