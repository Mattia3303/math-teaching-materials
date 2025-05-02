---
title: "Scomposizione di Polinomi di Secondo Grado"
output: pdf_document
header-includes:
  - \usepackage{enumitem}
  - \setlist[itemize]{left=0pt}
  - \setlist[enumerate]{left=0pt}
---

# <u>Premessa</u>
La **formula generale del polinomio di secondo grado** è:
$$ax^2 + bx + c$$
 Di cui $a, b, c$ sono i **coefficienti**.  
 Se $a$ o $b$ valgono 1, allora sono sottintesi.  
 Se uno degli elementi della formula manca, vuol dire che il suo coefficiente vale 0.

`Esempio`:   
In $x^2 - 1$:
* $a = 1$
* $b = 0$
* $c = -1$

# Passaggi preliminari:

## 1. Cambiare il segno in modo da avere $a$ positivo
`Esempio`:
$$-2x^2 + 5x - 6 \to -(2x^2 - 5x + 6)$$

## 2. Ridurre ai minimi termini
`Esempio`:
$$4x^2 - 2x + 6 \to 2(2x^2 - x + 3)$$


# Scomposizione

I polinomi di secondo grado possono dividere in due sottogruppi:
- `incompleti`, se almeno uno tra $b$ e $c$ è nullo
- `completi`, se $a \neq 0, b \neq 0$ e $c \neq 0$


## Formula Incompleta
### Pura ($b=0$)
$$ax^2 + c$$
- Se $c < 0$
    Si può applicare la differenza di due quadrati:  
    $A^2 - B^2 = (A-B)(A+B)$

    `Esempio`:  
    $x^2 - 1 \to (x -1)(x + 1)$  
    $4x^2 - 3 \to (2x + \sqrt3)(2x - \sqrt3)$
- Se $c > 0$  
    Il binomio **<u>non</u> è scomponibile** (ed è sempre posivivo)

### Spuria ($c = 0$)
$$ax^2 + bx$$

Si raccoglie la x:  
$ax^2 + bx \to x(ax +b)$



## Formula Completa
$$ax^2 + bx + c$$

### 1. Verificare se è uno sviluppo di quadrato di binomio
La formula di scomposizione è:  
$A^2 + 2AB + B^2 = (A + B)^2$

Prendiamo come esempio  
$4x^2 - 4x \sqrt 3 + 3$

I due quadrati presenti nella formula($A^2$ e $B^2$) dovranno essere cercati nei termini $ax^2$ e $c$.  
Nel nostro esempio quindi dobbiamo verificare che $4x^2$ e $+3$ siano i quadrati di qualche valore.  
Si ricorda che un numero che non è un quadrato perfetto può essere in ogni caso visto come il quadrato della sua radice.  
Ad esempio $3 \to \sqrt 3$

Quindi l'unico controllo che bisogna fare è che $c$ ($+3$ nel nostro caso) sia **positivo**, in alternativa è **impossibile** che scomporlo come quadrato di binomio.  
Ora possiamo trovare i valori di $A$ e $B$:  
$A = 2x$  
$B = \sqrt 3$  
Tuttavia non siamo certi del segno di A e B, perché sappiamo che il quadrato di un numero negativo diventa positivo, quindi sia A che B possono avere sia segno positivo che negativo  
$A = \pm 2x$   
$B = \pm \sqrt 3$  
Il segno di A si prende sempre quello positivo, mentre quello di B deve essere lo stesso del termine $2AB$, corrispondente a $bx$  
Nel nostro caso quindi:  
$A = 2x$   
$B =- \sqrt 3$ (meno perché è il segno di $-4x \sqrt 3$)  

Ora l'unica cosa da verificare è la corrispondenza tra i termini $2AB$ e $bx$
Cioè, nel nostro esempio, verificare che  
$2AB = 2 \cdot (2x) \cdot (- \sqrt 3) = bx = -12x$  
$2(2x)(- \sqrt 3) = -4x \sqrt 3$✅

Abbiamo quindi la conferma che il trinomio si può scomporre come quadrato di binomio. Ora basta applicare la formula di scomposizione conoscendo i valori di A e B:  
$A^2 + 2AB + B^2 = (A+B)^2 = (2x -\sqrt 3)^2$

---
### 2. Metodo Somma Prodotto
Il metodo si può applicare **solo** se si ha un <u>*trinomio speciale*</u>, cioè se il coefficiente $a$ di $x^2$ è 1. Consideriamo il trinomio nella forma:
$$x^2 + sx + p$$  
Se si trovano due numeri $a$ e $b$ tali che la loro somma dia $s$ e il loro prodotto dia $p$ ($a + b = s$ e $a \cdot b = p$), allora si può scomporre il trinomio in:  
$$x^2 + sx + p = (x + a)(x + b)$$

`Esempio con Trucco`:  
$x^2 -3x - 10$

Possiamo applicare il metodo perché $a=1$.  
Dobbiamo trovare due numeri $a$ e $b$ tali che $a+b = -3$ e $a \cdot b = -10$.  
Si parte dal prodotto che deve fare $-10$.  
Cerchiamo tutte le coppie di numeri che moltiplicati tra di loro danno $10$, dimenticandosi per un attimo del segno negativo:  
$1$ e $10$  
$5$ e $2$  
Pensiamo ora per ogni coppia se la loro differenza o somma danno $3$ (dimenticandosi ancora una volta del segno negativo):  
$10 - 1 = 9$❌ e $10+1 = 11$❌: non è la coppia giusta  
$5 + 2 = 7$❌ e $5-2 = 3$✅: è potenzialmente la coppia giusta  
Ora vanno decisi i segni di $5$ e $2$ per far si che la loro somma dia $-3$ e il prodotto $-10$.  
Dato che il prodotto ha segno $-$, le combinazioni sono:  
$a=5$ e $b = -2$  
$a=-5$ e $b = 2$  
L'unica coppia la cui somma $a+b$ è uguale a $-3$ è $a=-5$ e $b = 2$.  
Quindi possiamo scomporre:  
$x^2 -3x - 10 = (x - 5)(x + 2)$

---
### 3. Metodo Somma Prodotto Esteso
Se abbiamo un trinomio su cui non possiamo applicare il metodo somma prodotto perché $a \neq 1$, possiamo però utilizzare una sua variante.  
Consideriamo:  
$$ax^2 + sx + p$$

Dobbiamo trovare due numeri $n_1$ e $n_2$ tali che:  
$n_1 + n_2 = s$  
$n_1 \cdot n_2 = ap$

Trovati i due numeri, riscrivo il trinomio nella forma:  
$ax^2 + n_1x + n_2x + p$

Infine applico il ***raccoglimento parziale***.

`Esempio`:  
$6x^2 + 11x+ 3$    
I due numeri sono:  
$n_1 = 9$  
$n_2 = 2$  
Infatti  
$n_1 + n_2 = 9 + 2 = s = 11$✅  
$n_1 \cdot n_2 = 9 \cdot 2 = ap = 18$✅

Riscriviamo il trinomio come:  
$6x^2 + 9x + 2x + 3$  
Applichiamo il raccoglimento parziale:  
$6x^2 + 9x + 2x + 3 = 3x(2x + 3) + 1(2x+3) = (2x +3)(3x +1)$  

---
### 4. Applicare la formula risolutiva:
$$
x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
Dopo aver trovato le due soluzioni $sol_1$ e $sol_2$, si scompone in:  
$$
(x - sol_1)(x - sol_2) 
$$

**Attenzione**:
Se applicando la formula l'argomento della radice risulta *negativo*, allora il polinomio è **sempre positivo** e quindi <u>**non scomponibile**</u>





