# Nawigacja UI
PhpStorm jest zbudowany z wielu elementów UI, co można od razu zauważyć. Jak już wspomniałem we wcześniejszej części artykułu, do prawie każdego z tych miejsc można się dostać poprzez odpowiedni skrót klawiaturowy. Zobaczmy zatem, czy tak jest :).

## Zakładki narzędzi
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

## Breadcrumbs

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

## Zakładki otwartych plików

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
