# Raport przygotowania artykułów WordPress

## Zmienione pliki

- 00-podrecznik-jako-artykuly.md
- 01-wstep.md
- 02-model-organizacji.md
- 03-cele-systemu.md
- 04-zasady-ogolne.md
- 05-podstawy-prawne-i-standardy.md
- 06-definicja-operacyjna-niezbednosci.md
- 07-najczestsze-bledy.md
- 08-standardy-publikacji.md
- 09-tworzenie-tresci.md
- 10-kontrola-przed-publikacja.md
- 11-rejestr-zasobow.md
- 12-tresci-od-innych-podmiotow.md
- 13-przeglad-i-naprawa.md
- 14-archiwizacja-i-wycofanie.md
- 15-publikacja-w-bip.md
- 16-publikacja-kryzysowa.md
- 17-ai-w-tresciach-publicznych.md
- 18-narzedzia-systemowe.md
- 19-listy-kontrolne.md
- 20-formularze.md
- 21-rejestry.md
- 22-mapy-odpowiedzialnosci.md
- 23-schematy-procesow.md
- 24-slownik-pojec.md
- 25-o-autorze.md
- 26-kontakt.md

## Liczba artykułów

Przygotowano 26 artykułów poradnikowych: od 01-wstep.md do 26-kontakt.md.

## Kontrola front matter

Każdy artykuł 01-26 ma front matter YAML z polami:

- title
- slug
- meta_title
- meta_description
- focus_keyword
- secondary_keywords
- wordpress_category
- wordpress_tags
- suggested_excerpt
- suggested_image_prompt

## Kontrola nagłówków H1

Każdy artykuł 01-26 ma dokładnie jeden nagłówek H1.

## Wyniki kontroli jakości

Sprawdzono serię pod kątem:

- obecności front matter YAML,
- dokładnie jednego H1,
- logicznej struktury H2,
- braku poziomych separatorów poza granicami front matter,
- braku znaku em dash,
- braku emoji,
- obecności elementu praktycznego,
- obecności opisu grafiki wyróżniającej,
- obecności meta title i meta description,
- zapisu tagów po przecinku.

Kontrola nie wykazała błędów strukturalnych.

## Tematy do późniejszej ręcznej weryfikacji

- Doprecyzowanie lokalnych podstaw prawnych dla konkretnych typów publikacji w BIP.
- Uzupełnienie przykładów o nazwy faktycznie stosowanych formularzy, rejestrów i procedur w instytucji.
- Sprawdzenie, czy kategorie WordPress odpowiadają docelowej strukturze serwisu.
- Dostosowanie opisów grafik wyróżniających do finalnego stylu graficznego strony.
- Weryfikacja długości i tonu artykułów po osadzeniu w motywie WordPress.

## Propozycja kolejnego kroku

Następny krok: przygotowanie importu do WordPressa w formacie XML lub CSV, a potem wygenerowanie grafik wyróżniających na podstawie pól suggested_image_prompt.
