# Praktikm&aring;l app
Appen skal være en hjælp til virksomhederne i dokumentation af deres opfyldelse af praktikmål under elevernes praktik tid.
# Funktionalitet
* Bruger skal kunne indgive en opgave
* For hver opgave skal man kunne tilknytte praktikmål
* Oversigt over opgaver
* Profil side for brugeren
* Profil side for virksomheden

**Vær opmærksom på at alle filer i denne mappe er eksempler på programmering**

# Opsætning af systemet
Alle dependencies og kørsler sker via yarn og ikke npm.<br/>
Docker containere har en tendens til at få konflikter, når man bruger npm.<br/>

## Setup af fullstack website (Node-Express-React-MongoDB) 
Localhost:/8000 = Backend<br/>
Localhost:/3000 = Frontend<br/>

## Setup Frontend
CD til frontend mappen i terminalen<br/>

yarn start (for at køre script til at starte backend)<br/>
yarn build<br/>
yarn test<br/>

## Setup Backend-

CD til Backend mappen i terminale<br/>
npm i (for at download alt i json.package)<br/>
npm start (for at køre script til at starte backend)

## Ændring af PORT i Backend-

open .env og ænder port=8000 til en anden<br/>
efter det åben så app.js og ænder const port = process.env.PORT || 8000; til en anden port

## Testing-
for at testet backend funktioner brug postman (https://www.getpostman.com/)
for at se data/api i databasen brug Robo 3T (https://robomongo.org/)

 

# Links og inspiration

Tak til Mathias Bramstorp hvis projekt har inspireret det projekt
