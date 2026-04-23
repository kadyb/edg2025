# Analiza cen nieruchomości

## Dane

**Zmienne wyjaśniające:**

 - `distbuses.tif` -- odległość od przystanków autobusowych [m]
 - `distcentre.tif` -- odległość od geometrycznego centrum miasta [m]
 - `distgreens.tif` -- odległość od obszarów zielonych [m]
 - `distpublic.tif` -- odległość od obiektów administracji publicznej [m]
 - `distroads.tif` -- odległość od głównych dróg [m]
 - `diststations.tif` -- odległość od najbliższej stacji kolejowej [m]
 - `distwaters.tif` -- odległość od wody [m]

**Zmienna wyjaśniana:**

 - `ceny.gpkg` -- wartość transakcji nieruchomości [PLN/m^2]

*Zbiór danych został przygotowany przez prof. Jarosława Jasiewicza.*

## Projekt

Celem projektu jest zbadanie i zrozumienie czynników wpływających na
kształtowanie się cen nieruchomości na obszarze Poznania z wykorzystaniem
metody analizy przestrzennej. Projekt obejmuje wykonanie działań obliczeniowych,
wizualizację wyników oraz napisanie raportu analitycznego wraz z interpretacją
wyników. W zależności od zakresu wykonanych prac, można uzyskać następujące oceny:

### Ocena dostateczna

Przeprowadzenie eksploracyjnej analizy danych:

- Sprawdzenie statystyk opisowych, brakujących i odstających wartości oraz
  rozkładu wszystkich zmiennych.
- Zbadanie zależności pomiędzy poszczególnymi zmiennymi wyjaśniającymi oraz
  zmienną wyjaśnianą.
- **Wykonanie analizy głównych składowych dla zmiennych wyjaśniających
  i interpretacja wyników**.
- Wskazanie i wyjaśnienie, która składowa jest najbardziej skorelowana z cenami
  nieruchomości.

### Ocena dobra

Opracowanie modelu regresyjnego cen nieruchomości:

- Zbudowanie modelu liniowego (lub innego wybranego) pomiędzy ceną a zmiennymi
  wyjaśniającymi.
- Dokonanie oceny jakości modelu.
- Zbadanie wpływu transformacji zmiennych na model.
- Stworzenie mapy prognozowanych cen nieruchomości dla całego obszaru.
- **Wyjaśnienie roli poszczególnych zmiennych w modelu**.

Ocena dobra wymaga spełnienia warunków na ocenę dostateczną.

### Ocena bardzo dobra

Analiza wzorców w zbiorze danych:

- Wykonanie grupowania przestrzennego zmiennych wyjaśniających i uzasadnienie
doboru liczby klastrów.
- Wizualizacja wyników klasteryzacji na mapie.
- **Dokonanie interpretacji otrzymanych klastrów**.

Ocena bardzo dobra wymaga spełnienia warunków na ocenę dobrą oraz dostateczną.

\
Projekt należy wykonać w języku R i jako rozwiązanie przesłać na platformie
MS Teams:

1. Działający plik źródłowy (np. Quarto `.qmd` lub RMarkdown `.Rmd`). 
2. Wygenerowany raport z wynikami przeprowadzonej analizy, rycinami oraz
wnioskami (np. `.html` lub `.pdf`). Uwaga: Jeśli generujesz raport w formacie
`.html`, to pamiętaj osadzić wszystkie niezbędne pliki.
