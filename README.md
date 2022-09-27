# Duskers
## EN
### Description
A simple adventure game of exploring the world and acquiring titanium. The player starts with three robots, then explores the generated locations collecting titanium on them. Be warned, the player may encounter enemies, and each such encounter results in the loss of one of the robots. The game also has a shop where you can purchase a titanium scanner (shows how much titanium you can collect in a location), an enemy scanner (shows the probability of an enemy in a location) and robots. The game ends when the player has no more robots.

The game supports game save functions and a list of top scores.

At start-up, "save_file.txt" and "high_scores.txt" files are created in the folder where the game is located.

The script can be run with additional parameters from the command line, `python3 -u duskers.py <seed> <min_animation> <max_animation> <locations>`, where:
* \<seed> - seed to random module;
* <min_animation>, <max_animation> - minimum and maximum animation duration;
* \<locations> - names of locations in the game, separated by "/" (commas as spaces), e.g.: "High,street/Green,park/Destroyed,Arch".

## PL
### Opis
Prosta gra przygodowa, polegająca na eksplorowaniu świata i zdobywaniu tytanu. Gracz zaczyna z trzema robotami, następnie eksploruje generowane lokacje zbierając na nich tytan. Uwaga, gracz może napotkać przeciwników, a każde takie spotkanie skutkuje utratą jednego z robotów. W grze istnieje także sklep w którym można zakupić skaner tytanu (pokazuje ile tytaniu można zebrać w danej lokacji), skaner przeciwników (pokazuje prawdopodobieństwo wystąpienia przeciwnika w danej lokacji) oraz roboty. Gra się kończy, kiedy gracz nie ma już robotów.

Gra obsługuje funkcje zapisu gry oraz listę najlepszych wyników.

Przy uruchamianiu tworzone są pliki "save_file.txt" oraz "high_scores.txt" w folderze w którym znajduje się gra.

Skrypt można uruchomić z dodatkowymi parametrami z linii komend, `python3 -u duskers.py <seed> <min_animation> <max_animation> <locations>`, gdzie:
* \<seed> - ziarno do modułu random;
* <min_animation>, <max_animation> - minimalny i maksymalny czas trwania animacji;
* \<locations> - nazwy lokacji w grze, oddzielone "/" (przecinki jako spacje), np:"High,street/Green,park/Destroyed,Arch".

*Project from JetBrains Academy*
