# Raport jakości

## Ile szkiców wejściowych przeanalizowano

Przeanalizowano 26 szkiców z pliku:

`content-generated/wordpress-handbook/wordpress-handbook-artykuly.txt`

## Ile tematów połączono

Do 10 docelowych artykułów scalono łącznie 26 szkiców źródłowych.

Najważniejsze połączenia:

- 4 szkice o rejestrach, formularzach i narzędziach redakcyjnych połączono w temat o rejestrze zasobów.
- 3 szkice o rolach, mapach odpowiedzialności i schematach procesów połączono w temat o rolach w redakcji publicznej.
- 3 szkice o wstępie, celach i zasadach ogólnych połączono w artykuł filarowy.
- 3 szkice o kontroli, błędach i listach kontrolnych połączono w poradnik praktyczny dla redaktora.
- 2 szkice o przeglądzie i archiwizacji rozdzielono na dwa teksty z wyraźną granicą zakresu.

## Ile tematów odrzucono jako duplikaty

Jako osobne artykuły odrzucono 16 tematów lub wariantów tematów. Nie zostały usunięte z materiału źródłowego. Zostały przypisane jako sekcje, ramki, elementy praktyczne albo fragmenty do wykorzystania w większych tekstach.

## Jakie 10 artykułów docelowych powstało

1. Jak zarządzać dostępną treścią publiczną w WordPressie i BIP
2. Role w redakcji publicznej: kto odpowiada za treść, dostępność i publikację
3. Lista kontrolna redaktora przed publikacją w WordPressie i BIP
4. Jak przyjmować treści od innych podmiotów i nie tracić kontroli nad dostępnością
5. Rejestr zasobów: jak uporządkować dokumenty, pliki i aktualności
6. Publikacja w BIP: procedura, kategorie i odpowiedzialność
7. Publikacja kryzysowa: jak działać szybko i nie psuć dostępności
8. Przegląd i naprawa starszych treści: jak odzyskać kontrolę nad archiwum strony
9. Archiwizacja i wycofanie treści publicznych: kiedy zostawić, kiedy opisać, kiedy usunąć
10. AI w redakcji publicznej: pomocne narzędzie, nie autor decyzji

## Które 3 artykuły napisano jako testowe

W katalogu `artykuly/` przygotowano:

- `01-jak-zarzadzac-dostepna-trescia-publiczna.md`
- `02-role-w-redakcji-publicznej.md`
- `03-lista-kontrolna-redaktora.md`

Każdy tekst ma front matter YAML, jeden H1, lead, strukturę H2 i H3 tam, gdzie jest potrzebna, blok SEO, sugestię grafiki, tekst alternatywny i propozycje linków wewnętrznych.

## Najbardziej powtarzalne fragmenty materiału wejściowego

Najbardziej powtarzalne były:

- identyczne nagłówki sekcji w 26 szkicach,
- powtarzany wstęp o krótkich terminach i dokumentach przesłanych w ostatniej chwili,
- identyczny przykład dokumentu PDF przesłanego do natychmiastowej publikacji,
- identyczna lista kontrolna,
- identyczny akapit o małym zespole,
- identyczne zakończenie o konsekwencji i regularnym przeglądzie.

## Wykryte błędy składniowe

W materiale wejściowym wykryto błędy po automatycznym podstawieniu fraz, między innymi:

- `publikacja w BIP trzeba opisać`,
- `cele systemu publikacji decyduje`,
- `zasady publikowania treści publicznych decyduje`,
- `kontrola przed publikacją warto traktować`,
- `archiwizacja treści publicznych trzeba opisać`,
- `kontakt dostępność cyfrowa`.

Te frazy nie zostały użyte w artykułach testowych. Występują tylko w analizie jako przykłady błędów.

## Co wymaga ręcznej decyzji Bartłomieja Wilka

Do decyzji pozostają:

- finalne adresy linków wewnętrznych na beardedwolf.pl,
- dokładne powiązanie artykułów z usługami,
- wybór kategorii WordPress, jeżeli obecna struktura kategorii różni się od zaproponowanej,
- decyzja, czy temat kontaktu w sprawie dostępności ma być osobnym artykułem w przyszłym klastrze,
- zakres prawny tekstu o BIP, jeżeli ma zawierać konkretne podstawy prawne,
- decyzja, czy artykuły testowe rozwijać w tym samym tonie i długości.

## Czy seria nadaje się do dalszego generowania artykułów

Tak, ale nie na podstawie pierwotnych szkiców jeden do jednego.

Seria nadaje się do dalszego pisania na podstawie przygotowanych briefów. Każdy kolejny artykuł powinien mieć własny przykład, własny element praktyczny i odrębny zakres. Nie należy wracać do automatycznego schematu 26 podobnych tekstów.

## Wynik kontroli technicznej

Sprawdzono pliki w nowym katalogu pod kątem:

- obecności jednego H1 w dokumentach,
- braku długiego myślnika,
- braku niedozwolonej obcej nazwy listy kontrolnej,
- braku błędnych fraz automatycznych w artykułach testowych,
- front matter YAML w trzech artykułach testowych,
- obecności bloku SEO w trzech artykułach testowych.

Nie wykryto problemów w artykułach testowych.
