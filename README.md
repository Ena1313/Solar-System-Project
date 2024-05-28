# Solar-System-Project
Projektni zadatak iz kolegija Vizualizacija Podataka FERIT

Projektni zadatak “Vizualizacija Sunčevog sustava” uključuje razvoj interaktivne vizualizacije Sunčevog sustava koristeći D3.js biblioteku za prikaz planeta i njihove orbite oko Sunca. Cilj je pružiti edukativni alat koji omogućava korisnicima da istraže karakteristike svakog planeta, te prati njihove orbitalne putanje kroz animaciju. Cilj je i prikazati realne udaljenosti, veličine i brzine vrtnje planeta oko Sunca, kao i usporedba njihovih različitih atributa putem stupčastih grafova.

## Prikupljanje Podataka
Podaci o planetama i njihovim satelitima su prikupljeni i pohranjeni u JSON formatu. Podaci uključuju informacije o svakom planetu, poput promjera, mase, udaljenosti od Sunca, orbitalnog perioda, itd.

## Dizajn i Vizualizacija
Dizajn vizualizacije je baziran na prikazu Sunca u centru, s planetama koje kruže oko njega po svojim orbitalnim putanjama. Svaka planeta je interaktivna i omogućava prikaz detaljnih informacija putem iskočnog prozora.

## Implementacija
Implementacija je obuhvatila korištenje D3.js za kreiranje SVG elemenata koji predstavljaju Sunce, planete i njihove orbite. Animacija kretanja planeta je postignuta pomoću JavaScript funkcija koje ažuriraju pozicije planeta u realnom vremenu.

## Izvješća o Provedenim Testovima i Rezultatima
Testiranje je obuhvatilo:
•	Provjeru ispravnosti prikaza planeta i njihovih orbita.
•	Testiranje interaktivnosti klikabilnih planeta.
•	Provjeru ispravnosti animacije kretanja planeta.
•	Testiranje funkcionalnosti zumiranja i pomicanja po prikazu.
•	Osiguranje pravilnog prikaza iskočnih prozora s informacijama o planetama.
•	Osiguranje pravilnog prikaza grafova

## Hijerarhija Projekta
•	index.html: Glavna HTML datoteka.
•	style.css: CSS datoteka za stilizaciju.
•	planetGraphs.js: JavaScript datoteka za grafove planeta.
•	moonGraphs.js: JavaScript datoteka za grafove mjeseca.
•	data/planetsDatabase.json: JSON datoteka s podacima o planetama.
•	images/: Direktorij s slikama planeta i Sunca.

## Popis Korištenih Tehnologija
•	HTML
•	CSS
•	JavaScript
•	D3.js
•	JSON
•	SVG

## Upute za Postavljanje
1.	Klonirajte repozitorij projekta na vaše računalo.
2.	Otvorite projekt u vašem omiljenom editoru koda.
3.	Otvorite index.html datoteku u web pregledniku (možda će biti potrebno koristiti Live Server radi pravilnog prikaza grafova)

## Upute za Korištenje
1.	Pokrenite index.html datoteku u web pregledniku.
2.	Koristite gumbe za zaustavljanje “Stop animation”, ponovno pokretanje “Start animation” i resetiranje animacije “Reset animation”.
3.	Kliknite na bilo koju planetu da biste vidjeli detaljne informacije o njoj.
4.	Koristite funkcionalnosti zumiranja i pomicanja za bolje pregledavanje sustava.
5.	Kliknite na gumbove za prikaz grafova o planetima i satelitima
6.	Sortirajte podatke za satellite uzlazno ili silazno klikom na “Sort Data”
