# Praktikm&aring;l app
Appen skal være en hjælp til virksomhederne i dokumentation af deres opfyldelse af praktikmål under elevernes praktik tid.
# Funktionalitet
* Bruger skal kunne indgive en opgave
* For hver opgave skal man kunne tilknytte praktikmål

# Vær opmærksom på at alle filer i denne mappe er eksempler på programmering

# Opsætning af systemet
Alle dependencies og kørsler sker via yarn og ikke npm. 
Docker containere har en tendens til at få konflikter, når man bruger npm.

<br/>
Setup af fullstack website (Node-Express-React-MongoDB) 

Localhost:/8000 = Backend
Localhost:/3000 = Frontend

-Setup Frontend-

CD til frontend mappen i terminale 
npm i (for at download alt i json.package)
npm start (for at køre script til at starte backend)
npm build
npm test

-Setup Backend-

CD til Backend mappen i terminale 
npm i (for at download alt i json.package)
npm start (for at køre script til at starte backend)

-Ændring af PORT i Backend-

open .env og ænder port=8000 til en anden
efter det åben så app.js og ænder const port = process.env.PORT || 8000; til en anden port

-Testing-
for at testet backend funktioner brug postman (https://www.getpostman.com/)
for at se data/api i databasen brug Robo 3T (https://robomongo.org/)

 

# Links og inspiration

Tak til Mathias Bramstorp hvis projekt har inspireret det projekt
