# Raport

Projekt eUDT

Raport z testów

ID: RAP.001

Autor: Bartłomiej Stasiak

#### Spis treści


### 1. Metryka dokumentu
|                |      |
|----------------|------|
| Nazwa produktu | eUDT |
| Etap  | Pierwszy |
| Obszar/Moduł | System eUDT |

### 2. Historia dokumentu
|||||
|--------|----------|------|-----------|
| Wersja | Utworzył | Data | Opis zmian |
| 0.001  | Bartłomiej Stasiak | 15.03.2018 | Pierwsza wersja dokumentu|
### 3. Lista załączników
| Nr. | Nazwa dokumentu | Wersja | Miejsce przechowywania dokumentu |

### 4. Slowing

### 5. Podsumowanie
Podczas tygodnia 12.03.18-16.03.18 zostały wykonane testy funkcjonalne systemu eUDT.
Testy przeprowadził niezależny zespół testerów.
Zostało wykrytych 71 błędów w tym 6 błędów krytycznych, z czego 5 nie zostało do tej pory
rozwiązanych.
#### 5.1 Rekomendacja
Nie wszystkie wymagane funkcje zostały zaimplementowane oraz nie wszystkie błędy zostały
naprawione. W moim odczuciu system nie jest jeszcze gotowy do wdrożenia. Rekomenduję
wykonać więcej testów wewnętrzych przed przejściem do etapu testów akceptacyjnych.
### 6. Kryteria wejścia
| Kryterium | Spełnienie |
|------|------|
|Przygotowanie przypadków (10) i scenariuszy (2) testowych.| |
|Przygotowanie środowiska testowego.| |
|Przygotowanie i konfiguracja stanowisk testowych.| |
|Przygotowanie opisu testów wewnętrznych.| |
|Akceptacja scenariuszy testowych przez zamawiającego.| |
### 7. Kryteria wyjścia
| Kryterium | Spełnienie |
|-----------|------------|
|Wykonanie 10 przypadku testowych.| |
|Brak błędów krytycznych.| |
|Wydajność nie mniejsza niż 90% wymaganej. | Nie zweryfikowane |

### 8. Środowisko testowe
System eUDT – środowisko testowe portalu wewnętrznego.
System operacyjny: Windows 8.1
Przeglądarka internetowa: Opera 51.0.2830.55
### 9. Zakres testów
Typ testów:
- testy funkcjonalne

Ilość scenariuszy testowych: 2

- Natalia_15.03
 5 przypadków testowych (eUDT-28, eUDT-44, eUDT-67, eUDT-101, eUDT-149)
- iwona czeladko
 5 przypadków testowych (eUDT-40, eUDT-54, eUDT-77, eUDT-99, eUDT-136)
### 10. Harmonogram testów
| Lp. | Data | Godzina | Czynność |
|-----|------|---------|----------|
|1. | 12.03.18 | 14:00 | Przygotowywanie planu testów. |
|2. | 13.03.18 | 9:00  |Przygotowanie i konfiguracja stanowiska i narzędzi testowych |
|3. | 13.03.18 | 14:00 | Przygotowywanie przypadków i scenariuszy testowych. |
|4. | 14.03.18 | 14:00 | Rozpoczęcie wykonywania testów. |
|5. | 14.03.18 | 14:30 | Aktualizacja środowiska testowego. |
|6. | 15.03.18 | 13:00 | Zakończenie testów. |
|7. | 15.03.18 | 14:00 | Przygotowywanie raportu z testów. |
### 11. Wyniki testów
|   |Logowanie | Rejestracja | Operacje w systemie | Łącznie |
|---|--------|-------------|-------------------- |---------|
|Pozytywne | 0 | 2 | 1 | 3 |
|Negatywne | 1 | 2 | 3 | 6 |
|Niewykonane | 0 | 0 | 1 | 1 |
|Zablokowane | 0 | 0 | 0 | 0 |
### 12. Błędy
|   |W toku | Do zrobienia | Gotowe | Łącznie |
|---|-------|--------------|--------|---------|
|Krytyczne | 1 | 4 | 1 | 6 |
|Poważne | 1 | 6 | 1 | 8 |
|Średnie | 7 | 35 | 8 | 50 |
|Drobne | 2 | 4 | 1 | 7 |
|Łącznie | 11 | 49 | 11 | 71 |

