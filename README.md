# wine_quality_classification
# 📊 Predikcia kvality vína pomocou logistickej regresie

Tento projekt sa zameriava na klasifikáciu vín na **podpriemerné** a **nadpriemerné** na základe ich chemického zloženia. Použitý bol dataset [Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality) (červené vína) a algoritmus **logistickej regresie**.

---

## 🧠 Ciele projektu

- Predspracovať dáta a vytvoriť binárnu cieľovú premennú na základe priemernej kvality.
- Preskúmať a vizualizovať vlastnosti dát (EDA).
- Vytvoriť klasifikačný model pomocou logistickej regresie.
- Vyhodnotiť výkonnosť modelu pomocou metrík: presnosť, F1-skóre, ROC AUC.
- Interpretovať váhy modelu a identifikovať najvýznamnejšie premenné.

---

## 🗃️ Dataset

- Zdroj: UCI Machine Learning Repository
- Typ: Červené vína (red wine)
- Počet vzoriek: 1599
- Počet číselných vstupných premenných: 11
- Cieľová premenná: **quality** (hodnotenie od 3 do 8)

---

## ⚙️ Použité technológie

- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (modelovanie a evaluácia)
- Google Colab / Jupyter notebook

---

## 📈 Výsledky modelu

| Metrika        | Hodnota     |
|----------------|-------------|
| Presnosť       | 75.8 %      |
| F1-skóre       | 0.76        |
| ROC AUC        | ~0.84       |

- Najvýznamnejšia pozitívna premenná: **alkohol**
- Najvýznamnejšia negatívna premenná: **volatile acidity**

---

## 🖼️ Vizualizácie (pozri wine quality report)

- Histogramy vstupných premenných
- Korelačná matica
- Boxploty podľa kvality
- ROC krivka
- Matica zámien (confusion matrix)
- Koeficienty modelu

---

## ✅ Záver a odporúčania

Model logistickej regresie dosiahol solídne výsledky pri rozlišovaní medzi vínami podpriemernej a nadpriemernej kvality. V budúcnosti odporúčame:

- Vyskúšať iné modely (napr. Random Forest, XGBoost)
- Vyvážiť triedy, ak dôjde k nevyváženosti
- Použiť pokročilé metódy interpretácie ako SHAP alebo LIME
Podrobnejšie informácie sú uvedené v dokumente wine quality report.pdf

---

## 📁 Štruktúra projektu
- dataset wineQT.csv
- Google colab notebook
- wine quality report.pdf

---

## 📌 Autor

Tento projekt bol vypracovaný ako súčasť portfólia v oblasti strojového učenia.


