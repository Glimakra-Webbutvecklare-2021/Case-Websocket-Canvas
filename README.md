# Case-Websocket-Canvas

## Spel och websockets

I det här caset kan ni arbeta individuellt. 

Ni kan välja mellan tre olika scenarion. I varje scenario ska finnas någon form av 'spelupplevelse - interaktion', där canvas och websockets används.

1. Ett multiplayer canvas spel
2. En realtids chatt 
3. En kollaborativ online paint

Applikationen behöver inte vara helt baseras på canvas, utan den kan i delar som du väljer baseras på andra DOM element. 

Ni lämnar in genom en **länk till er publicerade applikation**.

# Krav

## 1. Minimum

- Funktionalitet i applikationen ska vara baserad på både websockets och canvas
- Applikationen ska kunna användas meningsfullt med fler än en uppkopplad klient
- Använd `ws` biblotektet 
- Applikationen kan ha delar med 'vanliga' DOM element för ex chatt
- En `README.md` som beskriver hur man installerar och använder applikationen

## 2. Extra
Utöver samliga minimum-punkter ska dessutom följade krav vara uppfyllda:

- Tillståndet av applikationen ska lagras i en fil alternativt local storage för senare referens (exempelvis: 1. highscore, 2. chatthistorik, 3. canvas-state..)
- Applikationen ska vara hostad (via linode, heroku eller dylikt)

## 3. Extra Extra
Utöver samliga minimum-punkter och extra-punkter ska dessutom följade krav vara uppfyllda:

- Authentisering för att skapa privata sessioner
- Bygg klienten med frontend ramverk (exempelvis React)

# Feedback
Veckan efter presentation kommer feedback ges under följande rubriker:

- Kommunikation med websocket
- Git commits dokumentering
- Användarupplevelse
- Allmän kodstil

*Designfeedback tillkommer eventuellt från Mattias*

# Presentation- och Inlämningsdatum
Enligt planering hålls presentation av caset under vecka 42 och tid för feedback justering vecka 43. 
- Preliminärt datum för presentation är **2021-10-20, Torsdag kl. 10:25**
