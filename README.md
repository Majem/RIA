# JavaScript: Funkcje

### Cwiczenie 1 `Zestaw1/cw1.html`
1. Zaimplementuj funkcję zwracającą kwadrat liczby podanej jako parametr.

2. Utwórz tablicę zawierającą kilka liczb i oblicz kwadraty wszystkich liczb z tablicy
wszystkimi poniższymi sposobami:
a. Pętla for
b. Pętla for … of
c. Pętla for … in
d. Metoda forEach

3. Zmodyfikuj wariant z metodą forEach zastępując zwykłą funkcję funkcją strzałkową

### Cwiczenie 2 `Zestaw1/cw2.html`
1. Zaimplementuj funkcję zwracającą na zmianę wartości logiczne true i false. Zadbaj o to
aby nie było możliwe ustawienie „ręcznie” wartości zmiennej przechowującej informację
o tym jaka wartość ma być przy kolejnym wywołaniu zwrócona.
Wskazówka: Użyj closure.

### Cwiczenie 3 `Zestaw1/cw3.html`
1. Zaimplementuj funkcję zwracającą sumę liczb podanych jako parametry. Funkcja
powinna akceptować dowolną liczbę parametrów.

2. Zmodyfikuj funkcję tak aby przy sumowaniu pomijała parametry niebędące liczbami i
niedające się skonwertować do liczb. W przypadku gdy żaden z parametrów nie będzie
liczbą lub funkcja będzie wywołana bez parametrów, jej wynikiem powinien być NaN.

#JavaScript: Obiekty
### Cwiczenie 1 `Zestaw2/cw1.html`

1. Nie korzystając na razie z konstruktora i prototypu, utwórz obiekt reprezentujący
samochód, zawierający atrybuty marka, cena i moc oraz metodę zwiekszMoc (z jednym
parametrem do przekazania wartości, o którą ma wyć zwiększona wartość atrybutu
moc).

2. Wypisz utworzony obiekt na konsoli.
3. Zwiększ moc samochodu.
4. Ponownie wypisz utworzony obiekt na konsoli.
5. Utwórz konstruktor Samochod do tworzenia obiektów takich jak utworzony wcześniej
ręcznie. Wykorzystaj prototyp do udostępnienia implementacji metody zwiekszMoc
obiektom tworzonym utworzonym konstruktorem.
6. Utwórz tablicę 3 samochodów.
7. Wypisz w pętli zawartość tablicy samochodów na konsoli.
8. Zwiększ moc jednemu z samochodów z tablicy.
9. Ponownie wypisz w pętli zawartość tablicy samochodów na konsoli.
10. Sprawdź czy na rzecz obiektu samochodu można wywołać metody toString() i valueOf().
Zastanów się dlaczego. Porównaj ich działanie wypisując wyniki ich zastosowania do
samochodu na konsoli.
11. Nadpisz w prototypie samochodów metodę toString() tak aby działała jak valueOf().
12. Sprawdź działanie metody toString() na jednym z samochodów.

### Cwiczenie 2 `Zestaw2/cw2.html`

1. Wygeneruj reprezentację JSON dla jednego z obiektów z poprzedniego ćwiczenia.
Wyświetl wygenerowaną zawartość JSON na konsoli. Co stało się z metodami obiektu?

2. Przygotuj obiekt JSON reprezentujący strukturę obiektu samochodu. Skonwertuj dane
JSON do obiektu JavaScript. Sprawdź działanie metod toString() i valueOf() dla tak
utworzonego obiektu. Czy metoda zwiekszMoc również dla niego zadziała

# JavaScript: Klasy

### Cwiczenie 1 `Zestaw3/cw1.html`

1. Zdefiniuj klasę Osoba do reprezentacji osób posiadających imię i wiek. Zdefiniuj w klasie
odpowiedni konstruktor 2-argumentowy oraz metodę przedstaw() zwracającą tekstową
reprezentację zawartości obiektu np. w formacie „Jestem Marek, mam 25 lat”.

2. Utwórz obiekt klasy Osoba i wypisz jego zawartość na konsoli korzystając z metody
przedstaw().

3. Zmień utworzonej osobie imię i wiek.

4. Ponownie wypisz utworzony obiekt na konsoli.

# Biblioteka jQuery

### Cwiczenie 1 `Zestaw4/cw1.html`

1. Utwórz stronę HTML zawierającą nienumerowaną listę punktów <LI>, np.
 Polska
 Niemcy
 Czechy
2. Dodaj kod JavaScript+jQuery, który po załadowaniu dokumentu ponumeruje pozycje listy
dopisując na początku kolejny numer pozycji pogrubioną czcionką, np.
 1 Polska
 2 Niemcy
 3 Czechy
Wskazówka: Wykorzystaj metody .each i .prepend

### Cwiczenie 2 `Zestaw4/cw2.html`

1. Utwórz stronę HTML zawierającą formularz z jednym polem tekstowym.

2. Dodaj kod JavaScript+jQuery, który po zmianie zawartości pola tekstowego (i jego
opuszczeniu) będzie dopisywał na końcu dokumentu element `<p>` z tekstem „Zmieniono
tekst na: <tu_aktualny_tekst_z_pola>.
Wskazówka: Wykorzystaj metodę .change do podpięcia własnej funkcji reagującej na zmianę
zawartości pola.