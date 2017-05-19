Deltakere:

Erdvik, Magnus

Lie, Eva Kristine

Nguyen, Philip

Tellefsen, Erlend Frøysnes

Van Dijk, Richard

Younas, Osman



                                                  ICA06 - Gruppe 11
                                                      Eksperiment 1:
                                                  
  
![](https://raw.github.com/IS-105-Gruppe11/ICA06/master/bilder/hjelpErlend.png "Hjelp Erlend")
Erlend: Hjelp


![](https://raw.github.com/IS-105-Gruppe11/ICA06/master/bilder/hjelpOsman.png "Hjelp Osman")

Osman: Hjelp


![](https://raw.github.com/IS-105-Gruppe11/ICA06/master/bilder/hjelpMagnus.png "Hjelp Magnus")
Magnus: Hjelp


![](https://raw.github.com/IS-105-Gruppe11/ICA06/master/bilder/hjelpPhillip.png "Hjelp Phillip")

Phillip: Hjelp


![](https://raw.github.com/IS-105-Gruppe11/ICA06/master/bilder/hjelpRichard.png "Hjelp Richard")
Richard: Hjelp


![](https://raw.github.com/IS-105-Gruppe11/ICA06/master/bilder/hjelpEva.png "Hjelp Eva")
Eva: Hjelp  

I den første oppgaven skulle vi sammenligne frekvensspektrummet til medlemmene av gruppen. 
De røde linjene danner det som kalles formantlinjer og defineres som "det frekvens områdetet hvor vokal lyder er på sitt 
mest karakteristiske". Utifra bildene kan man se at formantlinje 1 og 2, som vil si de lave frekvensene, er relativt like,
men forskjellen blir større på de høye frekvensene. Vi tror dette kan ha med vokalen "e" som blir brukt i ordet "hjelp" ligger
i de lavere frekvensene, derfor er det ikke store forandringer mellom oss på hvordan vi utaller fonemen "e". Bildet nummer 6 
er en jente stemme og vi la merke til at det var mer prikker på de høyere frekvensene. 

Hvordan hadde dere gått frem for å implementere et system for å gjennskjennelse av språk? 
Vi tenker at den beste måten hadde vært å gå for enkelte lydsegmenter, istedenfor hele ord eller setninger. 
Dette gjør at mest mulig data kan bli lagret for et enkelt lydutslag. Dette vil gjøre databasen mer rik på detaljer
og gjengjenningen av ord og setninger kan enklere bli tolket med større variasjon I uttalelsen.

Vi tenker at en algoritme må utvikles for å innhente mest mulig informasjon fra mange brukere, som kan lære av brukerne 
gjenkjenne mønsteret i hver uttalelse av bestemte ord. Dette kan da settes sammen til en rik database som må bli analysert,
bearbeidet og testet grundig.

Vi søkte rundt på nettet og fant ut at programmer bruker såkalte fonemer til å forstå hva du sier. 
Fonemer er kort fortalt det minste lydsegmentet som kan forandre meningen til et ord. Forkjelige språk har ulike fonemer,
for eksempel norsk har rulle -r og skarre –r.  Så en annen måte kunne vært å lage en database med fonemer og sammenlignet 
dette med input og gitt hvilket språk det mest sannsynlig er, basert på hvilke fonemer som blir brukt. 

                                                    Eksperiment 2:
                                                    
I eksperiment 2 skulle vi lage en egen skytjeneste som genererer lyd basert på tekst.

- Koden ligger i "server.go"

- For å sette i gang tjenesten kjøres server.go i en terminal (go run server.go). I en nettleser skriver man "localhost:8001/speech/Hva du vil at tjenesten skal si". Man kan eventuelt bytte ut localhost med ip adressen til maskinen om tjenesten blir kjørt på en annen maskin. 

                                                    Eksperiment 3:
            
Forsøkte å bruke eksempel 1 som var gspeech, men fikk det ikke til å fungere. Fulgte instruksene fra denne repositoryen
https://github.com/amsehili/gspeech-rec og videre informasjon fra blogg av samme person
https://aminesehili.wordpress.com/2015/02/08/on-the-use-of-googles-speech-recognition-api-version-2/ men greide ikke finne ut hva
problemet var. Jeg bytta api key med en jeg skaffet fra Google Cloud speech api uten lykke. Virker som jeg fikk sendt flac filen til
google, men fikk tilbake "Google was unable to recognize any speech in the audio data". Er veldig sikker på at jeg har riktig format på
flac filen som er mono, 16000 hertz og ikke lengre en 15 sekunder. Tror problemet kan være at jeg ikke lastet ned SOX på riktig sted,
men fant ingen instrukser på hvor det skulle være så la den i git/Ming64/bin hvor jeg la wget som fungerte. 
