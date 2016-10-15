# 0036493100

# Pitanje 1
Kad smo dodali class library kao referencu u Bin/Debugu se pojavila datoteka s .dll ekstenzijom.
Ukoliko maknemo .dll datoteku javlja se greška jer CLR ne može naći međukod metode MyConsole.PrintHelloWorld. Da bi aplikacija bila uporabljiva, treba imati datoteke: KonzolnaAplikacija.exe i ClassLibrary1.dll.

# Pitanje 2
Konzolna aplikacija je koristila staru verziju class library assemblija jer nova verzija nije zapisana u metapodacima konzolne aplikacije.

# Pitanje 3
Ispisalo se „Pero: Hello World“.

# Pitanje 4
U Bin/Debug folderu nalazi se još jedna datoka: PeroClassLibrary.dll.

# Pitanje 5
PeroClassLibrary se sad traži iz Bin/Debug foldera.

# Pitanje 6
Build proces se uspio završiti, a u packages direktoriju se ponovo našao NodaTime direktorij.
