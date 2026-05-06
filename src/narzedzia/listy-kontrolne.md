# Listy kontrolne

## Rola list kontrolnych w systemie

Listy kontrolne są podstawowym narzędziem weryfikacji treści w procesie publikacji i utrzymania zasobów cyfrowych.

Ich główną funkcją nie jest przypominanie o czynnościach, lecz wspieranie podejmowania decyzji. Lista kontrolna pozwala jednoznacznie ustalić, czy materiał może zostać opublikowany, czy wymaga poprawy, czy należy zastosować tryb wyjątkowy.

Dzięki listom kontrolnym:
- wymagania są stosowane w sposób spójny,
- decyzje nie są uznaniowe,
- możliwe jest odtworzenie procesu weryfikacji,
- ograniczane są błędy wynikające z pominięcia elementów,
- organizacja działa według standardu, a nie indywidualnych nawyków.

---

## Zasada podstawowa

Lista kontrolna ma charakter decyzyjny.

Oznacza to, że:
- odpowiedź „NIE” w wymaganiu obowiązkowym blokuje publikację,
- lista nie jest opcjonalna,
- wynik listy musi prowadzić do decyzji.

Lista kontrolna nie zastępuje wiedzy, ale porządkuje jej zastosowanie.

---

## Zasady budowy list kontrolnych

Każda lista kontrolna powinna:

- być powiązana z konkretnym typem treści,
- zawierać wymagania wynikające ze standardów publikacji,
- rozróżniać wymagania obowiązkowe i uzupełniające,
- umożliwiać odpowiedzi: TAK / NIE / NIE DOTYCZY,
- zawierać miejsce na uwagi lub dowód,
- być możliwa do wypełnienia w praktyce (bez nadmiarowej złożoności).

Lista nie powinna być zbiorem ogólnych zaleceń. Każdy punkt powinien być możliwy do sprawdzenia.

---

## Struktura listy kontrolnej

Typowa lista kontrolna powinna zawierać:

- nazwę i zakres (np. „lista dla materiałów wideo”),
- opis zastosowania,
- zestaw wymagań,
- oznaczenie wymagań obowiązkowych,
- pole odpowiedzi,
- pole uwag,
- identyfikację osoby weryfikującej,
- datę weryfikacji.

---

## Typy list kontrolnych

### Lista kontrolna treści tekstowych

Dotyczy:
- struktury nagłówków,
- czytelności,
- linków,
- tabel,
- kompletności informacji.

Powiązanie:
- tworzenie treści,
- standardy publikacji.

---

### Lista kontrolna grafik i materiałów wizualnych

Dotyczy:
- obecności opisu alternatywnego,
- przekazywania informacji w tekście,
- kontrastu,
- czytelności.

Powiązanie:
- standardy grafiki,
- publikacja treści.

---

### Lista kontrolna materiałów wideo

Dotyczy:
- napisów,
- synchronizacji,
- audiodeskrypcji lub alternatywy,
- dostępności odtwarzacza.

Powiązanie:
- standard wideo,
- publikacja multimediów.

---

### Lista kontrolna materiałów audio

Dotyczy:
- transkrypcji,
- jakości nagrania,
- zrozumiałości przekazu.

Powiązanie:
- standard audio.

---

### Lista kontrolna dokumentów i załączników

Dotyczy:
- struktury dokumentu,
- możliwości odczytu,
- dostępności PDF,
- obecności alternatywy.

Powiązanie:
- przegląd i naprawa,
- publikacja dokumentów.

---

### Lista kontrolna publikacji (całościowa)

Dotyczy:
- kompletności materiału,
- zgodności ze standardami,
- decyzji publikacyjnej.

Jest stosowana jako ostatni etap przed publikacją.

Powiązanie:
- kontrola przed publikacją.

---

### Lista kontrolna treści od innych podmiotów

Dotyczy:
- kwalifikacji ABCD,
- możliwości modyfikacji,
- oceny dostępności,
- decyzji publikacyjnej.

Powiązanie:
- treści od innych podmiotów.

---

## Powiązanie z procesami

Listy kontrolne są bezpośrednio powiązane z:

- kontrolą przed publikacją – jako narzędzie weryfikacji,
- standardami publikacji – jako źródłem wymagań,
- rejestrem zasobów – jako źródłem danych o wyniku kontroli,
- przeglądem i naprawą – jako narzędzie oceny zasobów,
- treściami zewnętrznymi – jako element kwalifikacji.

---

## Powiązanie z formularzami

Listy kontrolne mogą być realizowane jako:
- formularze,
- arkusze,
- moduły systemowe.

Dane z list powinny być możliwe do:
- zapisania,
- analizy,
- powiązania z konkretnym zasobem.

---

## Minimalny model wdrożenia

W prostym modelu lista kontrolna może być:
- dokumentem tekstowym,
- arkuszem,
- checklistą w formularzu.

Najważniejsze jest:
- stosowanie jej przy każdej publikacji,
- dokumentowanie wyniku,
- powiązanie z decyzją.

---

## Najczęstsze błędy

- brak list kontrolnych,
- traktowanie listy jako formalności,
- brak powiązania z decyzją,
- pomijanie wymagań obowiązkowych,
- zbyt ogólne zapisy,
- zbyt rozbudowane listy, których nikt nie używa,
- brak dokumentowania wyniku.

---

## Efekt dobrze zaprojektowanych list kontrolnych

- spójność decyzji,
- ograniczenie błędów,
- większa przewidywalność procesu,
- lepsza jakość treści,
- możliwość analizy i doskonalenia procesu.

---

## Odniesienia

- [Materiały źródłowe](../../_sources/sdc/)

## Model listy kontrolnej

Lista kontrolna powinna być traktowana jako zestaw reguł walidacyjnych.

### Struktura wymagania

| id | kategoria | wymaganie | typ | krytyczne | dowod |
|----|----------|-----------|-----|-----------|------|

---

### Typy wymagań

- boolean (TAK/NIE)
- ocena (skala)
- opisowe (uwagi)

---

### Reguła decyzyjna

Publikacja możliwa tylko gdy:
- wszystkie wymagania krytyczne = TAK

---

### Przykład (fragment)

| id | kategoria | wymaganie | krytyczne |
|----|----------|-----------|----------|
| T01 | struktura | nagłówki logiczne | TAK |
| G01 | grafika | alt tekst | TAK |
| V01 | wideo | napisy | TAK |
