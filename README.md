# Esercizio DB University
Modellizzare la struttura delle entità di un database per memorizzare tutti i dati riguardanti una università:
- sono presenti diversi Dipartimenti (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);
- ogni Dipartimento offre più Corsi di Laurea (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc..)
- ogni Corso di Laurea prevede diversi Corsi (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);
- ogni Corso può essere tenuto da diversi Insegnanti;
- ogni Corso prevede più appelli d’Esame;
- ogni Studente è iscritto ad un solo Corso di Laurea;
- ogni Studente può iscriversi a più appelli di Esame;
- per ogni appello d’Esame a cui lo Studente ha partecipato, è necessario memorizzare il voto ottenuto, anche se non sufficiente.
<br>

Pensare a quali entità (tabelle) creare per il database e cercare di stabilirne le relazioni.<br>
Infine, andiamo a definire le colonne e i tipi di dato di ogni tabella.<br><br>

## Modello DB
![db-university](https://github.com/MatteoSanson/db-university/assets/128544980/6efb2f77-70db-455e-afee-f6b847b29d6c)