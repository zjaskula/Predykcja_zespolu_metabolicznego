# Predykcja zespołu metabolicznego

Projekt polega na budowie modelu predykcyjnego umożliwiającego identyfikację pacjentów z zespołem metabolicznym na podstawie danych demograficznych i klinicznych. Wykorzystano publiczny zbiór danych dostępny na platformie Kaggle [[link do zbioru]](https://www.kaggle.com/datasets/antimoni/metabolic-syndrome/data).

## Zastosowane metody
Analiza została przeprowadzona w środowisku `R` i obejmuje:
- eksploracyjną analizę danych i statystyki opisowe,
- analizę brakujących danych oraz imputację wielokrotną metodą MICE,
- budowę modelu regresji logistycznej.

## Wyniki
Otrzymany model regresji logistycznej pozwala przewidywać prawdopodobieństwo wystąpienia zespołu metabolicznego na podstawie wybranych cech klinicznych. Analiza wskazuje również istotne zależności między zmiennymi, w tym interakcję wieku i poziomu glukozy.

## Uruchomienie
Analizę można odtworzyć, uruchamiając kod w środowisku R.
