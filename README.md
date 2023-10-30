# 4 funktioner, 4 loopar

Gör ett program enligt nedan krav.

Tre av funktionerna ska utföra samma operation men med olika typer av loopar. Den sista ska endast skriva ut innehållet i en array.
Alla funktionerna ska ta en array som argument. Arrayen ska innehålla flera olika heltal, både jämna och udda.
De tre första funktionerna ska returnera två arrayer; 

- en ska innehålla jämna tal och den andra ojämna tal.

Talen ska hämtas från den array som skickats in som argument.

De olika funktionerna ska namnges enligt nedan och använda loopar enligt följande krav;

**separateNumbersForLoop**

ska använda en for-loop för att itera över arrayen som är parameter och
returnerar två arrayer: en med jämna tal och en med udda


**separateNumbersWhileLoop**

som ovan fast med en while-loop
returnerar två arrayer: en med jämna tal och en med udda


**separateNumbersDoWhileLoop**

som ovan fast med en do-while-loop
returnerar två arrayer: en med jämna tal och en med udda


**printArray**

ska skriva ut innehållet i arrayen med som itereras med en foreach-loop.
ska inte returnera någonting


Testet som följer i repot med ska användas och godkänt ges om testet kan köras utan fel.
Du kan installera jest med kommandot


    $ npm install jest


För att köra testet;


    $npm test separatenumbers.test.js


  

