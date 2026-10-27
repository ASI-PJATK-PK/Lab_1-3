https://vincentarelbundock.github.io/Rdatasets/csv/AER/CollegeDistance.csv

Proszę o wykorzystanie już zdobytej wiedzy i zautomatyzowanie procesów w GitHub Action.

# Lab3 — Analizator wyników

## Zasady oddawania

1. **Nazwa repozytorium** musi zawierać numer s studenta (lub numery studentów), np. `Lab-3_sXXXXX` (można kontynuować dotychczasowe repo Lab1/Lab2, zmieniając nazwę i zachowując numer s).
2. **Zadanie Lab3** musi mieć **dedykowany branch** z rozwiązaniem (np. `lab3`). Poprzednie laboratoria pozostają na swoich branchach.
3. **Oddanie** odbywa się wyłącznie przez Microsoft Teams: przesłanie **linku do brancha** z rozwiązaniem Lab3 (jako **link**, nie jako plik tekstowy).
4. **Każda poprawa** wymaga przesłania **nowego linku** do brancha z poprawionym rozwiązaniem.
5. **Commity** przesłane po ostatecznym terminie oddania będą traktowane jako **oszustwo**.

---

## Zadanie 1: Budowa modelu predykcyjnego (20 punktów)

**Cel:**
Na podstawie dostarczonego datasetu studenci mają za zadanie zbudować model predykcyjny, który będzie przewidywał zmienną score. Powinni wybrać odpowiedni algorytm, przeprowadzić analizę danych i ocenić jakość modelu. Do całej pracy ma zostać stworzona dokumentacja, może być w formie Readme.pdf i tam zamieszczone wykresy, albo można użyć bardziej profesjonalnego oprogramowania do tworzenia dokumentacji IT.

### Etapy:

**Eksploracja i wstępna analiza danych (5 punktów)**

- Wczytanie i zapoznanie się z danymi.
- Sprawdzenie brakujących wartości oraz ich odpowiednia obsługa (np. imputacja lub usunięcie).
- Analiza statystyczna zmiennych.
- Ocena: 5 punktów za pełną eksplorację danych, w tym wykresy i opisy zmiennych.

**Inżynieria cech i przygotowanie danych (5 punktów)**

- Przeprowadzenie odpowiedniej inżynierii cech (np. kategoryzacja, standaryzacja, normalizacja, tworzenie nowych zmiennych, jeśli konieczne).
- Podział danych na zbiór treningowy i testowy.
- Ocena: 5 punktów za poprawne przygotowanie danych, z wyjaśnieniem wszystkich kroków.

**Wybór i trenowanie modelu (5 punktów)**

- Wybór odpowiedniego algorytmu (np. regresja liniowa, lasy losowe, regresja logistyczna, sieci neuronowe itp.) (WYBÓR MIĘDZY MINIMUM 3).
- Wytrenowanie modelu na zbiorze treningowym.
- Wyjaśnienie, dlaczego wybrano dany model.
- Ocena: 5 punktów za wybór odpowiedniego modelu i poprawne przeszkolenie modelu.

**Ocena i optymalizacja modelu (5 punktów)**

- Ocena jakości modelu na zbiorze testowym (np. przy użyciu metryk takich jak R², MAE, MSE).
- Jeśli wyniki nie są satysfakcjonujące, należy przeprowadzić optymalizację (np. tunowanie hiperparametrów, walidacja krzyżowa).
- Ocena: 5 punktów za ocenę modelu i ewentualną optymalizację.
