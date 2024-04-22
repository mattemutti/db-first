# Descrizione

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB_NAME: rivenditore


table name: veicoli

- id						| INDEX		| INT o BIGINT | AI | NOTNULL | UNIQUE | PK
- n.telaio					| INDEX		| NOTNULLL 	| UNIQUE 
- targa						| VARCHAR(20)| NOTNULL 	| UNIQUE
- marca						| VARCHAR(30)| NOTNULL	
- modello					| VARCHAR(30)| NOTNULL
- note_modello
- prezzo
- anno di immatricolazione
- importazione
- categoria
- alimentazione
- alimentazione_aggiuntiva
- consumo_carburante
- classe_emissione
- chilometraggio
- potenza
- tipo cambio
- marce
- cilindrata
- n_cilindri
- posti
- porte
- ruote_motrici
- colore_vernice
- tipo_vernice
- peso
- materiale_interni
- colore_interni
- note_interni
- proprietari
- non_fumatori
- ultimo tagliando
- comfort
- intrattenimento_media
- sicurezza
- extra
- descrizione
- note