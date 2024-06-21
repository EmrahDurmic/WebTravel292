Za ovaj projektni zadatak uradio sam bekend i frontend
Projekat se sastoji iz dva dijela
-Client koji predstavlja frontend i je rađen koristeći React framework i
-Server koji prestavlja backend i rađen je koristeći Node.js
Za bazu podataka korištena je MongoDB
Projekat je izgrađen koristeći MERN stack

Koraci za pokretanje (backend):
-Otvoriti webtravel_292 folder u Visual Studio Code
-U jednom terminalu locirati se u folder server (cd server)
-Izvršiti komandu npm install" kako bi se instalirali svi potrebni dependency i paketi
-Kada se instalacija završi treba pokrenuti komandu npm start i tada bi nam se trebala spojiti baza podataka i dići server na port 3001

Za frontend:
-Lociramo se u folder client (cd client) i ponavljamo postupak instalacije dependency-a uz pomoć komande npm install
-Nakon instalacije pokrećemo komandu npm start koja pokreće naš frontend na portu 3001
http://localhost:3001 bi se trebao automatski pokrenuti, ali ako ne, dovoljno je ukucati ovaj navedeni path u browser

Baza podataka se spaja na moj MongoDB Atlas i podešena da se svi mogu spojiti 

NAPOMENA:
Kada se bude pokretao server, u slučaju da bude pisalo da je port već u upotrebi, slijediti ove korake:
-cd server
-ukucati u terminal taskkill /F /IM node.exe
-npm install
-npm start
Još jedna napomena: file .env se nije mogao prebaciti na github jer piše da je hidden ali u projektu je svakako sadržan.

Hvala!
