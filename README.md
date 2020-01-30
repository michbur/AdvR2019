## Zaawansowane Programowanie w R 2019/2020

Strona przedmiotu Zaawansowane programowanie w R na wydziale MiNI PW.

> If you think you can learn all of R, you are wrong. For the foreseeable future you will not even be able to
> keep up with the new additions.
>

[Patrick Burns (Inferno-ish R)](https://www.burns-stat.com/documents/books/the-r-inferno/), CambR User Group Meeting, Cambridge (May 2012)

### Plan zajęć

| Data  | Wykład                                                                  | Laboratoria                                                        | Projekt | PD | Wyjściówka |
|-------|-------------------------------------------------------------------------|--------------------------------------------------------------------|---------|----|------------|
| 03.10 | Dobre praktyki tworzenia kodu w R.                                      | Efektywne programowanie w R.                                       |         | 1  |            |
| 10.10 | Znajomość pakietów z rodziny tidyverse.                                 | Lexical scoping. Elementy programowania obiektowego.               |         |    | 1          |
| 17.10 | Tworzenie pakietów R (część 1).                                         | Dokumentacja (roxygen2, pkgdown) i testowanie kodu (testthat).     | 1*      | 2  |            |
| 24.10 | Tworzenie pakietów R (część 2).                                         | Dobre praktyki tworzenia pakietów.                                 | 1*      |    |            |
| 31.10 |                                                                         |                                                                    |         |    |            |
| 07.11 | Shiny. Programowanie reaktywne.                                         | Tworzenie aplikacji Shiny. Shiny i Electron.                       | 1       |    | 2          |
| 14.11 | Prezentacje wyników projektu 1.                                         |                                                                    |         |    |            |
| 21.11 | R jako interfejs do obliczeń rozproszonych.                             | ShinyJS. shinyproxy.                                               |         | 3  | 3          |
| 28.11 | Prezentacje studentów.                                                  | Programowanie równoległe w R.                                      | 2       |    |            |
| 05.12 | Prezentacje studentów.                                                  | Reprodukowalne analizy w R (drake, archivist).                     | 2       |    | 4          |
| 12.12 | Prezentacje studentów.                                                  | Praktyczne uczenie maszynowe w R.            | 2       | 4  |            |
| 19.12 | Znajomość pakietów z rodziny DrWhy.AI.                                  | XAI w R.                                                           | 2       |    | 5          |
| 16.01 | Praca z bazami danych w R.                                              |                                                                    | 2       |    |            |
| 23.01 | Prezentacje wyników projektu 2.                                         |                                                                    |         |    |            |
| 30.01 | Rozwój R.                                                               | R i API. Plumber.                                                  |         |    |            |

### Zasady zaliczenia

Zaliczenie jest oparte o cztery składowe:

Punkty z prac domowych (4 prac domowych, każda praca to od 0 do 5 punktów).
Punkty z wyjściówek (5 wyjściówek, każda oddana wyjściówka to od 0 do 3 punktów).
Punkty z projektów. W semestrze wykonać należy dwa projekty. Każdy projekt to od 0 do 25 punktów.
Punkty z prezentacji wybranego tematu. Poprawnie wykonana prezentacja to od 0 do 15 punktów.
W sumie uzyskać można do 100 punktów. 51 punktów zalicza przedmiot.

51-60 ocena 3
61-70 ocena 3,5
71-80 ocena 4
81-90 ocena 4,5
91-100 ocena 5

#### Projekt

Każdy projekt wykonuje się w grupie do 5 osób. Nie wolno wykonywać projektu z osobami, z którymi wykonywało się inny projekt na tym przedmiocie bądź prezentację. Projekty można realizować z osobami z innej grupy ćwiczeniowej. Za każdy projekt można otrzymać do 25 punktów z czego:
 
 - 1 punkt za każdą konsultację projektu podczas spotkania projektowego. Za każdą konsultację uznaje się przedyskutowanie z prowadzącym postępów w pracy nad projektem podczas spotkania projektowego. W ciągu jednego spotkania nie można zdobyć więcej niż 1 punkt.
 - od 0 do 10 punktów za poprawność techniczną projektu (np. dobrze skomentowany, udokumentowany i przetestowany kod).
 - od 0 do 5 punktów za dodatkowy wysiłek włożony w projekt (np. porównanie z innymi, istniejącymi rozwiązaniami).
 - od 0 do 5 punktów za ciekawą prezentację projektu.  

Rezultaty projektu są prezentowane przez studentów podczas wykładów 14.11 i 16.01. Każda grupa ma ok. 7 minut na prezentację. 
 
#### Prezentacja

Prezentację na zadany temat przygotowuje i wygłasza w grupach do 3 osób. Nie wolno przygotować prezentacji z osobami, z którymi wykonywało się projekt na tym przedmiocie. Prezentację można przygotować z osobami z innej grupy ćwiczeniowej. Każda prezentacja powinna być również uzupełniona cheatsheetem z omawianego pakietu. Za prezentację można otrzymać do 15 punktów z czego:

 - od 0 do 5 punktów za informatywny cheatsheet.
 - od 0 do 5 punktów za prawidłowo przygotowaną prezentację.
 - od 0 do 5 punktów za ciekawe wygłoszenie prezentacji.

#### Prace domowe

W trakcie semestru pojawią cztery prace domowe. Prace domowe należy oddać do północy do dnia w którym zostanie ogłoszona następna praca domowa. Prace domowe należy rozwiązywać samodzielnie.

#### Wyjściówki

W trakcie semestru podczas zajęć laboratoryjnych pojawi się pięć wyjściówek. Wyjściówki należy rozwiązać samodzielnie i zgłosić rozwiązanie w repozytorium przed zakończeniem zajęć laboratoryjnych danej grupy.

### Efekty kształcenia

Student:

- Zna i potrafi używać zaawansowanych narzędzi do wizualizacji danych w R.
- Zna i potrafi wykorzystywać obiektowe i funkcyjne paradygmaty programowania w R.
- Potrafi korzystać i tworzyć w R narzędzia do wizualizacji danych.
- Potrafi tworzyć internetowe aplikacje Shiny.
- Potrafi wykorzystać R jako interfejs do systemów rozproszonych.
- Potrafi tworzyć pakiety R wraz z dokumentacja i testami jednostkowymi.
- Potrafi w zespole tworzyć pakiety R i aplikacje internetowe Shiny.

### Materiały pomocnicze

- [Przemysław Biecek; Przewodnik po pakiecie R](http://pbiecek.github.io/Przewodnik/).
- Marek Gągolewski; Programowanie w języku R.
- [Jakub Nowosad, Elementarz programisty](https://nowosad.github.io/elp/).
- [Hadley Wickham; Advanced R](https://adv-r.hadley.nz/).
- [Patrick Burns; The R Inferno](https://www.burns-stat.com/documents/books/the-r-inferno/).
- Michael J. Crawley; R Book.
- [Hadley Wickham, Jennifer Bryan;](https://r-pkgs.org/).
