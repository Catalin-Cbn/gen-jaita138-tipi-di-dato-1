#### Database 1
##### Gestione di una biblioteca:
###### Libri:

| Attributi          | Java      | Database |
| ------------------ | --------- | -------- |
| immagine           | string    | VARCHAR  |
| titolo             | string    | VARCHAR  |
| autore             | string    | VARCHAR  |
| editore            | string    | VARCHAR  |
| serie              | string    | VARCHAR  |
| anno_pubblicazione | LocalDate | DATE     |
| formato            | string    | VARCHAR  |
| lingua             | string    | VARCHAR  |
| genere             | string    | VARCHAR  |
| isbn               | string    | VARCHAR  |
| licenza            | string    | VARCHAR  |
| descrizione        | string    | TEXT     |
| numero_pagine      | short     | SMALLINT |
| disponibilità      | boolean   | BIT      |
###### Membri:

| Attributi          | Java      | Database |
| ------------------ | --------- | -------- |
| nome               | string    | VARCHAR  |
| cognome            | string    | VARCHAR  |
| password           | string    | VARCHAR  |
| mail               | string    | VARCHAR  |
| data_registrazione | LocalDate | DATE     |
| prestiti           | short     | SMALLINT |
###### Prestiti:

| Attributi         | Java      | Database |
| ----------------- | --------- | -------- |
| titolo            | string    | VARCHAR  |
| isbn              | string    | VARCHAR  |
| codice            | string    | VARCHAR  |
| data_prestito     | LocalData | DATA     |
| scadenza_prestito | LocalData | DATA     |
| rinnovo_prestito  | LocalData | DATA     |
| scadenza_superata | boolean   | BIT      |
#### Database 2
##### Catalogo di un ristorante:
###### Piatti:

| Attributi      | Java    | Database |
| -------------- | ------- | -------- |
| nome           | string  | VARCHAR  |
| ingredienti    | string  | VARCHAR  |
| allergeni      | string  | VARCHAR  |
| vegetariano    | boolean | BIT      |
| vegano         | boolean | BIT      |
| piccante       | boolean | BIT      |
| numero_serviti | byte    | TINYINT  |
| codice_piatto  | string  | VARCHAR  |
| attesa_stimata | short   | SMALLINT |
| prezzo         | float   | DECIMAL  |
###### Ingredienti:

| Attributi     | Java      | Database |
| ------------- | --------- | -------- |
| surgelato     | boolean   | BIT      |
| nome          | string    | VARCHAR  |
| data_acquisto | LocalDate | DATA     |
| data_scadenza | LocalDate | DATA     |
| allergeni     | boolean   | BIT      |
| quantità      | short     | SMALLINT |
| costo_extra   | float     | DECIMAL  |
###### Clienti:

| Attributi    | Java   | Database |
| ------------ | ------ | -------- |
| nome         | string | VARCHAR  |
| numero_posti | short  | SMALLINT |
| conto        | short  | DECIMAL  |

#### Database 3
##### Catalogo di un negozio di fiori
###### Fiori

| Attributi        | Java    | Database |
| ---------------- | ------- | -------- |
| nome             | string  | VARCHAR  |
| caratteristica   | string  | TEXT     |
| descrizione      | string  | TEXT     |
| cura             | string  | TEXT     |
| temperatura      | short   | SMALLINT |
| prezzo           | int     | DECIMAL  |
| specie           | string  | VARCHAR  |
| significato      | string  | TEXT     |
| esposizione_sole | boolean | BIT      |
###### Fornitori

| Attributi      | Java   | Database |
| -------------- | ------ | -------- |
| nome           | string | VARCHAR  |
| località       | string | VARCHAR  |
| codice_fiscale | string | VARCHAR  |
###### Clienti

| Attributi      | Java   | Database |
| -------------- | ------ | -------- |
| nome           | string | VARCHAR  |
| cognome        | string | VARCHAR  |
| indirizzo      | string | VARCHAR  |
| mail           | string | VARCHAR  |
| numero_tel     | string | VARCHAR  |
| codice_cliente | string | VARCHAR  |
