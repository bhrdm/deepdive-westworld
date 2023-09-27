# Deep-dive Delos

Delos Inc. is het bedrijf achter Westworld, een geavanceerd pretpark in het Wilde Westen met levensechte androids genaamd "hosts." Gasten beleven er een meeslepende en tijdloze ervaring in een zorgvuldig gerecreëerde omgeving.

## Inleiding:

- **Waarom:** Het doel van dit project is het analyseren van de incidenten aan de hand van eerdere rapporten die wij hebben gekregen. Wij hebben de belangrijke data zoals: aantal incidenten, types incidenten, tijd van incidenten enzo. omgezet in diagrammen waaruit makkelijk conclusies getrokken kunnen worden. We hebben logische mogelijkheden voorgesteld zoals een tunnelsysteem om de problemen te verhelpen. Hierdoor kunnen we incidenten sneller oplossen zonder onze gewaardeerde gasten te verstoren.

- **Doelgroep:** Dit project is gericht op bedrijfsanalisten en managers van het park. Door al deze data-analyses kunnen zij een inzicht krijgen op problemen die zij ervaren en aan de hand van al deze informatie en tips kunnen ze maatregelen nemen om de klantervaring te verbeteren.

## 💡 Installatie:

Om dit project te gebruiken, volg je deze stappen:

1. **Python en vereiste bibliotheken:** Zorg ervoor dat Python is geïnstalleerd op je systeem. Als je Python nog niet hebt geïnstalleerd, kun je het downloaden van de officiële website: [Python Downloads](https://www.python.org/downloads/). Installeer vervolgens de vereiste Python-bibliotheken met behulp van pip:

-Python 3.x
-Jupyter Notebook
-pip install plotly
-pip install numpy
-pip install pandas 
-pip install seaborn
-pip install matplotlib
-pip install folium 

### mappen en bestanden

- 📁 **`data/`**: Deze map bevat essentiële datasets:

  - 📄 `incident_reports.json`: Een jaar lang aan incidentrapporten, te gebruiken voor data-analyse.
  - 📄 `visitor_data.json`: Informatie over bezoekersactiviteiten in het park.
  - 📄 `points_of_interest.json`: Informatie over de belangrijkste aandachtspunten binnen Westworld.

- 📁 **`foto/`**:

  - 🖼️ `cirkel.jpg`: cirkeldiagram van types incidenten.
  - 🖼️ `figuredag.jpg`: lijndiagram van incidenten per week
  - 🖼️ `figuremaand.jpg`:lijndiagram van incidenten per maand
  - 🖼️ `heat.jpg` + `heatmap.jpg`: een heatmap van de incidenten
  - 🖼️ `histogram.jpg`: een histogram van de incidenten
  - 🖼️ `scatter1.jpg`:scatterplot van aantal bezoekers
  - 🖼️ `staafdia.jpg`: staafdiagram
  - 🖼️ `typesevdio.jpg`c+ `typesevhor`: servernity histogram
  - 🖼️ `map.png`: afbeelding van de map met een tunnelsysteem en verblijplaatsen voor ploegen.


- 📄 **`deepdive.ipynb`**: een Jupyter Notebook met Python code om data te lezen, opschonen, sorteren en te visualiseren.

- 📄 **`dashbaord.html`**: een html bestand van onze dashboard

- 📄 **`requirements.txt`**: : een lijst met Python-pakketten die vereist zijn voor het opzetten van de ontwikkelomgeving.


2. **Project klonen:** Clone dit project naar je lokale machine(terminal) met behulp van de volgende opdracht: git clone git@bitlab.bit-academy.nl:bsjn/deep-dive-delos.git

3. **Projectmap:** Navigeer naar de projectmap:
    cd deep-dive-delos
  
4. **Start de applicatie:** Voer de volgende opdracht uit om de applicatie te starten:
    cd dashboard.html
    cd deepdive.ipynb
   

## Gebruik

Dit dashboard bevat enkele visualisaties waaruit algemene informatie te lezen is van het park. In het jupyter bestandje is duidelijk te zien hoe de data is verzameld, opgeschoond en gesorteerd. Tot slot is er een conclusie getrokken.

De belangrijkste bestanden zijn:

- **deepdive.ipynb:** Dit is het hoofdbestand waarin wij alle data en de bijbehorende visualisaties hebben verzameld samen met de conclusies die wij eruit hebben getrokken
- **dashboard.html/:** HTML bestand van onze dashboard
- **data/:** rapports van incidents, points of interest and visitor data.

