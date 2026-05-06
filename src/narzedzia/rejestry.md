# Rejestry

## Rola rejestrów w systemie

Rejestry są centralnym narzędziem zarządzania informacją o treściach publicznych i działaniach podejmowanych wobec nich.

To w rejestrach:
- zapisywane są decyzje,
- utrwalany jest przebieg procesu,
- widoczny jest stan zasobów,
- możliwe jest zarządzanie w czasie.

Bez rejestrów organizacja działa „na bieżąco”, bez pamięci systemowej. Rejestr wprowadza ciągłość, umożliwia analizę i pozwala zarządzać całym cyklem życia treści.

---

## Zasada podstawowa

Każdy istotny element procesu powinien pozostawiać ślad w rejestrze.

Oznacza to, że:
- publikacja musi być odnotowana,
- kontrola musi mieć wynik,
- decyzja musi być zapisana,
- naprawa musi być udokumentowana,
- archiwizacja musi mieć uzasadnienie.

Rejestr nie jest statyczną listą. Jest dynamicznym narzędziem pracy.

---

## Rodzaje rejestrów w systemie

### Rejestr zasobów cyfrowych

Podstawowy rejestr obejmujący wszystkie zasoby.

Zawiera:
- identyfikację zasobu,
- właściciela,
- lokalizację,
- status publikacji,
- status dostępności,
- daty,
- powiązania z innymi działaniami.

Powiązanie:
- wszystkie etapy systemu.

---

### Rejestr kontroli

Służy do zapisu wyników kontroli przed publikacją.

Zawiera:
- identyfikację materiału,
- zastosowaną listę kontrolną,
- wynik,
- decyzję,
- osobę wykonującą kontrolę,
- datę.

Powiązanie:
- kontrola przed publikacją,
- publikacja.

---

### Rejestr braków i działań naprawczych

Służy do zarządzania problemami wykrytymi w zasobach.

Zawiera:
- opis braku,
- zasób, którego dotyczy,
- priorytet,
- odpowiedzialność,
- termin,
- status naprawy.

Powiązanie:
- przegląd i naprawa,
- zgłoszenia użytkowników.

---

### Rejestr zgłoszeń dostępności

Służy do obsługi zgłoszeń od użytkowników.

Zawiera:
- zgłoszony problem,
- zasób,
- datę zgłoszenia,
- sposób obsługi,
- wynik,
- powiązanie z naprawą.

Powiązanie:
- przegląd i naprawa,
- rejestr zasobów.

---

### Rejestr decyzji

Służy do dokumentowania kluczowych decyzji.

Zawiera:
- decyzję (publikacja, odmowa, archiwizacja, wyjątek),
- uzasadnienie,
- osobę decyzyjną,
- datę,
- powiązanie z zasobem.

Powiązanie:
- kontrola,
- treści zewnętrzne,
- archiwizacja.

---

## Powiązanie rejestrów

Rejestry nie powinny funkcjonować osobno.

Powinny być powiązane poprzez:
- identyfikator zasobu,
- wspólne pola (np. status),
- relacje między wpisami.

Przykład:
- zasób w rejestrze zasobów,
- powiązany wpis w rejestrze kontroli,
- zgłoszenie w rejestrze zgłoszeń,
- działanie naprawcze w rejestrze braków.

To tworzy pełną historię zasobu.

---

## Minimalny model wdrożenia

W prostym modelu rejestry mogą być prowadzone jako:

- jeden arkusz z wieloma kolumnami,
- kilka powiązanych arkuszy,
- formularze zapisujące dane do arkusza.

Najważniejsze:
- spójność danych,
- możliwość filtrowania,
- aktualność.

---

## Model rozwinięty

W bardziej zaawansowanym modelu rejestry mogą być:

- częścią systemu CMS,
- systemem ticketowym,
- bazą danych,
- dashboardem raportowym.

Ważne jest:
- automatyczne zasilanie danych,
- możliwość raportowania,
- integracja z procesami.

---

## Aktualizacja rejestrów

Rejestry muszą być aktualizowane na bieżąco.

Momentami aktualizacji są:
- przekazanie treści,
- kontrola,
- publikacja,
- zgłoszenie błędu,
- naprawa,
- przegląd,
- archiwizacja,
- wycofanie.

Rejestr, który nie jest aktualizowany, traci wartość.

---

## Najczęstsze błędy

- brak rejestrów,
- prowadzenie ich tylko do audytu,
- brak aktualizacji,
- brak powiązań między rejestrami,
- brak identyfikatora zasobu,
- zbyt skomplikowana struktura,
- brak wykorzystania danych.

---

## Efekt dobrze działających rejestrów

- pełna kontrola nad zasobami,
- możliwość analizy,
- łatwiejsze podejmowanie decyzji,
- spójność procesów,
- lepsza obsługa użytkowników,
- mniejsze ryzyko błędów,
- realne zarządzanie dostępnością.

---

## Odniesienia

- [Materiały źródłowe](../../_sources/sdc/)

- ## Model danych – rejestr zasobów cyfrowych

Rejestr powinien być traktowany jako baza danych, a nie tabela pomocnicza.

### Pola obowiązkowe

| Pole | Typ | Opis |
|------|-----|------|
| id | string | unikalny identyfikator zasobu |
| tytul | text | nazwa zasobu |
| typ | enum | strona / dokument / wideo / grafika / formularz |
| url | text | lokalizacja zasobu |
| kanal | enum | www / BIP / social media / system |
| wlasciciel | text | właściciel merytoryczny |
| jednostka | text | komórka organizacyjna |
| status | enum | roboczy / opublikowany / warunkowy / archiwalny / wycofany |
| status_dostepnosci | enum | zgodny / częściowo zgodny / niezgodny / nieoceniony |
| data_publikacji | date | data publikacji |
| data_ostatniego_przegladu | date | ostatnia weryfikacja |
| termin_przegladu | date | kolejny przegląd |
| priorytet | enum | wysoki / średni / niski |
| czy_zewnetrzny | boolean | czy materiał pochodzi z zewnątrz |
| mozliwosc_modyfikacji | boolean | czy można zmieniać treść |
| decyzja | enum | publikacja / poprawa / archiwizacja / wycofanie |
| uwagi | text | dodatkowe informacje |

---

### Relacje

Rejestr powinien być powiązany z:

- rejestrem kontroli
- rejestrem zgłoszeń
- rejestrem napraw
- rejestrem decyzji

Identyfikatorem wspólnym jest `id`.

---

### Minimalny model wdrożenia

- Google Sheets (z walidacją danych)
- kolumny jako pola
- filtry po statusie i właścicielu

---

### Model docelowy

- baza danych (np. Airtable / system wewnętrzny)
- integracja z CMS
- automatyczne zasilanie danych
