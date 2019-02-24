Start med:

    npm i g ionic

Når du kloner projektet - vær opmærksom på parent-folderen - en galt installeret node_modules fra tidligere kan fucke det hele op
Lav en helt ny Ionic-Projects - folder og klon til den

    npm i

Bemærk @ionic/lab - der giver dig en browser med noget der er tæt på både en iphone og en android (DET er ret fedt :-)

kør så ionic lab (ionic = CLI´et)

Du får 2 url´er - en til almindelig web og en til lab-siden (den med de to browserbaserede emulatorer)

Hvis ikke projektet virker, flyt det så til en folder langt langt væk fra tidligere node apps....

Projektet viser et http kald til omdbapi - et gratis movie-api
En listevisning og en detalje-side