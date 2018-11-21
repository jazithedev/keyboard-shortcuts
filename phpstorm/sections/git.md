# Git

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
