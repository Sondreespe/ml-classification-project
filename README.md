# ML Classification Project

Et maskinlæringsprosjekt for klassifisering av håndskrevne tegn ved hjelp av SVM og KNN, med PCA for dimensjonsreduksjon.

## Beskrivelse

Prosjektet er delt inn i tre oppgaver:

1. Trening og evaluering av baseline-klassifikatorer (SVM og KNN)
2. Dimensjonsreduksjon med PCA og sammenligning av ytelse og hastighet
3. Analyse av et korrupt datasett ved hjelp av den trente modellen

## Tech Stack

- **Python 3**
- **NumPy** – array-operasjoner og datalasting
- **Matplotlib** – visualisering
- **Pandas** – databehandling
- **scikit-learn** – ML-modeller, pipelines, preprocessing og evaluering
- **Jupyter Notebook** – kjøremiljø for prosjektet

## Installasjon

Installer nødvendige pakker med:

```bash
pip install numpy matplotlib pandas scikit-learn jupyter
```

## Slik kjører du prosjektet

1. Sørg for at følgende filer ligger i samme mappe som notebooken:
   - `dataset.npz`
   - `dataset_corrupted.npz`

2. Start Jupyter Notebook:

\```bash
jupyter notebook project2.ipynb
\```

3. Kjør alle celler i rekkefølge ved å velge **Run All** (`Ctrl+F9`)

## Prosjektstruktur

\```
ml-classification-project/
├── project2.ipynb          # Hovednotebook med alle oppgaver
├── dataset.npz             # Originalt datasett
├── dataset_corrupted.npz   # Korrupt datasett (brukes i oppgave 3)
└── README.md
\```



