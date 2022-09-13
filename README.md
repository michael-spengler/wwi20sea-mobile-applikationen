# Technologische Aspekte in der Entwicklung mobiler Applikationen
W3WI_SE432.1  

## Prüfungsleistungen
1. Gruppen- oder Einzel Referate   
2. Erstellung einer Mobile First Web Applikation (Chat, Event Finder, Tweet Platform oder NFT Platform) 

## Lernziele
Nachdem in der Vorlesungsreihe [Webprogrammierung](https://github.com/michael-spengler/wwi20sea-web-programmierung) Grundlagen - im Hinblick auf Frontendentwicklung, Backendentwicklung und CICD - erkundet wurden, nutzen wir diese Vorlesungsreihe, um tiefer in die effiziente und skalierende Nutzung von Plattformen, Frameworks und Vorgehensmodellen einzutauchen. 

Im diesem (5.) Semester fokussieren wir uns auf non-proprietäre Cross-Platform Ansätze.   
Im nächsten (6.) Semester beleuchten wir native (proprietäre) Ansätze und erkunden in welchen Kontexten diese möglicherweise weiterhin von Bedeutung sind - [Cross-Platform vs. Native App Development](https://www.youtube.com/watch?v=Mq_HS-o-v6o).  

#### Technologien
Die folgenden Technologien stehen in diesem Semester im Fokus:  
[Deno](https://deno.land)    
[Svelte](https://svelte.dev) using [snel](https://deno.land/x/snel) in order to reuse deno modules like [svelte_map](https://deno.land/x/svelte_map) - [see also latest changes...](https://www.youtube.com/watch?v=LMTfzyVJIXs)    
[flutter](https://flutter.dev)    
[GitHub Actions for CI/CD](https://github.com/features/actions)     
Ethereum oder Polygon als Platform / Backend --> Solidity  

##### Abwägungen / Trade-Offs
**Deno vs. NodeJS als Backend Laufzeitumgebung / RTE**

Mögliche Challenge bei Nutzung von Deno: Finden wir stets passende libraries / module? 
Falls es ein Modul in https://deno.land/x noch nicht gibt, eine passende library allerdings via npmjs.com bereit stünde, können wir grundsätzlich 
https://cdn.skypack.dev nutzen. Falls dies nicht funktioniert (weil der code der library oder einer ihrer dependencies noch nicht deno ready ist), empfehle ich, dass wir entweder die library deno ready machen (selbst ein deno modul dazu veröffentlichen - gerne auch feedback zu [diesen beispielen](https://github.com/michael-spengler/deno-modules-monitoring) geben).


**Backend Optionen**
1. deno (weil state of the art wenn es um zentrale backends geht)
2. polygon (weil günstig in sachen transaction fees wenn es um dezentrale backends geht + polygon = ethereum kompatible plattform) 


#### Vorgehensmodelle
Nachdem jede Gruppe ein [Value Proposition Canvas](https://www.youtube.com/watch?v=ReM1uqmVfP0) und eine User Story Map für ihre zu bauende Mobile First Web App angefertigt hat, nutzen wir [Test Driven Development](http://xunitpatterns.com/Philosophy%20Of%20Test%20Automation.html) mit dem [Outside-In](http://xunitpatterns.com/Philosophy%20Of%20Test%20Automation.html) Ansatz als Vorgehensmodell.  

Hierbei erkunden wir wie die Notwendigkeit für einen passenden [Umgang mit Dependencies](http://xunitpatterns.com/Test%20Double.html) zu einer hohen Code Qualität im Hinblich auf Separation of Concerns, High Cohesion, Loose Coupling... beiträgt. 


## Bewertungskriterien zur Mobile First Web Applikation
1. Ein repräsentatives [Value Proposition Canvas](https://www.youtube.com/watch?v=ReM1uqmVfP0&t=3s) wurde angefertigt   
2. Die User Stories sind klar dokumentiert   
3. Die App funktioniert performant und fehlerfrei    
4. Die App bietet eine gute User Experience (mit wenigen "clicks" ... zum gewünschten Ergebnis...)       
5. Die App ist sicher (Datenschutz, need to know prinzip etc. / Möglichst resistent gegenüber (D)DOS Attacks etc.)     
6. Hohe Codequalität (Separation of Concerns, High Cohesion, Loose Coupling, [automatisierte Tests](https://medium.com/remix-ide/solidity-unit-testing-using-remix-tests-part-1-bc10ab1be864) --> leichte Wartbarkeit...)    
7. Continuous Integration / Continuous Deployment ist sauber automatisiert (z.B. via GitHub Actions)      
8. Die Lernerfahrungen der einzelnen Gruppen wurden sauber dokumentiert (z.B. in einer learnings.md Datei)    
9. Die Technologieentscheidungen der einzelnen Gruppen wurden sauber dokumentiert (z.B. in einer technology-decisions.md Datei)     
10. Jedes Teammitglied hat erfolgreich zum Projekt beigetragen (e.g. erkennbar an der Commit Historie...)  

## Vorlesungsgestaltung
Die erste Stunde jeder Vorlesung nutzen für die Erkundung wertvoller Kenntnisse und Fähigkeiten in der großen Runde. Hierbei geht es um theoretische Grundlagen, sowie um gegenseitige, gruppenübergreifende Unterstützung bei Herausforderungen und Lösungen. 

Danach arbeiten wir in Gruppen (3-6 Personen) an den einzelnen Projekten.

## App Stores
[progressivewebapp.store](https://progressivewebapp.store/)  
[Android Playstore](https://play.google.com/store)  
[IOS Appstore](https://www.apple.com/app-store/)


## Feedback & Questions
In case of Feedback and Questions you can always contact me via [telegram](https://t.me/danceplanner) or [twitter](https://twitter.com/Peer2peerE).
