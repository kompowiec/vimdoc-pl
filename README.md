# vimdoc-pl
The vimdoc polish user manual from http://www.vim.org/translations.php

#Instalacja
Większość instrukcji odnosi się się także do systemu MS-Windows. Wystarczy podmienić tar.gz na zip.
W katalogu domowym

Rozpakuj archiwum tar.gz do katalogu ~/.vim/doc.
Uruchom Vima i wydaj polecenie
:helptags ~/.vim/doc/
Od tej chwili będziesz mógł przeglądać pliki Podręcznika Użytkownika po polsku. Dostaniesz się do nich wydając polecenie:
:help usr_toc

#Systemowa

Tutaj sytuacja zależy do tego czy masz Vima kompilowanego ręcznie, czy dystrybucyjnego.

W pierwszym wypadku najlepszym miejscem na umieszczenie polskiej wersji będzie katalog
/usr/local/share/vim/vimfiles/doc/
W ten sposób polska wersja nie będzie nadpisana przy instalacji następnej wersji Vima. Po rozpakowaniu w Vimie wydaj polecenie (jako root):
:helptags /usr/local/share/vim/vimfiles/doc

W drugim wypadku: dystrybucje robią różne rzeczy ze strukturą plików Vima. Jedynym pewnym rozwiązaniem jest nadpisanie plików usr* dostarczanych wraz z dystrybucją. Powinny one znajdować się w katalogu
/usr/share/vim/doc
Żeby z nich korzystać wydaj polecenie (jako root):
:helptags /usr/share/vim/doc

Oznaką prawidłowego zainstalowania się plików pomocy w katalogach ~/.vim/doc, /usr/local/share/vim/vimfiles/doc będzie ich lista na końcu strony pomocy :help help.txt, w sekcji LOCAL ADDITIONS. 
