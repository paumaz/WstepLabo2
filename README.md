WstepLabo2
==========
```sh
cd c
vim program.c
```

1. Wyświetl na ekran 2 pierwsze wiersze pliku program.c. (head)

```sh
head -2 program.c
```

2. Wyświetl na ekran 4 ostatnie wiersze pliku program.c. (head, tail)

```sh
tail -5 program.c
```

3. W pliku program.c znajdź wszystkie wiersze z wystąpieniem słowa „main”. (grep)

```sh
grep -e main program.c
```

4. Plikowi program.c nadaj następujące uprawnienia: właściciel – czytanie, pisanie, grupa – czytanie, pozostali użytkownicy: brak uprawnień. (chmod)

```sh
chmod u=rw,g=r,o=r,o-r program.c
```

5. Będąc w katalogu temp przenieś katalog wazne-sprawy do katalogu praca.

```sh
cd temp
mv 
```

6. Zarchiwizuj cały katalog temp. (zip i tar)

```sh

```

