![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/152855/73064373-5ed69780-3ea1-11ea-8a71-3d370a5e7dd8.png)

# Kilka ważnych informacji

Przed przystąpieniem do rozwiązywania zadań przeczytaj poniższe wskazówki

## Jak zacząć?

1. Stwórz [*fork*](https://guides.github.com/activities/forking/) repozytorium z zadaniami.
2. Sklonuj repozytorium na swój komputer. Użyj do tego komendy `git clone adres_repozytorium`
Adres repozytorium możesz znaleźć na stronie repozytorium po naciśnięciu w guzik "Clone or download".
3. Rozwiąż zadania i skomituj zmiany do swojego repozytorium. Użyj do tego komend `git add nazwa_pliku`.
Jeżeli chcesz dodać wszystkie zmienione pliki użyj `git add .` 
Pamiętaj że kropka na końcu jest ważna!
Następnie skommituj zmiany komendą `git commit -m "nazwa_commita"`
4. Wypchnij zmiany do swojego repozytorium na GitHubie.  Użyj do tego komendy `git push origin master`
5. Stwórz [*pull request*](https://help.github.com/articles/creating-a-pull-request) do oryginalnego repozytorium, gdy skończysz wszystkie zadania.

Poszczególne zadania rozwiązuj w odpowiednich plikach.

# Poniżej znajdziesz wytyczne do zadań

## Tworzenie tablicy - for
### Wykorzystajcie do tego zadania pętlę for

Napiszcie program, który na podstawie wartości zmiennej `n` utworzy tablicę jednowymiarową w zmiennej `array` zawierającą kolejne liczby całkowite od `1` do `n`


#### Podpowiedź
Do wstawiania wartości do tablicy skorzystajcie z metody `push` np.: `array.push(2);`.


## Liczby parzyste i nieparzyste - for
### Wykorzystajcie do tego zadania pętlę for

Napiszcie program, który na podstawie wartości zmiennej n wypisuje wszystkie liczby od `zera` do `n` (włącznie).
 
Przy każdej liczbie program ma napisać, czy liczba jest parzysta czy nie. Np.:
```
0 – parzysta
1 – nieparzysta
2 – parzysta
3 – nieparzysta
...
```
   
   
### Podpowiedź

Jak sprawdzić czy liczba jest parzysta lub nieparzysta?  
Wystarczy podzielić ją modulo przez 2, jeżeli wynik to 0, wtedy liczba jest parzysta, w przeciwnym przypadku jest nieparzysta. Skorzystajcie z instrukcji "jeżeli".


## Tworzenie tablicy - while
### Wykorzystajcie do tego zadania pętlę while

Napiszcie program, który na podstawie wartości zmiennej `n`.
Utwórzcie tablicę jednowymiarową w zmiennej `array` zawierającą kolejne liczby całkowite od 1 do `n`.


## Liczby parzyste i nieparzyste - while
### Wykorzystajcie do tego zadania pętlę while

Napiszcie program, który na podstawie wartości zmiennej n wypisuje wszystkie liczby od `zera` do `n` (włącznie).
 
Przy każdej liczbie program ma napisać, czy liczba jest parzysta czy nie. Np.:
```
0 – parzysta
1 – nieparzysta
2 – parzysta
3 – nieparzysta
...
```
   
   
### Podpowiedź

Jak sprawdzić czy liczba jest parzysta lub nieparzysta?  
Wystarczy podzielić ją modulo przez 2, jeżeli wynik to 0, wtedy liczba jest parzysta, w przeciwnym przypadku jest nieparzysta. Skorzystajcie z instrukcji "jeżeli".


## Wyświetlanie napisów - while
### Wykorzystajcie do tego zadania pętlę while

Napiszcie program, który na podstawie wartości zmiennej `n` wyświetli n-razy napis "Kocham JS-a"
    
Zwróćcie uwagę ile razy wyświetli się napis przy `n = 0`.


## Wyświetlanie danych z tablicy

Napiszcie program, który wypisze w kolejnych liniach wartości z przygotowanej tablicy dwuwymiarowej.

## Tworzenie tablicy 2D

Napiszcie program, który w zmiennej `array` utworzy tablicę wielowymiarową zgodnie z wartościami w zmiennych `rows` i `cols`.

Elementami tablicy mają być **kolejne liczby całkowite zaczynając od jedynki**.


## Tabliczka mnożenia

Napiszcie program tworzący tabliczkę mnożenia dla podanej zmiennej `n`.
 
Wyniki zwróćcie w tablicy dwu wymiarowej (w zmiennej `calc`).
Wartości w tej tablicy mają być tekstami obliczeń.
 
Na przykład dla n = 3 wynik będzie następujący:
```
1 x 1 = 1 | 1 x 2 = 2 | 1 x 3 = 3
2 x 1 = 2 | 2 x 2 = 4 | 2 x 3 = 6
3 x 1 = 3 | 3 x 2 = 6 | 3 x 3 = 9
```
 
W tablicy przechowywane są tylko teksty obliczeń np:
```
1 x 1 = 1
```
 
Tablicę należy wyświetlić w **konsoli**. Wtedy należy dodać kreski pionowe.
 
 

## Gwiazdki

Napiszcie program rysujący na podstawie wartości zmiennej `n` następujący schemat (tutaj dla `n = 5`).

Użyjcie do tego pętli zagnieżdżonych (zależnych).

```
*
**
***
****
*****
```


## Break

Napiszcie program, w którym wykorzystacie instrukcję `break` aby przerwać działanie pętli gdy `i` będzie miało wartość `5`.


---

Repozytorium z ćwiczeniami zostanie usunięte 2 tygodnie po zakończeniu kursu. Spowoduje to też usunięcie wszystkich forków, które są zrobione z tego repozytorium.
