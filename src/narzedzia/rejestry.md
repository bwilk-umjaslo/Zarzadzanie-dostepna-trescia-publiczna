# Rejestry

## Rola rejestrów

Rejestr jest narzędziem organizacyjnym, a nie tylko tabelą. Jego zadaniem jest utrzymanie wiedzy o zasobach, decyzjach, brakach, zgłoszeniach i naprawach. Rejestry powinny być aktualizowane w procesie, a nie raz na jakiś czas przy porządkowaniu serwisu.

## Zasada identyfikatora głównego

Każdy zasób powinien mieć jeden identyfikator główny, który pozwala połączyć wpisy w różnych rejestrach. Ten sam identyfikator powinien pojawiać się w rejestrze zasobów, rejestrze załączników, rejestrze napraw, rejestrze zgłoszeń dostępności, rejestrze treści od innych podmiotów i rejestrze decyzji archiwizacyjnych.

Przykład formatu: `ZAS-2026-0001`.

## Słowniki wartości

### Typ zasobu

- strona,
- dokument,
- załącznik,
- multimedia,
- grafika,
- post,
- komunikat,
- formularz,
- treść BIP,
- treść archiwalna.

### Źródło zasobu

- własne,
- inna komórka,
- podmiot zewnętrzny,
- wykonawca,
- BIP,
- system automatyczny,
- AI jako wsparcie redakcyjne.

### Status dostępności

- dostępny,
- dostępny częściowo,
- wymaga poprawy,
- opublikowany z oznaczeniem,
- niedostępny,
- brak danych,
- wymaga decyzji.

### Wynik kontroli

- publikuj,
- popraw przed publikacją,
- odeślij do uzupełnienia,
- opublikuj warunkowo,
- opublikuj z oznaczeniem,
- odmów publikacji,
- przekaż do procedury żądania dostępności.

### Status przeglądu

- nie dotyczy,
- zaplanowany,
- w toku,
- zakończony,
- zaległy,
- wymaga decyzji właściciela.

### Decyzja o dalszym losie

- pozostaw,
- aktualizuj,
- napraw,
- zastąp,
- zastąp HTML,
- archiwizuj,
- usuń z nawigacji,
- wycofaj,
- pozostaw historycznie.

## Rejestr zasobów cyfrowych

Cel: podstawowa pamięć organizacji o treściach publicznych.

Proponowane kolumny:

| Kolumna | Opis |
|---|---|
| Identyfikator zasobu | unikalny numer |
| Tytuł | nazwa zasobu |
| URL | adres publikacji |
| Typ zasobu | wartość ze słownika typów |
| Źródło | wartość ze słownika źródeł |
| Właściciel merytoryczny | osoba albo komórka |
| Redaktor publikujący | osoba publikująca |
| Data publikacji | data pierwszej publikacji |
| Data ostatniej aktualizacji | data ostatniej zmiany |
| Status dostępności | wartość ze słownika statusów |
| Wynik kontroli | wartość ze słownika wyników kontroli |
| Status przeglądu | wartość ze słownika przeglądu |
| Termin kolejnego przeglądu | data |
| Decyzja o dalszym losie | wartość ze słownika decyzji |
| Uwagi | informacje pomocnicze |
| Powiązane zgłoszenia dostępności | identyfikatory zgłoszeń |

## Rejestr załączników

Cel: kontrola dokumentów i plików do pobrania, szczególnie opublikowanych po 23 września 2018 r.

Proponowane kolumny:

| Kolumna | Opis |
|---|---|
| Identyfikator zasobu | powiązanie z rejestrem zasobów |
| Identyfikator załącznika | numer załącznika |
| Nazwa pliku | nazwa techniczna |
| Tytuł załącznika | nazwa dla użytkownika |
| URL strony publikacji | gdzie jest link |
| URL pliku | adres pliku |
| Typ pliku | PDF, DOCX, XLSX, ODT, inne |
| Data publikacji | data |
| Czy po 23 września 2018 r. | tak / nie / brak danych |
| Właściciel | osoba albo komórka |
| Status dostępności | wartość ze słownika statusów |
| Ocena niezbędności | bieżąco / okresowo / dowodowo / nieniezbędny / brak danych |
| Priorytet naprawy | 0 / 0A / 1 / 2 / 3 / 4 |
| Decyzja | wartość ze słownika decyzji |
| Termin naprawy | data |
| Status wykonania | nowe / w toku / zakończone / odroczone |

## Rejestr treści od innych podmiotów

Cel: udokumentowanie materiałów zewnętrznych, klasyfikacji A/B/C/D i decyzji publikacyjnych.

Proponowane kolumny:

| Kolumna | Opis |
|---|---|
| Identyfikator zasobu | powiązanie z rejestrem zasobów, jeżeli materiał opublikowano |
| Identyfikator materiału zewnętrznego | numer |
| Podmiot przekazujący | nazwa |
| Osoba do kontaktu | dane kontaktowe |
| Tytuł materiału | nazwa |
| Typ materiału | dokument, plakat, film, komunikat |
| Klasyfikacja | A, B, C, D |
| Czy publikacja obowiązkowa | tak / nie / wymaga decyzji |
| Zgoda na modyfikację | tak / nie / częściowo |
| Braki dostępności | opis |
| Decyzja publikacyjna | wartość ze słownika wyników kontroli |
| Oznaczenie braku | tak / nie |
| Alternatywna forma dostępu | opis |
| Data decyzji | data |
| Powiązany zasób | identyfikator w rejestrze zasobów |

## Rejestr zgłoszeń dostępności

Cel: obsługa zgłoszeń użytkowników i powiązanie ich z zasobami.

Proponowane kolumny:

| Kolumna | Opis |
|---|---|
| Identyfikator zgłoszenia | numer |
| Data wpływu | data |
| Kanał wpływu | e-mail, formularz, telefon, pismo |
| Zgłaszający | dane, jeżeli można przetwarzać |
| Zasób | URL albo identyfikator |
| Opis braku | opis użytkownika |
| Właściciel zasobu | osoba albo komórka |
| Decyzja | naprawa, alternatywa, odmowa, inne |
| Termin odpowiedzi | data |
| Sposób zapewnienia dostępności | opis |
| Data zakończenia | data |
| Czy wymaga przeglądu podobnych zasobów | tak / nie |

## Rejestr decyzji archiwizacyjnych

Cel: zachowanie informacji, dlaczego zasób został zarchiwizowany, wycofany, zastąpiony albo pozostawiony jako historyczny.

Proponowane kolumny:

| Kolumna | Opis |
|---|---|
| Identyfikator decyzji | numer |
| Identyfikator zasobu | powiązanie |
| Tytuł | nazwa |
| URL przed decyzją | adres |
| Decyzja | wartość ze słownika decyzji o dalszym losie |
| Uzasadnienie | tekst |
| Data decyzji | data |
| Osoba decyzyjna | imię i nazwisko albo rola |
| Data wykonania | data |
| Nowy URL albo powiązana wersja | adres |
| Status w rejestrze zasobów | po zmianie |

## Rejestr napraw i korekt

Cel: prowadzenie planu naprawczego po kontroli, przeglądzie albo zgłoszeniu dostępności.

Proponowane kolumny:

| Kolumna | Opis |
|---|---|
| Identyfikator naprawy | numer |
| Identyfikator zasobu | powiązanie z rejestrem zasobów |
| Zasób | identyfikator albo URL |
| Źródło naprawy | kontrola, przegląd, zgłoszenie, audyt |
| Opis problemu | brak dostępności albo błąd |
| Priorytet | 0 / 0A / 1 / 2 / 3 / 4 albo wysoki / średni / niski |
| Osoba odpowiedzialna | właściciel albo wykonawca |
| Termin | data |
| Sposób naprawy | opis |
| Status | nowe, w toku, zakończone, odroczone |
| Wynik weryfikacji | poprawne, wymaga dalszej pracy |
| Data zamknięcia | data |

## Powiązanie rejestrów

Rejestry powinny łączyć się przez identyfikator zasobu. Jedno zgłoszenie dostępności może prowadzić do naprawy, a naprawa może zmienić status zasobu. Decyzja archiwizacyjna powinna zmienić rekord w rejestrze zasobów. Materiał od innego podmiotu po publikacji staje się zasobem i powinien mieć powiązanie z rejestrem treści zewnętrznych.

## Reguły aktualizacji rejestrów

Rejestr aktualizuje się:

- po publikacji,
- po każdej istotnej zmianie treści,
- po decyzji warunkowej,
- po oznaczeniu braku dostępności,
- po zgłoszeniu dostępności,
- po zakończeniu naprawy,
- po przeglądzie,
- po archiwizacji,
- po wycofaniu albo usunięciu z nawigacji.

## Minimalne wdrożenie

Mały podmiot może prowadzić jeden arkusz z zakładkami. Duży podmiot powinien ustalić właściciela każdego rejestru, częstotliwość aktualizacji i zasady dostępu.
