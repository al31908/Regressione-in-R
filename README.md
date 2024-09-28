## Regressione-in-R

# Panoramica
Questo progetto analizza un dataset contenente dati ambientali di 36 paesi raccolti nel corso di 28 anni. L'obiettivo principale è utilizzare tecniche di regressione per esplorare le relazioni tra variabili ambientali e i livelli di emissioni di CO2.

# Dataset
Il dataset utilizzato contiene informazioni su:

**co2.pc**: Emissioni di CO2 pro capite

**pop**: Popolazione (logaritmizzata)

**en.pc**: Consumo di energia pro capite (logaritmizzato)

**gdp.pc**: PIL pro capite (logaritmizzato)

**urb**: Urbanizzazione (logaritmizzata)

**ci**: Indice di consumo (logaritmizzato)

**lagco2.pc**: Emissioni di CO2 pro capite nel periodo precedente (logaritmizzato)

**country**: Nome del paese

# Obiettivi
Analizzare le relazioni tra CO2 e altre variabili economiche e demografiche

Costruire modelli di regressione per prevedere le emissioni di CO2.

Valutare la bontà dei modelli attraverso R², AIC e BIC.

Visualizzare i risultati per facilitare l'interpretazione.

# Requisiti
Per eseguire il codice, è necessario avere installato i seguenti pacchetti R:

lme4

haven

tidyverse

lmerTest

sjPlot

glmmTMB

