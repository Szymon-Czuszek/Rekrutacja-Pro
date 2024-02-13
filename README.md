# Rekrutacja Pro

Projekt z przedmiotu Inżynieria Oprogramowania II, zawierający dokumentację, diagram aktywności i diagram wymagań systemowych.

## Krótka charakterystyka organizacji

**Organizacja:** Mikro przedsiębiorstwo z sektora usług, zajmujące się udostępnianiem systemu informatycznego służącego do wyszukiwania ofert pracy przez użytkownika, zamieszczania ofert pracy przez pracodawcę oraz udostępnia opcje wyszukiwania pracowników na podstawie stworzonego CV użytkownika.

**Liczba zatrudnionych:** Team leader (również główny programista); 3 programistów (dwóch back-end developer i jeden front-end developer); 1 analityk biznesowy; 1 tester.

**Stosowane systemy informatyczne w organizacji:** Portal Rekrutacja Pro; Pakiet Office (głównie Excel, Power Bi, MS Teams, Outlook); Google Cloud; Visual Studio Code; System bazy danych SQL.

## Analiza problemu biznesowego

Projekt Rekrutacja Pro ma na celu rozwiązanie problemów biznesowych związanych z procesem rekrutacji pracowników. Kluczowe wyzwania identyfikowane w procesie to:

**Procesy:** Niezorganizowany proces rekrutacji; Ograniczone opcje wyszukiwania.

**Ludzie:** Trudności w preselekcji kandydatów; Brak efektywnej komunikacji.

**Narzędzia:** Brak jednolitej platformy rekrutacyjnej; Złożoność wyszukiwania pracowników.

Rozwiązanie problemu polega na stworzeniu systemu RekrutacjaPro, który integruje wszystkie etapy procesu rekrutacyjnego, oferuje zaawansowane opcje wyszukiwania, ułatwia preselekcję kandydatów i poprawia komunikację między pracodawcą a kandydatem.

## Przebieg procesu biznesowego

Przebieg procesu biznesowego w kontekście projektu Rekrutacja Pro obejmuje m.in. zamieszczanie ofert pracy przez pracodawcę, wyszukiwanie ofert pracy przez użytkownika, aplikowanie na ofertę pracy przez kandydata, preselekcję kandydatów, komunikację między stronami oraz podjęcie decyzji o zatrudnieniu.

## Cel biznesowy realizacji SI

Celem projektu Rekrutacja Pro jest ułatwienie, przyspieszenie i zwiększenie efektywności procesu rekrutacyjnego poprzez wprowadzenie systemu informatycznego, który usprawni współpracę między pracodawcami a kandydatami oraz zminimalizuje trudności związane z organizacją i zarządzaniem danymi rekrutacyjnymi.

## Udziałowcy systemu

Udziałowcy systemu to wszyscy, którzy korzystają z platformy Rekrutacja Pro:

**Pracodawcy:** Osoby lub firmy, które zamieszczają oferty pracy.
**Kandydaci:** Osoby poszukujące pracy i aplikujące na oferty pracy.
**Administratorzy:** Osoby odpowiedzialne za zarządzanie systemem i danymi.
**Testersi:** Osoby odpowiedzialne za testowanie i weryfikację poprawności działania systemu.

## Wymagania systemowe

### Funkcjonalne

**Zarządzanie ofertami pracy:**
- Dodawanie, edycja i usuwanie ofert pracy przez pracodawców.
- Przeglądanie ofert pracy przez kandydatów.
- Aplikowanie na oferty pracy przez kandydatów.
**Wyszukiwanie ofert pracy:**
- Zaawansowane opcje filtrowania ofert pracy.
- Preselekcja kandydatów:
- Automatyczna ocena dopasowania kandydata do oferty pracy.
- Ręczna preselekcja przez pracodawcę.
**Komunikacja:**
- Wysyłanie powiadomień o zmianach w statusie aplikacji.
- Komunikacja między pracodawcą a kandydatem poprzez platformę.
**Zarządzanie użytkownikami:**
- Rejestracja i logowanie użytkowników.
- Przyznawanie ról i uprawnień.

### Niefunkcjonalne

**Wykorzystanie technologii:**
- Aplikacja webowa oparta na architekturze RESTful API.
- Wykorzystanie języka TypeScript oraz frameworka Angular do budowy interfejsu użytkownika.
- Wykorzystanie języka Java oraz frameworka Spring do budowy backendu aplikacji.
- Baza danych MySQL.
**Wydajność:**
- Czas odpowiedzi aplikacji nie dłuższy niż 2 sekundy.
- Obsługa jednoczesnych zapytań od 1000 użytkowników.
**Bezpieczeństwo:**
- Mechanizmy uwierzytelniania i autoryzacji użytkowników.
- Szyfrowanie danych przesyłanych między klientem a serwerem.
- Mechanizmy zabezpieczające przed atakami typu SQL Injection oraz Cross-Site Scripting (XSS).
**Dostępność:**
- Aplikacja dostępna 24/7, z minimalnym czasem przestoju na potrzeby konserwacji.
- Zapewnienie skalowalności aplikacji w razie wzrostu liczby użytkowników.
- 
### Pozostałe wymagania

**Interfejs użytkownika:**
- Responsywny interfejs użytkownika dostosowany do różnych urządzeń (komputery, tablety, telefony).
**Dokumentacja:**
- Dokumentacja techniczna i użytkowa systemu.
**Testowanie:**
- Testy jednostkowe, integracyjne i akceptacyjne aplikacji.
- Zapewnienie pokrycia testami na poziomie co najmniej 80%.

## Weryfikacja wymagań

Weryfikacja wymagań będzie odbywać się w następujący sposób:

**Testowanie manualne:** Przeprowadzenie testów przez zespół testerski w celu weryfikacji poprawności działania aplikacji.
**Testy automatyczne:** Implementacja testów jednostkowych, integracyjnych i akceptacyjnych do automatycznej weryfikacji funkcjonalności i wydajności systemu.
**Review kodu:** Przegląd kodu przez członków zespołu deweloperskiego w celu zapewnienia zgodności z wymaganiami funkcjonalnymi i niefunkcjonalnymi.

## Ryzyka projektowe

**Opóźnienie w implementacji:** Spowodowane może być np. problemami technicznymi lub trudnościami w rekrutacji dodatkowych członków zespołu.
**Niezgodność z oczekiwaniami użytkowników:** Wymagania użytkowników mogą się zmieniać w trakcie realizacji projektu, co może prowadzić do konieczności wprowadzania znaczących zmian w systemie.
**Problemy z bezpieczeństwem:** W przypadku ataków hakerskich lub błędów w implementacji zabezpieczeń, dane użytkowników mogą być zagrożone.

## Diagram wymagań systemowych (VP)

**Diagram wymagań systemowych (VP) ma za zadanie:**
- Opisać wszystkie wymagania w notacji podstawowej w VP, w tym opis, źródło pochodzenia, rodzaj, metodę weryfikacji zakodowanego wymagania, ryzyko oraz status.
- Zawierać związki między wymaganiami, takie jak zagnieżdżenie, zależność wyprowadzania, realizacji, powielania, weryfikowania, precyzowania oraz śledzenia.

## Diagram czynności (VP)

Rozszerzony diagram czynności (VP) lub diagram czynności (VP) powinien zawierać elementy zależne od analizowanego procesu i zdefiniowanych wymagań, takie jak czynności/akcje, przepływy sterowania oraz przepływy danych. Na diagramie, czynności powinny być zgrupowane według poszczególnych udziałowców systemu informatycznego (SI).

## Podsumowanie

Projekt Rekrutacja Pro ma na celu stworzenie kompleksowego systemu wspierającego proces rekrutacji pracowników. Wymagań dotyczących funkcjonalności oraz niefunkcjonalności zostały szczegółowo opisane i poddane weryfikacji. Realizacja projektu będzie obejmować analizę, projektowanie, implementację, testowanie oraz wdrożenie systemu, z uwzględnieniem określonego harmonogramu i ryzyk.
