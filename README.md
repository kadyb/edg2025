# Eksploracja danych geoprzestrzennych

To repozytorium zawiera materiały do kursu "Eksploracja danych geoprzestrzennych" prowadzonego
na Uniwersytecie Adama Mickiewicza w semestrze letnim w 2025 r.

Eksploracyjna analiza danych jest kluczowym krokiem w zrozumieniu zbiorów danych, odkrywaniu wzorców
i identyfikacji anomalii przed przystąpieniem do modelowania. Kurs ten stanowi kompleksowe wprowadzenie
do eksploracyjnej analizy danych ze szczególnym uwzględnieniem danych przestrzennych przy użyciu języka
programowania R. Druga część kursu obejmuje wprowadzenie do modelowania danych wykorzystując narzędzia
uczenia maszynowego do analizy regresji oraz klasyfikacji (nadzorowanej i nienadzorowanej).

# Wstęp

**1. Instalacja R**

Interpreter języka **R** można pobrać dla [Windows](https://cloud.r-project.org/bin/windows/base/),
[MacOS](https://cran.r-project.org/bin/macosx/) oraz [Linux](https://cloud.r-project.org/bin/linux/).

**2. Instalacja RStudio**

**RStudio** jest zintegrowanym środowiskiem programistycznym z edytorem kodu.
Aplikacja dostępna jest na różnych platformach do pobrania w [tym miejscu](https://posit.co/download/rstudio-desktop/).

**3. Instalacja pakietów**

Jednym z najpopularniejszych pakietów do analizy przestrzennej w R jest pakiet [**terra**](https://github.com/rspatial/terra).
Umożliwia on analizę zarówno danych rastrowych i wektorowych.
Można go zainstalować w następujący sposób:

```r
install.packages("terra")
```

Następnie można go załadować używając funkcji `library()`.

```r
library("terra")
```

Dokumentację do tego pakietu znajdziesz tutaj: <https://rspatial.github.io/terra/reference/terra-package.html>

# Materiały do kursu

1. [Wprowadzenie do R](https://kadyb.github.io/edg2025/cwiczenia/01_Wprowadzenie_do_R.html)
2. [Przetwarzanie danych przestrzennych](https://kadyb.github.io/edg2025/cwiczenia/02_Przetwarzanie_danych.html)
3. [Analiza danych](https://kadyb.github.io/edg2025/cwiczenia/03_Analiza_danych.html)
4. [Redukcja wymiarowości](https://kadyb.github.io/edg2025/cwiczenia/04_Redukcja_wymiarowosci.html)
5. [Klasyfikacja nienadzorowana](https://kadyb.github.io/edg2025/cwiczenia/05_Grupowanie.html)
6. [Klasyfikacja nadzorowana](https://kadyb.github.io/edg2025/cwiczenia/06_Klasyfikacja.html)
7. Analiza regresji

# Materiały dodatkowe

1. ["Geocomputation with R"](https://r.geocompx.org/) Robin Lovelace, Jakub Nowosad i Jannes Muenchow
2. ["Spatial Data Science with R and terra"](https://rspatial.org/) Robert Hijmans i inni

# Kontakt 

W razie pytań proszę o kontakt na <krzysztof.dyba@amu.edu.pl>.
