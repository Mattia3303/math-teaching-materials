# Scomposizione Polinomi con Grado Superiore al primo
## <u>Premessa</u>
I vari metodi vengono descritti con formule generali, che usano simboli come $A$ e $B$ per indicare termini generici, sia *letterali* sia *numerici*.  
Per verificare quale metodo usare, bisogna analizzare il polinomio da scomporre e notare se corrisponde ad una delle formule indicate nei metodi; successivamente si può applicare la formula di scomposizione.  
Si ricorda che le lettere generiche $A$, $B$...ecc possono avere anche segno negativo.  
Inoltre ricorda che se un elemento di una formula ha forma $AB$, si intende che può essere visto come la moltiplicazione tra due termini:  
`Esempio`  
Se ho $8x^2$, esso può essere visto come:
- $8 \cdot x^2$
- $4 \cdot 2x^2$
- $-2x \cdot (-4x)$
- $ \frac{x^2}{2} \cdot 16$
- *ecc...*


## Raccoglimento Totale
Raccogliere il termine comune tra tutti gli elementi del polinimio.  
$$
AB + AC + AD \to A(B + C + D)
$$

`Esempio`:  
$$
4x^3 + 8x^2 + 12x \to 4x(x^2 + 2x + 3)
$$

---

## Raccoglimento Parziale
Se non è possibile raccogliere un termine comune per tutto il polinomio, si cerca di raggruppare i termini in modo da applicare il raccoglimento su gruppi parziali.  
`Formula Generale`:
$$
AB + AC + DB + DC \to A(B + C) + D(B + C) \to (A + D)(B + C)
$$

`Esempio`:  
$$
x^3 + x^2 + 2x + 2 \to (x^2(x + 1) + 2(x + 1)) \to (x^2 + 2)(x + 1)
$$

---

## Quadrato di Binomio
Si utilizza quando il polinomio può essere scritto come il quadrato di una somma o di una differenza.  
`Formula Generale`:  
$$
 A^2 + 2AB + B^2 \to (A + B)^2
$$


`Esempio`:  
$$
x^4 + 6x^2 + 9 \to (x^2 + 3)^2
$$

---

## Differenza tra Due Quadrati
Si utilizza quando il polinomio è una differenza tra due termini che sono quadrati perfetti.  
`Formula Generale`:  
$$
A^2 - B^2 \to (A - B)(A + B)
$$

`Esempio`:  
$$
4x^2 - 9 \to (2x - 3)(2x + 3)
$$

---

## Metodo di Ruffini
Si utilizza per scomporre un polinomio di grado maggiore al secondo, dividendo il polinomio per un binomio del tipo $(x - r)$, dove $r$ è una radice del polinomio.  
`Passaggi`:
1. Individuare una radice del polinomio, $r$, tale che $P(r) = 0$.
2. Applicare la divisione sintentica (o schema di Ruffini).  
3. Il polinomio $P(x)$ si scompone come:
   $$
   P(x) = (x - r) \cdot Q(x)
   $$
   Dove $Q(x)$ è il quoziente ottenuto dalla divisione.

`Esempio`:  
**Polinomio**: $P(x) = x^3 - 6x^2 + 11x - 6$  
**Radice**: $r = 1$ (poiché $P(1) = 0$)

**Divisione sintetica:**
$$
\begin{array}{r|rrr}
1 & 1 & -6 & 11 & -6 \\
  &   & 1  & -5 & 6  \\
\hline
  & 1 & -5 & 6  & 0  \\
\end{array}
$$

**Risultato**:  
$$
P(x) = (x - 1)(x^2 - 5x + 6)
$$






