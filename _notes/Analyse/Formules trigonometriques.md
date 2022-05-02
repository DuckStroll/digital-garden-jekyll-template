#man #analyse
# Propriétés
propriétés du sin
$sin(x) =sin(\pi-x)$
## Valeurs type
|     | 0   | $\pi/6$      |   $\pi/4$    | $\pi/3$      | $\pi/2$ |   $2\pi/3$   |
| --- | --- | ------------ |:------------:| ------------ |:-------:|:------------:|
| sin | 0   | 1/2          | $\sqrt{2}/2$ | $\sqrt{3}/2$ |    1    | $\sqrt{3}/2$ |
| cos | 1   | $\sqrt{3}/2$ | $\sqrt{2}/2$ | 1/2          |    0    |     -1/2     |
## Sommes d'angles
On va démontrer plusieurs formules trigonométriques à partir de 2 simples formules.
$$sin(\alpha+\beta) = sin(\alpha)cos(\beta) + sin(\beta)cos(\alpha)$$
$$cos(\alpha+\beta)=cos(\alpha)cos(\beta)-sin(\alpha)sin(\beta)$$
On démontre cela de manière geometrique --> voir Onenote
Le reste des formules trigonometriques sont des consequences de ces formules:
$tan(\alpha+\beta) = \frac{sin(\alpha+\beta)}{cos(\alpha+\beta) }=\frac{tan(\alpha)+ tan(\beta)}{1-tan(\alpha)tan(\beta)}$
$sin(2x) = 2cos(x)sin(x)$
$cos(2x)= cos^{2}(x)sin^{2}(x)=\begin{cases}
1-2sin^{2}(x) \\
2cos^{2}(x)-1
\end{cases}$
$tan(2x) =\frac{2tan(x}{1-tan^{2}(x)}$
$sin^{2}(\alpha) =(1-cos(2\alpha)/2)$
$cos^{2}(\alpha)=(1+cos(2\alpha)/2)$
## Sommes et produits
$$cos(x+y) + cos(x-y)= 2cos(x)cos(y)\rightarrow$$
$$cos(x)cos(y)=\frac{1}{2}(cos(x+y)+cos(x-y)$$
$$sin(x)sin(y=\frac{1}{2}(sin(x+y)+sin(x-y))$$
Sommes:
$$\boxed{\displaylines {cos(x+cos(y)= 2cos(\frac{x+y}{2})cos(\frac{x-y}{2})
\\
sin(x)\pm sin(y)=2cos(\frac{x+y}{2})sin(\frac{x\pm y }{2})}}$$
## Formules "magiques"
$$sin(x) =\frac{2tan(x/2)}{1+tan^{2}(x/2)} $$
$$cos(x) = \frac{1-tan^{2}(x/2)}{1+tan^{2}(x/2)}$$
$$tan(x)=\frac{2tan(x/2)}{1-tan^{2}(x/2)}$$
Ces formules sont notamment utiles pour les techniques d'[[Integration]].
_Preuve pour le cos_: 
$tan(x) =\frac{2tan(x/2)}{1-tan^{2}(x/2)}=\frac{1-cos(x)}{1+cos(x)}$
Le résultat précedant se déduit en isolant le cos.
# [[Dérivation]] des formules trigonométriques:
$sin(x)'=\underset{h \rightarrow0}{\lim} \frac{sin(x+h)-sin(x)}{h}= sin \dagger$
# (In)équations trigonometrique linéaire
cas général: $\delta cos(x) + \delta sin(x) =c$
On veut écrire nos deux deltas comme les sin et cos d'un même angle!
Si on ne peut pas montrer ça de manière évidente,
$$\frac{\delta _{1}}{\sqrt{\delta_{1}^{2}+\delta_{2}^{2}}}cos(x) + \frac{\delta _{2}}{\sqrt{\delta_{1}^{2}+\delta_{2}^{2}}}sin(x) = \frac{c}{\sqrt{\delta_{1}^{2}+\delta_{2}^{2}}}$$
Graçe à cette formule, il est possible de placer sur le cercle trigonometrique:
$\exists \alpha$ t.q.  
$sin(\alpha)cos(x) + cos(\alpha)sin(x) = \frac{c}{\sqrt{\delta_{1}^{2}+\delta_{2}^{2}}}$