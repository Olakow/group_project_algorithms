# Opis zadania:

KP (Karetki Pogotowia) realizują kursy do pacjentów (P) potrzebujących pomocy. Pacjenci mogą znajdować się w dowolnym miejscu na terenie kraju, a znalezionego pacjenta (P) należy przetransportować do najbliższego ośrodka medycznego (OM).
Znane są odległości pomiędzy poszczególnymi OM. Choć w niektórych miejscach kraju może nie występować bezpośrednia droga łącząca ze sobą OM.
Znany jest również fakt, że OM mają ograniczoną liczbę łóżek (LŁ) dla pacjentów.

Opis zadania

Pomóż zespołom ratowników z Karetek Pogotowia (KP) przewozić pacjentów (P) do Ośrodków Medycznych (OM). Do tego celu możesz wykorzystać informacje, które otrzymujesz od Dyspozytora Pogotowia (DP).

 Szpitale (id | nazwa | wsp. x | wsp. y | Liczba łóżek | Liczba wolnych łóżek)
1 | Szpital Wojewódzki nr 997 | 10 | 10 | 1000 | 100
2 | Krakowski Szpital Kliniczny | 100 | 120 | 999 | 99
3 | Pierwszy Szpital im. Prezesa RP | 120 | 130 | 99 | 0
4 | Drugi Szpital im. Naczelnika RP | 10 | 140 | 70 | 1
5 | Trzeci Szpital im. Króla RP | 140 | 10 | 996 | 0

 Obiekty (id | nazwa | wsp. x | wsp. y)
1 | Pomnik Wikipedii | -1 | 50
2 | Pomnik Fryderyka Chopina | 110 | 55
3 | Pomnik Anonimowego Przechodnia | 40 | 70

 Drogi (id | id_szpitala | id_szpitala | odległość)
1 | 1 | 2 | 700
2 | 1 | 4 | 550
3 | 1 | 5 | 800
4 | 2 | 3 | 300
5 | 2 | 4 | 550
6 | 3 | 5 | 600
7 | 4 | 5 | 750
Do programu może zostać przekazana lista zawierająca wspołrzędne pacjentów. Należy umożliwić przeprowadzenie symulacji "obsługi" pacjentów (z poziomu graficznego interfejsu użytkownika).

 Pacjenci (id | wsp. x | wsp.y)
1 | 20 | 20
2 | 99 | 105
3 | 23 | 40

Ważne:

Jeżeli drogi przecinają się, to można przyjąć, że w miejscu przecięcia jest skrzyżowanie;
współrzędne pacjenta (punkt początkowy) może być dowolnym miejscem w obszarze ograniczonym przez współrzędne pozostałych punktów na mapie;
obszar / mapa jest ograniczony przez najbardziej oddalone punkty (jest to najmniejszy zbiór wypukły zawierający w sobie wszystkie punkty);
nie opiekujemy się pacjentami poza granicami kraju.




## Wykorzystane algorytmy:

Alogrytm wyznaczenia, po kt rej stronie wektora znajduje
sie punkt

Algorytm przeciecia linii (line-line intersection)

Algorytm konstrukcji grafu

Algorytm Dijkstry

Algorytm Grahama
