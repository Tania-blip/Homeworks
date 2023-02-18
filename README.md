# Homeworks

1. Calculator

Cerinta:
Pentru aceasta tema va trebui sa implementati un calculator care sa faca operatii aritmetice. Programul citeste de la tastatura o expresie aritmentica si afiseaza rezultatul acestei expresii. Formatul de citire a expresiei de la tastatura este urmatorul: se citeste un numar N, apoi N numere reale, iar in final se citesc N-1 operatii. O operatie este reprezentata de un caracter si poate avea valorile: '+', '-', '*', '/'. Astfel, urmatorul input:
// N = 4
3    // operand 1
3    // operand 2
4    // operand 3
5    // operand 4
+*/  // N-1 = 3 operatii
Va fi interpretat ca: “3+3*4/5”.

Task1:
Pentru prima cerinta va trebui sa implementati citirea unei expresii si evaluarea acesteia, neglijand precedenta operatorilor. Astfel, pentru expresia “3+3*4/5”, veti evalua operatiile in ordinea in care apar: 3+3*4/5 6*4/5 = 24/5 = 4.8 . Afisarea rezultatului va avea si o linie noua (adica “printf(”%f\n”, result)”, *NU* “printf(”%f”, result)”).
Task2:
Pentru a doua cerinta va trebui sa implementati citirea unei expresii si evaluarea acesteia tinand cont si de precendenta operatorilor. Astfel, pentru expresia “3+3*4/5”, veti evalua operatiile tinand cont de faptul ca operatiile '*' si '/' au precedenta mai mare fata de '+' si '-'. In consecinta, pentru acesta sarcina, rezultatul expresiei anterioare va fi: 3+3*4/5 = 3+12/5 = 3+2.4 = 5.4 .
Task3:
Pentru a 3-a cerinta va trebui sa implementeti un nou operator, operatorul `#`. Operatorul `#` este definit astfel: a#b = (a+b)*(a+b). Operatorul `#` are precedenta mai mare ca `+`/`-`, dar mai mica ca `*`/`/`. Astfel, pentru aceasta cerinta, rezultatul expresiei “1+2#3*4” va fi: 1+2#3*4 = 1+2#12 = 1 + (2 + 12)*(2 + 12) = 1 + 196 = 197.


2.Avioane
Cerinta: https://ocw.cs.pub.ro/courses/programare/teme_2022/tema2_2022_cbd

