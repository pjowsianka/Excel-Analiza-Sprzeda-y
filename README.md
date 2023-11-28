# Analiza Danych - Zadania 1 i 2

Przedstawiam poniżej analizę dwóch zadań, które zostały przeprowadzone na danych z plików Excel. Szczegółowe treści zadań można znaleźć w pliku Treść Zadań.pdf

### Źródła Danych

- **Zadanie 1:** Dane do analizy zostały dostarczone w pliku Analiza produktów w kategorii Smartfony.xlsx.
  
- **Zadanie 2:** Dane dla drugiego zadania zostały udostępnione w pliku Sprzedaż w II półroczu 2022.xlsx. 


## Zadanie 1

### 1. Wczytanie danych z pliku CSV

Dane zostały wczytane z pliku CSV do odpowiedniej struktury danych.

### 2. Zamiana separatora dziesiętnego

W kolumnie "przychody2" dokonano zamiany kropek na przecinki, aby umożliwić poprawne odczytanie liczb dziesiętnych.

### 3. Przetwarzanie daty

W celu lepszej analizy danych, daty zostały podzielone na trzy osobne kolumny: dzień, miesiąc i rok. Następnie przekształcono te zmienne w formę uniwersalną dla poprawnego sortowania.

### 4. Usuwanie zbędnych odstępów

W kolumnie "źródło ruchu" zastosowano funkcję usuń.zbędne.odstępy (trim), aby usunąć nadmiarowe spacje i utworzyć nową kolumnę z poprawionymi danymi.

### 5. Tworzenie tabeli przestawnej

Na podstawie przetworzonych danych utworzono tabelę przestawną, umożliwiającą grupowanie danych według wybranych kategorii i wykonywanie obliczeń.

### 6. Tworzenie pól obliczeniowych

Na podstawie tabeli przestawnej stworzono pola obliczeniowe, takie jak średni przychód na sesję czy konwersja.

### 7. Stworzenie tabel i wykresów potrzebnych do analizy

Utworzono tabele i wykresy, które pozwalają na głębszą analizę danych.

### 8. Utworzenie arkusza "Analiza"

Na arkuszu "Analiza" opisano wnioski z analizy wykresów oraz zaproponowano dalsze działania na podstawie uzyskanych danych.

## Zadanie 2

### 1. Przeniesienie kolumny "transactionid"

Kolumna "transactionid" została przeniesiona z pierwszej tabeli na lewą stronę w celu zastosowania funkcji VLOOKUP.

### 2. Użycie funkcji VLOOKUP

Zastosowano funkcję VLOOKUP dla drugiej tabeli, a wyniki przeniesiono do nowego arkusza o nazwie "TabelaDanych".

### 3. Zamiana kropek na przecinki

W kolumnie "przychody" dokonano zamiany kropek na przecinki za pomocą kombinacji klawiszy Ctrl+H, umożliwiając poprawne odczytanie danych liczbowych przez Excel.

### 4. Utworzenie tabel przestawnych i wykresów

Stworzono tabele przestawne wraz z odpowiednimi wykresami, które odpowiadają na pytania analizy.

### 5. Stworzenie dashboardu

Utworzono dashboard, który łączy wszystkie wykresy, umożliwiając łatwe monitorowanie i analizowanie danych.

![image](https://github.com/pjowsianka/Excel-Analiza-Sprzeda-y/assets/130370888/ec505ff0-816f-4323-abf4-5e89880e63f5)


