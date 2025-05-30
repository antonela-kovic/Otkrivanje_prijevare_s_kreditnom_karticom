
# Otkrivanje prijevare s kreditnom karticom

Ovaj projekt koristi strojno učenje za otkrivanje prijevara s kreditnim karticama u stvarnim transakcijama. Projekt implementira analizu podataka, obradu neuravnoteženog skupa podataka te evaluaciju modela za klasifikaciju transakcija kao prijevarne ili ispravne.

## Ciljevi projekta

* Analizirati i vizualizirati podatke o transakcijama.
* Riješiti problem neuravnoteženih klasa korištenjem tehnika kao što su **SMOTE**.
* Trenirati modele za otkrivanje prijevara, uključujući:

  * Logistic Regression
  * Random Forest Classifier
    
* Evaluirati modele pomoću metrika:

  * Preciznost, točnost, recall i F1 score.
  * ROC AUC krivulje.
* Izraditi jednostavnu interpretaciju rezultata i preporuke za daljnja poboljšanja.

## Struktura projekta

```
 Otkrivanje_prijevare_s_kreditnom_karticom.ipynb
 data/
    └── creditcard.csv
```

## Korištene tehnologije

* **Python** (Jupyter Notebook)
* **pandas** — analiza podataka
* **numpy** — numeričke operacije
* **matplotlib** i **seaborn** — vizualizacija
* **scikit-learn** — ML modeli i evaluacija
* **imbalanced-learn** — SMOTE za balansiranje klasa

##  Kako pokrenuti

1. Kloniraj repozitorij:

   ```bash
   git clone https://github.com/korisnik/ime-repozitorija.git
   cd ime-repozitorija
   ```
2. Instaliraj ovisnosti:

   ```bash
   pip install -r requirements.txt
   ```
3. Pokreni Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Otvori i pokreni `Otkrivanje_prijevare_s_kreditnom_karticom.ipynb`.

##  Rezultati

Projekt pokazuje da korištenjem modela poput Random Forest Classifier i Logistic Regression možemo značajno povećati točnost detekcije prijevara, uz visoke vrijednosti recall i F1 score. Primjena SMOTE-a pomaže u balansiranju skupa podataka i smanjuje pristranost modela prema dominantnoj klasi.

##  Moguća poboljšanja

* Isprobati naprednije modele poput **XGBoost** ili **LightGBM**.
* Uvesti **feature engineering** za dodatnu optimizaciju performansi.
* Uključiti **analizu važnosti značajki** za bolju interpretaciju modela.

