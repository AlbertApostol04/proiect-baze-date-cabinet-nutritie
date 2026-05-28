# Proiect Baze de Date - Cabinet de Nutritie

Acest repository contine proiectul realizat la disciplina **Baze de Date**, avand ca tema proiectarea si implementarea unei baze de date relationale pentru gestionarea unui cabinet de nutritie.

## Descriere proiect

Proiectul modeleaza activitatea unui cabinet de nutritie si permite gestionarea informatiilor despre pacienti, nutritionisti, consultatii, planuri alimentare, plati si afectiuni medicale.

Baza de date permite urmarirea istoricului pacientilor, a consultatiilor efectuate, a planurilor alimentare recomandate si a situatiei platilor.

## Entitati principale

Modelul bazei de date contine urmatoarele tabele:

* `PACIENT`
* `NUTRITIONIST`
* `CONSULTATIE`
* `PLAN_ALIMENTAR`
* `PLATA`
* `AFECTIUNE`
* `PACIENT_AFECTIUNE`

Tabelul `PACIENT_AFECTIUNE` este tabel asociativ si modeleaza relatia multi-la-multi dintre pacienti si afectiuni.

## Functionalitati implementate

Proiectul include:

* descrierea modelului real;
* definirea entitatilor si a relatiilor dintre acestea;
* stabilirea cheilor primare si a cheilor straine;
* constrangeri de tip `NOT NULL`, `UNIQUE` si `CHECK`;
* normalizare pana la forma normala 3;
* creare de secventa pentru generarea automata a cheii primare;
* creare de tabele in Oracle SQL;
* inserare de date coerente in tabele;
* interogari SQL complexe;
* subcereri sincronizate si nesincronizate;
* grupari, functii de grup si filtrare cu `HAVING`;
* functii `NVL` si `DECODE`;
* expresii `CASE`;
* clauza `WITH`;
* operatii de actualizare si stergere folosind subcereri.

## Cerinte acoperite

Proiectul acopera cerintele 1-13:

1. descrierea modelului real;
2. prezentarea constrangerilor;
3. descrierea entitatilor;
4. descrierea relatiilor si cardinalitatilor;
5. descrierea atributelor;
6. diagrama entitate-relatie;
7. diagrama conceptuala;
8. scheme relationale;
9. normalizare FN1-FN3;
10. creare secventa;
11. creare tabele si inserare date;
12. cinci cereri SQL complexe;
13. actualizari si stergeri cu subcereri.

## Tehnologii folosite

* Oracle Database
* Oracle SQL Developer
* SQL
* Microsoft Word

## Fisiere

* `proiect-baze-date-cabinet-nutritie.docx` - documentatia completa a proiectului;
* `proiect-baze-date-cabinet-nutritie.pdf` - versiunea PDF pentru vizualizare rapida, daca este adaugata in repository.

## Autor

**Apostol Albert-Marian**

