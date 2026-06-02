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
<img width="876" height="547" alt="mix_energetico" src="https://github.com/user-attachments/assets/2b75deb1-6094-4b8f-b980-c65c7a49c7f7" />
<img width="1161" height="545" alt="profilo_orario" src="https://github.com/user-attachments/assets/48121c95-45bc-4a8e-b257-7e9bfce7bb76" />

## Fonte dati
[Terna - Dati Generazione](https://dati.terna.it)
