# Ćwiczenie punktowane

W przykładzie terminator.c uruchamiamy podproces w tle, po czym proces-rodzic w pętli czeka na sygnały i kończy jeśli dostanie dwa razy SIGINT (Ctrl+C) w ciągu sekundy.

Uzupełnij funkcję parent() aby po pierwszym SIGINT wysłać SIGINT do dziecka, a po podwójnym SIGINT wysłać SIGKILL do dziecka. Popraw kod aby proces-rodzic wychodził od razu z pętli także kiedy dziecko samo zakończy działanie (SIGCHLD). Nie zmieniaj child().

W razie wypadków przy pracy warto pamiętać, że wciśnięcie Ctrl + \ wysyła SIGQUIT.