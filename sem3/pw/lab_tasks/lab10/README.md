# Zadanie: prezenty

Okres przedświąteczny jest zawsze pracowity: szczególnie gdy termin dostarczenia zadania zbliża się, a Ty jesteś elfem w fabryce prezentów.

Pomóż elfom pracującym w fabryce Mikołaja przygotować prezenty na święta.

Prezenty w fabryce produkuje N_ELFS elfów, a do Mikołaja dostarcza je N_REINDEERS reniferów. Każdy elf produkuje LOOPS prezentów, funkcja int produce() tworzy jeden prezent. Po wytworzeniu prezentu, każdy elf odnosi go do magazynu i zaczyna produkcję kolejnego prezentu. Magazyn jest buforem cyklicznym o rozmiarze BUFF_SIZE. Prezenty z magazynu do Mikołaja dostarczają renifery. Każdy renifer odbiera jeden prezent z magazynu i dostarcza go prosto do Mikołaja procedurą void deliver(int gift).

Uzupełnij (w miejscach oznaczonych TODO) kod w pliku gifts.c tak, by elfy i renifery mogły pracować bezpiecznie. Wykorzystaj pamięć współdzieloną i semafory do obsługi magazynu. Zadbaj o współbieżność i nie zapomnij zwolnić zasobów systemowych po zakończeniu zadania. 