# Dinamica
## Secondo principio della dinamica 
Gurda [risposta](#1-si-enunci-e-si-commenti-la-seconda-legge-della-dinamica-unità-di-misura-sono-grandezze-scalari-o-vettoriali).
## Forza d'attrito
### Forza d'attrito radente
Sperimentalmente si osserva che quando si applica ad un corpo appoggiato su di un piano orizzontale una forza parallela al piano, il corpo rimane fermo fino a che la forza non supera in modulo un certo valore:

$$F < \mu_sN$$
Definiamo $\mu_s$ come __coefficiente di attrito statico__ (adimensionale) che è dovuto alle forze di coesione tra il corpo e il piano in particolare: 
$$ 
\begin{cases}
quiete && F \le \mu_s N \\
moto && F > \mu_s N \\
\end{cases}
$$

Quando in quiete la risultante delle forze deve essere nulla:
$$ \vec R + \vec F + \vec P = 0$$

- $\vec R$ __reazione vincolare__ del piano con $\vec N$ sua componente verticale $N = mg$ e $\vec F_{as}$ sua componente orizzontale $F_{as} = F$
- $\vec P$ __forza peso__ del corpo

>Quindi il valore della forza di attrito statico non ha un valore prefissato, ma varia con il variare della forza $\vec F$ applicata, fino a che quest'ultima non supera in modulo $\mu_s N$.

### Forza d'attrito dinamico
Dal momento in cui la forza $\vec F$ supera $\mu_s N$ in modulo allora si osserva che si oppone al moto un'altra forza, detta __forza di attrito radente dinamico__:
$$F_{ad} = \mu_d N$$
dove $\mu_d$ è detto __coefficiente di attrito dinamico__ e risulta sempre che 
$$\mu_d < \mu_s$$

La risultante delle forze ortogonali al piano è nulla, quindi possiamo dedurre che la forza d'attrito dinamico ha stessa direzione e verso contrario al versore della velocità $\hat u_v$: 
$$ \vec F_{ad} = - \mu_d N \hat u_v$$

In natura eliminare l'attrito per due materiali in contatto è impossibile, per quanto si possa comunque ridurre. Quindi per mantere un corpo in un moto rettilineo uniforme bisogna applicare una forza eguale e contraria alla forza d'attrito.

## Tensione e Carrucola
## Forza elastica

Prendiamo una molla attaccata ad un muro, la molla è orizzontale al piano su cui è adagiata, non ci sono attriti e all'estremità della molla è presente una massa puntiforme $m$, il sistema è a riposo. Fissiamo l'origine nel punto in cui la massa si trova a riposo. Ora allunghiamo la molla di una certa lunghezza $x$ per poi rilasciarla, si osserverà che la massa inizierà a oscillare periodicamente attorno all'origine: partendo dalla posizione $x$, passerà per l’equilibrio, raggiungerà la posizione $-x$, e poi tornerà indietro seguendo lo stesso percorso. Questo comportamento suggerisce che il moto possa essere descritto da una funzione sinusoidale.

Utilizzando la legge Hook's law abbiamo che:
$$\vec F = - kx$$
Sappiamo anche che $$\vec F = m\vec a = \frac {d^2x}{dt}$$
quindi otteniamo la seguente equazione differenziale:
$$\frac {d^2x}{dt} = - \frac km x$$
Per risolverla appunto utilizziamo l'intuizione che il moto descrive una sinusoide:
$$x(t) = A\sin(\omega+ \phi)$$
$$v(t)=\frac {dx}{dt} = \omega A\cos(\omega+ \phi)$$
$$a(t) = \frac {d^2x}{dt} = - \omega^2 A\sin(\omega+ \phi)$$
da cui possiamo dire che $$\omega^2 = \frac k m$$


## Piano inclinato
## Pendolo

### Descrizione

Il pendolo semplice è costituito da un punto materiale appeso tramite filo ideale. Filo ideale significa che è inestensibile e non ha massa. 

Le forze che entrano in gioco nel pendolo semplice sono la forza peso $\vec F_p = m\cdot \vec g$ e la tensione del filo $\vec T$.

Un ottimo sistema di riferimento per questa situazione è quello di utilizzare l'asse concorde con il filo __asse normale__ alla traiettoria e l'__asse tangenziale__ alla traiettoria.

In questo modo possiamo scomporre le forze negli assi:$$\begin{cases} 
\vec R_N = \vec F_{PN} + \vec T = m\vec g \cdot \cos (\theta) + \vec T  \\ 
\vec R_T = \vec F_{PT} = m\vec g \cdot \sin (\theta) \\
\end{cases}$$
### Asse tangenziale
Secondo la seconda legge della dinamica nell'asse tangenziale si ottiene:
$$-m g \cdot \sin (\theta) = ma_T $$
l'accelerazione: 
$$a_T = \frac{dv}{dt}$$

con$$v = \omega R$$
$$a_T = \frac{dv}{dt} = l \frac{d\omega}{dt} = lm\frac{d^2\theta}{dt}$$
quindi si ottiene: $$-\cancel mg\sin(\theta) = \cancel ml\frac{d^2 \theta}{dt} \quad \Rightarrow \quad \frac{d^2\theta}{dt} + \frac l g \sin(\theta) = 0$$
A questo punto la risoluzione di questa equazione differenziale risulta difficile, ma se consideriamo piccole oscillazioni ($< 10° \sim 0.17\;rad$) e ricordando che per lo sviluppo di Taylor $$\sin \theta = \theta - \frac{\theta^3}{3!} + \frac{\theta ^5}{5!} - \cdots$$ possiamo approssimare $\sin \theta$ a $\theta$ con un errore dello $0.5\%$. $$err = \bigg|\frac{\theta^3/3!}{\theta}\bigg|\cdot 100 = 0.5 \% $$
Quindi otteniamo l'equazione differenziale del moto armonico: $$\frac{d^2\theta}{dt} + \frac l g \theta = 0$$
$$\theta(t) = \theta_i \sin\bigg(\sqrt{\frac{l}{g}}t + \phi\bigg)$$
$$s(t) = l \theta_i \sin\bigg(\sqrt{\frac{l}{g}}t + \phi\bigg)$$
### Asse normale
Applicando la seconda legge sull'asse normale invece si ottiene: $$R_N = T - mg\cos(\theta) = ma_N$$
$$a_N = \frac{v^2}l = \omega^2 l$$
$$T = m (g\cos(\theta) + \omega^2 l)$$

Quindi la tensione del filo sarà massima con $\theta = 0$ e sarà minima nel punto più alto dell'oscillazione.


## Domande
##### 1) Si enunci e si commenti la seconda legge della dinamica. Unità di misura? Sono grandezze scalari o vettoriali?

La seconda legge della dinamica detta anche __seconda legge di Newton__ è definita come

$$\vec F = m \vec a = m\frac{d\vec v}{dt} = m \frac {d^2 \vec s}{dt^2}$$

>L'interazione del punto con l'ambiente circostante, espresso tramite la __forza__ $\vec F$, determina l'accelerazione del punto, ovvero la variazione della sua velocità nel tempo, secondo un fattore di proporzionalità $m$ che è la __massa inerziale__ del corpo.

Si dice __massa inerziale__ perché esprime l'inerzia del corpo, cioè la sua resistenza a variare il suo stato di moto, cioè a modificare la sua velocità in modulo, direzione o verso.

Definita la quantità di moto come 

$$\vec p = m\vec v$$

allora un'altra formulazione più generale della seconda legge di Newton

$$\vec F = \frac {d\vec p}{dt}$$

>L'azione di una __forza__ determina la variazione nel tempo della quantità di moto, ovvero di qualcuna o di tutte queste quantità: __massa__ del corpo, __direzione__, __verso__, __modulo__ della velocità.


- todo: definizione impulso da $\vec Fdt =d\vec p$ 

<br>

---
<br>

##### 2) Un proiettile sta procedendo parallelamente al suolo, la sua quota è invariata e la sua velocità diminuisce; si commenti la situazione con la 2° legge della dinamica
<br>
Se il proiettile sta proseguendo parallelamente al suolo, mantenendo quota costande, ma con velocità in diminuzione, significa che il corpo ha un'accelerazione opposta al vettore velocità.

Per la seconda legge della dinamica:

$$
\vec R = m\vec a=m\frac {d\vec v}{dt}
$$

Questo significa che la risultante delle forze agenti sul corpo ha la stessa direzione del moto ma con verso opposto e modulo proporzionale alla decelerazione. 

Poiché il proiettile non perde quota, la forza peso $m\vec g$ deve essere bilanciata da un'altra forza con componente verticale uguale e contraria.


---

##### 3) Le forze di attrito sono sempre..? _hint: Opposte alla direzione del moto_
<br>

---

##### 4) Appendiamo un corpo al soffitto con una molla. Cosa succede?
<br>

---

##### 5) Cos’è la statica? _hint Su un corpo possono agire più forze_
<br>

---

##### 6) Parli dell’attrito statico
<br>

---

##### 7) Reazioni vincolari, nel modo più generico che conosci
<br>

---

##### 8) Ho una pallina che cade (in acqua? su un pavimento?) e dopo un po’ si ferma. Cosa è successo? Se volessimo scrivere un bilancio energetico?
<br>

---

<a id="dinamica-domanda-9"></a>

##### 9) Sensazione del peso: entriamo in un ascensore con una bilancia e saliamo, cosa succede? 
<br>

---

##### 10) Domanda di [prima](#dinamica-domanda-9) ma su un vagone di un treno in viaggio
<br>

---

##### 11) Terzo principio della dinamica. Se considero un sistema che prevede delle forze di reazione, mi fanno escludere a priori che il sistema sia isolato, oppure non è vero? La legge vale sempre? Quando un sistema si dice isolato?
<br>

---

##### 12) Funi inestensibili.
<br>

---

##### 13) Appendiamo una molla al soffitto con a un estremo un corpo di massa m.
<br>

---

##### 14)  Forza di attrito statico.
<br>

---

##### 15) Cos’è la quantità di moto?
<br>

---

##### 16)  Ha a disposizione una bilancia, come può misurare il tempo sapendo solo massa e lunghezza. _hint moto armonico del pendolo_
<br>

---

##### 17) Quali sono le forze fondamentali della natura?

Le forze fondamentali della natura sono riconducibili all'interazione [Gravitazionale](./forza-gravitazionale.md), l'interazione Elettromagnetica, a livello nucleare e subnucleare ci sono l'interazione Forte e l'interazione Debole

---



