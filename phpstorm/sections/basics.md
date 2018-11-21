# Podstawy

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