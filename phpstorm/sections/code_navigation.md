# Nawigacja w kodzie

Nie będę ukrywać, że PhpStorm dostarcza wielu przydatnych narzędzi i funkcjonalności znacząco ułatwiających pracę z kodem, oraz odpowiednie przemieszczanie się pomiędzy klasami, metodami i wieloma innymi. W tej sekcji nie będę rozpisywał się na ich temat, a po prostu przedstawię listę tych, z których korzystam najczęściej, i które moim zdaniem wydają się być najbardziej przydatne.

## Podstawowe operacje

<kbd>ctrl</kbd> + <kbd>d</kbd> - zduplikowanie aktualnej linii kodu
<kbd>ctrl</kbd> + <kbd>c</kbd> - skopiowanie aktualnej linii kodu (jeśli test nie jest zaznaczony)
<kbd>ctrl</kbd> + <kbd>x</kbd> - wycięcie aktualnej linii kodu (jeśli test nie jest zaznaczony)
<kbd>ctrl</kbd> + <kbd>y</kbd> - usunięcie aktualnej linii kodu
<kbd>ctrl</kbd> + <kbd>Del</kbd> - usunięcie całego następnego słowa
<kbd>ctrl</kbd> + <kbd>Backspace</kbd> - usunięcie całego poprzedniego słowa
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>v</kbd> - operacja wklejenia z historii schowka
<kbd>ctrl</kbd> + <kbd>space</kbd> - podpowiadanie składni
wpisanie dowolnego znaku w kodzie + <kbd>Tab</kbd> - uzupełnienie składni
<kbd>alt</kbd> + <kbd>Enter</kbd> - pokazanie akcji "Intencji" (np. przy błędzie w kodzie)

## Zaznaczanie kodu

<kbd>ctrl</kbd> + <kbd>w</kbd> - zaznaczanie coraz większej porcji kodu (wielokrotne użycie)
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>←</kbd>/<kbd>→</kbd> - zaznaczanie słów w lewo/prawo
<kbd>shift</kbd> + <kbd>←</kbd>/<kbd>→</kbd> - zaznaczanie znaków w lewo/prawo

## Operacje na zaznaczonym kodzie

<kbd>ctrl</kbd> + <kbd>f</kbd> - wyszukiwanie w pliku po zaznaczonej frazie
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>f</kbd> - wyszukiwanie w całym projekcie po zaznaczonej frazie
<kbd>ctrl</kbd> + <kbd>/</kbd> - skorzystanie z wcześniej użytej części kodu (wielokrotne użycie)
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>t</kbd> - funkcjonalność "Surround with"
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>m</kbd> - wydobycie metody z zaznaczonego kodu
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>v</kbd> - wydobycie zmiennej z zaznaczonego kodu
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>↑</kbd>/<kbd>↓</kbd> - relokacja zaznaczonego bloku kodu
<kbd>ctrl</kbd> + <kbd>r</kbd> - operacja zamiany zaznaczonej frazy w ograniczeniu do pliku
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>r</kbd> - operacja zamiany zaznaczonej frazy w danym miejscu projektu
<kbd>alt</kbd> + <kbd>shift</kbd> + <kbd>↑</kbd>/<kbd>↓</kbd> - relokacja aktualnej linii kodu
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>L</kbd> - autoformatowanie zaznaczonego miejsca

## Umiejscowienie kursora

<kbd>alt</kbd> + <kbd>↑</kbd> - przejście do metody wyżej (wewnątrz klasy)
<kbd>alt</kbd> + <kbd>↓</kbd> - przejście do metody wyżej (wewnątrz klasy)
<kbd>ctrl</kbd> + <kbd>g</kbd> - przejście do wskazanej linii kodu
<kbd>ctrl</kbd> + <kbd>Home</kbd> - przejście na początek pliku
<kbd>ctrl</kbd> + <kbd>End</kbd> - przejście na koniec pliku
<kbd>ctrl</kbd> + <kbd>{</kbd> - przejście do początku bloku kodu
<kbd>ctrl</kbd> + <kbd>}</kbd> - przejście na koniec bloku kodu
<kbd>ctrl</kbd> + <kbd>←</kbd>/<kbd>→</kbd> - nawigacja pomiędzy słowami
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>←</kbd> - nawigacja do poprzedniego miejsca kursora
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>→</kbd> - nawigacja do następnego miejsca kursora
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>Backspace</kbd> - nawigacja do ostatniego miejsca edycji
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>m</kbd> - relokacja kursora pomiędzy końcem a początkiem bloku kodu

Ponad powyższymi opcjami, istnieje możliwość zaznaczania odpowiednich partii kodu, a następnie nawigowania pomiędzy nimi:

<kbd>F11</kbd> - oznaczanie aktualnej linii kodu
<kbd>ctrl</kbd> + <kbd>F11</kbd> - oznaczanie aktualnej linii kodu numerem lub literą
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>1</kbd> ... <kbd>9</kbd> - oznaczenie aktualnej linii kodu numerem
<kbd>ctrl</kbd> + <kbd>1</kbd> ... <kbd>9</kbd> - nawigacja do konkretnego oznaczenia
<kbd>shift</kbd> + <kbd>F11</kbd> - lista wszystkich oznaczeń

## Użycia w kodzie

<kbd>ctrl</kbd> + <kbd>b</kbd> - przejście do deklaracji
<kbd>shift</kbd> + <kbd>ctrl</kbd> + <kbd>b</kbd> - przejście do deklaracji typu
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>b</kbd> - przejście do implementacji
<kbd>alt</kbd> + <kbd>F7</kbd> - wyszukiwanie użyć klasy/metody/zmiennej
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>F7</kbd> - szybkie  zaznaczanie miejsc użyć klasy/metody/zmiennej

## Debugging

Jeśli w danym pliku, w którym tworzymy lub modyfikujemy kod, wystąpią jakieś błędy wykryte przez IDE (począwszy od krytycznych, po literówki), bardzo łatwo możemy między nimi nawigować przy pomocy klawisza <kbd>F2</kbd>.

<kbd>F2</kbd> - nawigowanie pomiędzy błędami w aktywnym pliku

Jednocześnie zawsze można wyświetlić więcej szczegółów:

<kbd>ctrl</kbd> + <kbd>F1</kbd> - wyświetlenie szczegółów na temat błędu znajdującego się w miejscu kursora
<kbd>ctrl</kbd> + <kbd>q</kbd> - wyświetlenie dokumentacji w pop-up danego elementu
<kbd>ctrl</kbd> + <kbd>q</kbd> + <kbd>q</kbd> - wyświetlenie dokumentacji w zakładce

## Struktura

Niezwykle pomocnym narzędziem w PhpStorm IDE jest okienko ukazujące strukturę danej klasy, bądź pliku, jeśli ten nie zawiera w sobie klasy. Po jego włączeniu ukaże się cała jej budowa, czyli lista metod oraz zmiennych instancyjnych. Całość dostępna pod następującą kombinacją:

(<kbd>ctrl</kbd> + <kbd>F12</kbd>) lub (<kbd>alt</kbd> + <kbd>7</kbd>)

Wewnątrz możemy nawigować do odpowiedniego elementu, a następnie kliknąć <kbd>Enter</kbd>, aby do niego przejść.

Poza powyższym, IDE udostępnia również możliwość podejrzenia całej hierarchii klasy:

(<kbd>alt</kbd> + <kbd>8</kbd>) lub (<kbd>ctrl</kbd> + <kbd>h</kbd>)

Poza samą możliwością przeglądania struktury plików i klas, istnieje narzędzie do generowania odpowiednich części ich kodu. Jest to okno _"Generate"_. Przy jego użyciu można wygenerować:
- settery;
- gettery;
- konstruktor;
- adnotacje Doctrine;
- implementację metody z interfejsu lub klasy nadrzędnej;
- wiele innych.

Opcja dostępna pod następującym skrótem:

<kbd>alt</kbd> + <kbd>Insert</kbd> - otwarcie okna _"Generate"_

Powyższa opcja jest przydatna nie tylko wewnątrz kodu, ale również i w strukturze plików projektu (<kbd>alt</kbd> + <kbd>1</kbd>). Będąc w tym miejscu, i korzystając w wcześniej wspomnianej kombinacji klawiszy, otrzymuje się możliwość utworzenia katalogu lub pliku o wskazanym formacie.

![enter image description here](https://lh3.googleusercontent.com/Z2DLo6e9uXmQpqRZmiC8YWshBrfR2z6uzxYV4xfOiy6NkJX4eY0zy7cHvyqPQqUxRLgJw6Zfkw67=s1024)

Każda pozycja jest tak naprawdę szablonem konkretnego formatu pliku dostarczanym przez PhpStorm IDE. Lista ta jednak może zostać rozszerzona o niestandardowe szablony utworzone przez użytkowników aplikacji.

## Testowanie (PhpUnit)

<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>t</kbd> - przejście do testu aktualnej klasy
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>F10</kbd> - wykonanie testu aktualnej klasy
<kbd>ctrl</kbd> + <kbd>F5</kbd> - (_będąc w okienku wykonanych testów_) ponowne wykonanie testu

## Przydatne operacje

Poniżej lista innych przydatnych funkcjonalności i operacji, jakie łatwo można wykonać w PhpStorm IDE przy pomocy odpowiednich skrótów klawiaturowych:

<kbd>F5</kbd> - skopiowanie pliku do innego miejsca
<kbd>F6</kbd> - przeniesienie pliku/klasy/metody do innego miejsca
<kbd>shift</kbd> + <kbd>F6</kbd> - zmiana nazwy dowolnego bytu
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>L</kbd> - autoformatowanie kodu całego pliku lub zaznaczonego miejsca