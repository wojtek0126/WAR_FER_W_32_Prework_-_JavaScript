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

## Napisy

Stwórzcie dwie zmienne zawierające teksty: “Hello” i "JS".

W nowej zmiennej połączcie te dwa teksty, ale mają one być oddzielone spacją.

Stworzony napis wypiszcie w konsoli.

## Zmienne

Stwórz 6 zmiennych. Wstaw do nich następujące dane:

* liczbę
* string
* liczbę + string np. (2 + "dwa")
* wartość logiczną
* wartość specjalną

Dodaj do każdej zmiennej komentarz z informacją jaki typ danych przechowuje ta zmienna (do sprawdzenia typu wykorzystaj operator ```typeof```) oraz wypisz w konsoli wartości tych zmiennych.


Przykład:
```js
const numberOfUsers = 23;
console.log(numberOfUsers);
console.log(typeof numberOfUsers);
//Ta zmienna jest typu number i przechowuje wartość 23
```




## Tablice z imionami

### Zadanie 1

Zdefiniujcie tablicę w zmiennej `names1` zawierającą kolejne imiona: `Jan, Maria, Kasia, Wojtek, Zosia`

Na koniec wypiszcie w terminalu w kolejnych liniach:

- drugi element
- piąty element
- długość tablicy


### Zadanie 2

Zdefiniujcie pustą tablicę w zmiennej `names2`, a następnie **pojedynczo** dodajcie do niej następujące imiona:

```
Jan, Maria, Kasia, Wojtek, Zosia, Grzesiek
```

Na koniec wypiszcie w terminalu:

- pierwszy element
- trzeci element
- długość tablicy

## Tablica 2D

### Zadanie 1

Utwórzcie tablicę dwuwymiarową - 3 wiersze na 4 kolumny (w zmiennej `arrayOfNumbers`).

W kolejnych kolumnach mają wystąpić kolejne liczby całkowite, czyli powinno to wyglądać następująco:
```
1,2,3,4
5,6,7,8
9,10,11,12
```

Wyświetlcie:
- drugi element z pierwszego wiersza
- drugi wiersz (drugi element z pierwszego wymiaru)
- długość trzeciego elementu z pierwszego wymiaru


### Zadanie 2

Utwórzcie tablicę dwuwymiarową (w zmiennej `mixedArray`) odpowiednio składającą się z:

- tablicy z imionami: `Maria`, `Jan`, `Piotr`
- tablicy z wartościami liczbowymi: `1, 2, 3, 4, 5, 6`

Wyświetlcie:

- trzeci element z pierwszego wiersza
- piąty element z pierwszego wiersza
- długość drugiego elementu z pierwszego wymiaru

## Obiekty

### Samochód

W zmiennej `car` utwórzcie obiekt opisujący samochód.

Ma on mieć następujące atrybuty:

- **type** o wartości "sedan"
- **color** o wartości "green"
- **engine** o wartości 2.0

Wypiszcie informacje o obiekcie poprzez konkatenację (z wykorzystaniem spacji) z wartości w jego  atrybutach **type**, **color**, **engine**


### Kolor

W zmiennej `color` utwórzcie obiekt opisujący kolor.

Ma on mieć następujące atrybuty:
- **red** o wartości 100
- **green** o wartości 0
- **blue** o wartości 50

Poprzez zmienną **referenceColor** zmodyfikujcie wcześniej utworzony obiekt,
ustawicie mu:

- **red** na wartość 50
- **green** na wartość 50


---

Repozytorium z ćwiczeniami zostanie usunięte 2 tygodnie po zakończeniu kursu. Spowoduje to też usunięcie wszystkich forków, które są zrobione z tego repozytorium.
