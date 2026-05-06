# Schematy procesów

## Rola schematów procesów w systemie

Schematy procesów przedstawiają przebieg działań związanych z zarządzaniem treścią publiczną w sposób uporządkowany i zrozumiały.

Ich celem nie jest opisanie teorii, ale pokazanie:
- kolejności działań,
- punktów decyzyjnych,
- odpowiedzialności,
- powiązań między etapami.

Schemat procesowy pozwala przełożyć opis podręcznika na rzeczywisty sposób działania organizacji.

---

## Zasada podstawowa

Każdy proces powinien być możliwy do przedstawienia w formie schematu.

Oznacza to, że:
- wiadomo, od czego proces się zaczyna,
- wiadomo, jakie są jego etapy,
- wiadomo, gdzie zapada decyzja,
- wiadomo, kto odpowiada za dany krok,
- wiadomo, jaki jest wynik procesu.

Jeżeli nie da się narysować procesu, to najczęściej oznacza, że nie jest on dobrze zdefiniowany.

---

## Elementy schematu

Schemat procesu powinien zawierać:

- punkt startowy (np. potrzeba publikacji),
- kolejne kroki procesu,
- punkty decyzyjne,
- możliwe ścieżki (np. publikacja / poprawa / odmowa),
- przypisanie odpowiedzialności (rola),
- punkt końcowy (np. publikacja, archiwizacja).

Schemat powinien być możliwie prosty i czytelny.

---

## Typy schematów w systemie

### Proces tworzenia i publikacji treści

Obejmuje:
1. przygotowanie materiału  
2. przekazanie  
3. kontrolę  
4. decyzję  
5. publikację  
6. wpis do rejestru  

Punkt decyzyjny:
- czy materiał spełnia wymagania

Możliwe ścieżki:
- publikacja  
- poprawa  
- publikacja warunkowa  
- odmowa  

---

### Proces obsługi treści od innych podmiotów

Obejmuje:
1. przyjęcie materiału  
2. identyfikację źródła  
3. kwalifikację (ABCD)  
4. ocenę dostępności  
5. decyzję  
6. publikację lub odmowę  
7. wpis do rejestru  

Punkt decyzyjny:
- czy materiał może być opublikowany

---

### Proces przeglądu i naprawy

Obejmuje:
1. wybór zasobu  
2. ocenę  
3. identyfikację problemów  
4. decyzję  
5. przypisanie odpowiedzialności  
6. naprawę  
7. aktualizację rejestru  

Punkt decyzyjny:
- co zrobić z zasobem

---

### Proces archiwizacji i wycofania

Obejmuje:
1. identyfikację zasobu  
2. ocenę  
3. decyzję  
4. realizację  
5. aktualizację rejestru  

Punkt decyzyjny:
- archiwizacja czy wycofanie

---

### Proces obsługi zgłoszeń dostępności

Obejmuje:
1. przyjęcie zgłoszenia  
2. identyfikację zasobu  
3. ocenę problemu  
4. decyzję  
5. działanie (naprawa / dostęp alternatywny)  
6. odpowiedź użytkownikowi  
7. aktualizację rejestru  

Punkt decyzyjny:
- sposób obsługi zgłoszenia

---

## Powiązanie z mapami odpowiedzialności

Schematy procesów powinny być powiązane z mapami odpowiedzialności.

Oznacza to, że:
- każdy krok ma przypisaną rolę,
- decyzje mają właściciela,
- proces nie zawiera „pustych” etapów.

---

## Powiązanie z narzędziami

Schematy procesów powinny wskazywać, gdzie wykorzystywane są:

- formularze (wejście do procesu),
- listy kontrolne (weryfikacja),
- rejestry (zapis wyników),
- inne narzędzia systemowe.

---

## Forma schematów

Schematy mogą być tworzone jako:

- diagramy blokowe,
- BPMN,
- proste grafiki,
- diagramy w narzędziach online (np. Miro, Draw.io),
- wizualizacje w dokumentacji.

Nie jest wymagany konkretny standard graficzny. Ważna jest czytelność.

---

## Minimalny model wdrożenia

W prostym modelu wystarczy:

- jeden schemat publikacji,
- jeden schemat przeglądu i naprawy.

Pozostałe procesy mogą być rozwijane później.

---

## Najczęstsze błędy

- brak schematów,
- zbyt skomplikowane diagramy,
- brak powiązania z rzeczywistością,
- brak przypisania odpowiedzialności,
- brak aktualizacji schematów,
- tworzenie schematów tylko do dokumentacji.

---

## Efekt dobrze zaprojektowanych schematów

- lepsze zrozumienie procesów,
- łatwiejsze wdrożenie systemu,
- szybsze szkolenie pracowników,
- mniej błędów,
- większa spójność działań,
- możliwość optymalizacji procesów.

---

## Odniesienia

- [Materiały źródłowe](../../_sources/sdc/)

flowchart TD
    A[Input: potrzeba publikacji lub materiał] --> B[Formularz przekazania treści]
    B --> C[Rejestr zasobów: status roboczy]
    C --> D[Kontrola przed publikacją]
    D --> E{Decyzja}

    E -->|OK| F[Publikacja]
    F --> G[Rejestr zasobów: status opublikowany]

    E -->|NIE| H[Naprawa / uzupełnienie braków]
    H --> D

    E -->|Warunkowo| I[Publikacja warunkowa]
    I --> J[Rejestr: status opublikowany warunkowo]
    J --> K[Termin naprawy]
    K --> H
