# Toxic Content Classification using Deep Learning (NLP)

## 📌 Descrizione del Progetto
Sviluppo di un sistema avanzato di moderazione automatica dei contenuti basato su tecniche di **Deep Learning**. Il progetto affronta il problema della classificazione multi-label dei testi, identificando diverse sfumature di contenuti non appropriati (insulti, minacce, odio) all'interno di piattaforme social o forum di discussione.

## 🧠 Architettura Tecnica & Modelli
Il cuore del progetto è una rete neurale progettata per comprendere il contesto sequenziale del linguaggio:

1. **Deep Learning Model:** implementazione di una rete neurale ricorrente (**RNN**)con layer **LSTM**  bidirezionale, specificamente scelti per la loro capacità di gestire le dipendenze a lungo termine nel testo.
2. **Multi-label Classification:** il sistema è in grado di assegnare simultaneamente più categorie di tossicità a un singolo testo, garantendo una granularità superiore rispetto ai modelli binari.
3. **Text Preprocessing Pipeline:** pulizia del testo, tokenizzazione, rimozione delle stopword e applicazione di tecniche di padding per standardizzare gli input della rete.
4. **Performance Evaluation:** analisi approfondita tramite matrici di confusione e metriche di precision/recall per minimizzare i falsi positivi (censura non necessaria).

## 🛠 Tech Stack
* **Linguaggio:** Python
* **Deep Learning:** `TensorFlow` / `Keras`.
* **NLP & Data Handling:** `Pandas`, `NumPy`, `Scikit-learn`.

## 📈 Applicazioni Business
- **Scalable Content Moderation:** supporto ai team di moderazione per gestire grandi volumi di contenuti generati dagli utenti (UGC).
- **Brand Protection:** identificazione tempestiva di commenti dannosi che potrebbero ledere la reputazione aziendale.
- **Safe Communities:** creazione di ambienti digitali più sicuri tramite l'automazione della policy di community.

## 📂 Struttura del Repository
- `Filtro anti-hater per social network.ipynb`: notebook completo con l'analisi esplorativa, l'architettura della rete e il processo di addestramento.
