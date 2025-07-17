---
title: "Sistemi di punti materiali"
counter: 0
---
# Sistemi di punti materiali
## Moto del centro di massa

---

## Domande

{% assign counter = page.counter | plus: 1 %}
##### {{ counter }}) Terzo principio della dinamica. Se considero un sistema che prevede delle forze di reazione, mi fanno escludere a priori che il sistema sia isolato, oppure non è vero? La legge vale sempre? Quando un sistema si dice isolato?

###### a) Terzo principio della dinamica
L'enunciato della [terza legge di Newton](dinamica.md#terza-legge-di-newton-principio-di-azione-e-reazione) dice:
> - se un corpo <span class="color">A</span> esercita una forza $\vec F_{A\rightarrow B}$ su un corpo <span class="color">B</span> allora il corpo <span class="color">B</span> eserciterà una $\vec F_{B\rightarrow A}$ uguale e contraria sul corpo <span class="color">A</span>
> - le due forze hanno stessa direzione, modulo e verso opposto 
> - le due forze hanno la stessa retta d'azione (non sono solo parallele, ma sono collineari)

###### b) Quando un sistema si dice isolato?

Un sistema si dice __isolato__ se 
- non è soggetto a forze __esterne__, oppure 
- l'azione delle forze esterne è tale che la loro risultante $\vec F^{(e)}$ sia nulla:

$$ \vec a_{CM} = 0,\quad \vec v_{CM} = cost,\quad \sum_i \vec p_i = cost $$

>Quindi in un sistema isolato la quantità di moto totale  del sistema rimane costante nel tempo e il centro di massa si muove di moto rettilineo uniforme o resta in quiete.

###### c)  Se considero un sistema che prevede delle forze di reazione, mi fanno escludere a priori che il sistema sia isolato, oppure non è vero? La legge vale sempre?

Possiamo considerare due casi:
- le forze di reazione sono tutte interne al sistema: non possiamo dire a priori se il sistema è isolato perché le forze interne si compensano sempre a coppie (per il terzo principio), ma per essere davvero isolato è necessario che anche le forze esterne siano nulle o si bilancino
- alcune o tutte le forze di reazione sono esterne al sistema: allora il sistema non è isolato perché perché c'è un interazione con l'esterno che può modificare la quantità di moto totale

La legge di __azione e reazione__ non vale nei sistemi non inerziali in cui sono presenti __forze apparenti__ causate da accelerazioni o rotazioni del sistema di riferimento.

Se pensiamo a una palla all'interno di una macchina, quando la macchina accelera la palla si muoverà in direzione opposta e all'interno dell'abitacolo la forza apparente che muove la palla non è contrastata da nessuna reazione, rompendo così la terza legge di Newton.