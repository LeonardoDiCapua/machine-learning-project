# 📊 Machine Learning Project — Instagram Reels Engagement Prediction

## 📌 Descrizione

Questo progetto applica diversi algoritmi di **Machine Learning** all’analisi delle metriche di engagement dei *Reels* di Instagram.

L’obiettivo principale è studiare e predire i rapporti tra:

- **Like / Visualizzazioni**
- **Commenti / Visualizzazioni**

al fine di comprendere quali fattori influenzano maggiormente il coinvolgimento degli utenti e supportare l’ottimizzazione delle strategie di contenuto.

I dati utilizzati provengono dai Reels pubblicati dall’account ufficiale di **National Geographic**, scelto per l’elevato livello di interazione generato dai suoi contenuti.

---

## 🎯 Obiettivi del progetto

- Analizzare statisticamente le metriche principali dei Reels
- Identificare correlazioni e pattern significativi
- Costruire modelli predittivi per stimare:
  - il rapporto *like/views*
  - il rapporto *comments/views*
- Confrontare diversi algoritmi di regressione e ensemble learning

---

## 📂 Struttura della repository

├── Progetto Machine Learning.ipynb # Notebook completo con codice e analisi
├── data/
│ └── Dataset_Instagram.xlsx # Dataset utilizzato (400+ Reels)
├── report/
│ └── Relazione Machine Learning.pdf # Relazione finale del progetto


---

## 📊 Dataset

Il dataset contiene informazioni su oltre **400 Reels** e include variabili come:

- Numero di visualizzazioni
- Numero di like
- Numero di commenti
- Durata del Reel
- Età del video

Le analisi esplorative comprendono:

- Statistiche descrittive
- Standardizzazione delle metriche
- Matrice di correlazione
- Scatter plot e box plot mensili

---

## 🤖 Algoritmi utilizzati

Nel progetto sono stati implementati e confrontati diversi modelli di Machine Learning:

- Regressione Lineare
- Regressione Lasso (regularization)
- Decision Tree
- Random Forest
- Gradient Boosting Machine (GBM)
- Support Vector Regression (SVR)

---

## 📈 Metriche di valutazione

Le prestazioni dei modelli sono state valutate tramite:

- **MAE** (Mean Absolute Error)
- **RMSE** (Root Mean Squared Error)

---

## ⭐ Risultati principali

- **Random Forest** è risultato il modello più efficace per la predizione del rapporto *like/visualizzazioni*.
- Per il rapporto *commenti/visualizzazioni*, i modelli lineari (Lasso e Linear Regression) hanno ottenuto risultati migliori secondo RMSE.
- Il **Decision Tree** ha mostrato performance inferiori rispetto agli ensemble model.

---

## ▶️ Esecuzione del progetto

Installare le librerie principali:

```bash
pip install pandas numpy matplotlib scikit-learn

Aprire il notebook:
jupyter notebook "Progetto Machine Learning.ipynb"
