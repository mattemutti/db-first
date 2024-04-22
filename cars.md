# Descrizione

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB_NAME: rivenditore


table name: veicoli

- id						| INDEX		| INT o BIGINT | AI | NOTNULL | UNIQUE | PK
- n.telaio					| INDEX		| NOTNULLL 	| UNIQUE 
- targa						| VARCHAR(20)| NOTNULL 	| UNIQUE
- marca						| VARCHAR(30)| NOTNULL	
- modello					| VARCHAR(30)| NOTNULL
- note_modello				| VARCHAR(255)| NULL
- prezzo					| DECIMAL(9, 2)| NOTNULL |
- anno di immatricolazione	| TIMESTAMP(YYYY-MM) | NOTNULL | DEFAULT8('Da immatricolare')
- importazione				| VARCHAR (30) | NULL | DEFAULT('Italiana')
- categoria					| VARCHAR(30) 	| NULL
- alimentazione				| VARCHAR(30) 	| NOTNULL 
- alimentazione_aggiuntiva	| VARCHAR(30) 	| NULL
- consumo_carburante		| VARCHAR(20)	| NULL 
- classe_emissione			| VARCHAR(20)	| NULL 
- chilometraggio			| MEDIUMINT		| NOTNULL
- potenza					| SMALL			| NOTNULL
- tipo cambio				| VARCHART(20)	| NULL
- marce						| TINYINT		| NULL
- cilindrata				| MEDIUMINT		| NULL
- n_cilindri				| TINYINT		| NULL
- posti						| TINYINT		| NULL
- porte						| TINYINT		| NULL
- ruote_motrici				| TINYINT		| NULL
- colore_vernice			| VARCHAR(30) 	| NULL
- tipo_vernice				| VARCHAR(100) 	| NULL
- peso						| SMALL			| NULL
- materiale_interni			| VARCHAR(100) 	| NULL
- colore_interni			| VARCHAR(30) 	| NULL
- note_interni				| TINYINT		| NULL
- proprietari				| TINYINT		| NULL
- non_fumatori				| TINYINT		| NULL
- ultimo tagliando			| DATE			| NOTNULL	| DEFAULT('Nessun tagliando')
- comfort					| TEXT			| NULL
- intrattenimento_media		| TEXT			| NULL
- sicurezza					| TEXT			| NULL
- extra						| TEXT			| NULL
- descrizione				| MEDIUMTEXT	| NULL
- note						| MEDIUMTEXT	| NULL