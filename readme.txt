CONSEGNA
========
- sono presenti diversi Dipartimenti (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);

- ogni Dipartimento offre più Corsi di Laurea (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc..)

- ogni Corso di Laurea prevede diversi Corsi (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);;

- ogni Corso può essere tenuto da diversi Insegnanti;

- ogni Corso prevede più appelli d’Esame;

- ogni Studente è iscritto ad un solo Corso di Laurea;
- ogni Studente può iscriversi a più appelli di Esame;
- per ogni appello d’Esame a cui lo Studente ha partecipato, è necessario memorizzare il voto ottenuto, anche se non sufficiente
========

RELAZIONI: 
===1===
Dipartimenti : Corsi di Laurea		1:M
===2===
Corsi di Laurea : Corsi			1:M
===3===
Corsi di Laurea: Studenti		1:M
===4===
Corsi : Appelli d'Esame			1:M
===5===
Corsi : Insegnanti			M:M
===6===
Studenti : Appelli d'esame		M:M
---> in tabella ponte: Voto singolo esame.
