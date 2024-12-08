### Data Analyst Portfolio Project – Sales Management

![gallery](gallery.png)
### Wymagania użytkownika
W ramach tego projektu analizy danych moim celem biznesowym było stworzenie raportu sprzedażowego dedykowanego kadrze menedżerskiej. Na podstawie otrzymanego zapotrzebowania zdefiniowałem następujące historie użytkowników, aby zapewnić pomyślną realizację projektu i jednocześnie spełnić wszystkie kryteria akceptacji przez cały jego czas trwania.

Każdy element projektu został dopasowany do potrzeb odbiorców i zgodnie z wymaganiami dążyłem do tego, aby końcowy produkt dostarczał wartościowych informacji wspierających podejmowanie decyzji strategicznych.
### Czyszczenie i transformacja danych (SQL)
Aby stworzyć niezbędny model danych do analizy oraz spełnienia wymagań biznesowych zdefiniowanych w historiach użytkowników, wyodrębniłem poniższe tabele przy użyciu SQL.
Jedno ze źródeł danych (budżety sprzedaży) dostarczono w formacie Excel, a jego połączenie z modelem danych nastąpiło na późniejszym etapie procesu.
Poniżej znajdują się instrukcje SQL służące do czyszczenia i transformacji niezbędnych danych.
### DIM_Calendar:
![calendar](DIM_CALENDAR.png)
### DIM_Customers:
![Customers](DIM_CUSTOMERS.png)
### DIM_Products:
![Product](DIM_PRODUCTS.png)
### FACT_InternetSales:
![SALES](DIM_FACTSALES.png)
### Data Model
Poniżej znajduje się zrzut ekranu modelu danych po załadowaniu oczyszczonych i przygotowanych tabel do Power BI.
Model danych pokazuje również, w jaki sposób tabela FACT_Budget została połączona z FACT_InternetSales oraz innymi niezbędnymi tabelami wymiarów (DIM).

![model](DATA_MODEL.png)

### Podsumowanie 
Gotowy pulpit zarządzania sprzedażą zawiera jedną stronę pełniącą funkcję dashboardu i przeglądu, oraz dwie dodatkowe strony skupiające się na łączeniu tabel, aby dostarczyć niezbędnych szczegółów i wizualizacji przedstawiających sprzedaż w czasie, według klientów oraz według produktów.


![dashboard1](dashboard1.png)

![dashboard2](dashboard2.png)

### Zapraszam do pobrania pliku projektowego i wypróbowania dashboardu w Power Bi!  
Możesz pobrać [plik tutaj](project.pbix)











