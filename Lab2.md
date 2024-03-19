# Zad1.1
## A
rodzenstwo
## B
sa wnukami jakiegos dziadka
## C
sa dziadkami jakiegos wnuka
## D
Y to ojczym/macocha X
## E 
rodzenstwo przybrane
## F
Y to rodzenstwo rodzica dziecka X
## G
X to dziecko dziadka i rodzica Y , ciekawa rodzina

# Zad1.2
## A 
rodzic(x,a).  
rodzic(x,b).  
rodzic(y,a).  
rodzic(y,b).  
rodzenstwo(X, Y) :-  
   rodzic(X, A),  
   rodzic(X ,B),
   rodzic(Y, A),
   rodzic(Y, B),
   X \== Y.  

## B

## E
przybraneRodzenstwo(X, Y) :-  
   rodzic(X, A),  
   rodzic(X ,B),
   rodzic(Y, A),
   rodzic(Y, B),
   X \== Y.  
