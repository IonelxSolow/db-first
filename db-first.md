Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Cosa consegnare:
- come visto in classe fai un file readme.md
- inserisci nome della tabella,
- inserisci le colonne per definire il modello
- assicurati di indicare la struttura dati da usare ed eventuali attributi per ciascuna colonna
PUSHA


## Tabella: auto_usate

## Table columns

| Colonna                 | Tipo dati              | Attributi
|-------------------------|------------------------|------------------------------------------
| id                      | INT                    | PRIMARY KEY, AUTO_INCREMENT, NOT NULL
| marca                   | VARCHAR(50)            | NOT NULL
| modello                 | VARCHAR(50)            | NOT NULL
| anno_immatricolazione   | YEAR                   | NOT NULL
| chilometraggio          | INT                    | NOT NULL
| carburante              | VARCHAR(20)            | NOT NULL
| cambio                  | VARCHAR(20)            | NOT NULL
| prezzo                  | DECIMAL(10,2)          | NOT NULL
| numero_porte            | TINYINT                | NOT NULL
| descrizione             | TEXT                   | NULL
| disponibilità           | TINYINT                | DEFAULT 1, NOT NULL
| data_inserzione         | DATETIME               | DEFAULT CURRENT_TIMESTAMP, NOT NULL
| proprietari             | TINYINT                | NOT NULL
| consumo_medio           | FLOAT(4,1)             | NULL
| categoria               | VARCHAR(20)            | NOT NULL

