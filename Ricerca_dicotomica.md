# RICERCA DICOTOMICA
*L'algoritmo di ricerca binaria o dicotomica è un algoritmo che viene utilizzato per trovare elementi in un array ordinato*
- Si usa il termine dicotomica (dal greco: tagliare in due) perché si procede a divisioni successive dell’array.
- Questo algoritmo rientra dunque nella famiglia degli algoritmi che utilizzano il metodo divide et impera.
- Utilizzare la ricerca binaria in un array ordinato è molto più efficiente rispetto alla ricerca sequenziale, specialmente se l’array contiene tanti elementi.

- Conosciuto il criterio di ordinamento del vettore (per esempio crescente), è impostato su 2 step:
  - Si trova la posizione media del vettore e si confronta il suo contenuto con il valore cercato: se i due valori sono uguali, abbiamo trovato nella posizione media.
  - Se i due valori non sono uguali, si ripete il primo step, cercando nella metà del vettore in cui è possibile trovare il valore.
 
## Passaggi logici della ricerca dicotomica

## Codice:
```
int cera (int *V)
```
