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

## Tworzenie tablicy

Stwórzcie funkcję `createArray(rows)`,  która tworzy i zwraca tablicę. Jej rozmiar ma być zgodny z parametrem `rows`, a każdy kolejny element zawiera kolejne liczby całkowite począwszy od `1`.

Spróbujcie wywołać tę funkcję z argumentem `5`.


## Wyświetlanie tablicy

Stwórzcie funkcję `printArray(array)`, która wyświetla kolejne wartości z przekazanej tablicy.
 
Wywołajcie funkcję dla takiej tablicy i sprawdźcie wynik w konsoli:

```js
const people = ["John", "Ive", "Donna", "Chris"];
```

## Wyświetlanie tablicy 2D

Stwórzcie funkcję printArray2D(array2D), która wyświetla kolejne wartości z przekazanej tablicy dwu wymiarowej.

Przetestujcie jej działanie na tej tablicy: 

```js
const users = [
  ["Jan", "Nowak"],
  ["Zosia","Kowalska"]
];
```

## Wartość maksymalna

Stwórz funkcję `maxFromArray(numbers)` która przyjmuje tablicę liczb. Funkcja ma **zwracać** największą wartość ze zbioru (zmienna `randomNumbers`);

Wynik działania przypiszcie do zmiennej i wyświetlcie w konsoli.


## Powtarzająca się wartość

Stwórz funkcję `indexOfRepeatedValue(array)`. Prześlij do niej tablicę z 10 dowolnymi liczbami (niech kilka będzie takich samych). Stwórz w niej zmienną ```firstIndex```. W pętli ```for``` sprawdź, która z liczb powtarza się jako pierwsza i przypisz jej indeks do zmiennej ```firstIndex```. Następnie wypisz w konsoli tą zmienną, poza pętlą ```for```.

Przykładowa tablica:

```js
const numbers = [2, 4, 5, 2, 3, 5, 1, 2, 4];
```

W tej tablicy jako pierwsza powtarza się liczba 2, więc zmienna ```firstIndex``` powinna mieć wartość 0, ponieważ jest to pierwsza liczba w tablicy, która ma gdzieś swojego sobowtóra.
Przetestuj Twój skrypt z różnymi wartościami w tablicy.

Zwróć wartość `firstIndex` z funkcji.

*Podpowiedź: pamiętaj o odpowiednim przerwaniu pętli.*


---

Repozytorium z ćwiczeniami zostanie usunięte 2 tygodnie po zakończeniu kursu. Spowoduje to też usunięcie wszystkich forków, które są zrobione z tego repozytorium.
