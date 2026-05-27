# Bank Marketing Campaign Analysis - XGBoost Model

Projekt realizowany w ramach przedmiotu *Data Science i AI w bankowości* (semestr letni 2025/26).

## 🎯 Cel projektu
Celem projektu było zbudowanie modelu klasyfikacyjnego przy użyciu algorytmu **XGBoost**, który przewiduje, czy klient banku zdecyduje się na założenie lokaty terminowej. Model ma na celu optymalizację działań marketingowych (call center) poprzez identyfikację klientów o najwyższym prawdopodobieństwie konwersji.

## 🛠️ Wykorzystane technologie
* **Język:** Python 3.13.7
* **Biblioteki:** Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, Matplotlib, Shap
* **Techniki:**
    * Optymalizacja hiperparametrów (BayesSearchCV)
    * `Pipeline` do zapewnienia braku wycieku danych (data leakage)
    * Interpretowalność modelu (Feature Importance, SHAP)
    * Walidacja krzyżowa (Cross-validation)
    * Threshold tuning dla optymalizacji metryk biznesowych

## 📂 Struktura repozytorium
* `/notebooks/` - Jupyter Notebook z pełną analizą i kodem (`model1.ipynb`).
* `/reports/` - Wygenerowany raport końcowy w formacie HTML.
* `/docs/` - Specyfikacja zadania i wymagania projektowe.
* `/data/` - Zbiór danych.

## 🚀 Kluczowe wyniki
* Model osiągnął wysoką skuteczność w rozpoznawaniu potencjalnych klientów (Recall).
* Zastosowano rygorystyczne podejście do walidacji modelu, eliminując wyciek informacji ze zbioru testowego.
* Przygotowano analizę biznesową, wskazującą na konieczność doboru progu odcięcia w zależności od kosztów kontaktu z klientem.

---
*Autor: Oliwier Lewandowski*
*Kontakt: oliwier.lewandowski2525@gmail.com*
