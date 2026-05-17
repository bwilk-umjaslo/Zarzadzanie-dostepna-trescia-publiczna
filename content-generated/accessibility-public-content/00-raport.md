# Raport podsumowujący serię artykułów

## 1. Wykorzystane źródła z podręcznika

- `src/index.md` - logika treści publicznej jako zasobu, model cyklu życia, decyzje publikacyjne.
- `src/04-kontrola-przed-publikacja.md` - kontrola operacyjna, bramka publikacyjna, dokumentowanie decyzji.
- `src/06-tresci-od-innych-podmiotow.md` - materiały zewnętrzne, odpowiedzialność, klasyfikacja A/B/C/D.
- `src/07-przeglad-i-naprawa.md` - przegląd, priorytetyzacja, naprawa, statusy i decyzje.
- `src/08-archiwizacja-i-wycofanie.md` - archiwizacja, wycofanie, dostępność treści archiwalnej.
- `src/05-rejestr-zasobow.md` - znaczenie rejestru jako narzędzia operacyjnego.
- `src/02-standardy-publikacji.md` - opis plików, dokumentów, załączników i wymogów dostępności.
- `src/procesy/publikacja-w-bip.md` - praktyczne ujęcie publikacji w BIP oraz struktury informacji.

## 2. Sprawdzone istniejące treści w repozytorium

- katalogi `src/`, `book/` i `_sources/` z pełną dokumentacją podręcznika,
- brak katalogów dedykowanych WordPressowi: `content`, `posts`, `blog`, `pages`, `services`, `realizacje`, `drafts`, `wordpress-import` nie występują w repozytorium,
- istniejące rozdziały `Treści od innych podmiotów`, `Kontrola przed publikacją`, `Rejestr zasobów`, `Przegląd i naprawa`, `Archiwizacja i wycofanie`, `Publikacja w BIP` i inne powiązane treści.

## 3. Ryzyko duplikacji

- Ryzyko ogólne: niskie, ponieważ tworzone artykuły to nowe teksty blogowe z praktycznym, usługowym i eksperckim akcentem, a nie kopiowanie rozdziałów.
- Ryzyko średnie dla `Treści od innych podmiotów`, `Kontrola przed publikacją` i `Dostępny PDF`, ponieważ tematy są zbliżone do treści podręcznika; zostały jednak opracowane z nowym kątem i w narracji dla WordPressa/stron publicznych.

## 4. Lista utworzonych artykułów

1. Treść publiczna jako zasób: jak zaplanować odpowiedzialność w redakcji
2. Właściciel treści i status dostępności: kto odpowiada za dokumenty, załączniki i aktualności
3. Kontrola przed publikacją w WordPressie: co naprawdę musi przejść redakcja
4. Link, przycisk, załącznik: małe decyzje, które zmieniają dostępność strony
5. Dostępny PDF w urzędzie: czym różni się dokument od skanu
6. Jak opisywać pliki do pobrania, żeby użytkownik wiedział, co pobiera
7. Treści od innych podmiotów: decyzja publikacyjna, klasyfikacja i odpowiedzialność
8. Publikacja warunkowa i alternatywna forma dostępu: kiedy opublikować z zastrzeżeniem
9. Rejestr zasobów w praktyce: prosty sposób, by BIP i WordPress nie tonęły w chaosie
10. Przegląd i naprawa starych dokumentów: jak zacząć program w małej instytucji
11. Archiwizacja i wycofanie treści: kiedy stara informacja przestaje pomagać
12. BIP bez chaosu: jak uporządkować informacje publiczne i utrzymać dostępność

## 5. Lista tematów odłożonych na później

- szczegółowy artykuł o tabelach i ich dostępności,
- poradnik dla redakcji o metadanych SEO w treściach publicznych,
- case study z wdrożenia rejestru zasobów w urzędzie,
- tekst o obsłudze żądań dostępności w praktyce i procedurach wnoszenia zgłoszeń.

## 6. Propozycje kolejnych tekstów

- „Żądanie dostępności w praktyce urzędu - jak obsługiwać zgłoszenia i plan naprawy”,
- „Jak przygotować dostępne opisy wydarzeń i plakaty w serwisie publicznym”,
- „Raport z audytu dostępności plików PDF i formularzy w małej instytucji”,
- „Odpowiedzialność BIP i WordPress: kiedy treść powinna być w obu kanałach”.

## 7. Uwagi techniczne do importu do WordPressa

- wszystkie artykuły zostały zapisane jako pliki Markdown z YAML front matter,
- każdy plik ma jeden H1, metadane SEO, slug i listę tagów,
- nie użyto poziomych separatorów ani znaku „—” w treści,
- należy sprawdzić, czy temat „BIP bez chaosu” odpowiada strukturze kategorii w docelowym WordPressie,
- warto przypisać kategorie zgodne ze strukturą strony: `Dostępność cyfrowa`, `WordPress`, `BIP i instytucje publiczne`.

## 8. Struktura artykułów i różnice między nimi

- artykuły mają różną logikę i strukturę treści,
- część to teksty problemowe, część to eksperckie wyjaśnienia, a część to praktyczne poradniki,
- każdy tekst używa innego rytmu, innego podejścia do przykładów i innego układu śródtytułów,
- w tekstach uniknięto mechanicznego powtarzania jednego szablonu.

## 9. Dopasowanie promptów do grafik

- dla każdego artykułu przygotowano osobny prompt graficzny,
- każdy prompt wynika z tytułu i tematu tekstu,
- grafiki zaplanowano z równomiernym akcentem: ciemne tło, matowa czerń, grafit, stare złoto i profesjonalny charakter,
- każdy prompt unika tekstu na grafice, logo i piktogramów.

## 10. Lokalizacja plików

- artykuły: `content-generated/accessibility-public-content/drafts/`
- grafiki: `content-generated/accessibility-public-content/graphics/`
- mapy i raporty: `content-generated/accessibility-public-content/`
