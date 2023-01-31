# **Task 1 - Testy eksploracyjne** 
## Subtack 1 - Wyciągamy karteczki
Liczba punktów - **9** :blush:

## Subtask 3 - Formatowanie README file w GitHub
Hej jestem Sonia, z wykształcenia inżynier budownictwa szukający swojej życiowej ścieżki. Aktualnie kończę urlop macierzyński i od dłuższego czasu móżdżę, jak to zrobić by nie wracać do znienawidzonej pracy w urzędzie :D Po przegrzaniu wielu zwojów mózgowych doszłam do wniosku, że chcę zmienić brażę i spróbować IT. Gdy poznałazm cechy idealnego testera - stwierdziłam "to jest to!". I tak się tu znalazłam. A co jest moim celem? Podjęcie nowego wyzwania, sprawdzenie siebie, dobra zabawa i tworzenie nowych ścieżek neuronowych :) 

## Subtask 4 - Testy eksploracyjne – poznaj aplikację
1. Aplikacja dla skautów piłki nożnej to taka baza danych, dotycząca poszczególnych piłkarzy i informacji na ich temat. 
Aplikacja pozwala na dodawanie kolejnych graczy poprzez wypełnienie formularza, nastęnie na dodawanie meczów oraz raportów dla konkretnego gracza. Można następnie przeglądać listę graczy, filtrować interesującą nas część danych, posortować i wydrukować. 

2. Interfejs aplikacji jest bardzo prosty, białe tło, kilka przycisków. Generalnie nie bardzo mi się podoba.

4. Schemat działania aplikacji jest bardzo prosty, a mimo to mało intuicyjny. Trzeba się trochę naklikać i napróbować, żeby obczaić jak to działa. Podstawowa funkcja czyli dodawnie gracza jest umieszczone w rubryce "linki pomocnicze", mogłoby to być w panelu po lewej stronie w formie przycisku z kolorowym tłem, tak by każdy użytkownik od razu ten przycisk zauważył. W tym momencie ten przycisk wygląda jak podejrzany link, w który lepiej nie klikać bo coś wybuchnie :) Niektóre pola formularza są tak nazwane, że nie wiadomo o co chodzi np. "Łączy nas piła", albo "90 minut". Kolejne funkcjonalności, czyli dodawanie meczy i raportów również jest mało intuicyjne. Przyciski działają wolno. Poza tym aplikacja mogłaby nas wylogować, po jakimś czasie braku ruchu. 

5. Uważam, że błędów tu jest całe mnóstwo:
* w formularzu dodawania gracza gwiazdka powinna być opisana na dole, że jest to pole wymagane,
* wagę i wzrost gracza możemy wybrać lub wklepać jako liczby ujemne,
* w polach gdzie powinno być ograniczenie tylko do tekstu, można wpisywać dowolne znaki np. znaki specjalne lub emotikony,
* jeśli coś źle wpiszemy w formularzu i zatwierdzimy to pojawia się hasło "Nie można dodać gracza", ale generalnie nie wiadomo dlaczego. Powinna być określona przyczyna, lub wskazane pole z błędem,
* data urodzenia czy data meczu nie ma żadnych ograniczeń, przykładowo możemy dodać mecz z przyszłości, albo zawodnika w wieku kilkuset lat,
* w polu gdzie spodziewamy się podać link do youtuba czy adres e-mail można wpisać cokolwiek innego, albo np błędny adres e-mail czy link,
* w kolejnej funkcjonalności czyli dodawaniu meczów, mamy możliwość dodania ujemnego czasu gry w meczu, jak również datę meczu możemy wybrać z przyszłosci, 
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

## Subtack 4 - DLA CHĘTNYCH
https://docs.google.com/spreadsheets/d/1Z4GQxUTicf-5v0iVSGIMF_72bpZmDYHq/edit?fbclid=IwAR1VrGerm9mJfK_jdZjF7ljvzM6gc17t6MIOvbAdksK9DbPZ_hefSKePD4w&pli=1#gid=25870091


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

# **Task 3 - Raportowanie błędów**

## Subtack 1 - Utworzenie formatki do zgłaszania błędów systemu

## Subtack 2 - Testowanie według planów testów i raportowanie błędów
https://docs.google.com/document/d/10lpYHfWj8wLjSqiuV6VEXsbFCFlA7xLvsDoapBG3fvM/edit
https://docs.google.com/document/d/16VNxmm36MtV00ReSRfcxwDUrF5s4BF3ZJTZOE_02JG8/edit

## Subtack 3 - Raport z wykonanych testów
https://docs.google.com/document/d/1WZ-WwZ6n2dnYP1NNNGU1uUfqRL9SLxI3oFGGBWs1PPw/edit
