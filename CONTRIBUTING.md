# Zasady zgłaszania zmian

Ten plik opisuje, jak zgłaszać uwagi i propozycje zmian do podręcznika **Zarządzanie dostępną treścią publiczną**.

## Status materiału

Repozytorium jest udostępnione do wglądu i utrzymania projektu. Zgłoszenie uwagi, poprawki albo propozycji nie oznacza zgody na wykorzystanie treści podręcznika poza tym repozytorium.

Zasady wykorzystania treści opisuje plik `LICENSE`.

## Jak zgłaszać uwagi

Przy zgłoszeniu warto wskazać:

- którego pliku albo rozdziału dotyczy uwaga,
- czy problem jest merytoryczny, prawny, techniczny, redakcyjny, wizualny albo organizacyjny,
- jakie ryzyko powoduje obecne brzmienie lub obecne rozwiązanie,
- jaką zmianę proponujesz,
- czy zmiana wymaga aktualizacji słownika, formularzy, list kontrolnych, rejestrów, CSS albo schematów procesów.

## Zasady dostępności repozytorium

Repozytorium i wygenerowany podręcznik powinny być utrzymywane tak, aby były możliwie dostępne dla osób korzystających z klawiatury, czytników ekranu, powiększenia, ustawień wysokiego kontrastu i technologii wspomagających.

Przy każdej zmianie należy sprawdzić:

- czy nagłówki zachowują logiczną hierarchię,
- czy tekst linku opisuje cel, a nie brzmi tylko "kliknij tutaj" albo "pobierz",
- czy tabele mają nagłówki i prostą strukturę,
- czy diagram Mermaid ma opis tekstowy przed diagramem albo po nim,
- czy ważna informacja nie występuje wyłącznie w diagramie, kolorze albo układzie wizualnym,
- czy dodany plik do pobrania ma zrozumiałą nazwę, format, rozmiar i opis,
- czy nowy skrót albo trudne pojęcie trafiło do słownika,
- czy elementy interaktywne zachowują widoczny focus klawiatury,
- czy zmiana CSS nie usuwa kontrastu, podkreślenia linków ani obwódki focusu.

## Zasady redakcyjne

Przy zmianach treści należy pilnować, aby:

- nie tworzyć powtórzeń między rozdziałami,
- nie zaczynać wielu sąsiednich sekcji tym samym schematem zdania,
- nie dodawać definicji sprzecznych ze słownikiem,
- nie tworzyć martwych linków,
- zachować język wdrożeniowy i operacyjny,
- wskazywać role, decyzje, dowody i narzędzia tam, gdzie ma to znaczenie,
- unikać ogólników bez przełożenia na proces.

## Linki i pliki do pobrania

Link do pliku powinien informować użytkownika, co pobiera, w jakim formacie i, gdy to pomocne, jaki jest rozmiar pliku.

Przykład:

- Pobierz wniosek o wydanie dowodu osobistego (PDF, 200 KB)

Nie należy stosować linków typu:

- Pobierz
- Kliknij tutaj
- Dokument
- Załącznik

## Diagramy

Diagramy Mermaid można dodawać tylko wtedy, gdy wyjaśniają proces, decyzję albo relację. Diagram powinien mieć opis tekstowy i nie może zastępować treści merytorycznej.

## Sprawdzenie przed zgłoszeniem

Przed zgłoszeniem większej zmiany sprawdź:

- czy linki wewnętrzne działają,
- czy nazwy plików są zgodne ze strukturą repozytorium,
- czy pojęcia są spójne ze słownikiem,
- czy zmiana nie wymaga aktualizacji list kontrolnych albo formularzy,
- czy diagram Mermaid, jeśli został dodany, ma poprawną składnię,
- czy widoczny focus działa dla linków, wyszukiwarki, przycisków i nawigacji.
