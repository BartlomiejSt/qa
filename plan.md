# Plan testów

PLAN TESTÓW

PROJEKT: PLATFORMA „CODERS GURU”

WERSJA: WERSJA 1.0

#### Spis treści


#### METRYKA DOKUMENTU

| Nazwa dokumentu:    |  Plan testów platformy „Coders Guru” |
|------------------   |--------------------------------------|
| Nr ID dokumentu:    | 1P.7.2018                            |
|Streszczenie:        |Celem dokumentu jest opisanie planu testów, które zostaną wykonane dla platformy „Coders Guru”.|
|Projekt:             | Coders Guru                          |
|Właściciel dokumentu:| XYZ S.A.                             |
|Sporządził:          | Bartłomiej Stasiak                   |
|Nr wersji:           | 1.0                                 |
|Data sporządzenia:   | 16.07.2018                           |
|Status:              | do weryfikacji                       |
|Data ostatniej modyfikacji:| 16.07.2018                     |
|Zatwierdził:         | - - -                                |
|Data zatwierdzenia:  | - - -                                |

#### Historia zmian dokumentu

| Nr wersji | Data | Opis zmian | Działanie* | Rozdział** | Autor |
|-----------|------|------------|------------|------------|-------|
| 1.0       |16.07.2018 | Sporządzenie dokumentu | N | W |Bartłomiej Stasiak|

#### Lista załączników

| Lp. | Załącznik | Uwagi |
|-----|-----------|-------|
| 1.  | Codersguru – Specyfikacja Wymagań | - |

#### Slowing

### 1. Wprowadzenie
#### 1.1. Cel i zakres dokumentu
Celem planu testów jest przedstawienie ogólnego zarysu testów, sprawdzających zgodność działania
z wymaganiami funkcjonalnymi platformy internetowej “Coders Guru”. Dokument opisuje zakres,
metody, zasoby i harmonogram wykonania czynności testowych. W dokumencie określone zostały
wymagania funkcjonalne produktu, które należy przetestować. Plan testów został sporządzony z
uwzględnieniem wytycznych dokumentu Standard for Software Test Documentation (IEEE 829-
1998).
#### 1.2. Oczekiwania
Czynności testowania mają za zadanie wykazać czy zaprojektowana platforma spełnia wymagania
funkcjonalne, przedstawione przez Zamawiającego. Wymagania funkcjonalne zawarte są w
specyfikacji wymagań załączonej do tego dokumentu (Załącznik nr 1). Czynności testowania zostaną
wykonane przez niezależny zespół testujący, a wyniki testów zostaną przedstawione
Zamawiającemuw postaci pisemnych raportów.
### 2. Przedmiot testów
#### 2.1. Ogólna charakterystyka produktu
Przedmiotem czynności testowania jest system o nazwie Coders Guru, wraz ze specyfikacją,
stworzony na potrzeby działalności Zamawiającego, mający formę platformy internetowej, łączącej
doświadczonych programistów z osobami, które potrzebują wsparcia w rozwiązaniu konkretnego
problemu. Działanie platformy opiera się na:
• zdalnym połączeniu mentora i klienta za pomocą czatu wideo i tekstowego,
• wymianie plików pomiędzy mentorem i klientem
• edycji kodu na żywo
#### 2.2. Użytkownicy i cele produktu
Użytkownikami platformy są klienci, mentorzy oraz administratorzy.
Platforma ukierunkowana jest na trzy grupy klientów:
• potencjalnych kursantów, którzy rozważają naukę programowania (B2C)
• osoby uczące się samodzielnie i potrzebujące wsparcia mentora (B2C)
• firmy, które opłacają korzystanie z platformy swoim pracownikom (B2B)
Celem platformy jest budowa bazy potencjalnych kursantów oraz potencjalnych wykładowców.
#### 2.3. Elementy podlegające testowaniu
Testom zostanie poddana platforma Coders Guru umieszczona pod adresem: https://men-mens-01.codersguru.pl/ oraz Specyfikacja Wymagań platformy, będąca załącznikiem do tego
dokumentu (Załącznik nr 1).
### 3. Zakres planowanych testów
Planowane jest sprawdzanie, czy wszystkie wymagania funkcjonalne określone w specyfikacji
znalazły swoje odwzorowanie w implementacji systemu. Czynności testowania dotyczyć będą tylko
wymagań funkcjonalnych platformy. Wymagania niefunkcjonalne nie są przedmiotem tego procesu
testowego.
#### 3.1. Wymagania objęte zakresem testów
Czynności testowania mają wykazać czy następujące wymagania funkcjonalne zostały spełnione:
(Tabela wymagań)
#### 3.2. Wyłączenie z zakresu testów
Przez realizowane testy nie będą weryfikowane następujące wymagania:
(Tabela wymagań)
### 4. Podejście do testów
#### 4.1. Poziom i typ testów
W związku z faktem, że testowana platforma jest już zintegrowanym systemem, w celu sprawdzenia
zgodności z wymaganiami przeprowadzone zostaną testy systemowe, badające funkcjonowanie
produktu jako całości. Na działającym systemie będą odbywały się testy dynamiczne.
Testowanie będzie opierało się na podejściu metodycznym – przypadki testowe zostaną
zaprojektowane na podstawie zdefiniowanego wcześniej zestawu warunków testowych ustalonego
m.in. na podstawie wymagań produktu.
#### 4.2. Wykorzystane techniki projektowania testów oraz narzędzia
W celu przetestowania wymienionych wymagań odpowiednie będą testy funkcjonalne, z
zastosowaniem technik opartych na specyfikacji – technik czarnoskrzynkowych. I tak, zostaną użyte
następujące techniki projektowania testów:
• podział na klasy równoważności

• analiza wartości brzegowych
• testowanie przejść między stanami
• tablica decyzyjna
• testowanie oparte na podstawie przypadków użycia
Do przeprowadzenia testów zastosowanie mogą mieć również techniki oparte na doświadczeniu.
W przypadku testowania testowania platformy zostaną wykorzystane narzędzia wspomagające
proces testowy takie jak Jira i TestLink.
#### 4.3. Fazy testów
Proces testowy zostanie podzielony na etapy, ze względu na wskazane przez Zamawiającego
priorytety prawidłowego działania poszczególnych funkcjonalności. W związku z powyższym,
testowanie odbędzie w 3 etapach, zaczynając od funkcjonalności koniecznych do przetestowania w
pierwszej kolejności:
### 5. Kryteria
#### 5.1. Kryteria zaliczenia / niezaliczenia testu
Dla każdego z wymagań zostaną przygotowane testy. Aby uznać testy za zaliczone a system za
funkcjonujący poprawnie, powinien on przejść pomyślnie 80% testów.
#### 5.2. Warunki rozpoczęcia testów
Warunkami niezbędnymi do rozpoczęcia testów są:
• dostępność prawidłowo skonfigurowanego środowiska testowego
• dostępność do narzędzi testowych Jira i TesLink
• dla każdej z funkcjonalności przygotowane warunki testowe, przypadki testowe
• dostępność danych testowych
• dostępność do aktualnej wersji specyfikacji
• dostępność do aktualnej wersji testowanego produktu
• zaakceptowana dokumentacja testowa
• zaakceptowany plan testów
• zaakceptowany harmonogram testów
• dostępność zasobów do przeprowadzenia testów
#### 5.3. Warunki zakończenia testów
Możemy uznać, że testowanie zostało zakończone, gdy zostały spełnione warunki:
• wykonanych zostało 100% zaplanowanych przypadków testowych

• wszystkie błędy o priorytecie „blokujący” i „krytyczny” zostały usunięte
• zaplanowany termin zakończenia testów minął
• koszty wykonania testów przekroczyły zaplanowany budżet
#### 5.4. Kryteria zawieszenie i wznowienia testów
Jeżeli na skutek błędów w zaprojektowanym systemie pojawią się okoliczności, które uniemożliwią
przetestowanie kolejnych funkcjonalności i wykonanie kolejnych przypadków testowych lub w
przypadku, gdy zostanie wykryta zbyt duża liczba usterek o wysokiej krytyczności uniemożliwiająca
kontynuację prac, testowanie może zostać zawieszone. Wznowienie testów nastąpi po naprawie tych
błędów i umożliwieniu dalszego testowania.
### 6. Produkty procesu testowego
W rezultacie przeprowadzenia testów platformy dostępne będą następujące produkty:
• Plan Testów Platformy „Coders Guru” - 1P.7.2018
• Specyfikacja Testów Platformy „Coders Guru”, w tym
▪ przetestowane przypadki testowe
▪ wykonane procedury i skrypty testowe
• Zestaw wykorzystanych danych testowych
• Wyniki wykonanych testów
• Raport z przeprowadzonych testów, raporty o usterkach
• Raporty z postępu realizacji testów
• Harmonogramy z przebiegu prac testowych
### 7. Czynności i zadania testowe
W celu przeprowadzenia procesu testowego należy przeprowadzić poszczególne czynności testowe:

### 8. Środowisko testowe
Do przeprowadzenia testów niezbędne będzie środowisko testowe o parametrach:
• Dostęp do sieci, łącze internetowe min. 512kb/s
• Przeglądarka Firefox 61.0.1
• Windows 7 Home Premium, 64-bit
• Włączona obsługa Java
• Język polski
### 9. Role i odpowiedzialności, potrzeby szkoleniowe
#### 9.1. Podział obowiązków procesu testowego
Testowanie platformy przeprowadzone będzie przez niezależny zespół testerów, składający się z 11
osób,w tym lidera testów. Czynności związane z Planowaniem i Zamknięciem Testów zostaną
wykonane przez lidera testów, natomiast czynności Analizy, Projektowania i Wykonania Testów
zostaną wykonane przez zespół testerów.
Realizacja poszczególnych zadań testowych podzielona zostanie pomiędzy zespół w podziale na
testowane funkcjonalności systemu oraz z uwzględnieniem priorytetów poszczególnych
funkcjonalności i związanych z tym etapów testowania. Zadania z etapu 1 mają priorytet wysoki,
zadania z etapu 2 priorytet średni i zadania z etapu 3 priorytet niski.
Podział zadań przedstawia tabela:
#### 9.2. Potrzeby szkoleniowe
Aby zminimalizować ryzyka, zoptymalizować czas wykonania testowania i zapewnić najwyższą
jego jakość niezbędne jest szkolenie zespołu testerów z używania wykorzystywanych narzędzi,
takich jak Jira i TestLink.
### 10. Harmonogram
Okres wykonania poszczególnych zadań został oszacowany na podstawie podejścia opartego na
metrykach. Szacowanie pracochłonności wykonania testów bazuje na pomiarach minionych i
podobnych projektów. Poniżej przedstawiony jest planowany harmonogram wykonania zadań.
#### 11.1. Ryzyka projektowe
Do ryzyk procesu testowania platformy, które mogą mieć wpływ na niepowodzenie przedsięwzięcia
lub na przekroczenie terminów zawartych w harmonogramie możemy zaliczyć:
• niedostateczne doświadczenie testerów w przygotowywaniu warunków i przypadków
testowych oraz wykonywaniu przypadków testowych
• niedostateczne umiejętności obsługi narzędzi do testowania przez zespół
• możliwe braki kadrowe testerów ze względu na okres urlopowy
• środowisko testowe niegotowe na czas
#### 11.2. Ryzyka produktowe
Na wystąpienie ryzyk produktowych w przedsięwzięciu może mieć wpływ fakt, iż w opisywanym
procesie testowym nie są wykonywane testy dla wymagań niefunkcjonalnych systemu, co może
stanowić potencjalne obszary wystąpienia awarii w przyszłości.
### 12. Zatwierdzenie planu
Poniżej zamieszczona jest tabela interesariuszy, którzy muszą zatwierdzić plan, aby mógł on wejść
w życie.


