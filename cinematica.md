# Cinematica
## Moti su un piano
todo
## Pulsazione e frequenza
La pulsazione $\omega$ è la velocità con cui viene effettuata un'oscillazione nel moto armonico $$\omega = \frac {2\pi}T$$ con $T$ periodo del moto.
La frequenza determina determina invece quante oscillazioni vengono fatte al secondo: $$f = \frac 1 T = \frac \omega{2\pi}$$
## Moto parabolico

## Moto circolare
### Non uniforme
### Uniforme
## Moti su traiettoria curvilinea
Per descrivere il moto su una traiettoria curvilinea possiamo utilizzare anche una sola coordinata, fissata l'origine arbitraria sulla traiettoria, possiamo utilizzare un'__ascissa curvilinea__ che altro non è che la lunghezza del tratto di traiettoria dall'origine.

Quindi conoscendo la traiettoria, possiamo descrivere completamente il moto tramite questa ascissa curvilinea. 

L'incremento infinitesimo del raggio vettore $d\vec r$ ha direzione tangente alla curvatura nel punto P e in modulo sarà uguale allo spostamento infinitesimo $ds$ (arco di curva del percorso): $$d\vec r = ds \cdot \vec u_T$$
Possiamo pensare quindi al moto come una successione di spostamenti rettilinei infinitesimi con direzione variabile. La velocità diventa: $$\vec v= \frac {d \vec r}{dt} = \frac {ds}{dt}\cdot \vec u_T = v \cdot u_T$$
Si noti che questo è vero solo a livello infinitesimo, se andiamo a considerare uno spostamento finito avremo che $\Delta \vec r$ rappresenta la corda, mentre $\Delta \vec s$
rappresenta l'effettiva lunghezza del tratto di curvatura.

L'accelerazione avrà due componenti, una che influirà sul modulo della velocità e una sulla sua direzione:
$$\vec a = \frac {d\vec v}{dt} = \frac{d}{dt}(v\cdot \vec u_T) = \frac{dv}{dt}\vec u_T + v \frac{d \vec u_T}{dt} = \frac{dv}{dt}\vec u_T + v \frac{d\theta}{dt}\vec u_N$$

> Ma perché abbiamo che $$\frac{d\vec u_T}{dt} = \frac{d\theta}{dt}\vec u_N$$ ? 
> A livello geometrico abbiamo che $\vec u(t)$, $\vec u(t + \Delta t)$ e $d\vec u$ formano un triangolo isoscele, con $\Delta t \rightarrow 0$ si ha che $\theta \rightarrow 0$, con $\theta$ l'angolo al centro di curvatura. Questo significa che gli altri due angoli tendono a $\frac \pi 2$. Possiamo però provarlo matematicamente, considerando che $||\hat u|| = 1$  perché è un versore quindi anche il prodotto scalare $\hat u \cdot \hat u = ||\hat u||^2 = 1$. Quindi la derivata del prodotto scalare del versore con se stesso è costante perciò la sua derivata è zero:
> $$\frac{d(\hat u \cdot \hat u)}{dt} = 0$$
> Si applica la regola della derivazione per il prodotto scalare:
> $$\frac{d(\hat u \cdot \hat u)}{dt} =\frac{d\hat u}{dt} \cdot \hat u + \hat u \cdot \frac{d\hat u}{dt}  = 2 \hat u \cdot \frac{d\hat u}{dt} =0$$
> Si vede dall'ultima uguaglianza che $\hat u \perp d\hat u$.
> Per il modulo invece sappiamo che l'arco è uguale al raggio per l'angolo da cui per valori infinitesimi in cui la corda si confonde con l'arco abbiamo che: $$du = ||u(t)|| \cdot d\theta = d\theta $$
> Infine:$$\frac{d\hat u}{dt} = \frac{d\theta}{dt}\hat u_N$$

Il termine $v \frac{d\theta}{dt}\vec u_N$ determina quanto velocemente cambia direzione la velocità, in termini infinitesimi le rette normali alla traiettoria si incontreranno in un punto che coincide con il centro di una circonferenza tangente alla traiettoria in quel punto, esso viene chiamato __centro di curvatura__ della traiettoria nel punto P. Al variare del punto P il centro di curvatura e quindi anche il __raggio di curvatura__ cambiano. 
L'arco di traiettoria $ds = R \cdot d\theta$ con $R$ raggio di curvatura:
$$\frac{d\theta}{dt} = \frac{d\theta}{ds} \frac {ds}{dt} = \frac{1}{R} v$$
Sostituendo otteniamo:
$$\vec a = \frac{dv}{dt}\vec u_T + \frac{v^2}{R}\vec u_N$$

### TODO 
- traduzione in coordinate cartesiane nel piano

## Moto Armonico Semplice
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
Una condizione sufficiente affinché un moto sia armonico è che l'accelerazione del corpo sia proporzionale e di verso opposto allo spostamento rispetto alla posizione di equilibrio, indicando la presenza di una forza di richiamo (o forza restauratrice) che tende a riportare il corpo verso tale posizione.

Studiamo ora il moto:
$$x(t) = A\sin (\omega t + \phi)$$
### Ampiezza moto
$A$ è l'__ampiezza del moto__, in effetti sappiamo che la funzione $\sin$ ha come estremi $1$ e $-1$ quindi il punto percorre un segmento lungo $2A$ con centro nell'origine, il punto si sposta dall'origine di un massimo $A$.

### Periodo
Sappiamo che la funzione seno è periodica con periodo $2\pi$. Quindi se consideriamo due tempi $t$ e $t'=t+T$ sappiamo che per definizione: $$\omega t' + \phi = \omega t + \phi + 2 \pi  $$
$$\cancel{\omega t} + \omega T +  \cancel\phi =  \cancel{\omega t }+ \cancel \phi + 2 \pi  $$
$$T = \frac {2\pi}\omega$$

### TODO 
- CONDIZIONI INIZIALI
- DISEGNARE I GRAFICI ORARI

## Domande
1.  Moto circolare uniforme.
2. Cos’è la gittata?
3. Decomposizione delle accelerazioni nei moti piani.
