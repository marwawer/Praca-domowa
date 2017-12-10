FUNKCJA printf scanf
===================
Komputer byłby całkowicie bezużyteczny, gdyby użytkownik nie mógł się z nim porozumieć (tj. wprowadzić danych lub otrzymać wyników pracy programu). Programy komputerowe służą w największym uproszczeniu do obróbki danych - więc muszą te dane jakoś od nas otrzymać, przetworzyć i przekazać nam wynik.
Takie wczytywanie i "wyrzucanie" danych w terminologii komputerowej nazywamy wejściem (input) i wyjściem (output). Bardzo często mówi się o wejściu i wyjściu danych łącznie - input/output, albo po prostu I/O.
W C do komunikacji z użytkownikiem służą odpowiednie funkcje. Zresztą, do wielu zadań w C służą funkcje. Używając funkcji, nie musimy wiedzieć, w jaki sposób komputer wykonuje jakieś zadanie, interesuje nas tylko to, co ta funkcja robi. Funkcje niejako "wykonują za nas część pracy", ponieważ nie musimy pisać być może dziesiątek linijek kodu, żeby np. wypisać tekst na ekranie (wbrew pozorom - kod funkcji wyświetlającej tekst na ekranie jest dość skomplikowany).
## Funkcja printf()
Jest to funkcja wyjścia , służy do wypisywania danych na ekran.Jest jedną z bardziej skomplikowanych funkcji i jednocześnie jedną z  najczęściej używanych funkcji w języku C.
 Tak wygląda najprostsze użycie tej funkcji. Tekst umieszczony w cudzysłowach wewnątrz nawiasów funkcji 
 
     #include <stdio.h>
      int main(void)
     {
       printf("Witaj swiecie!\n");
       return 0;
     }
Po skompilowaniu i uruchomieniu komputer wyświetli na ekranie:
    
    Witaj swiecie!
