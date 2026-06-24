# eDo Manager
Aplikacja dla Windows do obsługi skrzynek eDoręczeń: podgląd przed odbiorem, załączniki, foldery, przekazywanie wiadomości na email i rejestr przekazań. Dla skrzynek firmowych i zawodowych.

![eDo Manager](https://kuczynski.biz/pomoc/18.jpg)

## Najważniejsze funkcje

- obsługa skrzynek eDoręczeń w jednym widoku,
- podgląd nadawcy i tematu wiadomości przed jej odebraniem,
- odbiór wiadomości z systemu eDoręczeń,
- otwieranie i zapisywanie załączników,
- przekazywanie pojedynczych lub wielu wiadomości na adresy email,
- rejestr przekazań wraz ze statusami,
- przenoszenie wiadomości między folderami,
- lokalna konfiguracja aplikacji i skrzynek.

## Dla kogo

eDo Manager jest przeznaczony dla użytkowników korzystających ze skrzynek:

- firmowych,
- zawodowych/profesjonalnych, m.in. adwokatów, radców prawnych, notariuszy i innych podmiotów działających w systemie eDoręczeń.

Z uwagi na ograniczenia systemu eDoręczeń aplikacja **nie obsługuje skrzynek osobistych**.

## Typowe zastosowania

eDo Manager sprawdza się przy:

- bieżącej obsłudze korespondencji z eDoręczeń,
- przekazywaniu wiadomości klientom lub współpracownikom na email,
- porządkowaniu korespondencji między folderami,
- kontroli, które wiadomości zostały przekazane dalej,
- pracy ze skrzynkami zawodowymi i firmowymi bez każdorazowego korzystania z interfejsu portalu.

## Konfiguracja

Aplikacja wymaga jednorazowej konfiguracji skrzynki eDoręczeń.

W uproszczeniu proces obejmuje:

1. dodanie skrzynki w eDo Managerze,
2. wygenerowanie klucza autoryzacyjnego,
3. wyeksportowanie pliku CSR,
4. wgranie danych w systemie edoreczenia.gov.pl,
5. aktywację i zapisanie konfiguracji w aplikacji.

Przekazywanie wiadomości na email wymaga również skonfigurowania serwera poczty wychodzącej SMTP.

Szczegółowy opis znajduje się w dokumentacji:

[Dokumentacja konfiguracji eDo Managera](https://kuczynski.biz/edo-manager/dokumentacja/)

## Pobieranie

Instalator będzie publikowany w sekcji **Releases** tego repozytorium.

Strona produktu: [kuczynski.biz/edo-manager](https://kuczynski.biz/edo-manager/)

Aktualne informacje o wersji: [version.json](https://kuczynski.biz/edo-manager/version.json)

## Wymagania

- Windows 10/11, 64-bit
- skrzynka firmowa albo zawodowa w systemie eDoręczeń
- konfiguracja klucza autoryzacyjnego w systemie edoreczenia.gov.pl
- opcjonalnie: dane serwera SMTP, jeżeli użytkownik chce przekazywać wiadomości na email

## Prywatność i dane

eDo Manager działa lokalnie na komputerze użytkownika.

Konfiguracja oraz dane aplikacji pozostają lokalnie. kuczynski.biz nie pośredniczy w korespondencji i nie zbiera danych przez formularz pobrania.

Aplikacja łączy się wyłącznie z:

- systemem eDoręczeń,
- serwerem synchronizacji czasu,
- serwerem poczty wychodzącej SMTP skonfigurowanym przez użytkownika.

## Licencja

Aplikacja, instalatory i wydania binarne są udostępniane na warunkach umowy licencyjnej użytkownika końcowego:

- [EULA](https://kuczynski.biz/edo-manager/)
- [Informacje o komponentach zewnętrznych](https://kuczynski.biz/edm_THIRD-PARTY-NOTICES.txt)

To repozytorium służy do publikacji wydań aplikacji i instalatorów. Kod źródłowy nie jest publikowany.

## Autor

eDo Manager jest autorską aplikacją adw. Marcina Kuczyńskiego.

Więcej narzędzi: [kuczynski.biz](https://kuczynski.biz/)

LinkedIn: [Marcin Kuczyński](https://www.linkedin.com/in/marcin-kuczynski-adwokat/)
