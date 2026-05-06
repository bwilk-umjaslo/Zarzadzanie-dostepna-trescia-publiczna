# Schematy procesów

## Rola schematów procesów w systemie

Schematy procesów przedstawiają przebieg działań związanych z zarządzaniem treścią publiczną w sposób uporządkowany i zrozumiały.

Ich celem nie jest opisanie teorii, ale pokazanie:
- kolejności działań,
- punktów decyzyjnych,
- odpowiedzialności,
- powiązań między etapami.

Schemat procesowy pozwala przełożyć opis podręcznika na rzeczywisty sposób działania organizacji.

## Zasada podstawowa

Każdy proces powinien być możliwy do przedstawienia w formie schematu.

Oznacza to, że:
- wiadomo, od czego proces się zaczyna,
- wiadomo, jakie są jego etapy,
- wiadomo, gdzie zapada decyzja,
- wiadomo, kto odpowiada za dany krok,
- wiadomo, jaki jest wynik procesu.

Jeżeli nie da się narysować procesu, to najczęściej oznacza, że nie jest on dobrze zdefiniowany.

## Elementy schematu

Schemat procesu powinien zawierać:

- punkt startowy,
- kolejne kroki procesu,
- punkty decyzyjne,
- możliwe ścieżki,
- przypisanie odpowiedzialności,
- punkt końcowy.

Schemat powinien być możliwie prosty i czytelny.

## Proces tworzenia i publikacji treści

```mermaid
flowchart TD
    A[Potrzeba publikacji lub materiał] --> B[Formularz przekazania treści]
    B --> C[Rejestr zasobów: status roboczy]
    C --> D[Kontrola przed publikacją]
    D --> E{Decyzja}

    E -->|OK| F[Publikacja]
    F --> G[Rejestr zasobów: status opublikowany]

    E -->|NIE| H[Naprawa lub uzupełnienie braków]
    H --> D

    E -->|Warunkowo| I[Publikacja warunkowa]
    I --> J[Rejestr: status opublikowany warunkowo]
    J --> K[Termin naprawy]
    K --> H
```

## Proces obsługi treści od innych podmiotów

```mermaid
flowchart TD
    A[Materiał od innego podmiotu] --> B[Identyfikacja źródła]
    B --> C[Kwalifikacja ABCD]
    C --> D[Ocena dostępności]
    D --> E{Czy materiał może być poprawiony?}

    E -->|Tak| F[Wezwanie do poprawy lub poprawa własna]
    F --> G[Kontrola przed publikacją]

    E -->|Nie| H{Czy istnieje obowiązek publikacji?}
    H -->|Tak| I[Publikacja z dostępem alternatywnym]
    H -->|Nie| J[Odmowa publikacji]

    G --> K{Decyzja publikacyjna}
    K -->|OK| L[Publikacja]
    K -->|NIE| F

    I --> M[Rejestr zasobów]
    J --> M
    L --> M
```

## Proces przeglądu i naprawy

```mermaid
flowchart TD
    A[Rejestr zasobów] --> B[Wybór zasobów do przeglądu]
    B --> C[Ocena aktualności i dostępności]
    C --> D{Decyzja}

    D -->|Pozostawić| E[Aktualizacja rejestru]
    D -->|Naprawić| F[Plan naprawy]
    F --> G[Wykonanie naprawy]
    G --> H[Kontrola po naprawie]
    H --> E

    D -->|Dostęp alternatywny| I[Zapewnienie alternatywy]
    I --> E

    D -->|Wycofać lub archiwizować| J[Przekazanie do procesu archiwizacji]
    J --> E
```

## Proces archiwizacji i wycofania

```mermaid
flowchart TD
    A[Zasób wymagający decyzji] --> B[Ocena aktualności i wartości]
    B --> C{Decyzja}

    C -->|Pozostawić| D[Aktualizacja statusu w rejestrze]
    C -->|Zarchiwizować| E[Oznaczenie jako archiwalne]
    E --> F[Określenie sposobu dostępu]
    F --> D

    C -->|Wycofać| G[Usunięcie z aktywnej publikacji]
    G --> H[Przekierowanie lub komunikat]
    H --> D
```

## Proces obsługi zgłoszeń dostępności

```mermaid
flowchart TD
    A[Zgłoszenie użytkownika] --> B[Identyfikacja zasobu]
    B --> C[Sprawdzenie w rejestrze]
    C --> D[Ocena problemu]
    D --> E{Sposób obsługi}

    E -->|Naprawa| F[Przypisanie działania naprawczego]
    F --> G[Wykonanie naprawy]
    G --> H[Aktualizacja rejestru]

    E -->|Dostęp alternatywny| I[Zapewnienie alternatywy]
    I --> H

    E -->|Brak zasadności| J[Udokumentowanie decyzji]
    J --> H

    H --> K[Odpowiedź dla użytkownika]
```

## Powiązanie z mapami odpowiedzialności

Schematy procesów powinny być powiązane z mapami odpowiedzialności. Każdy krok powinien mieć przypisaną rolę, decyzje powinny mieć właściciela, a proces nie powinien zawierać pustych etapów.

## Powiązanie z narzędziami

Schematy procesów powinny wskazywać, gdzie wykorzystywane są:

- formularze jako wejście do procesu,
- listy kontrolne jako weryfikacja,
- rejestry jako zapis wyników,
- mapy odpowiedzialności jako przypisanie ról.

## Odniesienia

- [Materiały źródłowe](../../_sources/sdc/)
