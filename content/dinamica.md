# Dinamica
{{ page.counter }}
## Secondo principio della dinamica 
Gurda [risposta](#1-si-enunci-e-si-commenti-la-seconda-legge-della-dinamica-unità-di-misura-sono-grandezze-scalari-o-vettoriali).

## Terza legge di Newton (principio di azione e reazione)

> - se un corpo <span class="color">__A__</span> esercita su un corpo <span class="color">__B__</span> una forza $\vec F_{A\rightarrow B}$, allora il corpo <span class="color">__B__</span> eserciterà una forza $\vec F_{B\rightarrow A}$ su <span class="color">__A__</span>
> - le due forze hanno stessa direzione, stesso modulo e hanno verso opposto
> $$\vec F_{A\rightarrow B} = - \vec F_{B\rightarrow A}$$
> - le due forze hanno la stessa retta d'azione
> 


## Forza d'attrito radente
### Forza d'attrito statico
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

Si definisce __forza elastica__ una forza con direzione costante, con verso sempre rivolta a una posizione di equilibrio, e con modulo proporzionale alla distanza dal'equilibrio.

Se assumiamo come asse $x$ la direzione della forza allora possiamo scrivere la __legge di Hooke__:
$$\vec F_{el} = -k\,x\,\hat u_x$$
In cui $k>0$ è la costante elsastica $\big[\frac N m\big]$ e il segno negativo indica che la forza è di __richiamo__ (cioè diretta verso l'equilibrio).

### Molla
Consideriamo una molla attaccata ad un muro, la molla è orizzontale al piano su cui è adagiata, non ci sono attriti e all'estremità della molla è presente una massa puntiforme $m$, il sistema è a riposo. 

Fissiamo l'origine nel punto in cui la massa si trova a riposo. Ora allunghiamo la molla di una certa lunghezza $x$ per poi rilasciarla, si osserverà che la massa inizierà a oscillare periodicamente attorno all'origine: 
- passa per la posizione di equilibrio
- raggiunge la posizione opposta $-x$
- torna indietro ripetendo ciclicamente il moto

Questa periodicità suggerisce che il moto possa essere descritto da una funzione sinusoidale.

Sapendo che la forza elastica e definita come (Hook's law):

$$\vec F = - kx$$

E applicando la seconda legge della dinamica

$$\vec F = m\vec a = m\frac {d^2x}{dt}$$

Eguagliando si ottiene

$$\frac {d^2x}{dt} = - \frac km x$$

Notiamo che ponendo $\sqrt{\frac k m} = \omega$ otteniamo la legge del [moto arominico](cinematica.md#moto-armonico-semplice)
$$\frac {d^2x}{dt}  + \omega^2 x = 0$$

I valori dell'ampiezza $A$ e la fase iniziale $\phi$ si calcolando dalle condizioni iniziali:
$$x_0 = A\sin(\phi) \quad \quad 0 = \omega A \cos(\phi)$$
- todo condizioni iniziali con $v_0\ne0$


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

##### 3) Le forze di attrito sono sempre..? 

Come specificato [qui](#forza-dattrito-radente), le forze d'attrito sono sempre opposte al moto.

---

##### 4) Appendiamo un corpo al soffitto con una molla. Cosa succede?

Quando una __molla__ è fissata al soffitto e vi appendiamo una massa $m$, la situazione è simile al caso orizzontale, ma la _posizione di equilibrio_ è diversa perché è presente anche la __forza peso__:

$$mg = kx_0 \quad \Rightarrow \quad x_0 = \frac {mg}k$$

Quindi la nuova posizione di equilibrio si troverà più in basso rispetto alla lunghezza della molla a riposo senza massa o posizionata orizzontalmente.

Valutiamo due casi:
###### a) Rilascio il corpo esattamente nella posizione di equilibrio
Il sistema rimane a riposo, in particolare abbiamo che secondo la seconda legge della dinamica: 

$$\vec R = m\vec a = \vec 0$$

con 

$$\vec R = \vec P + \vec F_{el} = \vec 0 \quad \Rightarrow \quad  mg = kx_0$$

###### b) Rilascio il corpo non dalla posizione di equilibrio
Rilasciando il corpo in una posizione diversa da $x_0$ la risultante delle forze richiamerà il corpo verso $x_0$ risultando così in un moto armonico semplice.

Poniamo l'origine su $x_0$ e $\Delta x$ il discostamento dall'equilibrio, sappiamo che il moto rispetta la legge del [moto armonico semplice](cinematica.md#moto-armonico-semplice):

$$x(t) = A\sin(\omega t + \phi)$$

$$\begin {cases}
x(0) = \Delta x = A \sin(\phi) \\
v_0 = 0 = \omega A\cos(\phi) \\
\end{cases} \Rightarrow  
\begin {cases}
A = \Delta x && \phi = \frac \pi 2 \\
A = -\Delta x && \phi = \frac {3\pi} 2 \\
\end{cases} 
$$


---

##### 5) Cos’è la statica? _hint Su un corpo possono agire più forze_

Secondo la __prima legge della dinamica__ (principio di inerzia), un corpo: 
- rimane in moto rettilineo uniforme o
- in rimane in quiete ($v = 0$) 

finché la risultante delle forze esterne che agiscono su di esso è __nulla__.

Un corpo è in __equilibrio statico__ quando la sommatoria delle forze agenti su di esso si bilanciano esattamente, quindi la risultante è nulla: 

$$
\sum_i \vec F_i = \vec 0 \rightarrow \begin{cases}
F_x = \sum_i F_{i,x} = 0 \\
F_y = \sum_i F_{i,y} = 0 \\
F_z = \sum_i F_{i,z} = 0 \\
\end{cases}
$$

Perciò avendo la forza nulla, per il secondo principio della dinamica:

$$ \vec a = \frac {\vec F_{tot}}m = \vec 0$$
il corpo rimane fermo, o non cambia di velocità.



---

##### 6) Parli dell’attrito statico
Vedi [attrito statico](#forza-dattrito-statico).

---

##### 7) Reazioni vincolari, nel modo più generico che conosci

Come dice il termine le reazioni vincolari dipendono da un __vincolo__. In accordo con il [principio di azione e reazione](#terza-legge-di-newton-principio-di-azione-e-reazione) quando un corpo esercita una forza su un vincolo questo vincolo eserciterà sul corpo una forza uguale e contraria.

In generale la reazione vincolare non si può conoscere a priori, ma va analizzata caso per caso andando a valutare il sistema fisico e il moto del corpo.

Le reazioni vincolari possono bilanciare le forze agenti sul corpo in un sistema in equilibrio, oppure vincolare la traiettoria del corpo. 

---


---

<a id="dinamica-domanda-9"></a>

##### 9) Sensazione del peso: entriamo in un ascensore con una bilancia e saliamo, cosa succede? 


---

##### 10) Domanda di [prima](#dinamica-domanda-9) ma su un vagone di un treno in viaggio


---

##### 11) Terzo principio della dinamica. Se considero un sistema che prevede delle forze di reazione, mi fanno escludere a priori che il sistema sia isolato, oppure non è vero? La legge vale sempre? Quando un sistema si dice isolato?


---

##### 12) Funi inestensibili.


---

##### 13) Appendiamo una molla al soffitto con a un estremo un corpo di massa m.


---

##### 14)  Forza di attrito statico.


---

##### 15) Cos’è la quantità di moto?


---

##### 16)  Ha a disposizione una bilancia, come può misurare il tempo sapendo solo massa e lunghezza. _hint moto armonico del pendolo_


---

##### 17) Quali sono le forze fondamentali della natura?

Le forze fondamentali della natura sono riconducibili all'interazione [Gravitazionale](./forza-gravitazionale.md), l'interazione Elettromagnetica, a livello nucleare e subnucleare ci sono l'interazione Forte e l'interazione Debole

---



