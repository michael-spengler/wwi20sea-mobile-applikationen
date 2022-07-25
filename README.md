# Software Engineering Mobile Applications

## Lernziele
Nachdem in der Vorlesungsreihe [Webprogrammierung](https://github.com/michael-spengler/wwi20sea-web-programmierung) Grundlagen - im Hinblick auf Frontendentwicklung, Backendentwicklung und CICD - erkundet wurden, nutzen wir diese Vorlesungsreihe, um tiefer in die effiziente und skalierende Nutzung von Plattformen & Frameworks einzutauchen. 

Im diesem (5.) Semester fokussieren wir uns auf non-proprietäre Cross-Platform Ansätze.   
Im nächsten (6.) Semester beleuchten wir native (proprietäre) Ansätze und erkunden in welchen Kontexten diese möglicherweise weiterhin von Bedeutung sind.

[Cross-Platform vs. Native App Development](https://www.youtube.com/watch?v=Mq_HS-o-v6o)   


## Prüfungsleistungen
1. Gruppen- oder Einzel Referate   
2. Erstellung einer Mobile First Web Applikation (Chat, Event Finder oder NFT Platform) 

## Bewertungskriterien zur Mobile First Web Applikation
1. Funktioniert   
2. Bietet gute User Experience   
3. Ist sicher (inkl. Datenschutz, need to know prinzip etc. / Möglichst resistent gegenüber (D)DOS Attacks etc.)    
4. Zeigt hohe Codequalität (Separation of Concerns, High Cohesion, Loose Coupling, automatisierte Tests --> leichte Wartbarkeit...)   
5. Continuous Integration / Continuous Deployment ist sauber automatisiert   
6. Die Lernerfahrungen der einzelnen Gruppen wurden sauber dokumentiert (z.B. in einer learnings.md Datei)   
7. Die Technologieentscheidungen der einzelnen Gruppen wurden sauber dokumentiert (z.B. in einer technology-decisions.md Datei)   

## Vorlesungsgestaltung
Die erste Stunde jeder Vorlesung nutzen für die Erkundung wertvoller Kenntnisse und Fähigkeiten in der großen Runde. Hierbei geht es um theoretische Grundlagen, sowie um gegenseitige, gruppenübergreifende Unterstützung bei Herausforderungen und Lösungen. 

Danach arbeiten wir in Gruppen (3-6 Personen) an den einzelnen Projekten.

## Technologien
Die folgenden Technologien stehen in diesem Semester im Fokus:  
[Deno](https://deno.land)  
[Svelte](https://svelte.dev)  
[flutter](https://flutter.dev)  

## App Stores
[progressivewebapp.store](https://progressivewebapp.store/)  
[Android Playstore](https://play.google.com/store)  
[IOS Appstore](https://www.apple.com/app-store/)


## Curriculum ideas

1. Test Driven Development - Overview, Pros & Cons, [dealing with dependencies](http://xunitpatterns.com/Test%20Double.html), [philosophies](http://xunitpatterns.com/Philosophy%20Of%20Test%20Automation.html) <br>

2. Svelte introduction (how to use "any" js-Framework) [svelte kit](https://kit.svelte.dev/)<br>

3. Use Svelte with TDD <br>

4. CI-Pipeline via GitHub Actions <br>

5. What is Deno? <br>

6. How to use erc20 as a Backend

The approach would be to start with the abstract TDD concept and connect students' knowledge of web dev with svelte. <br>
Through that, they learn TDD on a new and innovative js-Framework and can create a basic web app. <br> Simulating a real-world project, this app gets published on any server (maybe of the professors) via GitHub Actions. <br> Talking about the problems with such CI-Pipelines and the dangers of an attacked server, we can have a look at erc20.
