
# **Task 1**
## Subtack 1
9
## Subtask 3
Hej jestem Sonia, z wykształcenia inżynier budownictwa szukający swojej życiowej ścieżki. Aktualnie kończę urlop macierzyński i od dłuższego czasu móżdżę, jak to zrobić by nie wracać do znienawidzonej pracy w urzędzie :D Po przegrzaniu wielu zwojów mózgowych doszłam do wniosku, że chcę zmienić brażę i spróbować IT. Gdy poznałazm cechy idealnego testera - stwierdziłam "to jest to!". I tak się tu znalazłam. A co jest moim celem? Podjęcie nowego wyzwania, sprawdzenie siebie, dobra zabawa i tworzenie nowych ścieżek neuronowych w kopułce :) 

## Subtask 4
\1.Aplikacja dla skautów piłki nożnej to taka baza danych, dotycząca poszczególnych piłkarzy i informacji na ich temat. 
Aplikacja pozwala na dodawanie kolejnych graczy poprzez wypełnienie formularza. Następnie pozwala na dodawanie do konkretnego gracza meczów oraz raportów. Można następnie przeglądać listę graczy, wyfiltrować interesującą nas część danych, posortować, wydrukować itd. 
\2.Interfejs aplikacji jest bardzo prosty, białe tło, kilka przycisków. Generalnie nie bardzo mi się podoba.
\3.Schemat działani aplikacji jest bardzo prosty, a mimo to mało intuicyjny. Trzeba się trochę naklikać i napróbować, żeby obczaić jak to działa. Podstawowa funkcja czyli dodawnie gracza jest umieszczone w rubryce "linki pomocnicze", mogłoby to być w panelu po lewej stronie w formie przycisku z kolorowym tłem, tak by każdy użytkownik od razu ten przycisk zauważył. W tym momencie ten przycisk wygląda jak podejrzany link, w który lepiej nie klikać bo coś wybuchnie :) Niektóre pola formularza są tak nazwane, że nie wiadomo o co chodzi np. "Łączy nas piła", albo "90 minut". Kolejne funkcjonalności, czyli dodawanie meczy i raportów również jest mało intuicyjne. Przyciski działają wolno. Poza tym aplikacja mogłaby nas wylogować, po jakimś czasie braku ruchu. 

\4.Uważam, że błędów tu jest całe mnóstwo. Spróbuję wymienić to co najbardziej rzuciło mi się w oczy:
* w formularzu dodawania gracza gwiazdka powinna być opisana na dole, że jest to pole wymagane,
* wagę i wzrost gracza możemy wybrać lub wklepać jako liczby ujemne,
* w polach gdzie powinno być ograniczenie tylko do tekstu, można wklejać dowolne znaki np. emotikony, czy znaki specjalne,
* jeśli coś źle wpiszemy w formularzu i zatwierdzimy to pojawia się hasło "Nie można dodać gracza", ale generalnie nie wiadomo dlaczego. Powinna być określona przyczyna, lub wskazane pole z błędem.
* data urodzenia czy data meczu nie ma żadnych ograniczeń, przykłądowo możemy dodać mecz z przyszłości, albo zawodnika w wieku kilkuset lat,
* w polu gdzie spodziewamy się podać link do youtuba czy adres e-mail można wpisać cokolwiek innego,
* w kolejnej funkcjonalności czyli dodawaniu meczów, mamy możliwość dodania ujemnego czasu gry w meczu, oczywiście mecz z przyszłosci, 
* następna funkcjonalność czyli "rozpocznij mecz" gdzie pojawia się widok boiska piłarskiego - przyciski na górze powinny mieć jakieś opisy; przycisk z dodaniem drugiej połowy meczu działa nieskończoną liczbę razy; przycisk kosza w ogóle nie działa, 
* edycja meczu - nie działa przycisk "clear", z koleji po zatwierdzeniu danych przyciskiem "submit" nie wychodzi nam intuicyjnie z formularza, tylko nadal w nim pozostajemy, co daje dziwne wrażenie,
* tworzenie raportów - jako recenzję możemy wybrać liczbę gwiazdek np. pół, a legenda dotyczy tylko całowitych wartości 1-5, nie opisuje również zera, które można wybrać, 
* nie widzę możliwości usunięcia gracza,
* lista wszystkich graczy mogłaby mieć przycisk odsyłający do ostatniej strony listy graczy,
* zmiana języka nie wiąże się z całkowitym przejściem na dany język, przykładowo w polskim nadal niektóre przyciski są po angielsku.
