# predictie-participare-itf-ml

**Predicția participării la turnee ITF folosind algoritmi de machine learning**

Lucrare de licență — Universitatea Babeș-Bolyai Cluj-Napoca, Facultatea de Științe Economice și Gestiunea Afacerilor, Departamentul de Informatică Economică

**Absolvent:** Andrei Răzvan Laslo Roman
**Profesor coordonator:** Prof. dr. Gheorghe Cosmin Silaghi

## Descriere

Acest repository conține implementarea completă a sistemului de predicție a deciziei de participare a jucătorilor de tenis la turnee ITF, dezvoltat ca parte a lucrării de licență. Sunt comparate cinci modele de clasificare: Regresie Logistică, Arbore de Decizie, Random Forest, XGBoost și Rețea Neuronală Artificială.

## Conținut

- `Licenta_AndreiLaslo.ipynb` — notebook-ul complet, incluzând preprocesarea datelor, analiza exploratorie, antrenarea și optimizarea hiperparametrilor pentru toate cele cinci modele, evaluarea comparativă a performanțelor și interpretarea rezultatelor.
- `Dataset_licenta.xlsx` — datasetul original, colectat prin chestionar de la 88 de jucători de tenis prezenți la turnee ITF organizate în România în perioada martie–aprilie 2026 (1.056 de observații).

## Instrucțiuni de execuție

1. Descarcă fișierele `Licenta_AndreiLaslo.ipynb` și `Dataset_licenta.xlsx`.
2. Deschide notebook-ul în [Google Colab](https://colab.research.google.com/) sau Jupyter local.
3. Asigură-te că `Dataset_licenta.xlsx` este accesibil din mediul de execuție (de exemplu, încarcă-l în Google Drive, în folderul indicat în notebook, sau modifică calea de încărcare către locația locală a fișierului).
4. Rulează celulele în ordine, de la prima la ultima. Notebook-ul instalează automat dependențele suplimentare necesare (`xgboost`, `keras-tuner`).

## Tehnologii utilizate

Python 3.10, pandas, numpy, scikit-learn, XGBoost, TensorFlow/Keras, keras-tuner, matplotlib, seaborn.
