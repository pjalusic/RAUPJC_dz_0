# JMBAG
0036484339

# Pitanje 1:
U folderu su 2 nova filea - ClassLibrary1.dll i .pdb, a ako izbrišemo .dll onda konzolna aplikacija dojavljuje unhandled exception i ništa  niti ne izvodi jer nema kod sebe klasu iz koje čita metodu. Poslao bih .exe datoteku i .dll class library.

# Pitanje 2:
Konzolna aplikacija je prikazala nov string jer pokretanje builda konzolne aplikacije automatski pokreće i build class library projekta.

# Pitanje 3:
Ispisuje se metoda iz PeroClassLibraryja: "Pero: Hello World".

# Pitanje 4:
U folderu se pojavljuje PeroClassLibrary.dll asemblij.

# Pitanje 5:
Aplikacija radi zbog toga što koristi .dll asemblij iz svog Bin/Debug foldera, a ne onaj koji smo mi postavili kao referencu - napravljen je novi .dll u Bin/Debug folderu gdje i traži .dll asemblij.

# Pitanje 6:
Build proces je uspio, točnije ponovno je dohvatio sve potrebne podatke i smjestio ih u packages direktorij.
