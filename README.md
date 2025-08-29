# Progetto di Algoritmi e Strutture Dati

Questo progetto universitario ha come obiettivo lo **studio, l’implementazione e l’analisi sperimentale** di tre algoritmi di selezione del k-esimo elemento in un array:

- **Quick Select**
- **Median of Medians Select**
- **Heap Select** (sia versione con `MinHeap` implementata a lezione, sia versione ottimizzata con `heapq` di Python)

## Descrizione attività
- **Analisi teorica** degli algoritmi e della loro complessità temporale (casi medio e peggiore).
- **Implementazione in Python 3** con diverse versioni (naive/ottimizzata).
- **Pseudocodice e spiegazione** del funzionamento di ciascun algoritmo.
- **Esperimenti su array di diverse dimensioni** per misurare i tempi di esecuzione medi.
- **Benchmark e grafici** (scala lineare e log-log) per confrontare efficienza e stabilità.
- **Conclusioni comparative**: punti di forza e limiti di ciascun algoritmo.

## Risultati principali
- Quick Select → generalmente il più efficiente nei test, ma con fluttuazioni dovute alla scelta del pivot.
- Median of Medians Select → più stabile, crescita quasi lineare, buona prevedibilità.
- Heap Select → andamento simile a Median of Medians ma con maggiori fluttuazioni, soprattutto su input grandi.

📄 Per i dettagli completi (analisi, pseudocodice, grafici e conclusioni) consultare la relazione:  
[Relazione_Algoritmi.pdf](Relazione_Algoritmi.pdf)

## Autori
- Alessandro Roncadin  
- Alex Schiavoni  
- Francesco De Matteis  
- Matteo Pavan  
