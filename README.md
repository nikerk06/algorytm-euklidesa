# Algorytm Euklidesa

## Opis problemu

Celem zadania jest obliczenie największego wspólnego dzielnika (NWD) dwóch liczb z wykorzystaniem algorytmu Euklidesa.

## Algorytm 

Algorytm Euklidesa polega na wielokrotnym zastępowniu pary liczb (a, b) parą (b, a mod b) aż do momentu gdy b=0.

Po zakończeniu pętli algorytm zwraca aktualną wartość a jako największy wspólny dzielnik.

## Pseudokod

DOPÓKI b ≠ 0:

zamień [a, b] na [b, a MOD b] 

zwróć a.
