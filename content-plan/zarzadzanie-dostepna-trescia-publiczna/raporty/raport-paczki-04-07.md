# Raport paczki artykułów 04-07

## Zakres pracy

Napisano cztery artykuły w katalogu `artykuly`:

1. `04-tresci-od-innych-podmiotow.md`
2. `05-rejestr-zasobow.md`
3. `06-publikacja-w-bip.md`
4. `07-publikacja-kryzysowa.md`

Nie pisano artykułów 08-10, nie publikowano treści i nie zmieniano materiału źródłowego.

## Co napisano

### Artykuł 04: Treści od innych podmiotów

Powstał poradnik o przyjmowaniu materiałów od partnerów, organizatorów, wykonawców, innych komórek i podmiotów zewnętrznych. Tekst wyjaśnia, że redakcja nie przejmuje odpowiedzialności za sens merytoryczny cudzych dokumentów, ale odpowiada za sposób ich publikacji w serwisie.

Element praktyczny: pytania do nadawcy materiału.

Przykład: plakat JPG i regulamin PDF przesłane przez organizatora wydarzenia.

### Artykuł 05: Rejestr zasobów

Powstał artykuł organizacyjny o prowadzeniu rejestru dokumentów, plików i aktualności. Tekst pokazuje, po co redakcji rejestr, jakie pola powinien zawierać, jak rozdzielić rejestr treści, plików i spraw do naprawy oraz jak zacząć w małej instytucji.

Element praktyczny: tabela pól rejestru i minimalny wzór rejestru.

Przykład: przegląd PDF-ów opublikowanych po 23 września 2018 roku oraz aktualności z załącznikami.

### Artykuł 06: Publikacja w BIP

Powstał artykuł specjalistyczny o publikacji w BIP. Tekst rozróżnia stronę WWW i BIP, opisuje kategorie, metadane, historię zmian, odpowiedzialność merytoryczną i redakcyjną oraz dokumenty, których nie należy traktować jak zwykłej aktualności.

Element praktyczny: mini procedura publikacji w BIP.

Przykład: zarządzenie przesłane jako PDF bez kategorii, daty obowiązywania i informacji o poprzedniej wersji.

### Artykuł 07: Publikacja kryzysowa

Powstał poradnik o szybkim publikowaniu pilnych komunikatów bez utraty minimum dostępności. Tekst skupia się na pracy pod presją czasu: minimum informacji, unikaniu komunikatów wyłącznie graficznych, opisie załączników, skróconej akceptacji i uzupełnieniu publikacji po fakcie.

Element praktyczny: minimum komunikatu pilnego.

Przykład: awaria ogrzewania i przeniesienie obsługi mieszkańców do innego budynku.

## Jak rozdzielono zakresy

Artykuły mają różne funkcje w klastrze:

- 04 odpowiada na pytanie, co zrobić z materiałem, który przyszedł z zewnątrz i nie jest gotowy do dostępnej publikacji.
- 05 odpowiada na pytanie, jak utrzymać porządek po publikacji i nie zgubić właścicieli, terminów oraz statusów dostępności.
- 06 odpowiada na pytanie, jak prowadzić publikację formalną w BIP bez mieszania jej ze zwykłą aktualnością.
- 07 odpowiada na pytanie, jak opublikować pilny komunikat szybko, ale nadal czytelnie i dostępnie.

Zakresy nie dublują trzech artykułów testowych. Tekst filarowy opisuje cały proces, artykuł o rolach mapuje odpowiedzialność, a lista kontrolna pomaga przed publikacją. Nowa paczka rozwija konkretne sytuacje: materiał zewnętrzny, rejestr, BIP i tryb pilny.

## Zastosowane przykłady

Każdy artykuł ma osobny przykład:

- 04: organizator wydarzenia przesyła plakat JPG i regulamin PDF.
- 05: redakcja przegląda PDF-y opublikowane po 23 września 2018 roku i aktualności z załącznikami.
- 06: do BIP trafia zarządzenie bez kategorii, daty obowiązywania i informacji o poprzedniej wersji.
- 07: awaria ogrzewania wymusza szybki komunikat o zmianie obsługi mieszkańców.

Przykłady nie powtarzają wcześniejszych sytuacji z artykułów 01-03: starego formularza w kilku miejscach, komunikatu o zmianie godzin pracy ani naboru z formularzem i terminem.

## Powtórzenia wykryte i usunięte

Po napisaniu artykułów wykonano kontrolę zakazanych znaków i fraz oraz porównanie długich zdań między artykułami 01-07. Nie wykryto skopiowanych zdań o długości powyżej 90 znaków.

W trakcie redakcji ograniczono ryzyko powtórzeń przez:

- różne punkty wejścia w tekstach,
- różne przykłady praktyczne,
- różne elementy praktyczne,
- inne zakończenia dla każdego artykułu,
- dopasowane linki wewnętrzne zamiast jednej kopiowanej listy,
- różne opisy grafiki głównej i statusu jakości.

Stałe pozostały tylko wymagane bloki końcowe: propozycje linków wewnętrznych, blok SEO, grafika główna i status jakości. Ich treść została dopasowana do tematu artykułu.

## Kontrola techniczna

Sprawdzono:

- brak długiego myślnika,
- brak poziomych separatorów w treści poza wymaganym front matter YAML,
- brak fraz wskazanych jako sztuczne lub anglojęzyczne zamienniki,
- obecność jednego H1 w każdym artykule,
- obecność leadu po H1,
- obecność bloków SEO,
- obecność tagów WordPress po przecinku,
- obecność sugestii grafiki głównej,
- obecność tekstu alternatywnego,
- obecność propozycji linków wewnętrznych,
- obecność statusu jakości.

`git diff --check` nie wskazał błędów formatowania dla śledzonych plików. Nowe pliki są nieśledzone do czasu dodania ich do Git.

## Czy artykuły nadają się do dalszej redakcji

Tak. Artykuły nadają się do dalszej redakcji jako druga paczka serii. Mają kompletną strukturę, osobne przykłady, praktyczne elementy i spójny ton z poprawionymi artykułami testowymi.

Przed publikacją warto przejść zwykły etap redakcyjny:

- dopasować docelowe adresy linków wewnętrznych,
- sprawdzić, czy nazwy usług odpowiadają aktualnej ofercie beardedwolf.pl,
- zdecydować, czy z wybranych elementów praktycznych powstaną osobne materiały do pobrania.

## Miejsca wymagające decyzji Bartłomieja Wilka

Do decyzji Bartłomieja Wilka pozostają:

- czy artykuł 04 ma prowadzić do osobnej usługi lub formularza przyjmowania materiałów od partnerów,
- czy w artykule 05 dodać docelowy wzór rejestru jako plik do pobrania,
- czy w artykule 06 dodać odniesienia do konkretnych procedur BIP stosowanych u klientów,
- czy w artykule 07 dodać gotowy szablon komunikatu pilnego,
- jakie docelowe adresy URL podstawić pod opisowe linki wewnętrzne,
- czy w grafikach głównych zachować jednolity styl ciemny z akcentem starego złota dla całej serii,
- czy statusy jakości mają być widoczne w materiałach roboczych tylko wewnętrznie, czy także w planie publikacji.
