 # Obiekty &ndash; zadania

> Odpowiedzi wpisz w pliku **app.js**, chyba że treść polecenia wskazuje inaczej.
Pamiętaj, żeby oddzielać ćwiczenia komentarzami i pisać czytelny, dobrze sformatowany kod.

### Zadanie 1

Stwórz obiekt city. Dopisz do niego następujące właściwości:

* capital - string
* population - number
* president - string
* ministers - tablica stringów

Wypisz w konsoli wszystkie właściwości.

### Zadanie 2

Stwórz obiekt person. Dopisz do niego następujące właściwości i metodę:

* name,
* age,
* sayHello() - wypisującą "hello"

Wypisz w konsoli wszystkie właściwości oraz wywołaj metodę.

### Zadanie 3

Stwórz obiekt timeMachine. Dopisz do niego następujące właściwości:

* shape - string, 
* model - string,
* run(date, place) - metoda, dzięki której można się przenieść w czasie. Argument ```date``` to data, do jakiej chcemy się przenieść, a ```place``` to miejsce, do którego chcemy się przenieść. Oba argumenty to stringi. Metoda powinna wypisywać w konsoli do jakiego miejsca i czasu się przenieśliśmy.

Wypisz w konsoli wszystkie właściwości i uruchom metodę run.


### Zadanie 4

Stwórz obiekt, który będzie przetrzymywał Twój ulubiony przepis. Obiekt powinien mieć własność ```title``` (string), ```servings``` (number) oraz ```ingredients``` (tablica stringów). Pole ```ingredients``` dodaj poza ciałem obiektu. Wypisz w konsoli te wszystkie informacje.

### Zadanie 5

W pliku ```zadanie05.js``` znajdziesz obiekt ```movie```. Użyj pętli ```for ... in```, żeby wypisać w konsoli informacje o filmie.


### Zadanie 6

W pliku ```zadanie06.js``` znajdziesz tablicę obiektów ```animals```. Użyj pętli ```for``` oraz pętli ```for ... in```, żeby wypisać wszystkie informacje.

### Zadanie 7 

Do pliku ```app.js``` przekopiuj poniższy kod:

```JavaScript
var spoon = {
    isExist: true
}

var fork = spoon;
fork.isExist  = false;

```
Następnie sprawdź czy łyżka istnieje. 