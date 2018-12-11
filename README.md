# docs
GaGadki/docs - dokumentacja programu do przegldania wiadomosci


## Sposoby przegladania
na urzadzenia desktop i mobile

## Czytanie


## Usuwanie
jesli bedzie usuwana jakas wiadomosc, to:
+ sprawdz czy istnieje od tego samego adresata, czy watek lub temat byl wczesniej
jesli tak to pokaz te wiadomosci i zapytaj czy maja byc tez usuniete
+ jesli wczesniej nikt nie pisal z tego adresu to zaznacz jako podejrzane, 
+ jesli usune podejrzana wiadomosc, to oznacz te wiadomosc i adresata jako podejrzane

## Tagi
+ twórz meta tagi w oparciu o tekst wiadomosci
+ analizuj ilosc zdan, wyrazow, statystyke wystepowania:
  + rzeczownikow
  + czasownikow
  + przymiotnikow
  
## Lista Odbiorców
+ lista odbiorców traktowana priorytetowo,
+ wszyscy nowi nadawcy oznaczeni jako podejrzani
+ gdy wiadomosc nie zostanie usunieta po przeczytanie, tzn po pierwszych 3 sekundach od przeczytania, to jez zdejmowana flaga: PODEJRZANY NADAWCA
+ jesli usunieta w trakcie 3 sekund od pierwszego odkrycia to oznacz nadawce jako: SPAMER
+ jesli w przyszłości przyjdą wiadomości od niego to automatycznie ładuje do: SPAM

## Listy wysłane
analizuj wysłane wiadomości, sprawdzaj język w jakim wysyłam, jeśli nigdy nie wysłałem np w niemieckim to automatycznie niemieckie wiadomości oznaczaj jako: INNY JĘZYK i PODEJRZANE, jeśli usunę w trakcie 3 sekund to oznacz też jako SPAM

