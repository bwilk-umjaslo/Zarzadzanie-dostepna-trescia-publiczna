# Zarządzanie dostępną treścią publiczną

Repozytorium zawiera źródła podręcznika **Zarządzanie dostępną treścią publiczną**.

Podgląd online:

<https://bwilk-umjaslo.github.io/Zarzadzanie-dostepna-trescia-publiczna/>

## Cel projektu

Celem projektu jest przygotowanie praktycznego podręcznika dla podmiotów publicznych, które chcą zarządzać treścią cyfrową w całym cyklu jej życia: od planowania, przez publikację, kontrolę, rejestrację i utrzymanie, po przegląd, naprawę, archiwizację albo wycofanie.

Podręcznik łączy:

- dostępność cyfrową,
- publikację w serwisach WWW,
- publikację w BIP,
- dokumenty i załączniki,
- multimedia,
- treści od innych podmiotów,
- rejestry i dowody wykonania,
- mapy odpowiedzialności,
- listy kontrolne,
- formularze i schematy procesów.

## Czym projekt nie jest

Projekt nie jest opinią prawną, audytem dostępności cyfrowej ani gotowym regulaminem organizacyjnym dla każdego podmiotu publicznego. Jest materiałem wdrożeniowym, który należy dostosować do struktury, zakresu zadań, kanałów publikacji i procedur konkretnej organizacji.

## Status praw autorskich i wykorzystania

Na tym etapie repozytorium jest udostępnione wyłącznie do wglądu i utrzymania projektu.

Treść podręcznika nie jest udostępniona na wolnej licencji. Kopiowanie, adaptowanie, publikowanie, wdrażanie, rozpowszechnianie albo tworzenie opracowań zależnych na podstawie całości lub części materiału wymaga wcześniejszego kontaktu z właścicielem praw i uzyskania jego zgody.

Szczegóły znajdują się w pliku `LICENSE`.

## Struktura źródeł

Najważniejsze pliki i katalogi:

| Ścieżka | Znaczenie |
|---|---|
| `src/SUMMARY.md` | spis treści mdBook i główna struktura podręcznika |
| `src/index.md` | strona startowa podręcznika |
| `src/01-wstep.md` - `src/09-narzedzia-systemowe.md` | główne rozdziały podręcznika |
| `src/kontekst/` | kontekst systemowy, model organizacji, zasady i podstawy |
| `src/procesy/` | procesy szczególne, m.in. BIP, publikacja pilna, AI |
| `src/narzedzia/` | listy kontrolne, formularze, rejestry, mapy odpowiedzialności i schematy |
| `src/10-slownik-pojec.md` | słownik pojęć i skrótów |
| `src/11-o-autorze.md` | informacja o autorze |
| `book.toml` | konfiguracja mdBook |
| `LICENSE` | informacja o ograniczeniu wykorzystania treści |

## Technologia

Podręcznik jest przygotowany w formacie mdBook. Treści źródłowe są zapisane w Markdown.

Repozytorium korzysta z diagramów Mermaid. Konfiguracja znajduje się w `book.toml`.

## Praca z treścią

Przy zmianach w podręczniku należy pilnować, aby:

- nowe rozdziały były dodane do `src/SUMMARY.md`,
- linki wewnętrzne prowadziły do istniejących plików,
- pojęcia używane w treści były spójne ze słownikiem,
- procedury miały powiązanie z rolami, formularzami, listami kontrolnymi albo rejestrami,
- diagramy Mermaid nie były jedynym nośnikiem ważnej informacji,
- wymagania były powiązane z dowodem wykonania, gdy ma to znaczenie organizacyjne.

## Budowanie lokalne

Do lokalnego zbudowania podręcznika potrzebny jest mdBook oraz preprocesor Mermaid.

Przykładowo:

```bash
mdbook build
```

Podgląd lokalny:

```bash
mdbook serve
```

Jeżeli środowisko nie ma skonfigurowanego `mdbook-mermaid`, build może wymagać instalacji tego preprocesora.

## Zgłaszanie zmian

Przy zgłaszaniu zmian warto wskazać:

- którego rozdziału dotyczy uwaga,
- czy problem jest merytoryczny, prawny, techniczny, redakcyjny albo organizacyjny,
- jakie ryzyko powoduje obecne brzmienie,
- jaką zmianę proponujesz,
- czy zmiana wymaga aktualizacji słownika, formularzy, list kontrolnych, rejestrów albo schematów procesów.

Zgłaszanie uwag nie oznacza zgody na wykorzystanie treści poza tym repozytorium.

## Autor

Autorem podręcznika jest Bartłomiej Wilk.

Więcej informacji znajduje się w rozdziale `src/11-o-autorze.md`.
