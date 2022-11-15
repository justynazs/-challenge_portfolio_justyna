
# HELLO WORLD! MY VERY FIRST REPO 👍👏👩‍🦱

# **Task 1** 

## **Subtask 1**

## 8/10 pkt z fajnym komentarzem: _"No mordeczko, moja. Postarałaś się!"_


## Subtask 3 

## Dlaczego zdecydowałam się na udział w Challenge Portfolio? 
Moje motywacje to:

✔ zdobycie kompetencji cyfrowych 

✔ chęć nauki

✔ ciekawość

✔ przebranżowienie 

✔ nomadyzm cyfrowy

✔ niepewna sytuacja geopolityczna


Stay tuned 

###### _Justyna :)_ 
😊😺

## Subtask 4


## Na czym polega aplikacja Scout Panels? Do czego służy?

Scouts  Panel to aplikacja służąca do tworzenia, przeglądania i zarządzania danymi o zawodnikach (piłkarzach), rozegranych meczach oraz do tworzenia szczegółowych raportów.

W aplikacji zarejestrowanych jest 725 graczy (na dzień 31.10.)


## Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a?

Aplikacja wyposażona jest w następujące funkcjonalności:

- dodawanie graczy/zawodników (brak opcji “Usuń gracza”)
- uzupełnianie danych personalnych zawodników oraz dodawanie szczegółowych informacji meczowych w edytowalnych formularzach:


** danych obowiązkowych: imię i nazwisko, data urodzenia, główna pozycja 


** danych nieobowiązkowych: e-mail, telefon, waga, wzrost, dominująca noga, pozycja alternatywna, województwo, osiągnięcia, główna pozycja, rozegrane mecze, klub, poziom rozgrywek, języki, opcja dodawania odnośników do mediów społecznościowych, platform piłkarskich.


- tworzenie indywidualnych raportów meczowych z analizą gry zawodników: szczegóły i dane statystyczne o celnych i nietafionych strzałach, podaniach krótkich, podaniach głównych, dośrodkowaniach, pojedynkach 1 na 1, stratach, faulach, odbiorach, innych danych jak: reprezentowany klub, rodzaj meczu, barwę koszulki, recenzja meczu.


- wyszukiwanie i przeglądanie zarejestrowanych/dodanych graczy po wpisaniu w wyszukiwarkę imienia /nazwiska
- filtrowanie wyszukiwań zawodników (np. po wieku, klubie, pozycji)

- dodawanie meczy
- drukowanie list graczy

- generowanie plików CSS
- opcję przechodzenia/łączenia się z zespołem testerskim przez kliknięcie w Dev Team Contact
- opcję przełączenia strony na wersję angielską
- opcję wylogowania z systemu







Strona jest intuicyjna. 


Unowocześniłabym wygląd aplikacji bo jest zdecydowanie uboga, dodając kolor tła lub grafiki związane z piłką nożną.  

Proponuję dodatkowe zmiany:

- na stronie głównej dodałabym i zaakcentowała kolorem przycisk “Dodaj gracza” a usunęłabym wyrażenie “Linki pomocnicze”, ponieważ wprowadzają w błąd a żadnymi linkami nie są 
- na stronie głównej przy graczach dodałabym awatary użytkowników

- w formularzu danych personalnych dodałabym: ikony mediów społecznościowych, przy opcji “Języki” dodałabym frazę “Znajomość języków”. 


## Oceń interfejs aplikacji – czy Ci się podoba, czy nie?

Interfejs aplikacji nie powala na kolana designem ale sprawia, że strona jest czytelna i prosta w obsłudze.



Na stronie głównej po lewej stronie widoczne są podstrony z ikonkami określającymi ich funkcjonalność. 


W formularzu danych personalnych pojawia się wygodna opcja wyboru daty urodzenia z kalendarza za pomocą ”Date pickera”.

Z rozwijanej listy wybrać można "Województwo" - fajne rozwiązanie bo nie trzeba wpisywać nazwy województwa ręcznie.


Wartości liczbowe np. wiek zawodnika również można wybrać z rozwijanej listy.


Opcję "Dodaj język" oraz link do You Tube'a można usunąć - po wpisaniu frazy np. "angielski" lub wklejeniu linka do You Tube pojawia się czerwona ikonka kosza. 



## Czy aplikacja jest intuicyjna? 

Aplikacja jest prosta w obsłudze i nie sprawia użytkownikom trudności. 


Komunikat “Dodaj gracza” jest czytelny i nawet mało rozgarnięty użytkownik, nie będzie miał problemu z podjęciem właściwego działania :)

Aplikacja jest responsywna i czytelna na urządzeniu mobilnym.








## Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? 

W formularzu dodawania danych personalnych, przy dacie urodzenia gracza celowo podałam absurdalną datę - 31.10.2022 żeby sprawdzić czy system pozwoli mi pójść dalej. No i pozwolił, ładnie zapisując wszystkie dane i nie informując o błędzie.


Korzystając z Dev tools, na stronie głównej pojawiają się następujące komunikaty:


- Błąd 404: _Failed to load resource: the server responded with a status of 404_ czyli jakaś treść/zasób się nie wyświetlił (niestety w tej chwili nie mogę do niego dojść, ponieważ zakładka Console nie wyświetla mi zawartości (?)


- Parametry _`start`_ and _`limit`_ są przestarzałe. Use _`_start`_ and _`_limit`_



Raport z Lighthouse pokazuje co można ulepszyć i poprawić:


- wydajnosć strony oszacowana została na 67%, SEO 91%, ułatwienia dostępu 92%, sprawdzone metody 92%
- nie rejestruje skryptu service worker, który steruje stroną i elementem start_url
- wykryto 3 luki w zabezpieczeniach (aplikacja może być łatwym celem hakerów)
- nie skonfigurowano niestandardowego ekranu powitalnego: _"Failures: No manifest was fetched"_
- plik manifestu aplikacji internetowej lub skrypt service worker nie spełnia wymagań instalowalności 
- nie ustawia motywu kolorystycznego paska adresu: _"Failures: No manifest was fetched"_
- nie dostarcza prawidłowego atrybutu _apple-touch-icon_
- plik manifestu nie ma ikony z możliwością maskowania: _"No manifest was fetched"_


Po wejściu na konto Gracza przycisk “Clear” (różowy) jest nieaktywny i klikając w niego domyślnie powinien usuwać dane osobowe wraz z całym kontem, a tak się nie dzieje.

Kafelki na stronie głównej powinny być klikalne

Dużym błędem jest brak możliwości usunięcia Gracza z aplikacji




# **Task 2** 

https://drive.google.com/drive/folders/19kqP4betxQXrstihLRR8fu5I_nLssCrw

## Subtask 4

https://docs.google.com/document/d/164lum8wfixR88mhimARGnkl_FtmL5E5n7eGDKlgOF60/edit


# **Task 3** 

## **Subtask 1**

https://docs.google.com/spreadsheets/d/1Zw9536ijcbvO7mphFlzcEHwc686ZagMSifiKdcNm_S0/edit#gid=0

## **Subtask 2**

https://docs.google.com/spreadsheets/d/1WPYQe8Za87NjGtabYu8MtIbrKVSBEB7XGkPmvRujPHg/edit#gid=0

## **Subtask 3**

https://docs.google.com/document/d/1zeuzy9co_0sSew0ehgCVRNbG4BZGC2dB3zX7qsrf3Yo/edit


https://drive.google.com/drive/u/0/folders/1c8rVBC65SfG458uPo7uSVF3HJqoTjOuj

