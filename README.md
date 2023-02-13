# **Task 1 - Testy eksploracyjne** 
## Subtack 1 - Wyciągamy karteczki
Liczba punktów - **9** :blush: :muscle:

## Subtask 3 - Formatowanie README file w GitHub
Hej, mam na imię Sonia  - z wykształcenia inżynier budownictwa, który pragnie swój analityczny umysł wykorzystać w pracy testera oprogramowania. Aktualnie kończę urlop macierzyński, a wolny czas poświęcam na zgłębianie wiedzy i poszerzanie kompetencji zawodowych. A co jest moim celem? Podjęcie nowego wyzwania, sprawdzenie siebie, dobra zabawa i tworzenie nowych ścieżek neuronowych :smirk::fire::fire: 

## Subtask 4 - Testy eksploracyjne – poznaj aplikację
1. Aplikacja dla skautów piłki nożnej to taka baza danych, dotycząca poszczególnych piłkarzy i informacji na ich temat. 
Aplikacja pozwala na dodawanie kolejnych graczy poprzez wypełnienie formularza, nastęnie na dodawanie meczów oraz raportów dla konkretnego gracza. Można następnie przeglądać listę graczy, filtrować interesującą nas część danych, posortować i wydrukować. 

2. Interfejs aplikacji jest bardzo prosty, białe tło, kilka przycisków. Aplikacja wydaje mi się bardzo uboga, niedopracowania graficznie i mało ciekawa dla potencjalnego użytkowanika. 

4. Schemat działania aplikacji jest bardzo prosty, a mimo to mało intuicyjny. Trzeba się trochę naklikać i napróbować, żeby zrozumieć jak to działa. Podstawowa funkcja czyli dodawnie gracza jest umieszczona w rubryce "linki pomocnicze", mogłoby to być w panelu po lewej stronie w formie przycisku z kolorowym tłem, tak by każdy użytkownik od razu ten przycisk zauważył. W tym momencie ten przycisk wygląda jak podejrzany link, w który lepiej nie klikać bo coś wybuchnie :) Niektóre pola formularza są tak nazwane, że nie wiadomo o co chodzi np. "Łączy nas piła", albo "90 minut". Kolejne funkcjonalności, czyli dodawanie meczy i raportów również jest mało intuicyjne. Przyciski działają wolno. Poza tym aplikacja mogłaby nas wylogować, po jakimś czasie braku ruchu. 

5. Uważam, że błędów :bug::bug::bug: tu jest całe mnóstwo:

* w formularzu dodawania gracza gwiazdka powinna być opisana na dole, że jest to pole wymagane,

* wagę i wzrost gracza możemy wybrać lub wklepać jako liczby ujemne,

* w polach gdzie powinno być ograniczenie tylko do tekstu, można wpisywać dowolne znaki np. znaki specjalne lub emotikony,

* jeśli coś źle wpiszemy w formularzu i zatwierdzimy to pojawia się hasło "Nie można dodać gracza", ale generalnie nie wiadomo dlaczego. Powinna być określona przyczyna, lub wskazane pole z błędem,

* data urodzenia czy data meczu nie ma żadnych ograniczeń, przykładowo możemy dodać mecz z przyszłości, albo zawodnika w wieku kilkuset lat,

* w polu gdzie spodziewamy się podać link do youtuba czy adres e-mail można wpisać cokolwiek innego, albo np błędny adres e-mail czy link,

* w kolejnej funkcjonalności czyli dodawaniu meczów, mamy możliwość dodania ujemnego czasu gry w meczu, jak również możemy wybrać nieistniejącą datę meczu, 

* następna funkcjonalność czyli "rozpocznij mecz" gdzie pojawia się widok boiska piłarskiego - przyciski na górze powinny mieć jakieś opisy. Przycisk z dodaniem drugiej połowy meczu działa nieskończoną liczbę razy, przycisk kosza w ogóle nie działa, 

* edycja meczu - nie działa przycisk "clear", z koleji po zatwierdzeniu danych przyciskiem "submit" nie wychodzi nam intuicyjnie z formularza, tylko nadal w nim pozostajemy, co daje dziwne wrażenie, że coś poszło nie tak,

* tworzenie raportów - jako recenzję możemy wybrać liczbę gwiazdek np. pół, a legenda dotyczy tylko całowitych wartości 1-5, nie opisuje również zera, które można wybrać, 

* brak możliwości usunięcia gracza,

* lista wszystkich graczy mogłaby mieć przycisk odsyłający do ostatniej strony listy graczy,

* zmiana języka nie wiąże się z całkowitym przejściem na dany język, przykładowo w polskim nadal niektóre przyciski są po angielsku.

## Subtask 5 - Jira
*Grupa: sirtester* 

*Projekt: challenge portfolio projekt*


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------


# **Task 2 - Przypadki testowe (Test cases)** 

## Subtack 1 -  Pisanie przypadków testowych na podstawie User Story
https://docs.google.com/document/d/18wgTtFV4Ljza61ulkctG6leaGCW4PWpcjORW5GxpMcc/edit

## Subtack 2 - Pisanie przypadków testowych na podstawie “własnych doświadczeń
https://docs.google.com/document/d/1yK46afoGbRQEUS2-d7SiADxkT3Y1TyQMO02mWkaqEd8/edit

## Subtack 3 - Po co piszemy test case’y?
Test case'y piszemy w celu przejrzystego przedstawienia funkcjonalności danej aplikacji. Dążmy do tego by pokryć przypadkami testowymi wszystkie funkcjonalnosci aplikacji, co ułatwi później jej testowanie i raportowanie błędów. Ponadto test case'y są dobrym źródłem informacji dla pozostałych, niewtajemniczonych w aplikację osób. Generalnie przypadki testowe są bardzo ważnym aspektem pracy testera manualnego. 

## Subtack 4 - Dla chętnych 
https://docs.google.com/spreadsheets/d/1Z4GQxUTicf-5v0iVSGIMF_72bpZmDYHq/edit?fbclid=IwAR1VrGerm9mJfK_jdZjF7ljvzM6gc17t6MIOvbAdksK9DbPZ_hefSKePD4w&pli=1#gid=25870091


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Task 3 - Raportowanie błędów**

## Subtack 2 - Testowanie według planów testów i raportowanie błędów
https://docs.google.com/spreadsheets/d/1OhVn8Bs9auQadCJCn_fOIghmQUrdW6sNKlw2kdIDDZY/edit#gid=0

## Subtack 3 - Raport z wykonanych testów
https://docs.google.com/document/d/1WZ-WwZ6n2dnYP1NNNGU1uUfqRL9SLxI3oFGGBWs1PPw/edit

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Task 4 - Testowanie aplikacji mobilnych**

## Subtack 2 - Testowanie eksploracyjne i raportowanie błędów
https://docs.google.com/spreadsheets/d/1um4M3XI1Zzp3HBMtyfY8QQmoY3JgcxiVeKHaHTGVX-Q/edit#gid=0

## Subtack 3 - Do czego służy ta aplikacja OLX?
:chart: Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?


*Aplikacja służy do zamieszczania ogłoszeń w zakresie sprzedaży, zamiany, oddania za darmo rzeczy nowych lub używanych, a także wynajmu nieruchomości czy też zatrudnienia pracowników. Ponadto aplikacja pozwala na wyszukiwanie i przeglądanie ogłoszeń, dokonywanie zakupu, komunikację z innymi użytkowanikami, wspiera również system przesyłek. Głównym celem aplikacji jest nawiązywanie ze sobą kontaktów pomiędzy sprzedającymi a kupującymi z różnych części Polski i pośrednictwo w transakcjach finansowych.*  

:chart: Kto ma być użytkownikiem końcowym aplikacji?


*Użytkownikiem końcowym aplikacji mają być sprzedający i kupujący.* 

:chart: Czy według Ciebie aplikacja jest user friendly? 


*Jako użytkownik aplikacji OLX osobiście uważam, że jest ona user friendly. Głowne przyciski znajdują się na dole ekranu, gdzie są łatwo dostępne dla naszego kciuka. Podstawowe funkcje są wyraźnie pokazane, nie da się ich przeoczyć. Kolorowe grafiki z kategoriami umilają przeglądanie ogłoszeń. Procedura kupna przedmiotu jest również błyskawiczna dla użytkownika, praktycznie mamy tylko kilka szybkich etapów do przejścia. Możnaby troszkę dopieścić szatę graficzną aplikacji, ale poza tym funkcjonowanie appki jest intuicyjne.* 


:chart: Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność? 


*Poprawiłabym system zakupu przedmiotu. Tzn w momencie gdy ktoś kliknie "Kup z przesyłką", to zanim sprzedający zdąży zaakceptować lub odrzucić sprzedaż, ktoś inny może również dokonać zakupu. To rodzi potem niepotrzebne nieporozumienia. 
Ponadto po dokonaniu zakupu, tzn doręczeniu przesyłki i przekazaniu środków, OLX powinien przynajmniej zaproponować zakończenie ogłoszenia. Niestey sprzedający często o tym zapomina i dochodzi do powtornego zakupu sprzdanego już przedmiotu. 
Mogłaby się również pojawić dodatkowa opcja "Rezerwacja przedmiotu", użytkownicy często muszą tą informację zamieszczać w treści ogłoszenia.* 

:chart: Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?

*1. Aplikacja natywna musi zostać zaintalowana na urządzeniu mobilnym, czego nie wymaga aplikacja internetowa.*

*2. W przypadku apliakcji natywnej musimy wskazać nr builda, w przypadku internetowej nie.*

*3. Aplikacje natywną możemy przetestować w trybie offline, a internetową nie.* 

## Subtack 4 - Dla grupy i chętnych. Testy aplikacji mobilnej i webowej.
https://sirtester.atlassian.net/jira/software/projects/CPP/boards/1/backlog?selectedIssue=CPP-16



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Task 5 - Zadanie: SQL part 1**
## Subtack 1 - Krótki kurs podstaw SQL

 Zapytania w języku SQL: 
* `SELECT`
* `FROM`
* `ORDER BY` (`ASC`, `DESC`)
* `WHERE`
* `JOIN`

Operatory w języku SQL:
* `LIKE`
* `=`
* \`>`
* <
* `<>` lub `!=`
* `BETWEEN` 
* `%`
* `_`
* `AND`
* `OR`
* `IN`
* `IS NULL`
* `IS NOT NULL`

## Subtack 2 - Konfiguracja środowiska i wgranie bazy danych

## Subtack 3 - Kilka zadań na rozgrzewkę

1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

* SELECT * 
FROM actors
ORDER BY surname ASC

* ![1](https://user-images.githubusercontent.com/121582618/218319663-83ad281d-0d97-4a84-a27b-e4e7dedaa73f.png)

2. Wyświetl film, który powstał w 2019 roku.

* SELECT * 
FROM movies
WHERE year_of_production=2019

* ![2](https://user-images.githubusercontent.com/121582618/218319726-c284b28c-e9c2-4800-9501-a6a39072e51a.png)

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

* SELECT * 
FROM movies
WHERE year_of_production BETWEEN 1900 AND 1999

* ![3](https://user-images.githubusercontent.com/121582618/218319736-378358b8-71f0-4109-9cfe-e00255fca2e1.png)


4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$

* SELECT title, price 
FROM movies
WHERE price<7

* ![4](https://user-images.githubusercontent.com/121582618/218319742-3838e891-2766-4b6e-832d-34d3a300b533.png)

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

* SELECT *
FROM actors
WHERE actor_id >=4 AND actor_id <= 7

* ![5](https://user-images.githubusercontent.com/121582618/218319751-140e34df-2204-46a1-82bd-2a3b358b0741.png)

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

* SELECT *
FROM customers
WHERE CUSTOMER_ID=2 OR CUSTOMER_ID=4 OR CUSTOMER_ID=6

* ![6](https://user-images.githubusercontent.com/121582618/218319761-a766ee04-23bf-40c3-9937-c77724282f55.png)

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

* SELECT *
FROM customers
WHERE CUSTOMER_ID IN (1, 3, 5)

* ![7](https://user-images.githubusercontent.com/121582618/218319765-734c6cd8-c143-4ca5-9d2a-95a8c9f1147c.png)

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

* SELECT *
FROM actors
WHERE name like 'An%'


* ![8](https://user-images.githubusercontent.com/121582618/218319769-8bbf0bbe-32ca-4290-8fb7-61ac01b6f661.png)

9. Wyświetl dane klienta, który nie ma podanego adresu email.

* SELECT * 
FROM customers
WHERE email is null

* ![9](https://user-images.githubusercontent.com/121582618/218319774-4483f69e-a6ef-43ec-8698-b6da75533f03.png)


10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

* SELECT * 
FROM movies
WHERE (price>9) AND (movie_id BETWEEN 2 AND 8)


* ![10](https://user-images.githubusercontent.com/121582618/218319778-aaeeac76-0e10-48f4-9fd3-2805de9806b0.png)

