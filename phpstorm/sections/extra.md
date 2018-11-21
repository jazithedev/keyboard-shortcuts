# Extra
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