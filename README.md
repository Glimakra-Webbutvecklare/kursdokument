---
title: Glimåka Webbutvecklare - Kursdokument
authors: Henry Bergström | Anders Sjunnesson

---

# Webbutvecklare - Kursdokument

## Programöversikt
I kursen Webbutvecklare kommer du lära dig att programmera webbapplikationer. Tydliga fokus i kursen är dels webbprogrammering med god kodkvalité, dels webbdesign med förståelse för användargränssnitt. Ett övergripande mål med kursen är att göra dig redo för att ta dig an olika utmaningar som en frilansare eller ett arbete inom ett större team. 

### Hur du kommer lära dig
Kursen Webbutvecklare baseras på olika moduler. Varje modul inleds med ett par veckors föreläsningar, varvat med mindre övningsuppgifter. Till varje modul finns en större inlämningsuppgift – ett case. Ett case beskriver en applikation som ska utvecklas. I beskrivningen finns angivet ramar för applikationen, grundläggande krav och dessutom utmaningar som du kan välja att anta. Case syftar till att du ska visa vad du har lärt dig under en modul. 

Det finns möjlighet till handledning under modulperioder. I rollen som framtida programmerare bör du tycka om att lösa problem och att felsöka kod på egen hand.

De flesta case är individuella inlämningsuppgifter. Några moduler innebär att du arbetar tillsammans med andra i ett case.

Redovisning av case sker ca en arbetsvecka innan en modul avslutas. Case är obligatoriska och bedöms som Godkänt, eller Komplettering krävs.
I arbetsveckan efter redovisning av ett case finns möjlighet att förbereda sig för nästa modul, att på egen hand förbättra funktionalitet i en applikation, eller eventuellt komplettera ett case för att nå Godkänt.

Under de två åren som kursen pågår finns sammanlagt 12 case, 3 per termin. En ny modul baseras på kunskaper du inhämtat från tidigare moduler. Det innebär att du som kursdeltagare behöver vara i fas med studier för att tillgodogöra dig kursinnehållet. Kursdeltagare som behöver komplettera mer än en modul kommer erfarenhetsmässigt få svårt att fullfölja kursen. 

### Vad du kommer lära dig
Unders kursen kommer du att hantera en mängd olika verktyg, få kunskap förmedlat och nå färdigheter inom olika områden.

**Verktyg**
1.	Visual Studio Code (editor)
2.	Webbutvecklarverktyg i browsers (Chrome, Edge, Firefox mfl)
3.	Git och GitHub (versionshantering)
4.	Unix terminalen / WSL2 (bash)
5.	Docker (virtualisering)
6.	Insomnia (API klient)
7.	Wordpress (blog & CMS)
8.	Jekyll (static sitegenerator)
9.	MySQL Workbench (databashantering)
10.	Figma (design och prototype)
11.	Trello (projekthantering)
12.	Adobe Creative Suite (design)

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
16.	Använda olika tekniker för backend, som ex routes, modules, password hashing, templating engine, sessions, cookies
17.	Kunskap i hur man bygger en egen CRUD applikation för att hämta, lägga till, förändra och ta bort data från en databas
18.	Kunna kommunicera tekniska problem och lösningar med personer utan teknisk kompetens
19.	Planera och tidsuppskatta arbete 
20.	Arbeta i ett team för att utveckla en applikation


**Förståelse och färdigheter - webbdesign**
1.	Applicera grundläggande principer i grafisk formgivning
2.	Förstå och kommunicera varumärke, använda designspråk genom webbtjänster
3.	Planera och skissa gränssnitt, omsätta skisser till digital prototyp och färdig applikation
4.	Kunna applicera specifika design principer för webben


**Programspråk & Ramverk**
1.	Markdown
2.	HTML5
3.	CSS/Sass
4.	JavaScript
5.	JSON
6.	Nodejs
7.	Express
8.	Reactjs
9.	MongoDB
10.	MySQL
11.	PHP
12.	TypeScript


## Modulöversikt

| Modulnummer | Modulnamn                      | Beskrivning                                                                                            | Period | Case         | ~ veckor    | 
| ----------- | ------------------------------ | ------------------------------------------------------------------------------------------------------ | ------ | ------------ |             |
| 1           | HTML och Git                   | HTML är webbens språk för struktur och innehåll. Grundläggande versionshantering med GitHub.           | HT:1   | individuellt | 6 (v33-v37) |
| 2           | Grundläggande CSS              | Webbdesign och responsiv layout. Lär dig begrepp som *box model*, *media queries* och *mobile first*.  | HT:2   | individuellt | 6 (v38-v43) |
| 3           | Grundläggande Javascript       | Introduktion till JavaScript som programspråk, hantera Document Object Model (DOM).                    | HT:3   | individuellt | 6 (v45-v50) |
| 4           | Fortsättning JavaScript        | Asynkron kod med JavaScript, hämta data från API:er, läs data med filformaten JSON och XML.            | VT:1   | individuellt | 6 (v2-v7)   |
| 5           | Hosting, CMS och Wordpress     | Introduktion till webbservrar och publiceringssystem, static site generators och Wordpress.            | VT:2   | grupp        | 6 (v9-v14)  |
| 6           | Backend Node.js                | Bygg en CRUD applikation med resurser, hantera en filserver, och använd API för att hämta data.        | VT:3   | individuellt | 6 (v16-v22) |
| 7           | Frontend med ramverk           | Lär dig hur man bygger en Single Page Application med ramverket React.                                 | HT:1   | individuellt | 6 (v33-v37) |          
| 8           | Spel och websockets            | Skapa en canvasbaserad applikation med websocket för kommunikation i realtid - multiplayer.            | HT:2   | individuellt | 6 (v38-v43) |
| 9           | Fullstack Node.js              | Bygg en fullstack webbapplikation med inloggning och resurs. Använd en molnbaserad MongoDB databas.    | HT:3   | individuellt | 6 (v45-v50) |
| 10          | Arbeta i team                  | Jobba tillsammans i ett projekt mot extern kund. Planera och utför arbete enligt Scrum.                | VT:1   | grupp        | 6 (v2-v7)   |
| 11          | Fullstack PHP                  | Skapa en webbapplikation baserad på PHP. Lagra data i en relationsdatabas som MySQL.                   | VT:2   | ind /grupp   | 6 (v9-v14)  |
| 12          | Examensprojekt                 | Använd dina kunskaper och bygg en egen webbapplikation.                                                | VT:3   | individuellt | 6 (v16-v22) |


---

### 1. HTML och Git

**Verktyg**: 
- Visual Studio Code
- Git (GitHub)
- Unix Terminalen / WSL2

**Färdigheter**: 
- Bygga simpla statiska hemsidor med fokus på struktur och innehåll 
- Validering av kod
- Kunna samarbeta och versionhantera mjukvaruprojekt med Git.

**Programspråk & Ramverk**: 
- HTML

**Design**: 


#### Beskrivning
Modulen fokuserar på att göra er bekväma i era mest fundamentala verktyg och språk. Ni kommer att bli introducerade till editorn Visual Studio Code. Lär dig hur man startar projekt, anpassar editorn och namnger filer och mappar. Vidare får ni en genomgång av HTML5 och hur man använder taggar för struktur och enklare formatering av text, länkar och bilder. Git är ert vikigaste verktyg för att spara arbete och ni kommer med hjälp av GitHub pages publicera er första hemsida. 


#### Case
Publiceras snarast via länk

---
### 2. Grundläggande CSS

**Verktyg**: Visual Studio Code, Git (Github)

**Färdigheter**: 
- Bygga simpla statiska hemsidor med grundläggande webbtekniker
- Kunna samarbeta och versionhantera mjukvaruprojekt med Git
- Utforma de vanligaste responsiva layoutsen för hemsidor
- Kunna applicera de grundläggande principerna i grafisk formgivning för webben

**Programspråk & Ramverk**: 
- HTML
- CSS
- (Javascript)

#### Beskrivning
TO BE WRITTEN

#### Case
Publiceras snarast via länk

---
### 3. Grundläggande Javascript

**Verktyg**: Visual Studio Code, Git (Github)

**Färdigheter**: 
- Bygga simpla statiska hemsidor med grundläggande webbtekniker
- Kunna samarbeta och versionhantera mjukvaruprojekt med Git
- Kunna redogöra innebörden för grundläggande programmeringstermer

**Programspråk & Ramverk**: 
- HTML
- CSS
- Javascript

#### Beskrivning
Under modulen kommer du att lära dig att bygga enkla men snygga statiska hemsidor med hjälp av CSS.Vi kommer titta på de vanligaste responsiva layoutarna för moderna hemsidor. Du kommer också att få en förståelse för grundläggande principer i grafisk formgivning för webben, så att du kan applicera dem på dina projekt. Med denna modul som grund, kommer du vara redo att fortsätta din utbildning inom webbutveckling.

#### Case
Publiceras snarast via länk

---
### 4. Fortsättning JavaScript

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Insomnia

**Färdigheter**: 
- Bygga simpla statiska hemsidor med grundläggande webbtekniker
- Kunna samarbeta och versionhantera mjukvaruprojekt med Git
- Skapa en dynamisk hemsida med logik kopplat till knappar, sökfält med mera
- Struktera program enligt den objekt-orienterade paradigmen
- Förståelse hur man konsumerar ett RESTful API i en webbapplikation

**Programspråk & Ramverk**: 
- HTML
- CSS
- Javascript

#### Beskrivning
Vår introduktion till grundläggande programmering med Javascript. Du kommer att få en förståelse för de viktigaste programmeringstermerna och hur de används i samband med Javascript. Genom att arbeta med praktiska övningar, kommer du att lära dig att skapa en dynamisk hemsida med logik som är kopplad till knappar och sökfält. Du kommer också att få en förståelse för hur man konsumerar ett RESTful API i en webbapplikation, vilket är en viktig färdighet för att bygga avancerade webbapplikationer. Modulen lägger grunden för din fortsatta utbildning inom webbutveckling.

#### Case
Publiceras snarast via länk

---
### 5. Hosting och Wordpress

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix Terminalen / WSL2
- Wordpress
- Jekyll

**Färdigheter**: 
- Hantera en egen virtuel privat server för att publicera webbapplikationer
- Hur man använder köper och hanterar en domän
- Grundläggande förståelse hur man använder ett Content Management System (CMS)
- Använda etablerade grafiska verktyg för att bygga enklare hemsidor

**Programspråk & Ramverk**: 
- HTML
- CSS
- Javascript
- Markdown

#### Beskrivning
Modulen fokuserar på teknikerna som krävs för att publicera och hantera en webbapplikation på internet. Du kommer att lära dig att hantera en egen virtuell privat server (VPS) och hur man använder och hanterar en domän. Modulen ger också en grundläggande förståelse för hur man använder ett Content Management System (CMS), såsom Wordpress, för att bygga och underhålla hemsidor. Denna modul är avgörande för att förstå de tekniska aspekterna av att publicera och underhålla en webbapplikation.

#### Case
Publiceras snarast via länk

---

### 6. Backend med Node.js 

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix Terminalen / WSL2

**Färdigheter**: 
- Hantera en egen virtuel privat server för att publicera webbapplikationer
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Kunna bygga ett eget RESTful API med Node.js
- Kunna ta skisser och översätta dem till demonstrerande digitala prototyper


**Programspråk & Ramverk**: 
- HTML
- CSS
- Javascript
- Nodejs

#### Beskrivning
Modulen är en introduktion till att bygga backend med Javascript genom att använda Node.js. Du kommer att lära dig att söka och använda dokumentationsresurser för att lösa problem som uppstår under utvecklingen. Genom praktiska övningar kommer du att lära dig att bygga ett eget RESTful API med Node.js, en av de mest använda teknikerna för att struktera ett API. Du kommer också att lära dig att översätta skisser till demonstrerande digitala prototyper.

#### Case
Publiceras snarast via länk

---

### 7. Frontend med ramverk 

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix Terminalen / WSL2

**Färdigheter**: 
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Använda ramverket Reactjs för att bygga en modern Single Page App (SPA)
- Förståelse hur man konsumerar ett RESTful API i en webbapplikation
- Kunna ta skisser och översätta dem till demonstrerande digitala prototyper


**Programspråk & Ramverk**: 
- Javascript
- Reactjs

#### Beskrivning
Den här modulen fokuserar att använda ramverket Reactjs för att bygga moderna single page-applikationer (SPA). Du kommer att lära dig grunderna i Reactjs och hur man använder det för att bygga användarvänliga gränssnitt och interaktiva webbapplikationer. Du kommer också att få en förståelse för hur man konsumerar ett RESTful API i en webbapplikation och dynamiskt rendrerar ut komponenter.Vi kommer endast arbeta med Reacts grundläggande koncept: state-variabler, props, hämta data med useEffect och fetch samt react-router-dom för sidnavigering.

#### Case
Publiceras snarast via länk

---

### 8. Spel och Websockets 

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix Terminalen / WSL2

**Färdigheter**: 
- Struktera program enligt den objekt-orienterade paradigmen
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- implementera webapplikationer med realtidskommunikation


**Programspråk & Ramverk**: 
- HTML
- CSS
- Javascript
- Nodejs

#### Beskrivning
Modulen fokuserar på att förstå hur man använder websockets för att uppnå realtidskommunikation. Du kommer att lära dig om websockets, en teknik som tillåter webbapplikationer att ha en tvåvägskommunikation med servern. Vi kommer utforska hur man kan göra en chattapplikation samt multiplayer spel med canvas.

#### Case
Publiceras snarast via länk

---

### 9. Fortsättning backend

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix Terminalen / WSL2

**Färdigheter**: 
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Förståelse hur man konsumerar ett RESTful API i en webbapplikation
- Kunna applicera vanliga backendtekniker för dagens webbapplikationer så som password hasing, routes, templating engine, sessions, cookies
- Förståelse hur man hämtar, lägger till, förändrar och tar bort data från en databas
- Kunna ta skisser och översätta dem till demonstrerande digitala prototyper


**Programspråk & Ramverk**: 
- Nodejs
- Express
- MongoDB

#### Beskrivning
Denna gången kommer ni lära er tekniker som krävs av en modern webbapplikation. Nu fokuserar vi att utveckla din förståelse för backendsystem med Node.js, Express och MongoDB. Du kommer också att få en fördjupa din kunskaper inom Express, ett ramverk för Node.js som gör det enklare att hantera routrar, händelser och databasförfrågningar med MongoDB. Du kommer också att lära dig om hur man sköter lösenord på ett säkert sätt och hur man kan använda sessioner för att förbättra användarupplevelsen.

#### Case
Publiceras snarast via länk

---

### 10. Arbeta i team

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix Terminalen / WSL2
- Trello

**Färdigheter**: 
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Kunna ta skisser och översätta dem till demonstrerande digitala prototyper
- Hantera en egen virtuel privat server för att publicera webbapplikationer
- Kunna kommunicera tekniska problem och lösningar till personer utan teknisk kompetens
- Planera och estimera eget arbete och deadlines


**Programspråk & Ramverk**: 
- *Valfritt*

#### Beskrivning
Modulenfokuserar på grundläggande teamarbete och projektledning inom webbutveckling. Ni kommer att lära sig hur man samarbetar och hanterar mjukvaruprojekt på Github med Kanban-metodik. De kommer också att få en förståelse för projektstyrning, inklusive planering, uppföljning och organisation av uppgifter. Målet med modulen är att ge er färdigheter för att samarbeta effektivt i teams och leda framgångsrika projekt.

#### Case
Publiceras snarast via länk

---


### 11. Backend med PHP

**Verktyg**: 
- Visual Studio Code
- Git (Github)
- Unix Terminalen / WSL2
- Docker

**Färdigheter**: 
- Kunna söka i och använda dokumentationsresurser för att lösa problem som uppstår under utveckling
- Kunna ta skisser och översätta dem till demonstrerande digitala prototyper
- Hantera en egen virtuel privat server för att publicera webbapplikationer
- Kunna applicera vanliga backendtekniker för dagens webbapplikationer så som password hasing, routes, templating engine, sessions, cookies


**Programspråk & Ramverk**: 
- PHP
- JavaScript
- HTML
- CSS

#### Beskrivning
Den här modulen kommer ni utforska ett av de mest populära programspråken för att bygga webbapplikationer. Flera av koncepten ni stöter på här är kända sedan tidigare men nu får ni se skillnaden mellan Javascript och PHP. Dessutom kommer ni jobba med Docker containers för att isolera utecklingsmiljöer.

#### Case
Publiceras snarast via länk

---


### 12. Examensprojekt

**Verktyg**: 
- Visual Studio Code
- Git (Github)

**Färdigheter**: 
- Planera och estimera eget arbete och deadlines
- Kunna ta skisser och översätta dem till demonstrerande digitala prototyper
- Kunna kommunicera tekniska problem och lösningar till personer utan teknisk kompetens
- Hantera en egen virtuel privat server för att publicera webbapplikationer


**Programspråk & Ramverk**: 
- *Valfritt*

#### Beskrivning
Använd era nya kunskaper för att bygga något som imponerar er själva och framtida anställare och kunder. Detta är det sista projektet i webbutvecklingsprogrammet. Ni kan välja att arbeta ensamma eller i en grupp.

#### Case
Publiceras snarast via länk

---


## Kursintyg
Om alla casen är godkända kommer ni erhålla ett diplom

## Kompletting
Under hela terminen har ni tillfälle att lämna in case för rättning. 
