# pathfinder

## Setup

Po zainstalowaniu PCgen 6.06.01 wchodzimy do Tools > Preferences i ustawiamy następująco:

### Ustawienia

*BARDZO WAŻNE*: W menu PCGen -> Sources oznaczamy `Allow multi-line objects in sources` na `true`! Bez tego wszystko się posypie.

### Ścieżki do plików

W menu PCGen>location aktualizujemy ścieżki:

PCGen Character Directory -> folder `pathfinder` z tego repo

PCGen Portraits Directory -> folder `pathfinder/portraits` z tego repo

PCGen Homebrew Data Directory -> folder `pathfinder/homebrew` z tego repo


Przy okazji można ustawić browser path, ale to opcjonalne.

### Udogodnienia
W menu PCGen>Sources zaznaczamy:
* Do not show source selection dialog on program start
* Autoload sources with PC

W menu PCGen>Equipment zaznaczamy:
* Masterwork
* Magic(+1 to +5)
Dzięki temu magicznych i masterworkowych itemków nie będzie trzeba ręcznie dodawać do listy ekwipunku.

*UWAGA! Po dokonaniu niektórych zmian w ustawieniach trzeba zrestartować PCGena. Najlepiej na wszelki wypadek zawsze robić restart*

## Użytkowanie
Aby odpalić postać wybieramy File>Open i dzięki powyższym ustawieniom od razu mamy do wyboru pliki `.pcg` z postaciami.

Aby odpalić cały party wybieramy File>Party>Open Party i musimy ręcznie nawigować do folderu z tym repo. Otwieramy `Party.pcg.pcp`. Na szczęście od drugiego użycia Party.pcg.pcp będzie widoczne pod File>Party>Open Party jako jedno z ostatnich.
