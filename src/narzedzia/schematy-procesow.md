# Schematy procesów

## Zasada stosowania

Schemat procesu pokazuje punkt startowy, uczestników, decyzje, rezultat i powiązane narzędzia. Diagram Mermaid jest pomocą wdrożeniową, ale opis procesu jest równie ważny jak sam diagram.

## Publikacja treści własnej

Cel: opublikowanie materiału przygotowanego przez podmiot publiczny.

Punkt startowy: autor albo komórka merytoryczna przygotowuje materiał.

Uczestnicy: autor, właściciel treści, redaktor, osoba kontrolująca, osoba zatwierdzająca, administrator serwisu.

Decyzje: czy materiał jest kompletny, czy spełnia standard, czy wymaga rejestru.

Rezultat: opublikowany i zarejestrowany zasób albo materiał odesłany do poprawy.

Powiązane narzędzia: formularz przekazania, lista kontrolna, formularz decyzji publikacyjnej, rejestr zasobów.

```mermaid
flowchart TD
    A[Przygotowanie materialu] --> B[Formularz przekazania]
    B --> C{Kompletne dane?}
    C -- Nie --> D[Odeslij do uzupelnienia]
    C -- Tak --> E[Kontrola przed publikacja]
    E --> F{Wynik kontroli}
    F -- Publikuj --> G[Publikacja]
    F -- Popraw --> H[Poprawa przed publikacja]
    H --> E
    F -- Warunkowo --> I[Decyzja osoby zatwierdzajacej]
    I --> G
    G --> J[Rejestracja zasobu]
```

## Publikacja treści od innego podmiotu

Cel: przyjęcie, kwalifikacja i publikacja albo odmowa publikacji materiału zewnętrznego.

Punkt startowy: podmiot zewnętrzny przekazuje materiał.

Uczestnicy: podmiot zewnętrzny, osoba przyjmująca, redaktor, właściciel merytoryczny, koordynator dostępności, osoba zatwierdzająca.

Decyzje: klasyfikacja A/B/C/D, możliwość poprawy, obowiązek publikacji, oznaczenie braków.

Rezultat: publikacja, publikacja warunkowa, oznaczenie, alternatywna forma dostępu albo odmowa.

Powiązane narzędzia: formularz zewnętrzny, lista kontrolna treści zewnętrznej, rejestr treści od innych podmiotów.

```mermaid
flowchart TD
    A[Material zewnetrzny] --> B[Formularz zewnetrzny]
    B --> C{Dane kompletne?}
    C -- Nie --> D[Procedura brakow]
    D --> B
    C -- Tak --> E[Klasyfikacja A B C D]
    E --> F{Obowiazek publikacji?}
    F -- Tak --> G[Kontrola i oznaczenie brakow]
    F -- Nie --> H{Mozna poprawic?}
    H -- Tak --> I[Poprawa lub uzupelnienie]
    I --> G
    H -- Nie --> J{Cel publiczny uzasadnia publikacje?}
    J -- Nie --> K[Odmowa publikacji]
    J -- Tak --> G
    G --> L[Decyzja publikacyjna]
    L --> M[Publikacja i rejestr]
```

## Publikacja treści obowiązkowej w BIP

Cel: opublikowanie treści wymaganej przepisem albo obowiązkiem informacyjnym.

Punkt startowy: powstaje obowiązek publikacji.

Uczestnicy: właściciel treści, administrator BIP, redaktor, koordynator dostępności, osoba zatwierdzająca.

Decyzje: miejsce w BIP, dostępność materiału, oznaczenie braków, alternatywna forma dostępu.

Rezultat: publikacja w BIP z wpisem do rejestru i planem naprawy, jeżeli występują braki.

Powiązane narzędzia: formularz decyzji publikacyjnej, lista dokumentu albo załącznika, rejestr zasobów, rejestr załączników.

```mermaid
flowchart TD
    A[Obowiazek publikacji] --> B[Ustalenie wlasciciela]
    B --> C[Kontrola dostepnosci]
    C --> D{Braki?}
    D -- Nie --> E[Publikacja w BIP]
    D -- Tak --> F[Oznaczenie i plan alternatywy]
    F --> E
    E --> G[Wpis do rejestru]
    G --> H[Termin przegladu lub naprawy]
```

## Kontrola przed publikacją

Cel: podjęcie decyzji, czy materiał można opublikować.

Punkt startowy: materiał jest gotowy do sprawdzenia.

Uczestnicy: redaktor, właściciel, koordynator dostępności, osoba zatwierdzająca.

Decyzje: publikuj, popraw, odeślij, warunkowo, z oznaczeniem, odmów, przekaż do żądania dostępności.

Rezultat: udokumentowana decyzja.

Powiązane narzędzia: listy kontrolne, formularz braku dostępności, formularz decyzji.

```mermaid
flowchart TD
    A[Material do kontroli] --> B[Dobor listy kontrolnej]
    B --> C[Sprawdzenie minimalne]
    C --> D{Wynik}
    D -- Bez brakow --> E[Publikuj]
    D -- Braki do poprawy --> F[Popraw przed publikacja]
    D -- Brak danych --> G[Odeslij do uzupelnienia]
    D -- Wyjatek --> H[Decyzja warunkowa lub oznaczenie]
    D -- Niedopuszczalne --> I[Odmow publikacji]
    H --> J[Plan naprawy lub alternatywa]
```

## Obsługa braków dostępności

Cel: opisanie i usunięcie braków wykrytych przed publikacją albo po publikacji.

Punkt startowy: wykryto brak dostępności.

Uczestnicy: osoba zgłaszająca, właściciel, redaktor, koordynator dostępności, osoba naprawiająca.

Decyzje: poprawić, zapewnić alternatywę, opublikować warunkowo, odmówić, przekazać do żądania dostępności.

Rezultat: brak usunięty, oznaczony albo obsłużony alternatywnie.

Powiązane narzędzia: formularz braku dostępności, rejestr napraw, rejestr zgłoszeń.

```mermaid
flowchart TD
    A[Wykryty brak] --> B[Opis braku]
    B --> C{Mozna usunac przed publikacja?}
    C -- Tak --> D[Naprawa]
    D --> E[Ponowna kontrola]
    C -- Nie --> F{Czy publikacja konieczna?}
    F -- Nie --> G[Wstrzymaj lub odmow]
    F -- Tak --> H[Alternatywa lub oznaczenie]
    H --> I[Rejestr napraw]
```

## Obsługa żądania zapewnienia dostępności

Cel: zapewnienie użytkownikowi dostępu do treści i wykorzystanie zgłoszenia do poprawy zasobu.

Punkt startowy: wpływa żądanie zapewnienia dostępności.

Uczestnicy: osoba przyjmująca, właściciel zasobu, koordynator dostępności, redaktor, administrator.

Decyzje: sposób zapewnienia dostępności, termin, naprawa zasobu, przegląd podobnych zasobów.

Rezultat: udzielona odpowiedź, zapewniona dostępność albo alternatywa, zaktualizowany rejestr.

Powiązane narzędzia: rejestr zgłoszeń dostępności, rejestr zasobów, rejestr napraw.

```mermaid
flowchart TD
    A[Zgloszenie dostepnosci] --> B[Rejestracja zgloszenia]
    B --> C[Identyfikacja zasobu]
    C --> D[Ustalenie wlasciciela]
    D --> E{Mozliwa szybka naprawa?}
    E -- Tak --> F[Napraw zasob]
    E -- Nie --> G[Zapewnij forme alternatywna]
    F --> H[Odpowiedz uzytkownikowi]
    G --> H
    H --> I[Aktualizacja rejestrow]
    I --> J{Podobne zasoby?}
    J -- Tak --> K[Przeglad podobnych zasobow]
    J -- Nie --> L[Zamknij]
```

## Przegląd i naprawa załączników

Cel: identyfikacja, klasyfikacja i naprawa załączników, szczególnie opublikowanych po 23 września 2018 r.

Punkt startowy: rejestr albo przegląd serwisu wskazuje załączniki.

Uczestnicy: redaktor, właściciel, koordynator dostępności, osoba naprawiająca, osoba decyzyjna.

Decyzje: naprawić, zastąpić, wycofać, archiwizować, pozostawić z uzasadnieniem.

Rezultat: plan naprawczy i aktualny status zasobu.

Powiązane narzędzia: rejestr załączników, formularz wyniku przeglądu, rejestr napraw.

```mermaid
flowchart TD
    A[Lista zalacznikow] --> B[Identyfikacja daty publikacji]
    B --> C{Po 23 wrzesnia 2018?}
    C -- Tak --> D[Ocena dostepnosci]
    C -- Nie --> E[Ocena potrzeby utrzymania]
    D --> F[Priorytet naprawy]
    E --> F
    F --> G{Decyzja}
    G -- Napraw --> H[Plan naprawczy]
    G -- Zastap --> I[Nowa wersja]
    G -- Archiwizuj --> J[Decyzja archiwizacyjna]
    G -- Wycofaj --> K[Wycofanie]
    H --> L[Aktualizacja rejestru]
    I --> L
    J --> L
    K --> L
```

## Archiwizacja i wycofanie zasobu

Cel: zakończenie albo zmiana statusu zasobu po utracie aktualności.

Punkt startowy: przegląd, zgłoszenie, zmiana przepisów, nowa wersja albo decyzja właściciela.

Uczestnicy: właściciel, redaktor, administrator, koordynator dostępności, osoba zatwierdzająca.

Decyzje: aktualizuj, pozostaw, archiwizuj, usuń z nawigacji, wycofaj, zastąp, pozostaw historycznie.

Rezultat: zasób zaktualizowany, zarchiwizowany, wycofany albo oznaczony.

Powiązane narzędzia: formularz decyzji archiwizacyjnej, rejestr zasobów, rejestr decyzji.

```mermaid
flowchart TD
    A[Zasob do oceny] --> B[Ocena aktualnosci]
    B --> C{Potrzebny publicznie?}
    C -- Tak --> D{Aktualny?}
    D -- Tak --> E[Pozostaw lub aktualizuj]
    D -- Nie --> F[Oznacz historycznie lub archiwizuj]
    C -- Nie --> G{Wymaga zachowania?}
    G -- Tak --> H[Przenies do archiwum]
    G -- Nie --> I[Wycofaj]
    E --> J[Aktualizacja rejestru]
    F --> J
    H --> J
    I --> J
```
