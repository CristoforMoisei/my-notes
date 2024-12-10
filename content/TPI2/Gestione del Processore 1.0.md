
## Programma

Insieme di istruzioni, memorizzate su memoria di massa.

  

## Processo

Risiede in RAM.

  

### Multiprogrammazione

Contemporanea presenza di più programmi in memoria.

  

### Scheduling

- **Job Scheduling**: Strategie per scegliere quali programmi dal disco devono essere caricati in RAM.

- **CPU Scheduling**: Strategie per assegnare e sospendere l’utilizzo della CPU.

  

### Tipi di Processi

- **Indipendenti**: Evolvono autonomamente senza scambio dati con altri processi.

- **Cooperanti**: Necessitano di scambiare informazioni per evolvere.

- **Competitori**: Ostacolano l'uso della stessa risorsa, compromettendo la terminazione.

  

## Stati del Processo

1. **New**: Appena creato e caricato in RAM.

2. **Ready**: Pronto con tutte le risorse tranne la CPU.

3. **Running**: La CPU esegue le sue istruzioni.

4. **Waiting**: Attende risorse necessarie.

5. **Terminated**: Esecuzione completata.

  

### Transizioni

- Termina l'esecuzione.

- Esaurisce il tempo di CPU (torna in ready list).

- Attende risorse non disponibili (passa in waiting list).

  

### Descrittore di Processo

Informazioni mantenute dal SO per tracciare lo stato del processo.