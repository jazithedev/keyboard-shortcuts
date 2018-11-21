
# Skróty klawiaturowe w PhpStorm

**PhpStorm** jest obecnie jednym z najbardziej popularnych IDE do modyfikacji kodu napisanego w języku PHP. Znacząco usprawnia pracę pojedynczym programistom oraz ekipom składającym się z większej ilości osób dostarczając wielu niesamowitych funkcjonalności i usprawnień. Jedną z nich jest rozległa pajęczyna skrótów klawiszowych przyspieszająca proces wytwarzania oprogramowania. Niniejszy artykuł, który bardziej taktowałbym jako poradnik, chciałbym poświęcić właśnie tej tematyce.

## Podstawy

Nim przystąpię do konkretów, chciałbym najpierw przedstawić podstawowe nawigowanie w PhpStorm IDE. Podczas pracy w tej aplikacji, natknąć się można na wszelkiego rodzaju zakładki, okienka, i sekcje. Istnieją pewne ogólne skróty, które tyczą się każdego z tych elementów:

<kbd>ctrl</kbd> + <kbd>Enter</kbd> - zatwierdzenie operacji
<kbd>shift</kbd> + <kbd>ESC</kbd> - zamknięcie okna / zakładki
<kbd>Menu</kbd> - zestaw przydatnych opcji dla miejsca aktualnej pozycji kursora

Tak jak dwie pierwsze nie wymagają szerszego opisu, tak trzecia już może być nie w pełni jasna. Pod przyciskiem "[Menu](https://en.wikipedia.org/wiki/Menu_key)" programista otrzyma menu kontekstowe z zestawem przydatnych opcji, które może wykonać w zakresie aktualnego kontekstu kursora. Może to być dowolny plik w liście plików, bądź zmienna wewnątrz klasy PHP.

![enter image description here](https://lh3.googleusercontent.com/5i8lbK_q8nN92JtdAQzRjpmqR0fJoSKeWCljUzHcsNXAk9XOE2F7bbhAl25SoYeREQtZuTxopERn=s1024)

Opcja ta to tak naprawdę jak kliknięcie prawym przyciskiem myszy, lecz bez potrzeby przesuwania ręki :). Na dodatek, można kontynuować wybieranie odpowiedniej operacji przez dalsze wciskanie odpowiednich kombinacji klawiszy, co jest ważną rzeczą do zapamiętania podczas korzystania PhpStorm IDE. Funkcjonalność podpowiadana jest poprzez podkreślone literki w pozycjach. Przykładowo, aby wybrać operację zmianę nazwy dla ukazanej metody, należy wyklikać <kbd>Menu</kbd> + <kbd>r</kbd> + <kbd>r</kbd>.

![enter image description here](https://lh3.googleusercontent.com/FSC-1IYFOxBTSVJmalf0_WnABfhrC-tTS-sgDoTKt-U4YElqnegEMtaIM5bEdJ0OWbiAiM6wm58g=s1024)

W związku z powyższym, z poziomu klawiatury można dostać się do prawie dowolnego miejsca IDE (pop-up, zakładki, inne elementy UI), co pozwoli skorzystać z prawie każdej oferowanej przez niego opcji. Taki system ma niestety swoje ograniczenia, ale moim zdaniem i tak jest bardzo dobrze zaprojektowany. Weźmy może jeszcze jeden przykład:

![podkreślenia liter PhpStorm #1](https://lh3.googleusercontent.com/4vEqwm6goejldbU-SaigRk4v0e8L6P7qtv3ylS629NZewhm4JR4o5SKXqJC4FT2Dg_oZ2CBf64SQ=s1024)

Powyższe okienko pojawia się przy generowaniu setterów i getterów zmiennych instancyjnych klasy. Należy zauważyć, że przyciski _"OK"_, _"Select None"_ oraz _"Cancel"_ nie posiadają żadnej zaznaczonej literki w przeciwieństwie do, chociażby, opcji _"Fluent setters"_. Aby to zmienić, i aby dowiedzieć się jak wejść w interakcję z elementami tego okna poprzez klawiaturę, należy przytrzymać klawisz <kbd>alt</kbd>. Wtedy wówczas ukaże się pewna zmiana:

![podkreślenia liter PhpStorm #2](https://lh3.googleusercontent.com/ka5YV7TryvyaSFzRmWjEFIDhm5m1rMAzWye3HCMlu-PCF2tmPKNvXBxwJuWjzSSTi3G0RKtttBkO=s1024)

Na przycisku _"Select None"_ pojawiło się podkreślenie nad literą _"N"_. Oznacza to, że jeśli skorzystamy z kombinacji <kbd>alt</kbd> + <kbd>n</kbd>, to właśnie ta opcja zostanie wykonana. Jeśli natomiast użyje się kombinacji <kbd>alt</kbd> + <kbd>f</kbd>, checkbox _"Fluent setter"_ zostanie zaznaczony. Tak właśnie to działa :). Jest tylko jedno pytanie. Czemu  dwa pozostałe przyciski nie mają swoich podkreślonych odpowiedników? Ponieważ są to standardowe czynności określające potwierdzenie operacji, oraz jej anulowanie. Działają więc na odpowiednie kombinacje:

<kbd>ctrl</kbd> + <kbd>Enter</kbd> - potwierdzenie operacji
<kbd>ESC</kbd> - anulowanie operacji / wyjście

## Nawigacja menu

Jak w wielu aplikacjach desktopowych, tak i w PhpStorm IDE istnieje możliwość przejścia do menu programu przy pomocy klawiatury. 

![enter image description here](https://lh3.googleusercontent.com/AX9xWg3V3ACz9ZkIaqJa_xE7mQAYJxoVfGi7Rxo_zYxu5xg4uda-U4LzfItpL-9FV8ncbWdqI_kL=s1024)

Dokonuje się tego standardowo poprzez kliknięcie klawisza <kbd>alt</kbd> wraz z odpowiednią literką. Każda z takich liter jest podkreślona w celu podpowiedzenia kombinacji. Przykładowo:

<kbd>alt</kbd> + <kbd>f</kbd> - menu _"File"_
<kbd>alt</kbd> + <kbd>e</kbd> - menu _"Edit"_
<kbd>alt</kbd> + <kbd>t</kbd> - menu _"Tools"_

Po aktywacji jednej z tych sekcji, istnieje możliwość nawigowania po całym menu przy pomocy strzałek na klawiaturze. Nadal jednak, w wielu wypadkach, takie nawigowanie może okazać się dla programisty zbyt wolne. Stąd dostępność prawie każdej opcji wgłąb pod kolejnym zestawem klawiszy. Jedne z tych, z których na bieżąco korzystam, to:

<kbd>alt</kbd> + <kbd>f</kbd> + <kbd>x</kbd> - zamknięcie PhpStorm IDE
<kbd>alt</kbd> + <kbd>f</kbd> + <kbd>j</kbd> - zamknięcie aktualnego projektu
<kbd>alt</kbd> + <kbd>f</kbd> + <kbd>r</kbd> - otwarcie jednego z ostatnio modyfikowanych projektów

Można zauważyć, że większość pozycji menu dostępna jest również pod konkretnymi skrótami klawiszowymi. Warto więc zwrócić na to uwagę w przypadku najbardziej wykorzystywanych funkcjonalności, i spróbować je zapamiętać. Przykładowo, aby otworzyć okno _"Settings"_ poprzednio wspomnianym sposobem, należałoby użyć następującej kombinacji klawiszy:

<kbd>alt</kbd> + <kbd>f</kbd> + <kbd>t</kbd> - otworzenie okna "Settings"

Natomiast, tę czynność można wykonać inaczej:

<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>s</kbd> - otworzenie okna "Settings"

## Settings
Przy okazji wspominania o oknie ustawień PhpStorm IDE, chciałbym zahaczyć o jego możliwości względem nawigacji przy pomocy klawiatury. Najważniejszym jego elementem jest możliwość natychmiastowego filtrowania wszelkich opcji wpisując konkretny ciąg znaków zaraz po otwarciu okna (<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>s</kbd>). Po wpisaniu "PhpUnit", sekcje lewej części okna zostaną przefiltrowane i dopasowane do tego wyrażenia. Dalej można nawigować poprzez strzałki lub kombinacje <kbd>Tab</kbd> / <kbd>Shift</kbd> + <kbd>Tab</kbd>.

![Znajdywanie słów kluczych w ustawieniach PhpStorm IDE](https://lh3.googleusercontent.com/PiEvMCuJoegxIAVK_1NkIummK00UAchbIx8ZXXi739MPVaErIx2BcyqgYtDh_wU2wB3kGNbXMaOd=s1024)

PhpStorm IDE daje duże możliwości w konfiguracji i dopasowania odpowiednich skrótów klawiaturowych. W zakładce _"Keymap"_ pod prawie każdą operację lub opcję można zastosować wskazaną przez użytkownika kombinację klawiszy (lub gestów myszy!). Osobiście korzystałem z niej do swoich modyfikacji dopiero po jakimś czasie korzystania z tego IDE, lecz warto jest odwiedzić to miejsce na początek chociaż raz.

Warto też wspomnieć, że istnieje tam wyszukiwarka po skrócie klawiaturowym. Jeśli nie jesteśmy pewni co do użycia jakiejś z kombinacji, wystarczy kliknąć myszką w odpowiednie miejsce, i wypróbować tą kombinację. Po dokonaniu tej czynności pokaże nam się pusta lista lub konkretna operacja. Myślę, że może to być **jeden z lepszych sposobów na nauczenie się skrótów** - po prostu ich wyklikanie.

![enter image description here](https://lh3.googleusercontent.com/18-esg1AeULvetbHRHzCnu4OkNwLvDkIBSMpursTKXTY_07elt3KWbFTdqda8kBhfsVxYWOrrXGl=s1024)

## Nawigacja UI
PhpStorm jest zbudowany z wielu elementów UI, co można od razu zauważyć. Jak już wspomniałem we wcześniejszej części artykułu, do prawie każdego z tych miejsc można się dostać poprzez odpowiedni skrót klawiaturowy. Zobaczmy zatem, czy tak jest :).

### Zakładki narzędzi
Wokół głównego okna edycji kodu znajdzie się wiele zakładek z różnego typu narzędziami.

![Zakładki narzędzi](https://lh3.googleusercontent.com/YckV78ie56zWa0GXe-kpibSK_BH3eIIkyj1VaFvHglS8EjRAJXkwi3l0EZIpWMV2VX7HpBz9glRI=s1024)

Najbardziej wykorzystywanymi przeze są: _"Project"_, _"Version Control"_, _"Database"_ oraz _"Terminal"_. Wymagam więc, bym miał do nich bardzo szybki dostęp. Dzieje się to dzięki następującym kombinacjom:

<kbd>alt</kbd> + <kbd>1</kbd> - Zakładka _"Project"_
<kbd>alt</kbd> + <kbd>2</kbd> - Zakładka _"Favorites"_
<kbd>alt</kbd> + <kbd>5</kbd> - Zakładka _"TODO"_
<kbd>alt</kbd> + <kbd>7</kbd> - Zakładka _"Structure"_
<kbd>alt</kbd> + <kbd>8</kbd> - Zakładka _"Hierarchy"_
<kbd>alt</kbd> + <kbd>9</kbd> - Zakładka _"Version Control"_
<kbd>alt</kbd> + <kbd>F12</kbd> - Zakładka _"Terminal"_

Jako że _"Database"_ domyślnie nie posiadało tego typu skrótu, postanowiłem sam sobie go utworzyć. W związku z czym, w ustawieniach mojego IDE jest on następujący:

<kbd>alt</kbd> + <kbd>0</kbd> - Zakładka _"Database"_

### Breadcrumbs

Zaraz pod menu głównym umiejscowiona jest tak zwana "Nawigacja Okruszkowa", czyli "Bradcrumbs". Jest to ścieżka katalogów aktualnie przeglądanego pliku.

![PhpStorm IDE breadcrumbs](https://lh3.googleusercontent.com/7TSJInT6SKnTt7h7FeoFwbdxme5dCcT1axzx2DOoK0UtWLLtm2acy0n1bRmLZHUnAorSfQa4HtVT=s1024)

Istnieją dwie ogromne zalety tego elementu UI. W pierwszej kolejności, co jest dość oczywiste, natychmiastowe informowanie użytkownika o strukturze katalogów. W drugiej jest to możliwość przemieszczania się po tej strukturze. Wystarczy ustawić focus odpowiednią kombinacją klawiszy na końcowym elemencie tej nawigacji, a następnie się po niej przemieszczać korzystając z strzałek klawiatury.

<kbd>alt</kbd> + <kbd>Home</kbd> - aktywacja przemieszczania się po nawigacji breadcrumbs

![breadcrumbs ustawianie focus](https://lh3.googleusercontent.com/JYf1mFQ-rkYbb1Od2SU8xsmDT3AHNsT_Jfm2RCkcG-yPjQ4ZovoPffXR4gXncNlpHWYvvqmgGqYG=s1024)

Funkcjonalność ta jest o tyle przydatna, że nie trzeba włączać zakładki "Projects", która zajmuje nieco miejsca wszerz. Dodatkowo, z tego poziomu można:
- przejść do innego pliku;
- dodać nowy plik (<kbd>alt</kbd> + <kbd>Insert</kbd>);
- zmodyfikować już istniejące pliki
- wykonać wiele innych opcji (lista operacji dostępna pod klawiszem <kbd>Menu</kbd>).

### Zakładki otwartych plików

![PhpStorm - zakładki plików](https://lh3.googleusercontent.com/1chpmXWLK3LsBBZJmdVYvlVzZNPfn_rJ55S9Vw64ShmDSdYOsZb60KwTxRJIkvFojjlotwNJ05mh=s1024)

Mając otwartych wiele plików w jednym projekcie, wypadałoby mieć możliwość szybkiego zamykania oraz przemieszczania się z jednego do drugiego. Ba! Dobrze byłoby nawet mieć je widoczne na raz w celu porównania, bądź analizy znajdującej się w nich treści. Na szczęście, PhpStorm odpowiednio o to zadbał:

<kbd>alt</kbd> + <kbd>←</kbd> - przejście do zakładki w lewo
<kbd>alt</kbd> + <kbd>→</kbd> - przejście do zakładki w prawo
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>F4</kbd> - zamknięcie aktywnej karty
lub
<kbd>ctrl</kbd> + <kbd>F4</kbd> - operacja zamknięcia (nie mylić z <kbd>alt</kbd> + <kbd>F4</kbd> :D !!!)

Ok, a co z drugą nadmienioną przeze mnie kwestią dotyczącą przemieszczania? Jak najbardziej i to nie będzie stanowić większej trudności! Niestety jednak, opcje te nie są domyślnie zaprogramowane w mapie skrótów. Stanowią one jedne z nielicznych, które ustawiałem pod siebie. Aby więc je wdrożyć, należy w oknie _"Settings"_ (<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>s</kbd>) w odpowiedniej zakładce ustawić następujące wartości:

_Main Window -> Window -> Editor Tabs_
-> Move Right: <kbd>right alt</kbd> + <kbd>></kbd>
-> Goto Next Splitter: <kbd>alt</kbd> + <kbd><</kbd>
-> Goto Previous Splitter: <kbd>alt</kbd> + <kbd>></kbd>

A więc:

<kbd>right alt</kbd> + <kbd>></kbd>  - czyli przeniesienie danego pliku na prawą połowę okna
<kbd>alt</kbd> + <kbd><</kbd> - przejście do następnej części podzielonego ekranu
<kbd>alt</kbd> + <kbd>></kbd> - przejście do poprzedniej części podzielonego ekranu

![PhpStorm dzielenie ekranu](https://lh3.googleusercontent.com/K__0QuTOiTEOkEayiuY3PeUN-PHvFfv17kCJ9nRlv6_L0xwD5pQapDYb233NX5MsWa4hV6NbW4kV=s1024)

Czasami przydaje mi się dodatkowo podzielić ekran wzdłuż, lecz podział tworzę już przy pomocy myszki. Jeśli mam więcej podziałów obszarów roboczego, i mam problem z przeniesieniem jakiegoś pliku, to najpierw go zamykam, a następnie w danej części korzystam z otwarcia ostatnio modyfikowanego pliku (okienko _"Recent Files"_):

<kbd>ctrl</kbd> + <kbd>e</kbd>  - otwarcie okna ostatnio modyfikowanych plików

## Nawigacja w kodzie

Nie będę ukrywać, że PhpStorm dostarcza wielu przydatnych narzędzi i funkcjonalności znacząco ułatwiających pracę z kodem, oraz odpowiednie przemieszczanie się pomiędzy klasami, metodami i wieloma innymi. W tej sekcji nie będę rozpisywał się na ich temat, a po prostu przedstawię listę tych, z których korzystam najczęściej, i które moim zdaniem wydają się być najbardziej przydatne.

### Podstawowe operacje

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

### Zaznaczanie kodu

<kbd>ctrl</kbd> + <kbd>w</kbd> - zaznaczanie coraz większej porcji kodu (wielokrotne użycie)
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>←</kbd>/<kbd>→</kbd> - zaznaczanie słów w lewo/prawo
<kbd>shift</kbd> + <kbd>←</kbd>/<kbd>→</kbd> - zaznaczanie znaków w lewo/prawo

### Operacje na zaznaczonym kodzie

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

### Umiejscowienie kursora

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

### Użycia w kodzie

<kbd>ctrl</kbd> + <kbd>b</kbd> - przejście do deklaracji
<kbd>shift</kbd> + <kbd>ctrl</kbd> + <kbd>b</kbd> - przejście do deklaracji typu
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>b</kbd> - przejście do implementacji
<kbd>alt</kbd> + <kbd>F7</kbd> - wyszukiwanie użyć klasy/metody/zmiennej
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>F7</kbd> - szybkie  zaznaczanie miejsc użyć klasy/metody/zmiennej

### Debugging

Jeśli w danym pliku, w którym tworzymy lub modyfikujemy kod, wystąpią jakieś błędy wykryte przez IDE (począwszy od krytycznych, po literówki), bardzo łatwo możemy między nimi nawigować przy pomocy klawisza <kbd>F2</kbd>.

<kbd>F2</kbd> - nawigowanie pomiędzy błędami w aktywnym pliku

Jednocześnie zawsze można wyświetlić więcej szczegółów:

<kbd>ctrl</kbd> + <kbd>F1</kbd> - wyświetlenie szczegółów na temat błędu znajdującego się w miejscu kursora
<kbd>ctrl</kbd> + <kbd>q</kbd> - wyświetlenie dokumentacji w pop-up danego elementu
<kbd>ctrl</kbd> + <kbd>q</kbd> + <kbd>q</kbd> - wyświetlenie dokumentacji w zakładce

### Struktura

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

### Testowanie (PhpUnit)

<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>t</kbd> - przejście do testu aktualnej klasy
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>F10</kbd> - wykonanie testu aktualnej klasy
<kbd>ctrl</kbd> + <kbd>F5</kbd> - (_będąc w okienku wykonanych testów_) ponowne wykonanie testu

### Przydatne operacje

Poniżej lista innych przydatnych funkcjonalności i operacji, jakie łatwo można wykonać w PhpStorm IDE przy pomocy odpowiednich skrótów klawiaturowych:

<kbd>F5</kbd> - skopiowanie pliku do innego miejsca
<kbd>F6</kbd> - przeniesienie pliku/klasy/metody do innego miejsca
<kbd>shift</kbd> + <kbd>F6</kbd> - zmiana nazwy dowolnego bytu
<kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>L</kbd> - autoformatowanie kodu całego pliku lub zaznaczonego miejsca

## Zwijanie kodu

W PhpStorm IDE istnieje możliwość zwinięcia dowolnej części kodu. Przykładowo, klasę można złożyć w taki sposób, aby widoczne były tylko i wyłącznie definicje metod jak w interfejsie:

![enter image description here](https://lh3.googleusercontent.com/o4NOyH5DoUSFZs5JvdpZXzS4tY_PVvsyy94pv3BBmNcOP-oHcO328En-AqkuRy7Z4NOQbZb8HQvQ=s1024)

Jasne jest, że można tego dokonać między innymi poprzez kliknięcie myszką plusów / minusów znajdujących się pomiędzy numerami linii kodu, a samym kodem. Jednakże, czyż nie łatwiej byłoby zrobić to przez skrót klawiaturowy ;)? Jasne, że tak! I oto jest taki sposób:

<kbd>ctrl</kbd> + <kbd>-</kbd> - zwinięcie bloku kodu
<kbd>ctrl</kbd> + <kbd>.</kbd> - zwinięcie zaznaczonego kodu
<kbd>ctrl</kbd> + <kbd>+</kbd> - otwarcie zwiniętego kodu

## Wyszukiwanie

PhpStorm udostępnia programiście bardzo szybki system wyszukiwania, w którym to można wyszukiwać po nazwach klas, lub plików, akcjach, ustawieniach, a nawet i po wszystkim na raz. 

<kbd>shift</kbd> + <kbd>shift</kbd> - wyszukiwanie wszystkiego pod wskazaną frazą
<kbd>ctrl</kbd> + <kbd>n</kbd> - wyszukiwanie klasy
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>t</kbd> - wyszukiwanie pliku po nazwie
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>a</kbd> - wyszukiwanie akcji lub konkretnej opcji
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>f</kbd> - wyszukiwanie w kodzie projektu

Charakterystyczną funkcjonalnością tych wyszukiwarek jest natychmiastowe identyfikowanie potencjalnych wyników poprzez pojedyncze litery. Załóżmy, że chcemy wyszukać klasę _"IndexController"_. Aby dokonać tego **najszybciej**, wystarczy kliknąć <kbd>ctrl</kbd> + <kbd>n</kbd>, a następnie wpisać: _"ic"_. Cóż się stało? Otóż IDE użyło tych dwóch liter do dopasowania powiązanych według niego wyrazów. W tym przypadku została wykorzystana notacja _"CamelCase"_, i PhpStorm posłużył się użytymi w niej dużymi literami. Żeby nie było, sposób ten działa równie mądrze na innego typu notacjach :).

To nie koniec ciekawostek! W przypadku wyszukiwania po nazwach klas lub plików, można dodatkowo, po dwukropku, wpisać numer linii kodu, aby od razu do niej przejść! Wystarczy więc, że w nowo otwartym okienie wpisze się odpowiednią frazę i kliknie <kbd>Enter</kbd>.
Przykładowo, <kbd>ctrl</kbd> + <kbd>n</kbd> + _"ic:15"_ + <kbd>Enter</kbd> spowoduje przeniesienie do klasy `IndexController` do linii nr 15.

## Git

Obecnie rzadko który projekt nie jest przechowywany na zewnętrznym repozytorium kontroli wersji. Nie dosyć, że służy ono jako swojego rodzaju kopia zapasowa, to jeszcze znacząco usprawnia równoległą pracę wielu programistów. Nie ma więc opcji, aby jakieś IDE nie miało możliwości zintegrowania się z takim systemem. W PhpStorm tą funkcjonalność dla m.in. repozytoriów Git mamy już w wersji bez dodatków, i jak najbardziej jest ona wspierana przez cały wachlarz skrótów klawiszowych :).

Jak zapewne dobrze wiemy, podstawowymi, i zarazem najczęściej wykorzystywanymi komendami w tego typu repozytorium są `pull`, `commit`, `push`. Mają one, oczywiście, swoje odpowiedniki w skrótach w PhpStorm IDE:

<kbd>ctrl</kbd> + <kbd>t</kbd> - `git pull`
<kbd>ctrl</kbd> + <kbd>k</kbd> - `git commit`
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>k</kbd> - `git push`

Gdyby tak spojrzeć od praktycznej strony, to rzadko kiedy więcej będzie potrzebne. Jednakże, to na szczęście nie koniec zintegrowanych w PhpStorm funkcjonalności Git. Aby dowiedzieć się na ten temat czegoś więcej, warto zajrzeć do dedykowanego okna "VCS Operations" które otwiera się następująco:

<kbd>alt</kbd> + <kbd>~</kbd> - otwieranie okna "VCS Operations"

![PhpStorm IDE - VCS Operations](https://lh3.googleusercontent.com/UoUwgnWG2ZyudTYv59wLyz7XoyxiBDlIkTHWnDy16cUaEq0fylaEyX6OoE-21i8RNPyB9gJZoBj5=s1024)

Dodając jeszcze od siebie: zawartość tego okna jest dostosowywana automatycznie względem aktualnego stanu repozytorium. Inaczej wygląda kiedy jest już ono podpięte, inaczej kiedy nie, a i dodatkowe opcje pojawiają się w przypadku chociażby konfliktów.

Wracając jednak. Z poziomu okna _"VCS Operations"_ można wybrać dowolną opcję kierując się strzałkami <kbd>↑</kbd>/<kbd>↓</kbd>. Wygodniejszym jednak dla mnie sposobem jest natychmiastowe wybranie odpowiedniej pozycji. Wymaga to oczywiście zapamiętania cyfr odpowiednich pozycji, lecz gwarantuję, że to kwestia przyzwyczajenia. Głównie korzystam z następujących:

<kbd>alt</kbd> + <kbd>~</kbd> + <kbd>2</kbd> - commit aktualnie aktywnego pliku (jednego)
<kbd>alt</kbd> + <kbd>~</kbd> + <kbd>5</kbd> - przypisy VCS
<kbd>alt</kbd> + <kbd>~</kbd> + <kbd>7</kbd> - lista gałęzi

W przypadku tej ostatniej chciałbym dodać parę słów. Może wystąpić tak, że przy projekcie, przy którym aktualnie pracujemy, może równocześnie pracować wielu innych programistów pracujących nad wieloma funkcjonalnościami. Można więc się spodziewać, że ilość branchy będzie niemała i znalezienie odpowiedniego stanie się dość skomplikowane. Na całe szczęście, wyniki tej listy można odpowiednio przefiltrować.

Zaraz po otwarciu okna z listą gałęzi, programista ma możliwość wpisania jakiegokolwiek łańcucha znaków. W związku z czym, można:
- po prostu wpisać nazwę brancha, co spowoduje ukazanie się jego jako jedynego;
- wpisać skrót, po którym można listę gałęzi przefiltrować (np. wpisując _"om"_ w liście znajdzie się _"origin/master"_);
- numer issue brancha, co przefiltruje listę po odpowiednim numerze zagadnienia stworzonego na przykład w Jira lub GitLab;
- po prostu kliknąć <kbd>ctrl</kbd>+<kbd>v</kbd> jeśli mamy w schowku nazwę brancha lub jego część.

Kolejnym, bardzo istotnym elementem PhpStorm IDE związanym z informacjami o repozytorium Git aktualnego projektu, jest zakładka _"Version Control"_. Jest ona dostępna pod następującym skrótem:

<kbd>alt</kbd> + <kbd>9</kbd> - zakładka "Version Control"

W jej ramach znajduje się, w głównej mierze:
- lista aktualnie dokonanych modyfikacji na plikach;
- wizualna reprezentację `git log`.

W tej zakładce mogą również pokazać się dodatkowe informacje, jak np. historia Git danego pliku, bądź danego brancha. Przemieszczanie pomiędzy wszystkimi sekcjami działa tak samo, jak w przypadku tabów plików w IDE, czyli:

<kbd>alt</kbd> + <kbd>←</kbd> - przejście do zakładki w lewo;
<kbd>alt</kbd> + <kbd>→</kbd> - przejście do zakładki w prawo;

Poza wyżej wspomnianymi skrótami, dość przydatna jest funkcjonalność nawigowania pomiędzy dokonanymi zmianami w danym pliku w porównaniu do stanu z repozytorium. PhpStorm wizualizuje je odpowiednio niebieskimi, bądź zielonymi barwami przy lewej krawędzi. Istnieje jednak sposób na szybkie przemieszczanie się pomiędzy nimi:

<kbd>shift</kbd> + <kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>↑</kbd>/<kbd>↓</kbd> - przemieszczanie się pomiędzy zmianami w pliku

Mając powyższe na uwadze, warto znać skrót usunięcia nadanych modyfikacji:

<kbd>shift</kbd> + <kbd>ctrl</kbd> + <kbd>z</kbd> - przywrócenie aktualnej linii lub pliku do stanu z repozytorium


## Przydatne pluginy

Sekcja może nie mówi o skrótach, ale chciałbym zamieścić tutaj listę przydatnych dodatków ułatwiających, bądź przyspieszających pracę z kodem. Jest ona jak najbardziej możliwa do rozszerzenia, a więc z chęcią przyjmę wszelkie wskazówki :). Mi w chwili obecnej pomagają następujące pluginy:

- **.env files support**
wsparcie plików .env
- **.ignore**
wsparcie plików .gitignore
- **PHP Annotations**
wsparcie adnotacji (np. Doctrine)
- **Php Inspections (EA Extended)**
rozszerzenie funkcjonalności wskazywania błędów w kodzie
- **Symfony Plugin**
wsparcie dla frameworka Symfony


## Inne przydatne funkcjonalności PhpStorm
Abstrahując już całkowicie od tematu skrótów klawiaturowych, w PhpStormie znajdzie się jeszcze wiele innych funkcjonalności przyspieszających pracę programistów. Poniżej przedstawię parę z nich.

### Live templates
Tak zwane _"Live Templates"_, to szablony kodu generowanego po wpisaniu z góry określonej odpowiadającej danemu szablonowi frazy składającej się z krótszego, łatwego w zapamiętaniu łańcucha znaków. Mówiąc więc najprościej, generuje się większy kod po podaniu krótszego ciągu znaków. Chociażby, będąc w klasie, i chcąc utworzyć metodę publiczną, wystarczy podać łańcuch _"pubf"_ i kliknąć przycisk <kbd>Tab</kdb>:

![Live Template example](https://lh3.googleusercontent.com/Ouy2wKj_49b1r4OlYH3cj9EeUtNyjDyHzb9j4sRsRE0Jc1irv-mphNi1E5EjMF42BOkEfm-GGuX3=s1024)

Tego typu szablony można tworzyć w nieskończoność dla przeróżnych przypadków, które będą odpowiednio często występować. Ich lista znajduje się w "_Settings_ -> _Editor_ -> _Live Templates_". Istnieją nawet także repozytoria na GitHub, które zbierają zestawy żywych szablonów. Przykładowo, istnieją żywe szablony dla: 
- React: [minwe](https://github.com/minwe)/**[jetbrains-react](https://github.com/minwe/jetbrains-react)**
- jQuery / WordPress: [WPRiders](https://github.com/WPRiders)/**[PhpStorm_Live_Templates](https://github.com/WPRiders/PhpStorm_Live_Templates)**

### Emmet

Emmet to inteligentny sposób generowania plików HTML lub kodu CSS za pomocą bardzo prostej notacji bardzo podobnej do notacji selektorów CSS. Nie przedłużając za bardzo, najlepiej przedstawię przykład:

![Emmet in PhpStorm](https://lh3.googleusercontent.com/eovmfrZJhZMszbbmR1plVkTB0W2qRxTQaITIty_XYvH44vdeCrvO0hHspunU9SL7COCImyrqFtY_=s1024)


## PhpStorm Tips'n'Tricks

**Inicjalizacja atrybutów z kontrolera**
<kbd>alt</kbd> + <kbd>Enter</kbd> na parametrze konstruktora

![Inicjalizacja atrybutów z kontrolera](https://lh3.googleusercontent.com/BL77jPX2v-pl9yIkBDAHkLK59wdmCs2xX1B6sXIaWCUqRvmcPTzNhhTrsg9UUfrMj6NMFLK5I1WU=s1024)

**Generowanie settera / gettera zmiennej instancyjnej**
<kbd>alt</kbd> + <kbd>Enter</kbd> na zmiennej instancyjnej nie posiadającej settera lub gettera

![enter image description here](https://lh3.googleusercontent.com/hEUhreJoQ-dFO-MC930rfez0IW4ghffNITbvGM3UpZ1vmKdP9TXZzV89t0JNUXOMSb_VgQNKhYPe=s1024)

**Generowanie wielu setterów / getterów zmiennej instancyjnej**
<kbd>alt</kbd> + <kbd>insert</kbd> wewnątrz klasy

![enter image description here](https://lh3.googleusercontent.com/r5uFo2P6P3KTYdPScAe4OyyxEg5Kn728R0Y9UQTA3WXd8ZZMy4_HZwenhtWgTOmBXBnTGTC7_TIl=s1024)

## Podsumowując

Nie ma co ukrywać, iż nie dosyć, że PhpStorm IDE oferuje ogrom opcji, to umożliwia ich bardzo szybkie wykorzystanie. W taki oto sposób praca programisty staje się o wiele przyjemniejsza, co wysoko sobie cenię.

Zapraszam do komentowania! Napiszcie mi proszę, czy korzystacie z tego typu pomocnych skrótów, i czy może znacie jakieś jeszcze? Treść będę starał się modyfikować na bieżąco :).

Poza powyższym, polecam jeszcze zaglądnąć na stronę [SitePoint](http://www.sitepoint.com/phpstorm-top-productivity-hacks-shortcuts/), gdzie przedstawionych zostało parę najpopularniejszych skrótów przy pomocy pomocnych GIFów :).
