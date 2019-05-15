# Materiały do nauki ML

## Python
Trzeba się sprawnie poruszać w Pythonie, bo to ułatwi potem życie. Będzie się trzeba zwykle tylko zastanawiać nad sednem problemu, czyli co zakodzić, a nie jak to zakodzić.
* [Kanal Corey Schafer na YT](https://www.youtube.com/user/schafer5/playlists) Tutaj jest kilka fajnych kursów z Pythona, ale też z Linuxa, SQL czy gita, a to wszystko bardzo warto znać, to narzędzia, z których się na co dzień korzysta. 
* [Kurs sentdexa na YT](https://www.youtube.com/playlist?list=PLQVvvaa0QuDfju7ADVp5W1GF9jVhjbX-_) 
* [Kurs pandasa z PyCon 2015](https://www.youtube.com/watch?v=5JnMutdy6Fw) Jest kilka bibliotek pythonowych, których się używa nonstop, przede wszystkim `numpy` i `pandas`. To jest szybki, bardzo fajnie zrobiony kurst pandasa.

## Machine learning
### Kursy
Ja nie jestem jakimś wielkim fanem kursów, a już na pewno płacenia za nie, najwięcej się można nauczyć po prostu rozwiązując jakieś problemy. Ale są kursy, które wręcz trzeba zrobić, bo są tak dobre.
* [Kurs Andrew Ng na Coursera](https://www.coursera.org/learn/machine-learning/) Klasyka, must have, świetny kurs po prostu. Nie w pythonie tylko w Octave (Matlab), więcej Octave tego nie użyjesz, ale składnia jest prosta, takie trochę `numpy` + `scipy` w pythonie.
* [cs231n na Stanford](http://cs231n.stanford.edu/) Kolejny klasyk, ten już nie dotyczny generalnie ML tylko Deep Learningu, sieci konwolucyjnych, analizy obrazu
* [mlcourse by ods.ai](https://mlcourse.ai/) Bardzo fajny i przyjemny kurs z podstaw ML, bardzo polecam.
* [fast.ai](https://www.fast.ai/) Kursy z Deep Learningu, ewentualnie do zrobienia mogą być ciekawe, sam nie robiłem, ale podobno sporo ciekawych rzeczy w nim jest.

### Książki
Książki są fajne, ale długo się czyta :D. Te dwie na pewno są godne polecenia, ale nie są w żadnej mierze konieczne.
* [Deep Learning, Goodfellow](https://www.deeplearningbook.org/) Świetna książka, ale dużo w niej matematyki i teorii, na pewno dobrze przejść w niej przez `Part I` żeby ogarnąć chociaż podstawy matematyczne. Wbrew tytułowi nie dotyczy tylko DL, ale szerzej ML.
* [Deep Learning with Python, fchollet](https://www.manning.com/books/deep-learning-with-python?a_aid=keras&a_bid=76564dff) Poszukam czy nie mam pdf tej ksiązki. Ta już mniej się skupia na szczegółach, więcej na zastosowaniach i samym deep learningu.

## Kaggle
Jak już się ma trochę podstaw to najlepiej uderzać na [kaggle](https://www.kaggle.com/). To jest platforma z różnymi konkursami z ML, ale jest tam mnóstwo materiałów do nauki.

Jest cała oddzielna [sekcja](https://www.kaggle.com/learn/overview) poświęcona podstawom, więc można bardzo szybko tu iść.

Na początek zapoznać się z kernelami (to takie jupyter notebooki na kagglu), w których można tworzyć rozwiazania.

I w tych kernelach można rozwiązywać problemy z [playgrounds](https://www.kaggle.com/competitions?sortBy=grouped&group=general&page=1&pageSize=20&category=playground) oraz [getting started](https://www.kaggle.com/competitions?sortBy=grouped&group=general&page=1&pageSize=20&turbolinks%5BrestorationIdentifier%5D=641dde53-6c1c-4c3a-8d96-dda5b241594c), są to problemy dedykowane do nauki.
Można patrzeć na kernela innych użytkowników, na dyskusje na forum i jest to świetny sposób na naukę. Z jednej strony samemu trzeba rozwiązac jakiś prawdziwy problem na prawdziwych danych, ale też można korzystać z wiedzy innych i uczyć się na ich sukcesach i porażkach.

Gdy się już czuje trochę pewniej, można brać udział w innych [konkursach](https://www.kaggle.com/competitions?sortBy=grouped&group=general&page=1&pageSize=20&turbolinks%5BrestorationIdentifier%5D=641dde53-6c1c-4c3a-8d96-dda5b241594c), nie tylko playground. Dodatkową zabawą jest zdobywanie punktów i medali i rang za udział w dyskusjach, publikowanie kerneli i wysokie miejsca w konkursach.

Konkursy są bardzo różne ale przede wszystkim tabelkowe (czyli analiza danych z jakiś różnych tabel, mają tag `tabular data`, zwykle są tu używane różne modele drzewiaste, przede wszystkim Gradient Boosting Machines) oraz obrazkowych (analiza obrazu, tag `image data`, zwykle rozwiązania skupiają się na deep learningu i siecial konwolucyjnych.)

Te kernele to raczej nie jest piękna architektura kodu, to są zwykle małe szybkie rozwiązania, napisane w jednym skrypcie, więc pięknego kodzenia tam się nie nauczy, ale działających w ML rozwiązań już jak najbardziej można.
