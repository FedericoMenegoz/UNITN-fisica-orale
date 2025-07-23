---
title: "Termodinamica"
counter: 0
---

# Termodinamica
## Sistemi termodinamici
### Introduzione
Un sistema termodinamico può essere assimilato, dal punto di vista meccanico, a un sistema continuo costituito da un numero di elementi dell'ordine del __numero di Avogadro__:

$$
N_A = 6.022\cdot 10^{23}
$$

Di tale sistema si vgliono descrivere le __trasformazioni__ che può subire e gli scambi energetici ch ne derivano con l'ambiente circostante.

<img alt="un sitema termodinamico circondato dall'ambiente" src="../imgs/termodinamica-00_Universo.png">

- __sistema termodinamico__ una porzione di universo che può essere costituita da una o più parti
- __ambiente__ è tutto ciò con cui il sistema può interagire
- __universo termodinamico__ è l'insieme sistema più ambiente (in senso locale)

###### Sistema aperto
Se tra il sistema e l'ambiente possono avvenire sia scambi di energia che di materia, il sistema si dice __aperto__. Una pentola posizionata sul gas per essere portata in ebbolizione, senza coperchio è un sistema aperto, perché ovviamente scambia materia (il vapore) con l'ambiente e anche energia (il calore fornito dalla fiamma)

###### Sistema chiuso
Se tra il sistema e l'ambiente possono solo avvenire scambi di energia, il sistema si dice __chiuso__. Ad esempio, mettendo il coperchio alla pentola in ebbollizione, il sistema diventa _chiuso_ (in maniera approssimata).

###### Sistema isolato
Se il sistema non può scambiare né energia né materia con l'ambiente, si dice __isolato__. Si pensi ad un termos con una bevanda calda o fredda all'interno.

>
>Ovviamente un sistema isolato è attuabile solo con una certa approssimazione. 
>
>E' isolato solo per tempi ragionevoli: non possiamo aspettarci di portare un termos con del caffè caldo in un ghiacciaio, lasciarlo lì per dieci anni e poi pretendere di trovare ancora il caffè caldo. Tuttavia, su tempi brevi, rappresenta una buona approssimazione di un sistema isolato.
>

###### Aperto, chiuso e isolato

|Definizione\Scambio|Materia|Energia|Esempio|
|-|-|-|-|
|aperto|✅|✅|🫕 senza coperchio|
|chiuso|❌|✅|🫕 con coperchio|
|aperto|❌|❌|termos|

###### Variabili termodinamiche
Per descrivere lo stato di un sistema si possono usare delle variabili macroscopiche direttamente misurabili, dette __coordinate__ o __variabili termodinamiche__ come:
- volume $V$
- pressione $p$
- temperatura $T$
- massa $m$
- densità $\rho$

Le variabili termodinamiche si dividono in:
- variabili __estensive__: descrivono una proprietà globale del sistema e sono additive (massa, volume etc)
- variabili __intensive__: descrivono una proprietà locale del sistema, proprietà che possono variare da punto a punto e non sono additive (pressione, temperature, etc)

---
### Equilibrio Termodinamico

L'esperienza sperimentale evidenzia che un sistema termodinamico lasciato libero di evolversi in assenza di azioni esterne (cioè senza interagire con l'ambiente) tende ad uno __stato di equilibrio termodinamico__ in cui le variabili termodinamiche non variano più nel tempo.

All'equilibrio le variabili termodinamiche sono dette __variabili di stato__.

>L'equilibrio termodinamico è raggiunto quando sono realizzati tutti i seguenti equilibri:
>- __equilibrio meccanico__: inteso come equilibrio di forze e momenti, prese due sottoparti $A$ e $B$ in maniera arbirtaria, tra di loro non non misuro forze
>- __equilibrio chimico__: non avvengono reazioni chimiche qualsiasi sotto parte del sistema viene presa in considerazione
>- __equilibrio termico__: la temperatura è la stessa in tutto il sistema

In uno stato di equilibrio esistono, in generale, precise relazioni tra le _coordinate_ termodinamiche, dette __equazioni di stato__, per cui non tutte le variabili sono indipendenti.

Dati due diversi stati di equilibrio termodinamico, il passaggio da uno stato all'altro si chiama __trasformazione termodinamica__ del sistema.

###### Principio _zero_ della termodinamica

> Il __principio dell'equilibrio termico__ enuncia che se due sistemi A e B sono ciascuno in equilibrio con un terzo sistema C, cioè $T_A = T_C$ e $T_B = T_C$ allora i due sistemi sono in equilibrio tra loro $T_A = T_B$.

Un metodo per portare due sistemi all'equilibrio termico è quello di metterli in contatto tramite una parete.

Se viene raggiunto l'equilibrio allora la parete viene detta __diatermica__ e i sistemi sono in __contatto termico__, se invece l'equilibrio non viene raggiunto la parete viene detta __adiabatica__ e i sistemi sono in isolamento termico (sempre ideale, ma approssimabile per tempi brevi).

Un sistema è detto __adiabatico__ se è circondato da pareti adiabatiche e quindi non può essere messo in contatto termico con l'ambiente o un altro sistema.

---
### Termometro (extra?)

---
### Calorimetria

###### Calore, calore specifico e capacità termica
Quando due corpi solidi a temperature $T_1$ e $T_2$, con $T_1 > T_2$ messi in contatto termico all'interno di un contenitore adiabatico, dopo un certo tempo $\Delta t$ essi raggiungeranno l'equilibrio termico, con una temperatura di equilibrio $T_e$ ed in particolare:

$$
T_2 < T_e < T_1
$$

Si intuisce che che tra i due corpi avviene uno scambio di energia, tale energia è detta __calore__.

>La quantità di calore $dQ$ che è necessario fornire a un corpo di massa $m$ per variare la temperatura di $dT$ è definita dalla:
>
>$$
dQ = mcdT
>$$

in cui $c$ è una grandezza caratteristica della sostanza di cui è costituito il corpo, in generale funzione a sua volta della temperatura, chiamata __calore specifico__:

> Il calore specifico rappresenta il calore che occorre scambiare con l'unità di massa di una data sostanza, alla temperatura T, per farne variare la temperatura di $1\;K = 1\;°C$.

Il prodotto 

$$C=mc$$

è detto __capacità termica__ del corpo e rappresenta il valore necessario per far variare la temperatura del corpo di $1\;K$.

Integrando:

$$
Q = \int dQ = m\int _{T_{i}}^{T_{f}} c(T)dT
$$

Spesso però il calore specifico nell'intervallo di temperatura considerato può essere considerato costante portando a:

$$
Q = mc(T_f - T_i)
$$

Quindi tornando ai due corpi in contatto termico, essi scambieranno rispettivamente $Q_1$ e $Q_2$ ed essendo il recipiente adiabatico non c'è scambio di calore con l'esterno:

$$
Q_{tot} = Q_1 + Q_2 \Rightarrow Q_1 = - Q_2
$$

> Ovvero il calore ceduto dal corpo più caldo è uguale in modulo a quello assorbito da quello più freddo.
>
>$$
m_1c_1(T_e - T_1) = - m_2c_2(T_e - T_2) 
>$$
>
> Da cui noti i calori specifici e le temperature iniziali si può calcolare la temperatura di equilibiro:
>
>$$
T_e = \frac {m_1c_1T_1 + m_2c_2T_2}{m_1c_1 + m_2c_2} = \frac {C_1T_1 + C_2T_2}{C_1 + C_2} 
>$$


Per i gas la situazione si complica un po' e si avranno calori specifici diversi a seconda delle condizioni della trasformazione (volume o pressione costanti). Questa distinzione andrebbe fatta anche per i solidi, ma la variazione di volume causate da un cambio di temperature sono piccole abbastanza da poterle trascurare.
###### Mole

<a id="calore-specifico-molare"></a>

In molte situazioni si preferisce utilizzare il __calore specifico molare__:

$$
c = \frac 1n \frac {dQ}{dT}
$$

Una mole di sostanza è la quantità di materia di suddetta sostanza contenente $N_A = 6.022 \cdot 10^{23}$ entità elementari (atomi o molecole). $N_A$ è il __numero di Avogadro__ che corrisponde al numero di entità fondamentali di 12 grammi di isotopo $^{12}C$  del carbonio.


---
###### Cambiamenti di fase
Sono detti __cambiamenti di fase__ i passaggi di una sostanza da uno stato di aggregazione all'altro.

|Cambiamento di fase|Terminologia|
|-|-|
|solido $\Rightarrow$ liquido|fusione|
|liquido $\Rightarrow$ solido|solidificazione|
|liquido $\Rightarrow$ vapore|evaporazione|
|vapore $\Rightarrow$ liquido|condensazione|
|solido $\Rightarrow$ vapore|sublimazione|
|vapore $\Rightarrow$ solido |brinamento (sublimazione)|

A __pressione costante__, la temperatura durante la solidificazione e la fusione rimane costante. L'evaporazione, invece, può avvenire a qualsiasi temperatura; un caso particolare è l'ebollizione in cui la pressione massima del vapore eguaglia la pressione esterna.
Si osserva che durante i cambiamenti di fase viene scambiata una quantità ben definita di calore a seconda della sostanza, detto __calore latente__, il calore richiesto per il cambiamento di fase:

$$Q = m\lambda$$

Il calore cambia di segno a seconda del tipo di cambiamento:
- se la sostanza __fonde__ o __evapora__, allora __assorbe__ calore
- se la sostanza __solidifica__ o __condensa__, allora __cede__ calore


###### TODO
- aggiungere le parti relative da diagrammi pT

###### Sorgente di calore

Si definisce __sorgente di calore__ un corpo con capacità termica infinita.

--- 
######  Trasmissione del calore: CONDUZIONE
Consideriamo un corpo esteso in cui la temperatura non sia uniforme e tracciamo le superfici isoteerme, coiè il luogo dei punti in cui la funzione $T(x, y, z)$ assume un valore costante, per esempio $T_1$ sulla superficie $S_1$. 

<img alt="sorgente di calore e barra fino all'equilibrio termico" src="../imgs/termodinamica-01_Conduzione.png">

Allora la legge __fenomenologica__ che regola la conduzione del calore (legge di Fourier) è data:

$$
dQ = -k \frac {dT}{dz}dSdt
$$

- $dS$ elemento di una superficie isoterma
- $z$ l'asse perpendicolare alla superficie
- $\frac {dT}{dz}$ è il gradiente della temperatura
- $k$ detta __conducibilità termica__ con unità di misura $\frac J {m s K}$

Il segno negativo indica che il flusso di calore avviene nel senso in cui la temperatura diminuisce.
L'esistenza di un gradiente di temperatura su di un corpo (disequilibrio termico) indica che c'è una trasmissione di calore attraverso il corpo.

######  Trasmissione del calore: CONVEZIONE
Nei fluidi a contatto con una sorgente di calore, la porzione più vicina alla fonte si riscalda, aumenta di temperatura e quindi si dilata, diminuendo la propria densità.

Le masse di fluido più calde, essendo meno dense, subiscono una spinta di Archimede maggiore del loro peso e tendono a salire. Questo moto genera correnti ascensionali di convezione, che portano verso la sorgente masse di fluido più fredde.

In questo processo, il trasferimento di calore avviene insieme al movimento della materia: le porzioni di fluido più calde (con maggiore energia interna) si spostano e trasferiscono energia in altre zone, modificandone l’energia interna.

La __convezione__ è responsabile del movimento delle masse d'aria nell'atmosfera o delle correnti marine, con effetti sulle condizione climatiche e meteorologiche.


######  Trasmissione del calore: IRRAGGIAMENTO
Un corpo a temperatura T __irraggia__, ossia emette energia sotto forma di onde elettromagnetiche, che si propagano nello spazio circostante, anche se vuoto. 

Il __potere emissivo__ del corpo $ε$ è dato dalla legge di Stefan-Boltzmann:

$$
\varepsilon = \sigma e T^4 \quad \bigg[\frac J{m^2 s}\bigg]
$$

- $\sigma = 5.67\cdot 10^{-8} \;\frac J{m^2 s K^4}$ costante di Stepen-Bolztmann
- $e \in \{0,1\}$ __emissività__ se uguale a 1 la superficie è detta __corpo nero__ che a parità di temperatura presenta il massimo potere emissivo


E' attraverso l'irraggiamento che il Sole trasmette energia alla superficie terrestre:

$$ 1.37 \cdot 10^3 \;\frac W {m^2}$$

###### Vaso Dewar
Per ridurre al massimo lo scambio di calore bisogna quindi cercare di impedire il più possibile:
- conduzione 
- convezione
- irraggiamento 

Si utilizza a tale scopo un contenitore con due pareti isolanti, con in mezzo il vuoto. Questo minimizza la trasmissione di calore per conduzione e convezione.

Per annullare anche lo scambio di energia per irraggiamento, si installa una superficie argentata nelle superfici dell'intercapedine, cosicché l'irraggiamento è annullato completamente da pareti rifflettenti.

---
### Trasformazioni termodinamiche 
In una trasformazione qualsiasi gli stati intermedi possono essere di equilibrio e di non equilibrio:
- due corpi solidi con due temperature diverse messi a contatto termico raggiungeranno un equilibrio, ma tutti gli stati intermedi saranno di non equilibrio termico
- l'espansione libera di un gas, prima dell'equilibrio, tutti gli stati intermedi sono di non equilibrio perché in ogni momento ci sarà una differenza di pressione tra le parti del sistema

###### Trasformazione quasi-statica
Per cercare di ottenere una trasformazione in cui tutti gli stati intermedi siano di equilibrio, bisogna procedere con variazioni molto piccole delle variabili di stato. Quindi si fanno piccoli discostamenti dallo stato di equilibrio e si attende il ristabilirsi dell'equilibrio nelle nuove condizioni prima di procedere a un'ulteriore variazione infinitesima di stato. Una trasformazione di questo tipo viene chiamata __quasi-statica__.

La lentezza della trasformazione è condizione necessaria, ma non sufficiente per far si che gli stati intermedi siano di equilibrio, basti pensare a questi due [esempi](#trasformazioni-termodinamiche).

> ###### Trasformazioni reversibili e irreversibili
> - una trasformazione è detta __reversibile__ se essa avviene attraverso stati di equilibrio e in assenza di qualsiasi forza dissipativa;
>
> - una trasformazione è detta __irreversibile__ qualora non si svolga secondo le modalità precedenti, ossia passi attraverso stati di non equilibrio o avvenga in presenza di forze dissipative oppure si verifichino, durante il suo svolgimento, entrambe queste situazioni

---
### Lavoro Termodinamico
Consideriamo un gas all'interno di un contenitore dotato di di un pistone che è libero di muoversi con l'espandersi del gas.

Noti i valori del volume e della pressione, dall'equazione di stato possiamo ricavare la temperatura, e le trasformazioni effettuate dal sistema possono essere rappresentate nel piano di Clapeyron.

Ogni volta che il gas si espande o viene compresso avviene uno scambio di lavoro che a livello infinitesimo si può scrivere come:

$$
dW = pdV
$$

In una trasormazione da uno stato $A$ ad uno stato $B$:

$$
\int _A ^B p(V) dv
$$

> Questa funzione è utile solo quando si conosce $p(V)$:
>
> - __è nota la pressione esterna__ $p$ e quindi l'integrale è direttamente calcolabile
> 
> $$W = p_{amb}(V_B - V_A)$$
>
> - __la trasformazione è reversibile__ e pertanto si può calcolare l'integrale, dato che la pressione è determinata in ogni stato intermedio:
>
> $$p=p_{sist}=p_{amb}$$
>
> In tutti gli altri casi questo integrale non si può applicare però:
> - se la trasformazione è __isocora__, il lavoro è sempre nullo
> - se il sistema si espande, compie un lavoro sull'ambiente (positivo)
> - se il sistema si comprime, subisce un lavoro dall'ambiente (negativo)

---
## Primo principio della termodinamica
### Esperimenti di Joule
Joule, nella metà del 1800, condusse una serie di esperimenti per mettere in relazione gli effetti termici del lavoro meccanico. In particolare, il suo obiettivo era aumentare la temperatura di una certa quantità d’acqua utilizzando procedimenti diversi:
- viene messo in rotazione un mulinello nell'acqua, il lavoro $W_1$ viene fornito dalla variazione di energia potenziale di due masse che scendono sotto l'azione della forza peso, l'acqua viene riscaldata per l'effetto dell'attrito
- viene immerso nell'acqua una resistenza R, percorsa da una corrente. $W_2$ è il lavoro speso per fare circolare la corrente
- viene compressa una certa quantità di gas, contenuta in un recipiente con pareti diatermiche, immerso nell'acqua. Il processo di compressione del gas richiede un lavoro $W_3$
- vengono strofinati tra loro due blocchi di metallo immersi nell'acqua. Il lavoro speso contro le forze d'attrito è $W_4$

Il risultato osservato da Joule e confermato da altri esperimenti, purché il sistema sia adiabatico è che indipendentemente dal tipo di lavoro meccanico, $W_1$, $W_2$, $W_3$ e $W_4$, esso è proporzionale alla variazione di temperatura dell'acqua con la stessa costante di proporzionalità.

> Sulla base delle considerazioni sull'[energia potenziale](./lavoro-ed-energia.md#energia-potenziale) vale la relazione:
>
> $$ W_{ad} = -\Delta U = U_{in} - U_{fin}$$
>
> dove $U$ è una funzione che dipende solo dalle _coordinate_ termodinamiche del sistema.

- se il sistema fornisce lavoro all'esterno $W$ è assunto positivo e pertanto l'energia $U$ diminuisce
- se invece si compie lavoro dall'esterno al sistema il lavoro $W$ è assunto negativo e l'energia $U$ aumenta


>Il calore $Q$ scambiato, senza lavoro esterno, per far variare la temperatura di $\Delta T$. di una massa d'acqua è uguale al lavoro $W_ad$ chhe deve essere speso, in condizioni adiabiatiche, per ottenere la stessa variazione di temperatura

---
### Primo principio della termodinamica. Energia interna
>Se un sistema compie una trasformazione dallo stato $A$ allo stato $B$, scambiando calore e lavoro con l'ambiente, $Q$ e $W$ dipendono dalla trasformazione che congiunge i due stati termodinamici, mentre la differenza $Q- W$ risulta indipendente dalla trasformazione:
>
> $$ \Delta U = U_B - U_A = Q - W$$
>

Questo principio quindi mostra che l'energia interna del sistema ($U_i$) aumenta se il sistema assorbe calore dall'ambiente e diminuisce se esegue lavoro sull'ambiente. Inoltre per passare da uno stato iniziale a uno finale ci sono molteplici trasformazioni possibili, quindi quantità di lavoro e calore scambiati diversi, ma che la differenza di energia interna è sempre uguale a il calore assorbito meno il lavoro eseguito dal sistema.

<img alt="diverse trasformazioni da uno stato iniziale a uno finale" src="../imgs/termodinamica-02_PrimoPrincipio.png">

###### Osservazioni

- il primo principio della termodinamica è l'espressione del __principio generale di conservazione dell'energia__, applicato ai sistemi termodinamici: l'energia può essere trasferita sotto forma di calore e lavoro, ma la quantità totale si conserva
- __energia interna__ è tutta l'energia immagazzinata nel sistema, composta da diversi contributi quali l'energia cinetica delle molecole, l'energia potenziale delle interazioni intermolecolari, l'energia di legame, 
- nonostante il primo principio stabilisca la conservazione dell'energia, non tutta l'energia interna può essere convertita in lavoro utile; parte del calore fornito al sistema viene inevitabilmente disperso e non può essere trasformato in lavoro (questa limitazione è stabilita dal secondo principio della termodinamica)
- se lo stato iniziale coincide con lo stato finale allora la trasformazione è detta __ciclica__ e per definizione si ha che la temperatura finale coincide con quella iniziale e 

$$\Delta U = 0 \quad \Rightarrow \quad Q = W$$

- Nel calcolo infinitesimale, l'energia interna, essendo una funzione di stato, ha variazioni che sono differenziali esatti ($dU$). Al contrario, il lavoro e il calore dipendono dal percorso della trasformazione, quindi le loro variazioni infinitesime ($\delta Q$ e $\delta W$) non sono differenziali esatti

###### Convezionzione segni
Utilizzando la convenzione adottata nella formula $\Delta U = Q - W$:
- calore che entra nel sistema dall'esterno __segno positivo__
- lavoro compiuto dall'esterno verso il  sistema __segno negativo__
- lavoro compiuto dal sistema verso l'esterno  __segno positivo__
- calore che esce dal sistema verso l'esterno __segno negativo__


<img alt="convenzione segni" src="../imgs/termodinamica-03_ConvezioneSegni.png">

---
### Leggi dei gas ideali
Si considerano gas racchiusi in un contenitore di volume $V$ con parete mobile, con valore di pressione uguale per tutti i suoi punti, le variabili per descrivere lo stato sono:
- __pressione__ $p$ è la forza per unità di superficie esercitata dal gas sulle pareti del contenitore:
$$p = \frac {\vec F_{\perp}}{S} \quad \bigg[\frac N {m^2} = Pa\bigg]$$

Se il contenitore ha una parete mobile, in equilibrio la pressione del gas $p_g$ è uguale a quella esercitata dall’ambiente $p_a$
$$\frac {F_{\perp a}}{\cancel S} = \frac {F_{\perp g}}{\cancel S} \rightarrow p_a = p_g$$

Ad esempio, in un palloncino la pressione interna del gas è bilanciata dalla forza elastica della membrana.

- __volume__ $V$ il gas non ha un volume proprio: occupa tutto lo spazio disponibile del contenitore
- __temperatura__ $T$ è legata all’energia cinetica media delle molecole del gas. Negli urti con le pareti, assumendo che queste abbiano massa molto maggiore di quella delle particelle, l’energia cinetica del gas non cambia, ma determina la pressione esercitata

<img alt="convenzione segni" src="../imgs/termodinamica-04_TemperaturaEnergiaMolecole.png">

Quando un gas è sufficientemente rarefatto, si trova a bassa pressione e ad alta temperatura rispetto al punto di condensazione, può essere approssimato come gas ideale.

---
##### Legge di Boyle 
La __legge di Boyle__:

$$pV = cost$$

a temperatura costante la pressione è inversamente proporzionale al volume.

Una __trasformazione isoterma__ si può realizzare utilizzando un contenitore con pareti diatermiche che sono in contatto con una sorgente di calore, una parete mobile che si muove a seguito di una differenza infinitesimale di pressione tra gas e ambiente esterno. Quindi si può supporre che gli stati intermedi siano di equilibrio. Ma anche se non fossero di equilibrio, gli stati iniziale e finale se sono alla stessa temperatura rispetteranno:

$$p_1V_1 = p_2 V_2$$

Nel piano di Claperyon, il luogo dei punti che rappresentano gli stati di equilibrio di un gas ideale a una data temperatura è costituito da un ramo di iperbole dette __isoterme del gas ideale__.

<img alt="convenzione segni" src="../imgs/termodinamica-05_Isoterme.png">

#### Legge di Volta-Gay Lussac
###### Isobara
Se la pressione del gas rimane costante, si parla di __trasformazione isobara__, il volume varia linearmente con la temperatura:

$$ V = V_0(1 + \alpha t)$$

- $\alpha$ coefficiente di dilatazione termica che varia a seconda del gas (ma di poco)
- $V_0$ è il volume quando la temperatura è $0\;°C$
- la trasformazione isobara nel piano $p$, $V$ è rappresentata da un segmenteo di retta parallelo all'asse dei volumi

Per verificare la validità della __legge isobara di Volta-Gay Lussac__ si può mettere il gas in equilibrio termico con diverse sorgenti di calore, mantenendo sempre l'equilibrio meccanico con l'ambiente (pressione gas = pressione ambiente) e ogni volta misurare il volume del contenitore che ha una parete libera di muoversi.

###### Isocora
Se invece si mantiene costante il volume di un gas allora la pressione risulta funzione lineare della temperatura:

$$ p = p_0(1 + \beta t)$$

- $\beta$ è una costante praticamente indipendente dal tipo del gas
- $p_0$ è la pressione quando la temperatura è a $0\;°C$
- la trasformazione icora nel piano $p$, $V$ è rappresentata da un segmenteo di retta parallelo all'asse delle pressioni

Per verificare la validità della __legge isocora di Volta-Gay Lussac__ si utilizza lo stesso contenitore di prima, bloccandone la parete mobile e misurando la pressione al variare della temperatura.

###### $\alpha$ e $\beta$
Più si avvicina alle condizioni per i gas ideali più $\alpha$ e $\beta$ assumono lo stesso valore:

$$\alpha = \beta = \frac 1{273.15 °C}$$

Per tanto le leggi si possono scrivere:

$$V = V_0 \cdot \alpha (\frac 1 \alpha + t) = V_0\alpha T$$
$$p = p_0 \cdot \alpha (\frac 1 \alpha + t) = p_0\alpha T$$

###### Legge di avogadro
Volumi uguali di gas diversi, alla stessa temperatura e pressione, contengono lo stesso numero di molecole oppure equivalentemente lo stesso numero di moli.

$$N = \frac 1{k_B} \frac {pV}{T}$$

$$n = \frac 1 R \frac {pV}T$$

- $k_B = 1.38 \cdot 10^{-23}$ è la __costante di Boltzman__ con unità di misura $\big[\frac J K\big]$
- $R = 8.314 \cdot 10^{-23}$ è la __costante di Boltzman__ con unità di misura $\big[\frac J {K\cdot mol}\big]$

>Come conseguenza una mole di gas qualsiasi, a una data temperatura e pressione, occupa sempre lo stesso volume.
> - $n = 1\;mol$
> - $p = 1\;atm$
> - $t = 0\;°C \Rightarrow T = 273.15\;K$
> - $V_m = 22.41\;l = 0.02241\;m^3$ detto __volume molare__
>

###### Equazione di stato dei gas perfetti
Consideriamo $n$ moli di gas alla pressione atmosferica $p_0$ e alla temperatura $T_0 = 273.15\;K$ esse occupano, come appena visto, il volume $V_0 = n\cdot V_m$. Ora portiamo questo gas dallo stato A a uno stato termodinamico qualsiasi C di coordinate $p$, $V$ e $T$. Questo passaggio può essere fatto facendo una trasformazione isocora fino ad uno stato intermedio B seguito da un'isoterma a C.

- pressione nello stato B per la [legge isocora](#isocora)

$$p_B = p_0\alpha T$$

- nell'isoterma per la legge di [Boyle](#legge-di-boyle) abbiamo che:

$$pV = p_BV_0 = p_0\alpha T V_0= np_0 V_m \alpha T $$

Il prodotto 

$$p_0\alpha V_m = R  = 8.314 \frac J{mol\cdot K}$$

è detta __costante dei gas ideali__.


> Sulla base delle tre leggi elementari (Boyle, Volta-Gay Lussac) e della legge di Avogadro, definiamo quindi come gas ideale un sistema le cui coordinate termodinamiche in uno stato di equilibrio obbediscono a 
> 
> $$
> pV = n RT
> $$
>
> oppure utilizzando la costante di Boltzmann $k_b$
>
> $$
> pV = Nk_bT
> $$
>
> con $N$ numero di particelle e $n= \frac N {N_A}$

Questo è un comportamento limite dei gas ideali: quanto più un gas è caldo e rarefatto, tanto più il suo comportamento si avvicina a quello di un gas ideale, praticamente identico per tutti i gas in tali condizioni.

---
### Calori specifici gas ideali

---
### Energia interna gas ideale
###### Espansione libera dei gas
###### Relazione di Mayer

---
### Trasformazioni notevoli
###### Trasformazioni adiabatiche
###### Trasformazioni isocore
###### Trasformazioni isobare
###### Trasformazioni isoterme

---
### Trasformazioni cicliche
###### Ciclo di carnot

---
### Diagrammi pV pT (trovare analogia con lezioni iuppa)
###### Punto triplo

---
### Teoria cinetica dei gas

---
## Secondo principio della termodinamica
### Equivalenza enunciati

---
### Rev e Irr

---
### Teorema di carnot

---
### Teorema di Clausius

---
### Entropia
###### Interpretazione probabilistica dell'entropia

---

## DA SISTEMARE
- Zero assoluto
- funzioni di stato


## Domande
{% assign counter = page.counter | plus: 1 %}
##### {{ counter }}) Si commentino i tre modi di conduzione del calore affrontati a lezione.


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Si enunci il primo principio della termodinamica. Spiega il significato dei segni delle quantità calore e lavoro _hint: convenzione_


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Definisci capacità termica. è un’equazione scalare o vettoriale? Quali sono le unità di misura?


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Equazione che descrive lo scambio di calore tra due oggetti posti a contatto termico


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Primo principio della dinamica. _hint: Nella formulazione NON COMPARE la parola forza!_


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Si disegnino le vettori trasformazioni termodinamiche studiate.


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Per comprimere un gas facendo meno lavoro possibile che trasformazione ci conviene usare? _hint adiabatica_


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }})  Ha un senso che un gas abbia una pressione negativa? Perché no?


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Cos’è una trasformazione quasi-statica? + definizione trasformazione reversibile


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Teorema di Carnot. Una macchina potrebbe lavorare anche fra più di due sorgenti, il teorema di Carnot tra quale di queste due sceglie?_hint Massima e minima_


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Cos’è il rendimento?


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Si enuncino tutte le formulazioni conosciute del secondo principio della termodinamica. _hint due (forse tre con l’entropia?_


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Equazione di stato dei gas perfetti. Perché la temperatura si misura in Kelvin e non in Celsius?


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Cos’è un serbatoio di calore (o sorgente di temperatura)? _hint corpo in grado di cedere/assorbire calore senza variare la sua temperatura in maniera apprezzabile_


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Teoria cinetica dei gas, basi, disegno e risultato.


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Energia interna dei gas perfetti


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Definizione di entropia.


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Consideriamo un cilindro che contiene un fluido e mettiamo sopra un pistone, e immaginiamo di comprimere il fluido. Come si calcola il lavoro nel caso in cui avvenga per stadi quasi-statici (integrale pdV) e quando invece non avviene (sinceramente non lo so).


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Integrale di Clausius.


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Primo principio della termodinamica.


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }})  Si elenchino le trasformazioni termodinamiche visto e se ne discutano le proprietà.


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Come mai ΔU trovato per le isocore è lo stesso per tutte le trasformazioni? _Hint: Perché è una funzione di stato_


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Secondo principio della termodinamica + dimostrazione (se l’è chiamata)


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Mi parli dei cambi di fase


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Cos’è l’energia interna (termodinamica)?


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }})  Mi parla del ciclo di Carnot?


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Convezione.


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }})  Consideriamo un cubetto che si trovi a -20 gradi Celsius, inizio a dare calore al ghiaccio, che succede?


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Quanto vale la variazione di entropia nel processo di fusione?


---
{% assign counter = counter | plus: 1 %}
##### {{ counter }}) Quanto vale la variazione di entropia per una trasformazione adiabatica.


---