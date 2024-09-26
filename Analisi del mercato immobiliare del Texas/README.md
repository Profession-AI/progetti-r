# Analisi del Mercato Immobiliare del Texas

## Descrizione del progetto

L'azienda **Texas Realty Insights** desidera analizzare le tendenze del mercato immobiliare nello stato del Texas, sfruttando i dati storici relativi alle vendite di immobili. L'obiettivo è fornire insight statistici e visivi che supportino le decisioni strategiche di vendita e ottimizzazione delle inserzioni immobiliari.

### Obiettivi del progetto

- Identificare e interpretare i trend storici delle vendite immobiliari in Texas.
- Valutare l’efficacia delle strategie di marketing delle inserzioni immobiliari.
- Offrire una rappresentazione grafica dei dati che evidenzi la distribuzione dei prezzi e delle vendite tra città, mesi e anni.

## Valore Aggiunto

L'analisi statistica proposta permetterà a **Texas Realty Insights** di ottimizzare le loro strategie di mercato, identificando città con opportunità di crescita e valutando l'efficacia delle inserzioni immobiliari nel tempo. Grazie a una visione chiara e strutturata dei dati, l'azienda potrà prendere decisioni basate su informazioni concrete, migliorando la gestione delle vendite immobiliari in Texas.

## Dataset: "Real Estate Texas.csv"

Il dataset contiene le seguenti variabili:

- **city**: città di riferimento
- **year**: anno di riferimento
- **month**: mese di riferimento
- **sales**: numero totale di vendite
- **volume**: valore totale delle vendite (in milioni di dollari)
- **median_price**: prezzo mediano di vendita (in dollari)
- **listings**: numero totale di annunci attivi
- **months_inventory**: quantità di tempo necessaria per vendere tutte le inserzioni correnti, espresso in mesi

[Scarica il dataset](https://drive.google.com/file/d/1O4If8876MTwstkrZX0BqpQ_BxcsIMEko/view?usp=sharing)

## Steps del progetto

### 1. Analisi delle variabili
Identifica e descrivi il tipo di variabili presenti nel dataset. Valuta come gestire le variabili temporali e commenta sul tipo di analisi che può essere condotta su ciascuna variabile.

### 2. Indici di posizione, variabilità e forma
Calcola i seguenti indici per le variabili numeriche:
- Media, mediana, moda
- Deviazione standard e varianza
- Asimmetria e curtosi

Crea una distribuzione di frequenza per le variabili categoriche, come `city` e `month`. Commenta i risultati ottenuti.

### 3. Identificazione delle variabili con maggiore variabilità e asimmetria
Determina:
- Qual è la variabile con la più alta variabilità
- Qual è la variabile con la distribuzione più asimmetrica
Spiega come sei giunto a queste conclusioni e fornisci considerazioni statistiche.

### 4. Creazione di classi per una variabile quantitativa
Seleziona una variabile quantitativa (es. `sales` o `median_price`) e suddividila in classi. Crea una distribuzione di frequenze e rappresenta i dati con un grafico a barre. Calcola l’indice di Gini e discuti i risultati.

### 5. Calcolo della probabilità
Calcola le seguenti probabilità:
- Probabilità che un'immobile si trovi nella città di "Beaumont".
- Probabilità che un'immobile sia stato venduto nel mese di Luglio.
- Probabilità che un immobile sia stato venduto nel mese di Dicembre 2012.

### 6. Creazione di nuove variabili
- Crea una nuova colonna che calcoli il **prezzo medio** degli immobili utilizzando le variabili disponibili.
- Prova a creare una colonna che misuri l’**efficacia degli annunci di vendita**. Commenta e discuti i risultati.

### 7. Analisi condizionata
Usa il pacchetto `dplyr` o il linguaggio base di R per effettuare analisi statistiche condizionate per città, anno e mese. Genera dei **summary** (media, deviazione standard) e rappresenta graficamente i risultati.

### 8. Creazione di visualizzazioni con ggplot2
Utilizza `ggplot2` per creare grafici personalizzati. Assicurati di esplorare:
- Boxplot per confrontare la distribuzione del prezzo mediano tra le città.
- Grafici a barre per confrontare il totale delle vendite per mese e città.
- Line charts per confrontare l’andamento delle vendite in periodi storici differenti.

### 9. Conclusioni
Fornisci una sintesi dei risultati ottenuti, facendo riferimento alle principali tendenze emerse e fornendo raccomandazioni basate sull'analisi.

# Modalità di consegna: script R
