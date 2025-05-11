# Scomposizione Polinomi di Grado Superiore al primo
## \underline{Premessa}
I vari metodi vengono descritti con formule generali, che usano simboli come $A$ e $B$ per indicare termini generici, sia *letterali* sia *numerici*.    
Si ricorda che le lettere generiche $A$, $B$...ecc possono avere anche segno negativo.  
Inoltre ricorda che se un elemento di una formula ha forma $AB$, si intende che può essere visto come la moltiplicazione tra due termini:  
`Esempio`  
Se ho $8x^2$, esso può essere visto come:

- $8 \cdot x^2$

- $4 \cdot 2x^2$

- $-2x \cdot (-4x)$

- $\frac{x^2}{2} \cdot 16$

- *ecc...*



# Metodi
Di seguito saranno elencati i metodi di scomposizione più noti, ordinati in modo crescente per i **numeri di termini** della formula da scomporre.  
Come verrà descritto dopo l'elenco dei metodi, è importante ricordarsi il numero di termini di un metodo per capire subito se può essere utiizzato per la scomposizone.  

**IMPORTANTE**:  
Prima di applicare i seguenti metodi è importante verificare che non si possa applicare un ***raccoglimento totale***
La formula è:  
$$
AB + AC + AD \to A(B + C + D)
$$

`Esempio`:  
$4x^3 + 8x^2 + 12x \to 4x(x^2 + 2x + 3)$  
Successivamente si può procedere a scomporre il polinomio rimasto.

\vspace{1.8cm}


## Differenza tra Due Quadrati (2 termini)
Si utilizza quando il polinomio è una differenza tra due termini che sono quadrati perfetti.  
`Formula Generale`:  
$$
A^2 - B^2 \to (A - B)(A + B)
$$
`Esempio`:  
$4x^2 - 9 \to (2x - 3)(2x + 3)$

---

## Differenza tra Due Cubi (2 termini)
Si utilizza quando il polinomio è una differenza tra due termini che sono cubi perfetti.  
`Formula Generale`:  
$$
A^3 - B^3 \to (A - B)(A^2 + B^2 + AB)
$$
**CONSIGLIO PER RICORDARE LA FORMULA**: l'elemento $A^2 + B^2 + AB$ si chiama *falso quadrato* perché appunto ricorda la formuala del *quadrato di binomio* ma **senza** il **doppio** prodotto.  
`Esempio`:  
$4x^2 - 9 \to (2x - 3)(2x + 3)$

---

## Quadrato di Binomio (3 termini)
Si utilizza quando il polinomio può essere scritto come il quadrato di un binomio.  
`Formula Generale`:  
$$
 A^2 + 2AB + B^2 \to (A + B)^2
$$


`Esempio`:  
$x^4 + 6x^2 + 9 \to (x^2 + 3)^2$

\vspace{2.5cm}

## Raccoglimento Parziale(4 termini)
Se non è possibile raccogliere un termine comune per tutto il polinomio, si cerca di raggruppare i termini in modo da applicare il raccoglimento su gruppi parziali.  
`Formula Generale`:
$$
AB + AC + DB + DC \to A(B + C) + D(B + C) \to (A + D)(B + C)
$$

`Esempio`:  
$x^3 + x^2 + 2x + 2 \to (x^2(x + 1) + 2(x + 1)) \to (x^2 + 2)(x + 1)$

---

## Cubo di Binomio (4 termini)
Si utilizza quando il polinomio può essere scritto come il cubo di un binomio.  
`Formula Generale`:  
$$
A^3 + B^3 + 3A^2B + 3AB^2  \to (A + B)^3
$$  


`Esempi`:  
$x^3 + 6x^2 + 12x + 8 \to (x + 2)^3$  
$x^3 - 6x^2 + 12x - 8 \to (x - 2)^3$

---

## Quadrato di Trinomio (6 termini)
Si utilizza quando il polinomio può essere scritto come il quadrato di un trinomio.  
`Formula Generale`:  
$$
A^2 + B^2 + C^2 + 2AB + 2AC + 2BC \to (A + B + C)^2
$$

`Esempio`:  
$x^2 + y^2 + z^2 + 2xy + 2xz + 2yz \to (x + y + z)^2$


\vspace{4cm}

# Come capire quale metodo usare
La fase più importante della scomposizione non è quella in cui si applica la formula, ma quella in cui si capisce quale formula usare e si identifica i valori di $A$, $B$, ecc...   
Ecco due esempi per familiarizzare con il processo:

---

`Esempio 1`:  
$8x^5 - 2x$

Prima di ogni cosa, bisogna applicare il **raccogliemento totale**, se possibile.  
In questo caso si può raccogliere $2x$:  
$8x^5 - 2x = 2x(4x^4 - 1)$

Abbiamo raccolto il massimo. Ora possiamo pensare alla scomposizione vera e propria.  
$4x^4 - 1$ ha **2** termini, quindi le opzioni di scomposizione sono:  

- *Differenza di due quadrati* $\to A^2 - B^2 = (A+B)(A-B)$

- *Differenza di due cubi* $\to A^3 - B^3 = (A - B)(A^2 + B^2 + AB)$

Abbiamo una differenza. $1$ può essere visto sia come il cubo di $1$ che come il quadrato di un $1$.  
Invece il termine $4x^4$ non può essere visto come un cubo di qualcos'altro, ma solo come quadrato di $2x^2$.

Quindi supponiamo di scomporre tramite *quadrato di binomio*, con:  

- $A = 2x^2$

- $B = 1$  

Verifichiamo la corrispondenza applicando la formula $A^2 - B^2$:   
$(2x^2)^2  - 1^2 = 4x^4 - 1$✅  
Ora possiamo scomporre:  
$4x^4 - 1 = (A-B)(A+B) = (2x^2 -1)(2x^2 +1)$

Quindi l'intera scomposizione è:  
$8x^5 - 2x = 2x(4x^4 - 1) = 2x(2x^2 -1)(2x^2 +1)$

\vspace{4cm}

`Esempio 2`:  
$x^6 + 6x^4 + 12x^2 - 8$

Non possiamo raccogliere nulla, quindi procediamo subito a scomporre.  
Abbiamo **4 termini**, quindi le opzioni sono:

-  *Raccoglimento Parziale*

- *Cubo di Binomio*

Di media si inizia con quello più facile, cioè il *Raccoglimento Parziale*:  
$AB + AC + DB + DC \to A(B + C) + D(B + C) \to (A + D)(B + C)$  
In pratica dobbiamo raccogliere a due a due e sperare che ciò che rimane dai due raccoglimenti sia uguale.  
Facciamo un po' di tentativi:  
$x^4(x^2 + 6) + 4(3x^2 - 2)$❌  
$x^2(x^4 + 12) + 2(3x^4 - 4)$❌  
**Non si può usare il *raccoglimento parziale***

Vediamo se è possibile utilizzare il *Cubo di Binomio*:  
$A^3 + B^3 + 3A^2B + 3AB^2  \to (A + B)^3$

Dobbiamo trovare termini che siano due cubi (i corrispettivi di $A^3$ e $B^3$):  
$x^6$ è il cubo di $x^2 \to A = x^2$  
$-8$ è il cubo di $-2 \to B = -2$  
Gli *unici* valori possibili di $A$ e $B$ sono questi perché gli altri termini non sono dei cubi; basta quindi verificare la corrispondenza degli altri termini.  
Riscriviamo il polinomio in un ordine più congeniale:  
$x^6 - 8 + 6x^4 + 12x^2$  

Verifichiamo:  
$3AB^2 = 3 \cdot x^2 \cdot (-2)^2 = +12x^2$✅  
$3A^2B = 3 \cdot (x^2)^2 \cdot (-2) = -6x^4$❌

Purtroppo non corrisponde con la formula, quindi **non si può scomporre** con i metodi tradizionali.











