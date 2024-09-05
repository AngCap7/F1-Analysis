
# F1 Analysis

## Descrizione
Questo progetto esegue un'analisi dei dati di Formula 1, combinando vari dataset relativi a risultati di gare, qualifiche, soste ai box, classifiche piloti e costruttori. Viene eseguita una fase di preprocessamento dei dati, seguita da analisi visive utilizzando librerie come Bokeh, Plotly e Seaborn.

## Requisiti
Le seguenti librerie Python sono necessarie per eseguire il progetto:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- folium
- bokeh
- openpyxl

## Installazione
Per installare le dipendenze, eseguire:
```bash
pip install pandas numpy matplotlib seaborn plotly folium bokeh openpyxl
```

## Dataset
Il progetto utilizza diversi dataset Excel uniti per fornire informazioni complete sui piloti, i costruttori e le gare di Formula 1. Il file Excel contiene fogli che rappresentano:
- Risultati di gara
- Risultati di qualifiche
- Soste ai box
- Classifiche piloti e costruttori

## Analisi
Le seguenti operazioni di preprocessamento vengono eseguite:
1. **Unione dei dati**: vengono effettuati join tra le tabelle utilizzando chiavi come `driverId`, `constructorId`, `raceId` e `statusId` per arricchire i dati con i nomi dei piloti, costruttori e dettagli delle gare.
2. **Conversione dei tempi**: i dati relativi ai tempi vengono convertiti da millisecondi a minuti per una migliore leggibilità.

## Visualizzazioni
- **Grafici interattivi**: Utilizzando Bokeh, vengono creati grafici per visualizzare l'andamento delle vittorie e dei punti per anno, con la possibilità di filtrare per pilota o costruttore.

## Licenza
Questo progetto è concesso sotto licenza MIT.
