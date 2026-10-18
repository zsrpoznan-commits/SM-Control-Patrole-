# SM Control — Patrole RP

Prosta, responsywna strona do ewidencji patroli Straży Miejskiej na serwerze roleplay.

## Funkcje
- dodawanie patroli z unikalnym numerem i składem funkcjonariuszy
- typ patrolu, rejon i notatki
- zmiana statusu bezpośrednio w tabeli
- edycja i usuwanie patroli
- wyszukiwanie i filtrowanie według statusu
- podsumowania liczby patroli i dostępnych patroli
- eksport listy do CSV
- lokalny zapis danych w przeglądarce (`localStorage`)
- układ dopasowujący się do komputera i telefonu

## Uruchomienie lokalne
Otwórz `index.html` w nowoczesnej przeglądarce. Nie wymaga instalowania bibliotek ani serwera.

## Publikacja przez GitHub Pages
1. Zaloguj się na GitHub i utwórz nowe repozytorium, np. `sm-control-patrole`.
2. Wgraj `index.html` oraz `README.md` do głównego katalogu repozytorium.
3. Otwórz **Settings → Pages**.
4. W sekcji publikacji wybierz **Deploy from a branch**, gałąź `main` i katalog `/(root)`, a następnie zapisz.
5. Po zakończeniu publikacji GitHub pokaże adres strony w ustawieniach Pages.

## Ważne ograniczenie
To prototyp dla RP: dane przechowują się tylko w przeglądarce i na urządzeniu, na którym je wpisano. Nie synchronizują się między dyżurnymi ani komputerami. Do wspólnej pracy potrzebny będzie backend/baza danych oraz logowanie. Nie jest to integracja z oficjalnym SWD.
