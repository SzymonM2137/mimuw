# Zadanie punktowane: zlicz słowa

Napisz wielowątkowy program, który zliczy ile w sumie razy wystąpiło dane słowo w wymienionych plikach tekstowych. Wejście programu (na stdin) wygląda następująco:

szukane_słowo
liczba_plików
nazwa_pliku1
nazwa_pliku2
...

Twój program powinien tworzyć stałą liczbę wątków. Wątki powinny statycznie podzielić się pracą (każdy powinien otrzymać możliwie podobną liczbę nazw plików). Wątki powinny przekazać rezultaty do wątku głównego używając obietnic.

Kilka plików tekstowych - sztuk Szekspira udostępnionych przez Projekt Gutenberg - znajdziesz w data-txt.

Sekwencyjną implementację znajdziesz w grep-seq.cpp. (Możesz ją przetestować wykonując ./grep-seq < ../grep-input.txt)
