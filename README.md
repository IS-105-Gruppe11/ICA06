Deltakere:

Erdvik, Magnus

Lie, Eva Kristine

Nguyen, Philip

Tellefsen, Erlend Frøysnes

Van Dijk, Richard

Younas, Osman



                                                  ICA06 - Gruppe 11
                                                  
                                                      Ekseperiment 1
                                                  
Sammenligne frekvensspektrum (finn formanter) når flere personer sier et ord (for
eksempel, “hjelp”). Forsøk å forklare eventuelle forskjeller i frekvensanalyse.
Hvordan hadde dere gått frem for å impelementere et system for gjenkjennelse av
språk? For eksempel, hva skulle man klassifisere på, - enkelte lyd, hele ord eller
hele setninger?

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

- Vi skulle også tenke på hvordan vi ville gått fram for å implementere et system for gjennkjennelse av språk.

- Vi tenker at den  beste måten hadde vært å gå for enkelte lydsegmenter, istedenfor hele ord eller setninger. Dette gjør at mest mulig data kan bli  lagret for et enkelt lydutslag.Dette vil gjøre databasen mer rik på detaljer og gjengjenningen av ord og setninger kan enklere bli tolket med større variasjon I uttalelsen. 

- Vi tenker at en algoritme må utvikles for å innhente mest mulig informasjon fra mange brukere, som kan lære av brukerne gjenkjenne mønsteret i hver uttalelse av bestemte ord. Dette kan da settes sammen til en rik database som må bli analysert,bearbeidet og testet grundig.

- Vi søkte rundt på nettet og fant ut at programmer bruker såkalte fonemer til å forstå hva du sier. Fonemer er kort fortalt det minste lydsegmentet som kan forandre meningen til et ord. Forkjelige språk har ulike fonemer, for eksempel norsk har rulle -r og skarre –r.  Så en annen måte kunne vært å lage en database med fonemer og sammenlignet dette med input og gitt hvilket språk det mest sannsynlig er, basert på hvilke fonemer som blir brukt. 


                                                          Ekseperiment 2

Lag din egen skytjeneste som generer lyd basert på tekst.

- Koden ligger i "server.go"

- For å kjøre tjenesten startes server.go i terminalen (go run server.go). I en nettleser skrives "localhost:8001/speech/hva du ønsker at tjenesten skal si" (eventuelt ip adressen istedenfor localhost om tjenesten blir kjørt på en annen maskin). 


                                                           Ekseperiment 3
                                                           
                                                           
