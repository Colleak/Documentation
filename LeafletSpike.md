

<img src="https://leafletjs.com/docs/images/logo.png"/>

# Leaflet Integratie in IO React Native application 

Voor het weergeven van de medewerkers op een kaart hebben we gekozen voor Leaflet[^1]

## Wat is Leaflet?

Leaflet is een open-source JavaScript-bibliotheek voor mobielvriendelijke interactieve kaarten. Het is lichtgewicht, flexibel en beschikt over een schat aan plugins. In combinatie met React Native biedt het een krachtig hulpmiddel voor kaartgebaseerde applicaties.[^1] 

---
## Voordelen van het Gebruik van Leaflet in React Native

### 1. **Open Source**
Leaflet is open-source, wat betekent dat het gratis te gebruiken is en dat we het kunnen aanpassen aan onze behoeften.
### 2. **Mobielvriendelijk**
Leaflet is ontworpen om efficiënt te werken op mobiele apparaten. 
### 3. **Uitgebreide Plugin Bibliotheek**
De uitgebreide plugin-bibliotheek van Leaflet kan kaartfunctionaliteiten verbeteren en biedt functies zoals clustering, geocoding en dus de functie om React native te gebruiken.
### 4. **React Native Integratie**
Dankzij de gemeenschap is er een [`(_REACT-native Leaflet, n.d.)`](https://github.com/pavel-corsaghin/react-native-leaflet) pakket beschikbaar dat Leaflet naadloos integreert met React Native.[^2]
(Pavel-Corsaghin, n.d.)

---
## Mogelijke Nadelen

### 1. **Afhankelijkheid van WebView**
De React Native integratie is afhankelijk van WebView om de kaart weer te geven. Hoewel deze aanpak werkt, is het mogelijk niet zo performant als native kaartweergaven.
### 2. **Vereist Extra Setup**
Het opzetten van `react-native-leaflet` kan extra stappen vereisen in vergelijking met het gebruik van een native kaartoplossing.
### 3. **Ondersteunt Mogelijk Niet Alle Native Functies**
Hoewel Leaflet krachtig is, zijn er mogelijk enkele native kaartfuncties die het niet ondersteunt of waarvoor aanvullende plugins nodig zijn.

## Conclusie

Leaflet, in combinatie met React Native, biedt een robuuste oplossing voor onze kaartgebaseerde trackingbehoeften. Hoewel er enkele mogelijke nadelen zijn, maken de voordelen zoals het open-source karakter, de mobielvriendelijkheid en de uitgebreide plugin-bibliotheek het een aantrekkelijke keuze voor ons project.

### Sources:
[^1]:_REACT Leaflet | REACT Leaflet_. (n.d.). https://react-leaflet.js.org/
[^2]:Pavel-Corsaghin. (n.d.). _GitHub - pavel-corsaghin/react-native-leaflet: A LeafletView component using WebView and Leaflet map for React Native applications_. GitHub. https://github.com/pavel-corsaghin/react-native-leaflet
