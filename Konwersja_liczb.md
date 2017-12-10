KONWERSJA LICZB Z RÓŻNYCH SYSTEMÓW LICZBOWYCH
===========================================
Konwersja liczb z systemu 10 na 2 i odwrotnie
---------------------------------------------
Liczbe zapisaną w systemie dziesiętnym dzielimy przez 2 jeśli wynik jest bez reszty piszemy 0 jeśli z resztą 1 tak do końca
| liczba dziesiętn | dzielimy przez 2 |reszta 0 V 1|
| ------ | ------ |  ------ |
|251 |125| 1|
| 125|62|1|
| 62 |31|0|
| 31| 15|1|
|15 | 7|1 |
| 7| 3| 1 |
| 3| 1| 1 |
| 1| 1| 1 |
Wynik odczytujemy od dołu do góry 11111011


Druga metoda to wykorzystanie tabelki z potęgami liczby 2. Polega na tym, że znajdujemy w górnej pozycji liczbę o wartości 




8192 |4096 |2048|1024 |512 |256 |128 |64 | 32 |16 | 8 |4|2|1|
| - | - | - | - | - | -| - | - | - | - | - | - |  -| - |  
|2<sup>13</sup>|2<sup>12</sup>|2<sup>11</sup>|2<sup>10</sup>|2<sup>9</sup>|2<sup>8</sup>|2<sup>7</sup>|2<sup>6</sup>|2<sup>5</sup>|2<sup>4</sup>|2<sup>3</sup>|2<sup>2</sup>|2<sup>1</sup>|2<sup>0</sup>|
 | 1 |0 | 0 | 1 | 0 | 1 | 1 | 0 | 0 | 1 | 1 | 1 | 1| 0 |
>8192+1024+256+128+16+8+4+2=9630

 
 |0,5 |0,25 |0,125 |0,0625 |0,03125|0,015625|0,00390625|0,000976562
| - | - | -| - | - | - |  - |  -| 
|2<sup>-1</sup>|2<sup>-2</sup>|2<sup>-3</sup>|2<sup>-4</sup>|2<sup>-5</sup>|2<sup>-6</sup>|2<sup>-7</sup>|2<sup>-8</sup>|2<sup>-9</sup>|
 | 1 | 1 | 0 | 1 | 0 | 1 | 1 | 0 |
 
>0,5+0,25+0,0625+0,015625+0,00390625=0,83203125
>9630+0,83203125=9630,83203125
