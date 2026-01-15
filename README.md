# ProgetttoAI2
Progetto esame AI2 
Modello di classificazione binaria per predire l'outcome clinico (evento avverso vs censura) in pazienti HIV-positivi, basato sui dati dello studio ACTG 175.
Fonte: UCI Repository
Campioni: 2.139 pazienti
Feature: 23 variabili (demografiche, cliniche, terapeutiche)
Target: label (0 = no evento, 1 = event
Per far funzionare il progetto bisogna inserire nella variabile df la sua posizione del file AIDS_ClinicalTrial_GroupStudy175.csv, come mostrato sotto e poi semplicemente runnare partendo dall'installazione delle librerie:
df = pd.read_csv('../var/AIDS_ClinicalTrial_GroupStudy175.csv')

Dataset: AIDS Clinical Trials Group Study 175 (UCI ML Repository)

Librerie:
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
