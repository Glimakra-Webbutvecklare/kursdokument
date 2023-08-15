---
title: Glimåka Webbutvecklare - Kursdokument
authors: Henry Bergström, Anders Sjunnesson

---

# Webbutvecklare - Kursdokument

## Programöversikt
I kursen Webbutvecklare lär du dig hur programmering för webben. Ett hanterk där skisser i logik, struktur och design blir körbara applikationer. Tydligt fokus i kursen är att skapa versionshanterad kod av hög kvalité, att programmera utan och med ramverk och att designa funktionella och tillgängliga användargränssnitt. Ett övergripande mål med kursen är att göra dig redo för att ta dig an utmaningar i en framtida roll som webbprogammerare som anställd, eller frilans.  

### Hur du kommer lära dig
Kursen Webbutvecklare baseras på olika moduler. Varje modul inleds med 2-3 veckors föreläsningar, varvat med mindre övningsuppgifter. Till varje modul finns en större inlämningsuppgift – ett *case*. Ett case beskriver en applikation som du ska utveckla. I beskrivningen finns angivna ramar, grundläggande krav och valbara utmaningar. Case syftar till att du ska visa vad du har lärt dig under en modul. Ett case där du har antagit en eller flera utmaningar, kan bli en del av en framtida portfolio. 

Det finns möjlighet till handledning under modulperioder. I rollen som framtida programmerare bör du tycka om att lösa problem och att felsöka kod på egen hand.

De flesta case är individuella inlämningsuppgifter. Några moduler innebär att du arbetar i ett case tillsammans med andra.

Redovisning av case sker ca en arbetsvecka innan en modul avslutas. Case är obligatoriska och bedöms som *Godkänt*, eller *Komplettering krävs*.
I arbetsveckan efter redovisning finns möjlighet att förbereda sig för nästa modul, att på egen hand förbättra funktionalitet i en applikation, eller eventuellt komplettera för att nå *Godkänt* kursmoment.

Under de två åren som kursen pågår finns sammanlagt 12 case, 3 per termin. En ny modul baseras på kunskaper du inhämtat från tidigare moduler. Det innebär att du som kursdeltagare behöver vara i fas med studier för att tillgodogöra dig kursinnehållet. Kursdeltagare som behöver komplettera mer än en modul kommer erfarenhetsmässigt få svårt att fullfölja kursen. 

### Vad du kommer lära dig
Unders kursen kommer du att hantera en mängd olika verktyg, och nå färdigheter inom olika områden.

**Verktyg**
1.	Visual Studio Code (editor)
2.	Webbutvecklarverktyg i browsers (Chrome, Edge, Firefox mfl)
3.	Git och GitHub (versionshantering)
4.	Unix terminalen / WSL2 (bash)
5.	Docker (virtualisering)
6.	Insomnia (API klient)
7.	Wordpress (blog & CMS)
8.	Jekyll (static site generator)
9.	MySQL Workbench (databashantering)
10.	Figma (design och prototype)
11.	Trello (projekthantering)

**Förståelse och färdigheter - webbprogrammering**
1.	Bygga enkla statiska webbsidor
2.	Skapa tillgängliga webbsidor med struktur och innehåll
3.	Utforma responsiv layout för webben
4.	Bygga interaktiva dynamiska webbsidor
5.	Kunna samarbeta och versionshantera mjukvaruprojekt med Git
6.	Hantera en virtuell server för att publicera webbapplikationer
7.	Använda etablerade grafiska verktyg
8.	Förstå och redogöra för grundläggande termer inom webbprogrammering
9.	Strukturera och dokumentera kod, följa kodstandarder
10.	Skapa objektorienterad kod
11.	Skapa webbapplikationer för realtidskommunikation
12.	Använda dokumentationsresurser för att lösa problem
13.	Hantera kommunikation baserat på API resurser
14.	Kunna bygga ett eget REST API med Node.js
15.	Använda ramverket React för att bygga en modern Single Page Application (SPA)
16.	Använda olika tekniker för backend, som ex *routes, modules, password hashing, templating engine, sessions, cookies*
17.	Kunskap i hur man bygger en egen CRUD applikation för att hämta, lägga till, förändra och ta bort data
18. Hantera data från fil och databas 
19.	Kommunicera tekniska problem och lösningar med personer utan teknisk kompetens
20.	Planera och tidsuppskatta arbete 
21.	Arbeta enskilt och i team för att utveckla en applikation


**Förståelse och färdigheter - webbdesign**
1.	Applicera grundläggande principer i grafisk formgivning
2.	Förstå och kommunicera varumärken, använda designspråk med olika webbtjänster
3.	Planera och skissa gränssnitt, omsätta skisser till digital prototyp och färdig applikation
4.	Kunna applicera specifika designprinciper för webben


**Programspråk & Ramverk**
1.	Markdown
2.	HTML5
3.	CSS / Sass
4.	JavaScript
5.	JSON
6.	Node.js
7.	Express
8.	React.js
9.	MongoDB
10.	SQL/MySQL
11.	PHP
12.	TypeScript


## Modulöversikt
**OBS:** Angivna moduler och veckor kan komma att justeras.

| Modulnummer | Modulnamn                      | Beskrivning                                                                                            | Period | Case         | ~ veckor    | 
| ----------- | ------------------------------ | ------------------------------------------------------------------------------------------------------ | ------ | ------------ | ----------- |
| 1           | HTML och Git                   | HTML är webbens språk för struktur och innehåll. Grundläggande versionshantering med GitHub. *Design:* Grafisk Formgivning - Grund            | HT:1   | individuellt | 6 (v34-v39) |
| 2           | Grundläggande CSS              | Webbdesign och responsiv layout. Lär dig begrepp som *box model*, *media queries* och *mobile first*.  | HT:2   | individuellt | 6 (v40-v46) |
| 3           | Grundläggande Javascript       | Introduktion till JavaScript som programspråk, hantera Document Object Model (DOM).                    | HT:3   | individuellt | 6 (v47-v51) |
| 4           | Fortsättning JavaScript        | Asynkron kod med JavaScript, hämta data från API:er, läs data med filformaten JSON och XML.            | VT:1   | individuellt | 6 (v2-v7)   |
| 5           | Hosting, CMS och Wordpress     | Introduktion till webbservrar och publiceringssystem, static site generators och Wordpress.            | VT:2   | grupp        | 6 (v9-v13)  |
| 6           | Backend PHP                 | Bygg en applikation som kan spara data som en fil, och använd API för att hämta data.                  | VT:3   | individuellt | 6 (v16-v23) |
| 7           | Frontend med ramverk           | Lär dig hur man bygger en Single Page Application med ramverket React. *Design:* Micro-animtioner och usability                               | HT:1   | individuellt | 6 (v34-v39) |          
| 8           | Spel och websockets            | Skapa en canvasbaserad applikation med websocket för kommunikation i realtid - multiplayer. *Design:* PixelArt och Sprite Animation             | HT:2   | individuellt | 6 (v40-v46) |
| 9           | Fullstack NodeJS              | Bygg en fullstack webbapplikation med inloggning och resurs. Använd en molnbaserad MongoDB databas.    | HT:3   | individuellt | 6 (v47-v51) |
| 10          | Arbeta i team                  | Jobba tillsammans i ett projekt mot extern kund. Planera och utför arbete enligt Scrum.                | VT:1   | grupp        | 6 (v2-v7)   |
| 11          | Fullstack PHP                  | Skapa en webbapplikation med PHP. Lagra data i relationsdatabasen MySQL. Sökmotoroptimering. *Design:* CSS-Ramverk (Bootstrap)          | VT:2   | ind / grupp  | 6 (v9-v13)  |
| 12          | Examensprojekt                 | Använd dina kunskaper och skapa en webbapplikation utifrån dina egna idéer.                            | VT:3   | ind / grupp  | 6 (v16-v23) |


---

### 1. HTML och Git

**Verktyg**: 
- Visual Studio Code
- Git (GitHub)
- Unix terminalen

**Förståelse och färdigheter**: 
- Bygga enkla statiska webbsidor med fokus på struktur, innehåll och tillgänglighet
- Validera kod
- Versionhantera med Git

**Programspråk och ramverk**: 
- HTML
- Markdown

**Design**: 
- Grundläggande kunskaper i Grafisk Formgivning: Bl a Layout, Typografering, Färglära etc.

#### Beskrivning
Modulen har ett fokus på att förstå grundläggande verktyg och språk för webben. I modulen använder du editorn Visual Studio Code. Lär dig att starta projekt, anpassa editorn, namnge filer och mappar och skapa kod som kan valideras korrekt. Vidare får du en genomgång av HTML5 och hur man väljer rätt element för struktur och innehåll. Validering av formulärfält via inbyggda funktioner. Med Git lär du dig grundläggande versionshantering. I modulen kommer du även se hur webbsidor kan publiceras med GitHub pages. Vi går igenom grundläggande bildhantering och hur man använder olika mediaresurser på en webbsida.


#### Case
En individuell uppgift utifrån givna ramar där du ska skapa några olika webbsidor.  

---
### 2. Grundläggande CSS

**Verktyg**: 
- Visual Studio Code
- Git (GitHub)

**Förståelse och färdigheter**: 
- Bygga webbsidor med HTML och CSS
- Versionhantera mjukvaruprojekt med Git
- Utforma responsiv layout med fokus på *mobile first*
- Använda grundläggande principer i grafisk formgivning för webben

**Programspråk och ramverk**: 
- HTML
- CSS

#### Beskrivning
I modulen kommer du att bygga vidare på det innehåll som du arbetade med i första modulen. CSS skapar möjlighet att formge struktur och innehåll. Lär dig att använda olika selektorer för formgivning av webbsidor. Introduktion till responsiv layout. Lär dig begrepp som *box model*, *media queries* och *mobile first*. 

#### Case
En individuell uppgift utifrån givna ramar där du ska designa flera webbsidor. 

---
### 3. Grundläggande Javascript

**Verktyg**: 
- Visual Studio Code
- Git (GitHub)

**Förståelse och färdigheter**: 
- Förstå grunder i programspråket JavaScript 
- Bygga dynamiska webbsidor med HTML, CSS och JavaScript 
- Versionshantera mjukvaruprojekt med Git
- Kunna redogöra innebörden för grundläggande programmeringstermer

**Programspråk och ramverk**: 
- HTML
- CSS
- JavaScript

#### Beskrivning
Under modulen kommer du att lära dig grunderna i programspråket JavaScript. Du kommer att få hantera datatyper, villkor, kontrollstrukturer, händelselyssnare och upptäcka hur du med DOM (Document Object Model) kan skapa en dynamisk webbsida. Du kommer också att få en förståelse för grundläggande principer i grafisk formgivning för webben, och applicera dina idéer. Med modulen som grund, kommer du vara redo att fortsätta din utbildning inom webbutprogrammering.

#### Case
En individuell uppgift utifrån givna ramar där du ska skapa en enkel applikation med händelselyssnare för dynamsikt innehåll. 

---
### 4. Fortsättning JavaScript

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Insomnia

**Förståelse och färdigheter**: 
- Bygga mer avancerade dynamiska webbsidor 
- Versionhantera mjukvaruprojekt med Git
- Förstå hur asynkron kod skapar förutsättningar för en applikation
- Förståelse hur du hämtar data från ett API
- Använda olika metoder för att hantera arrayer och objekt
- Skapa egna funktioner för att rendera data

**Programspråk och ramverk**: 
- HTML
- CSS
- JavaScript
- JSON / XML

#### Beskrivning
I modulen kommer du att få en förståelse för vad synkron och asynkron kod är. Du kommer att få lära dig inbyggda objekt i JavaScript som Promise och Fetch. I olika praktiska övningar kommer du att få lära dig analysera och hämta data baserat på formatet JSON. Iterationer av arrayer och objekt, använda inbyggda och egna metoder för att välja ut och presentera data.

#### Case
En individuell uppgift utifrån givna ramar där du ska skapa en applikation som presenterar ett dynamiskt innehåll.  

---
### 5. Hosting och Wordpress

**Verktyg**: 
- Visual Studio Code
- Versionhantera och samarbeta kring mjukvaruprojekt med Git (GitHub)
- Unix terminalen
- Wordpress
- Static site generator Jekyll

**Förståelse och färdigheter**: 
- Hantera en egen virtuel privat server för att publicera webbapplikationer
- Domänhantering, köp av domän, olika typer av webbhotell
- Grundläggande förståelse för olika webbaserade system Content Management System (CMS)
- Använda etablerade grafiska verktyg för att bygga enklare hemsidor

**Programspråk och ramverk**: 
- HTML
- CSS
- Javascript
- Markdown

#### Beskrivning
Modulen fokuserar på tekniker som krävs för att publicera och hantera en webbapplikation på internet. Du kommer att lära dig att hantera en egen virtuell privat server (VPS) och hur man använder och hanterar en domän. Modulen ger också en grundläggande förståelse för hur man använder ett Content Management System (CMS), ex Wordpress, för att bygga och underhålla hemsidor. Modulen är avgörande för att förstå tekniska aspekter av att publicera och underhålla en webbapplikation.

#### Case
En gruppbaserad uppgift utifrån givna ramar där du tillsammans med andra ska använda ett befintligt system för webbpublicering

---

### 6. Backend Node.js 

**Verktyg**: 
- Visual Studio Code
- Git (GitHub)
- Unix terminalen

**Förståelse och färdigheter**: 
- Hantera en egen virtuell privat server för att publicera webbapplikationer
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Kunna bygga ett eget REST API med Node.js
- Omsätta skisser till digitala prototyper
- Validera av data frontend och backend


**Programspråk och ramverk**: 
- HTML
- CSS
- JavaScript
- Node.js
- Express
- JSON

#### Beskrivning
Modulen är en introduktion till att bygga en backend applikation med JavaScript med Node.js och Express. Du kommer att lära dig grunderna i hur en webbserver hanterar klienters förfrågningar. Du kommer också att söka och använda dokumentationsresurser för att lösa problem som uppstår under utvecklingen. Genom praktiska övningar kommer du att lära dig att bygga ett eget REST API med Node.js, en av de mest använda teknikerna för att struktera ett API. Du kommer också att lära dig att omsätta designskisser till fungerande användargränssnitt.

#### Case
En individuell uppgift utifrån givna ramar där du från grunden ska bygga en webbserver som kan hantera en enklare resurs son lagras i datafiler på servern.

---

### 7. Frontend ramverk 

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix Terminalen

**Förståelse och färdigheter**: 
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Använda ramverket React.js för att bygga en modern Single Page Application (SPA)
- Förståelse hur man konsumerar ett RESTful API i en webbapplikation
- Omsätta skisser till digitala prototyper och funktionella användargränsnitt


**Programspråk och ramverk**: 
- Javascript
- Reactjs

#### Beskrivning
Den här modulen fokuserar att använda ramverket React.js för att bygga en single page applikation (SPA). Du kommer att lära dig grunderna i React.js och hur man använder det för att bygga användarvänliga gränssnitt och interaktiva webbapplikationer. Du kommer också att få en förståelse för hur man konsumerar ett RESTful API i en webbapplikation baserat på komponenter för rendrering. Vi kommer endast arbeta med Reacts grundläggande koncept: state-variabler, props, hämta data med useEffect och fetch samt react-router-dom för sidnavigering.

#### Case
Publiceras snarast via länk

---

### 8. Spel och Websockets 

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix terminalen
- Local Storage

**Förståelse och färdigheterr**: 
- Struktera program enligt den objektorienterade paradigmen
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Implementera realtidskommunikation i webapplikationer
- Omsätta skisser till digitala prototyper och funktionella användargränsnitt


**Programspråk och ramverk**: 
- HTML
- CSS
- JavaScript
- Canvas
- Node.js

#### Beskrivning
Modulen fokuserar på att förstå och använda websockets för realtidskommunikation, en tvåvägskommunikation mellan klienter och en server. Du kommer att lära dig hur man upprättar en förbindelse och hur en chattapplikation kan se ut. I modulen finns ett fokus på objektorienterad programmering i JavaScript och att skapa grafik och animation i canvas element. Se hur data kan lagras i webbläsaren via Local Storage och hur cookies används för exempelvis att en användare av en applikation ska godkänna lagring av data enligt gällande datalagringsdirektiv. 

#### Case
En individuell uppgift utifrån givna ramar där du från grunden ska bygga en multiplayer applikation (exempelvis ett spel).


---

### 9. Fullstack PHP

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix Terminalen

**Förståelse och färdigheter**: 
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Förstå hur man konsumerar ett REST API i en webbapplikation
- Kunna applicera vanliga backendtekniker för dagens webbapplikationer så som *password hasing, routes, templating engine, sessions, cookies*
- Kunskap i hur man bygger en egen CRUD applikation för att hämta, lägga till, förändra och ta bort data 
- Omsätta skisser till digitala prototyper och funktionella användargränsnitt


**Programspråk och ramverk**: 
- PHP
- Laravel
- MySQL

#### Beskrivning
I den här modulen lär du dig fler tekniker som utmärker en modern webbapplikation. Nu fokuserar vi att utveckla din förståelse för backendsystem med Laravel som bygger på PHP. Du kommer också att få en fördjupa dina kunskaper inom hur man arbetar med Models, Views Controllers. Laravel som gör det enklare att hantera routrar, händelser och databasförfrågningar. Du kommer också att lära dig om hur man lagrar lösenord på ett säkert sätt och hur sessioner används för att förbättra användarupplevelsen av en applikation. Med fokus på både frontend och backend lär modulperioden ut hur en fullstack applikation fungerar.

#### Case
En individuell uppgift utifrån givna ramar där du från grunden ska bygga en applikation som hanterar inloggning, sessioner och en resurs du väljer att hantera.

---

### 10. Arbeta i team

**Verktyg**: 
- Visual Studio Code
- Git (GitHub)
- Unix terminalen
- Docker Desktop
- Trello

**Förståelse och färdigheter**: 
- Kommunicera med extern kund
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Omsätta skisser till digitala prototyper och funktionella användargränsnitt
- Hantera en egen virtuel privat server för att publicera webbapplikationer
- Kunna kommunicera tekniska problem och lösningar till personer utan teknisk kompetens
- Planera och tidsuppskatta ett arbete med olika sprintar
- Förståelse för att arbeta som webbprogrammerare


**Programspråk och ramverk**:
- Visual Studio Code
- Git (GitHub)
- Docker
- Scrum
- *Valfritt*, kundens önskemål kring vad webbapplikationen ska hantera bli avgörande 

#### Beskrivning
Modulen fokuserar på grundläggande arbete i ett team med projektledning inom webbutveckling. Ni kommer att lära sig hur man samarbetar och hanterar mjukvaruprojekt på Github med Kanban-metodik. De kommer också att få en förståelse för projektstyrning, inklusive planering, uppföljning och organisation av uppgifter. Målet med modulen är att ge er färdigheter för att samarbeta effektivt i teams och leda framgångsrika projekt. 

#### Case
En gruppbaserad uppgift utifrån givna ramar där du tillsammans med andra ska använda ta fram en färdig webbapplikation. Arbetet med caset pågår under hela modulperioden. Exempel på projekt: utveckla ett eget tema i Wordpress med anpassning av ett eller flera plugin.


---


### 11. Fullstack PHP

**Verktyg**: 
- Visual Studio Code
- Git (GitHub)
- Unix Terminalen / WSL2
- Docker Desktop
- MySQL Workbench

**Förståelse och färdigheter**: 
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Omsätta skisser till digitala prototyper och funktionella användargränsnitt
- Hantera en egen virtuel privat server för att publicera webbapplikationer
- Använda PHP för att skapa en webbapplikation med routes och sessioner
- Förstå grundläggande sökmotoroptimering
- Hantera en applikation med certifikat

**Programspråk och ramverk**: 
- Docker
- PHP
- Nginx / Apache
- MySQL
- HTML, CSS och JavaScript

#### Beskrivning
I den här modulen kommer du att utforska det populära programspråket PHP för att bygga en backend. Flera av backend koncept är kända sedan tidigare moduler, men nu får du se skillnaden mellan att använda Node.js och PHP. Du kommer att jobba med Docker containers för att isolerad utecklingsmiljö. Introduktion till att använda populära PHP servrar som Nginx och Apache. Hantera projekt baserat på composer. Introduktion till att använda ramerverket Laravel. Upptäck möjligheter med relationsdatabasen MySQL för att lagra data.  

#### Case
En uppgift som du kan välja att arbeta själv med eller tillsammans med någon annan. Caset mynnar ut i en färdig fullstack webbapplikation. Arbetar du tillsammans med någon annan finns möjlighet att ha dela upp arbetet och därmed indivudellt sätta fokus på backend eller frontend. 

---


### 12. Examensprojekt

**Verktyg**: 
- Visual Studio Code
- Git (GitHub)
- ...

**Förståelse och färdigheter**: 
- Planera och tidsuppskatta eget arbete
- Kunna ta skisser och översätta dem till demonstrerande digitala prototyper
- Kunna kommunicera tekniska problem och lösningar till personer utan teknisk kompetens
- Hantera en egen virtuel privat server för att publicera webbapplikationer
- Förståelse för webbprogrammering med TypeScript  


**Programspråk och ramverk**: 
- *Valfritt*

#### Beskrivning
Använd dina nya kunskaper för att bygga en applikation som kan bli en given produkt i din portfolio. En applikation att visa för framtida arbetsgivare och kunder. Detta är det sista projektet i webbutvecklingsprogrammet. Du kan välja att arbeta ensam eller i en grupp.

#### Case
Uppgiftens innehåll skapar du själv och kommer att framgå av ett slutgiltigt kursintyg som kursdeltagare får efter utbildningen. Arbetet med examensprojektet kommer för den som önskar kunna påbörjas innan modulen startar. Kurslärare kommer tillsamamns med dig se till att ditt projekt motsvarar den tid som anges för modulen.   

---


## Kursintyg
Case i kursen som betygsätts *Godkänd* framgår av slutgiltigt kursintyg. I kursintyget anges också examensprojektet. 

## Kompletting
Möjlighet att komplettera enstaka moduler erbjuds under pågående kurs.

## Portfolio
...
