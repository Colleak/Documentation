# Proceskaart Implementatie

## Inleiding

Na een spike-onderzoek om te bepalen welke bibliotheek we wilden gebruiken, zijn we gestart met de implementatie van [React-native-leaflet](https://github.com/pavel-corsaghin/react-native-leaflet/tree/main/android). We ondervonden echter enkele problemen omdat veel functionaliteiten van de normale leaflet.js ontbreken, zoals max-bounds en max/min-zoom instellingen. Deze functionaliteiten zijn essentieel om de applicatie er verzorgd uit te laten zien en te laten functioneren zoals bedoeld.

## Leaflet Spike

We hebben een spike uitgevoerd en dit zijn de resultaten:
- [Leaflet Spike](https://github.com/Colleak/Documentation/blob/DEV/LeafletSpike.md)

## Evaluatie van React-native-leaflet 

React-native-leaflet is een populaire keuze, maar voldeed niet volledig aan onze eisen vanwege het ontbreken van enkele cruciale functionaliteiten.

## Overweging van React-native-maps

We hebben ook [react-native-maps](https://github.com/react-native-maps/react-native-maps) overwogen, een bibliotheek die door React Native zelf wordt aanbevolen. Deze bibliotheek is echter beperkt tot het werken met echte kaarten en ondersteunt niet de aangepaste kaarten, zoals de vloerplannen van de verdiepingen, die we in onze applicatie willen implementeren.

## Conclusie 

We hebben besloten om zelf een kaartsysteem te ontwikkelen waarmee we avatars van medewerkers op specifieke coördinaten kunnen plaatsen.
