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
	Un dipartimento offre piu corsi, da consegna
	Un corso di Laurea sará offerto da un solo dipartimento, e a livello logico sará cosi per sempre (altrimenti sarebbe M:M)
===2===
Corsi di Laurea : Corsi			M:M
	... da consegna
	Ogni corso potrebbe appartenere a diversi corsi di laurea
	Esempio: Analisi Matematica 2 presente sia in matematica che Economia & stat.
===3===
Corsi di Laurea: Studenti		1:M
	Un corso di laurea avra molti studenti iscritti
	... da consegna
===4===
Corsi : Appelli d'Esame			1:M
	.. da consegna
	Ogni appello di esame si riferira ad uno specifico corso
===5===
Corsi : Insegnanti			M:M
	... da consegna
	Ogni insegnante potrebbe avere ruolo di insegnante di microeconomia in un corso e insegnante di macroeconomia in un altro.
===6===
Studenti : Appelli d'esame		M:M
	... da consegna
	Un appello di esame avra molti studenti registrati ad esso
---> in tabella ponte: Voto!