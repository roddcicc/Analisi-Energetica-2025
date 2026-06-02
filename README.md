# Analisi-Energetica-2025

Analisi della generazione elettrica italiana per fonte primaria, basata sui dati ufficiali Terna relativi all'anno 2025.

## Dataset
Dati orari (granularità 15 minuti) scaricati dal portale open data di Terna, contenenti la generazione effettiva in GW suddivisa per fonte primaria: Termoelettrico, Idroelettrico, Fotovoltaico, Eolico, Geotermico, Autoconsumo.

## Strumenti
- Python, Pandas, NumPy, Matplotlib, Seaborn

## Analisi
- Pulizia e conversione dei dati da GW a GWh
- Generazione totale annuale per fonte
- Profilo medio giornaliero per fonte (24 ore)

## Risultati principali
- La quota di energia rinnovabile sul totale nazionale nel 2025 è pari al **38.5%**, in linea con i dati Terna e a conferma della crescita del fotovoltaico rispetto agli anni precedenti
- Il profilo giornaliero evidenzia il ruolo complementare del termoelettrico e dell'idroelettrico nella compensazione della variabilità delle fonti rinnovabili
- L'eolico mostra una produzione pressoché costante nelle 24 ore, ciò è dovuto alla distribuzione degli impianti che compensa l'intermittenza del vento

## Visualizzazioni
| Mix Energetico 2025 | Profilo Medio Giornaliero |
| :---: | :---: |
|  <img width="2631" height="1638" alt="mix_energetico" src="https://github.com/user-attachments/assets/855ca4cb-4c98-40fa-b68f-04ce610ab6cb" />  | <img width="3480" height="1628" alt="profilo_orario" src="https://github.com/user-attachments/assets/f023c1f5-f75f-4142-84d6-dfe5436aacf4" /> |
## Fonte dati
[Terna - Dati Generazione](https://dati.terna.it)




