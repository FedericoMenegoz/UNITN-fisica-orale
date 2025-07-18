---
title: "Forza Gravitazionale"
counter: 0
---

# Forza Gravitazionale
## Legge di gravitazione universale


> Date due masse $m_1$ e $m_2$ qualsiasi, di dimensioni trascurabili rispetto alla distanza mutua, tra di esse agisce una forza attrativa diretta lungo la retta che congiunge le due masse, il cui modulo dipende dal prodotto delle due masse ed è inversamente proporzionale al quadrato della distanza 
>
<a id="legge-di-gravitazione"> </a>

>$$
\vec F_{1,2} = -\gamma\frac {m_1m_2}{r^2} \hat r_{1,2}
$$

<img alt="legge di gravitazione" src="../imgs/forza-gravitazionale-00_Legge.png" width="500">


Considero un grave qualsiasi sulla superficie terrestre e applico la seconda legge della dinamica:

$$
\large
\begin{cases}
    \vec F = m \vec a = m_i g \hat r\\
    \vec F = \gamma \frac {m_gM_T}{r^2} \hat r  
\end{cases} \quad \Rightarrow \quad m_ig = \gamma\frac {m_gM_T}{r^2}
$$

<a id="massa-inerziale-gravitazionale"></a>

- $m_g$ e $m_i$ anche se sono riferite allo stesso corpo, non sono concettualmente la stessa cosa:
    - la __masssa gravitazionale__: caratteristica del un corpo di attrarre e essere attratto secondo la legge di gravitazione universale
    - la __massa inerziale__: caratteristica del corpo a resistere al cambiamento del proprio stato di moto quando sottoposto a una forza
    - il loro rapporto $\frac{m_i}{m_g} = \frac {M_T}{r^2 g}$ è una costante indipendentemente, dalla natura del corpo quindi loro sono perlomeno proporzionali e per questo caso di studio si può suppore che siano uguali e che il loro rapporto sia uguale a 1 cioè $m_i = m_g$
- il grave avrà una distanza nell'ordine di una decina di metri dalla superficie della Terra ed il raggio della terra è di circa $6.378 \cdot 10^6 m$ (10 metri sono trascurabili rispetto a 6 milioni di metri) quindi $$r\approx R$$
- il raggio della terra era stato calcolato già al tempo degli egizi da [Eratostene](https://www.roma1.infn.it/exp/webmqc/Il%20metodo%20di%20Eratostene.pdf)
- $\large \gamma$ è la __costante gravitazionale universale__ misurata sperimentalmente da __Cavendish__ tramite l'utilizzo di una bilancia di torsione e vale $$\gamma = 6.67 \cdot 10^{-11} \bigg[\frac {m^3}{kg\,s^2} = \frac {Nm^2}{kg^2}\bigg]$$


> La massa della Terra quindi può essere calcolata a partire dalle assunzioni appena fatte come:
>
>$$M_T = \frac{g R^2}\gamma$$


---
## domande
{% assign counter = page.counter | plus: 1 %}

##### {{ counter }}) Forza di gravità. Cos’è il versore che appare nell'equazione? È una forza fondamentale? Si enunci qualche effetto macroscopico della forza di gravità. La massa della forza peso è la stessa che compare nell’equazione della forza di gravità?

Data l'[equazione](#legge-di-gravitazione)
###### a) Cos'e $\hat r_{1,2}$?
Il versore $\hat r_{1,2}$ è quel versore che ha direzione sulla retta che congiunge le due masse e verso dalla massa 1 alla massa 2. Il segno meno nell’equazione indica che la forza è attrattiva, quindi agisce in direzione opposta al versore (cioè dalla massa 2 verso la massa 1).
###### b) E' una forza fondamentale?
Si la forza gravitazionale è una delle quattro forze fondamentali della natura (insieme alla forza elettromagnetica, nucleare forte e nucleare debole).
###### c) Si enunci qualche effetto macroscopico della forza di gravità.
- la __caduta dei gravi__ sulla Terra
- il __moto orbitale__ della luna attorno alla terra
- la possibilità di misurare la costante gravitazionale $\gamma$ (esperimento di Cavendish con una bilancia di torsione)

###### d) La massa della forza peso è la stessa che compare nell’equazione della forza di gravità?

Vedi [qui](#massa-inerziale-gravitazionale).


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Se fossimo in orbita, ma poi siamo fermi e ci lasciano cadere verso la terra dentro uno scatolone, avremmo una sensazione del peso?


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Ci lanciano da un’astronave verso la terra dentro uno scatolone chiuso. Si avvertono variazioni nella propria sensazione di peso?

---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Legge di gravitazione universale. Se ho in un cesto quattro laptop in un cesto e quattro laptop in un altro cesto, e sposto due laptop nell’altro cesto, come cambia la forza?

---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Energia potenziale gravitazionale. Ragionamento molto lungo su questo.



