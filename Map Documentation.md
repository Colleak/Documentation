# Proccess kaart implementatie
## Inleiding 
Na een spike-onderzoek om te bepalen welke bibliotheek we wilden gebruiken, begonnen we met de implementatie van [React-native-leaflet](https://github.com/pavel-corsaghin/react-native-leaflet/tree/main/android). We liepen echter tegen enkele problemen aan omdat veel functionaliteiten van de normale leaflet.js ontbreken, zoals max-bounds en max/min-zoom instellingen. Deze zijn nodig om de applicatie er netjes uit te laten zien en te laten functioneren zoals we willen. 
## Leaflet Spike


## Evaluatie van React-native-leaflet 
React-native-leaflet, hoewel een populaire keuze, voldeed niet volledig aan onze behoeften vanwege het gebrek aan enkele cruciale functionaliteiten. 
## Overweging van React-native-maps
We hebben ook overwogen om [react-native-maps](https://github.com/react-native-maps/react-native-maps) te gebruiken, een bibliotheek die door react-native zelf wordt aanbevolen. Echter, deze bibliotheek werkt alleen met echte kaarten en niet met de aangepaste kaarten die we in onze applicatie willen implementeren. zoals de vloer plannen van de verdiepingen.
## Conclusie 
We zijn er over na aan het denken om eventueel zelf een coordinaten systeem te maken.
