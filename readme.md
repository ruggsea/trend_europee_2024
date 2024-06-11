## Dataset trend fra Elezioni Politiche Italiane 2022 e Elezioni Europee 2024

Il dataset calcola le differenze di tendenza di voto (in percentuale) tra le elezioni politiche italiane del 2022 e le elezioni europee del 2024. I dati sono stati calcolati a partire dei due dataset originali resi disponibili da OnData. 
Partiti politici considerati:
- Fratelli d'Italia
- Partito Democratico
- Movimento 5 Stelle
- Lega
- Forza Italia (insiema a Noi Moderati)

Il dataset principale è `trend_liste_europee_2024_politiche_2022.csv`, che contiene i cambiamenti in percentuale di voto per ogni partito politico. Ogni riga rappresenta un comune italiano e ha come indice il codice ISTAT del comune, per permettere l'incrocio con i dati geografici.

Per risparmiarsi la fatica, `comuni_italiani_trend_liste_2022_2024.geojson` è appunto l'incrocio tra i dati geografici comunali ISTAT e i dati sui trend di voto. 

La repo contiene inoltre delle mappe fatte in Matplotlib per dare un idea dei principali trend ricavati.

Il codice per riprodurre il dataset e le mappe è disponibile in `mapping_eu.ipynb`.
