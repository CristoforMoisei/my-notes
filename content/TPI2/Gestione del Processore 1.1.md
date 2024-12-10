## Rilocazione

- **Statica**: Indirizzo di base sommato all’offset all’inizio.

- **Dinamica**: Indirizzo di base sommato all’offset durante il processo.

  

## Traduzioni degli Indirizzi

- **MMU**: Traduce indirizzi logici in fisici.

- **Linking**: Calcolo degli indirizzi logici.

- **Binding**: Passaggio da indirizzo logico a fisico.

  

## Caricamento Processi in Memoria

1. Spazio libero sufficiente.

2. Spazio contiguo.

  

### Problemi di Spazio Contiguo

- **Frammentazione Esterna**: Spazi insufficienti per il processo.

- **Frammentazione Interna**: Spreco di memoria in partizioni più grandi del necessario.

  

### Soluzioni

- **Swapping**: Libera spazio nella RAM.

- **Caricamento Dinamico**: Carica solo moduli necessari.

- **Overlay**: Divide il programma in più parti.

- **Partizionamento della Memoria**:

  - **Fissa**: Blocchi di dimensione prefissata.

  - **Variabile**: Blocchi dinamici.

  

### Allocazione Dinamica

- **First-fit**: Prima zona libera sufficiente.

- **Best-fit**: Zona libera più piccola sufficiente.

- **Worst-fit**: Zona libera più grande.

- **Next-fit**: Partendo dall'ultima allocazione.