# Repozytorium na potrzeby przedmiotu WIRDS
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/newetka/wirds_binder-przyklad/main?urlpath=rstudio)


Aby binder działał potzrebuje nastepujacego pliku:
1. 'runtime.txt" - okreslamy z jakiej wersji R bedziemy korzystac oraz z jakiego dnia maja byc pakiety (np. ' r-2021-01-01', 'r-3.6-2021-01-01').
2. mozemy założyc jakie pakiety maja byc w ramach tego obrazu. w takim razie powinnismy utworzyc plik o onazwie 'install.R' który bedzie zawieral skrypt R do instalacji pakietów (np.:
install.packages("tidyverse") - wtedy obraz bedzie sie budował znacznie dlużej
