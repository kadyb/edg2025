# Analiza cen nieruchomości

## Dane

**Zmienne wyjaśniające:**

 - `distbuses.tif` -- odległość od przystanków autobusowych [m]
 - `distcentre.tif` -- odległość od geometrycznego centrum miasta [m]
 - `distgreens.tif` -- odległość od obszarów zielonych [m]
 - `distpublic.tif` -- odległość od obiektów administracji publicznej [m]
 - `distroads.tif` -- odległość od głównych dróg [m]
 - `diststations.tif` -- odległość od najbliższej stacji kolejowej [m]
 - `distwaters.tif` -- odległość do wody [m]

**Zmienna wyjaśniana:**

 - `ceny.gpkg` -- wartość transakcji nieruchomości [PLN/m^2]

*Zbiór danych został przygotowany przez prof. Jarosława Jasiewicza.*

## Projekt

Projekt obejmuje wykonanie działań obliczeniowych, wizualizację wyników oraz
napisanie raportu analitycznego wraz z interpretacją wyników. W zależności od
zakresu wykonanych prac, można uzyskać maksymalnie następujące oceny:

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

Opracowanie modelu przestrzennego cen nieruchomości na badanym obszarze:

- Zbudowanie modelu liniowego lub innego modelu regresyjnego pomiędzy ceną a
  zmiennymi wyjaśniającymi.
- Dokonanie oceny jakości modelu.
- Zbadanie wpływu transformacji zmiennych na model.
- Stworzenie mapy cen nieruchomości.
- **Wyjaśnienie roli poszczególnych zmiennych w modelu**.

### Ocena bardzo dobra

Analiza wzorców w zbiorze danych:

- Wykonanie grupowania przestrzennego zmiennych wyjaśniających i uzasadnienie
doboru liczby klastrów.
- Wizualizacja wyników klasteryzacji na mapie.
- **Dokonanie interpretacji otrzymanych klastrów**.

\
Raport należy wykonać w języku R i przesłać w formacie Quarto lub Markdown na
GitHub Classroom.
