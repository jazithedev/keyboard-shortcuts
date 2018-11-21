# Wyszukiwanie

PhpStorm udostępnia programiście bardzo szybki system wyszukiwania, w którym to można wyszukiwać po nazwach klas, lub plików, akcjach, ustawieniach, a nawet i po wszystkim na raz. 

<kbd>shift</kbd> + <kbd>shift</kbd> - wyszukiwanie wszystkiego pod wskazaną frazą
<kbd>ctrl</kbd> + <kbd>n</kbd> - wyszukiwanie klasy
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>t</kbd> - wyszukiwanie pliku po nazwie
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>a</kbd> - wyszukiwanie akcji lub konkretnej opcji
<kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>f</kbd> - wyszukiwanie w kodzie projektu

Charakterystyczną funkcjonalnością tych wyszukiwarek jest natychmiastowe identyfikowanie potencjalnych wyników poprzez pojedyncze litery. Załóżmy, że chcemy wyszukać klasę _"IndexController"_. Aby dokonać tego **najszybciej**, wystarczy kliknąć <kbd>ctrl</kbd> + <kbd>n</kbd>, a następnie wpisać: _"ic"_. Cóż się stało? Otóż IDE użyło tych dwóch liter do dopasowania powiązanych według niego wyrazów. W tym przypadku została wykorzystana notacja _"CamelCase"_, i PhpStorm posłużył się użytymi w niej dużymi literami. Żeby nie było, sposób ten działa równie mądrze na innego typu notacjach :).

To nie koniec ciekawostek! W przypadku wyszukiwania po nazwach klas lub plików, można dodatkowo, po dwukropku, wpisać numer linii kodu, aby od razu do niej przejść! Wystarczy więc, że w nowo otwartym okienie wpisze się odpowiednią frazę i kliknie <kbd>Enter</kbd>.
Przykładowo, <kbd>ctrl</kbd> + <kbd>n</kbd> + _"ic:15"_ + <kbd>Enter</kbd> spowoduje przeniesienie do klasy `IndexController` do linii nr 15.
