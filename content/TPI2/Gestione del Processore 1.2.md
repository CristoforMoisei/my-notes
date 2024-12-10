# Paginazione e Segmentazione

  

## Paginazione

Tecnica per allocare programmi in RAM.

  

### Come Funziona

1. Memoria divisa in **frame** (blocchi fissi).

2. Programmi divisi in **pagine logiche**.

3. Mappatura pagine-frame tramite tabella delle pagine.

4. **MMU** traduce indirizzi logici in fisici.

  

### Vantaggi

- Evita frammentazione esterna.

- Supporta memoria virtuale.

  

### Problemi

- **Page Fault**: Necessità di recuperare pagine dal disco.

  

## Segmentazione

Suddivide il programma in segmenti logici (es. codice, dati).

  

### Come Funziona

1. Memoria divisa in segmenti variabili.

2. Ogni segmento ha un **indirizzo base** e un **limite**.

3. Gli indirizzi logici comprendono numero del segmento e offset.

4. Traduzione tramite tabella dei segmenti.

  

### Vantaggi

- Gestione di dati e strutture dinamiche.

- Condivisione segmenti tra processi.

  

### Problemi

- **Frammentazione Esterna**: Spazi inutilizzabili.

  

## Differenze tra Paginazione e Segmentazione

- **Paginazione**: Blocchi fissi, ignora la logica del programma.

- **Segmentazione**: Blocchi variabili basati sulla logica del programma.

  

## Segmentazione con Paginazione

Tecnica ibrida:

- Memoria divisa in segmenti logici.

- Ogni segmento suddiviso in pagine fisse.