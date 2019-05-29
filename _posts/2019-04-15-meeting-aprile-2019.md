---
layout: post
title: GraalVM senza limiti
---

15 Aprile 2019

### GraalVM senza limiti: avviare Hibernate ORM in 5ms e con solo 15MB di memoria

GraalVM, noto anche come Substrate VM, rappresenta una rivoluzione nel
mondo Java.

Un tempo di avvio misurato in millisecondi abbinato ad un consumo di
memoria di pochi megabyte consentono di migliorare drasticamente
l'efficienza di microservizi basati su JVM, serverless, e anche
applicazioni tradizionali.

Ma non è facile passare a Substrate: le radicali scelte
architettoniche di questa nuova VM implicano sia vantaggi che forti
limitazioni; queste limitazioni spesso rendono incompatibili le
librerie più diffuse nella comunità Java, apparentemente vanificando
gli enormi investimenti sia nelle utilissime librarie esistenti, sia
il know-how sul loro utilizzo, per non parlare delle applicazioni su
di esse fondate.

Analizzeremo insieme queste limitazioni, quindi vedremo un esempio
reale di conversione: Hibernate ORM, preso come esempio di framework
non semplice da convertire, è stato adattato per beneficiare di
Substrate senza che alcuna limitazione abbia un impatto sul suo
utilizzo. Anzi, vedremo come il team Hibernate ha colto l’occasione
per migliorare ulteriormente la produttività di sviluppo.

Avremo una demo che purtroppo dura solo un paio di millisecondi. Forse
ve la potró mostrare più volte!


#### Speaker: Sanne Grinovero

Sanne cominciò la sua carriera in Italia come consulente specializzato
in Open Source Java, con un particolare interesse nelle performance,
sistemi scalabili, motori di ricerca ed accesso ai database. Oggi
lavora in R&D come Sr Principal Software Engineer presso Red Hat, ed è
meglio noto come leader del team Hibernate. Nel 2018 con alcuni
colleghi crea Quarkus. Ha vissuto nei Paesi Bassi, in Italia, nella
Repubblica Dominicana, in Chile, in Portogallo, e al momento dimora a
Londra.

[![Registrazione meeting](https://i.ytimg.com/vi/xfryfdlUNbo/hqdefault.jpg)](https://www.youtube.com/watch?v=xfryfdlUNbo)

#### Quando?

<u>15 Aprile 2019</u>

* 18:30 - Check-in
* 18:45 - Benvenuto e aggiornamenti
* 19:00 - **GraalVM senza limiti: avviare Hibernate ORM in 5ms e con solo 15MB di memoria**
* 21:00 - Pizza

#### Dove ?

Presso [Toolbox](/places/toolbox/).

#### Come faccio a partecipare ?

La partecipazione è aperta a tutti, previa *registrazione* (ci serve per sapere quanti saremo).

[Registratevi su meetup](https://www.meetup.com/JUGTorino/events/260366202/).

[Iscriviti](/subscribe/) alla mailing list del JUG Torino per venire a conoscenza degli eventi.

#### Posso avere un altro riferimento ?

La [mailing list](https://groups.yahoo.com/groups/it-torino-java-jug) è il riferimento principale,
la puoi consultare anche online se sei già iscritto.

Puoi contattare [Federico Fissore](/people/federicofissore/).
