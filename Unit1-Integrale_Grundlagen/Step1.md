
# 1: Das unbestimmte Integral und die Stammfunktionen

Bestimmt hast du schonmal so ein Integral gesehen:

$\int f(x) dx$

<details>
<summary>**1.1.1: Was ist das "besondere" an diesem Integral?**</summary>


Es ist unbestimmt.

Das heißt, dass es keine Grenzen hat.

Ein bestimmtes Integral würde so aussehen:

$\int_a^b f(x) dx$
 
</details>
-----

Bestimmt bist du auch schon über die Stammfunktion $F(x)$ gestolpert.


<details>
<summary><span style="color: red">1.1.2: Wie sieht der Zusammenhang zwischen der Stammfunktion und dem unbestimmten Integral oben aus?</span></summary>

$\int f(x) dx = F(X) + C$
mit $C \in \R$

Mit normalen Worten ausgedrückt die Stammfunktion ist das, was beim Integrieren rauskommt.

Du fragst dich jetzt aber bestimmt, was zum Teufel macht diese Konstante $C$ und wo kommt die her? Das klärt sich gleich als nächstes.
 
</details>
-----

Man kann sagen das Gegenteil von Addieren ist Subtrahieren, das Gegenteil von Multiplizieren ist Dividieren. Wenn man das ein wenig weiterspinnt, gibt es auch ein Gegenteil von Integrieren.


<details>
<summary><span style="color: red">1.1.3: Was ist das "Gegenteil?" von Integrieren</span></summary>

Die Differentialrechnung, auch bekannt als Ableiten.

Man kann den Zusammenhang zwischen unser Funktion $f(x)$ und der Stammfunktion $F(x)$ nämlich auch noch anders ausdrücken.

$$
F^{\prime}(x) = f(x)
$$
 
 Wieder mit normalen Worten ausgedrückt: Wenn ich die Stammfunktion ableite, muss meine ursprüngliche Funktion rauskommen.

 $\int f(x) dx = F(X) + C$ und $F^{\prime}(x) = f(x)$ sind also zwei Schreibweisen für die gleiche Sache.


</details>
-----

<details>
<summary><span style="color: red">1.1.4: Jetzt ein Praxistipp: Wie kann ich überprüfen, ob mein Ergebnis bei der Integralrechnung ist?</span></summary>

Ich leite das Ergebnis einfach schnell ab, und wenn dabei das gleiche rauskommt, das hinter dem Integralzeichen steht, hast du alles richtig gemacht.

Mein Integral und mein Ergebnis:

$\int x dx = \frac{1}{2}x^2 + C $

Und zum Überprüfen wieder ableiten:

$\frac{d}{dx}(\frac{1}{2}x^2 + C) = x$

Es kommt wieder x raus, also stimmt alles.

</details>
-----

Ja, das mit dem $C$ habe ich noch immer nicht erklärt. Das klären wir jetzt mit einem Beispiel. 


Stell dir vor wir haben zwei Stammfunktionen
$$F_1(x) = 2x +5$$
und
$$F_2(x) = 2x +13$$


Jetzt nutzen wir einen der Zusammenhänge zwischen $f(x)$ und $F(x)$, den wir schon kennen 
$$
F^{\prime}(x) = f(x)
$$

Daraus ergibt sich:

$$F_1^{\prime}(x) = 2 = f_1(x)$$

und
$$F_2^{\prime}(x) = 2 = f_2(x)$$

Wir merken, $F_1$ und $F_2$ sind zwei unterschiedliche Stammfunktionen. Sie unterscheiden sich in der Konstante, aber ihre ursprüngliche Funktion $f(x) = f_1(x) = f_2(x) $ ist die gleiche.

Man könnte jetzt sich unendlich viele Stammfunktionen ausdenken, die die gleiche ursprüngliche Funktion $f(x)$ haben, man muss nur die Konstante ändern. Und damit man alle Möglichkeiten abdeckt führt man hierzu die Konstante $C$ ein.
Und so kommt man dann auf diesen Term:
ko
$ \int f(x) dx = F(x) + C$ mit $ C \in \R
$



