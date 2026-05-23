# Campi e Forze Elettriche 

## Quantità di Elettricità - La Carica ($Q$)
> Proprietà fondamentale della materia

È misurata in **Coulomb ($C$)**;
considerantesi come carica fondamentale - minima misurata - quella di un'elettrone
$$e = 1.602 \cdot 10^{-19} C$$
ogni carica elettrica $q$è **quantizzata**, ovvero:
$$q = ne$$
con $(𝑛∈𝑍)$.

Si distinguono materiali **conduttori** ed **isolanti** (o dielettrici) in base al movimento di carica che consentono.
Un conduttore permette il passaggio di elettroni con facilità, e manterrà per questo lo stato di elettrizzazione per meno tempo rispetto al dielettrico.


### Elettrizzazione 
 > Processo di assunzione di carica, in seguito allo spostamento di elettroni a partire da uno stato di neutralità

 La carica può assumere nome, o segno, **positivo (+)**  per perdita di $e^-$, o **negativo (-)** guadagnando $e^-$;
**l'entità del segno provoca repulsione tra i corpi, al contrario, l'opposizione di questi genera attrazione**.

Il processo di elettrizzazione può avvenire in diversi modi, principalmente:

- **Per Contatto**
    Ovvero per il *trasferimento diretto di elettroni* tra oggetti a contatto.

- **Per induzione**
    La separazione delle cariche *senza contatto*. Gli elettroni si ridispongono nello stesso corpo dando origine a una parte carica positivamente e una negativamente - è il *principio di funzionamento dell'elettroscopio*.

    Il collegamento a terra permette la fuga di cariche e l'oggetto si può caricare.

- altri esempi includono elettrizzazione *piezoelettrica e piroelettrica nei cristalli*.

Nei **conduttori la carica si distribuisce sulla superficie** perché gli elettroni liberi si respingono e cercano la configurazione a minima energia.

### Forza Elettrostatica ($F_e$)

> Si tratta della *forza che agisce su due cariche in relazione*, essa è diretta lungo la congiungente delle cariche. 

La Forza totale è definita dal *principio di sovrapposizione* come *prodotto vettoriale* delle singole.

 **Legge di Charles Coulomb**: $$F_e = \frac{1}{4\pi\epsilon _0}\frac{qq'}{r^2}$$ 

 in cui $\epsilon _0$ è la costante dielettrica nel vuoto.

Assumendo per convenzione segno positivo in caso di repulsione, negativo per attrazione, in base al prodotto dei nomi delle cariche.

---

## Campo Elettrico
> Dicesi campo elettrico di un corpo elettrizzato, la regione dello spazio entro cui esso fa risentire la sua azione elettrica. 

L'intensità del campo elettrico in un punto di questo è la *forza che agisce sull'unità di quantità di elettricità posta in quel punto*:

$$\vec{E} = \frac{\vec{F}}{q}$$
misurata in $N/C$

Il vettore del campo avrà verso uscente se la carica generatrice è positva, se invece $Q < 0$, $\vec{E}$ sarà entrante

### Linee di Forza
> Sono le linee secondo cui si esplica l'azione elettrica di un corpo elettrizzato.

Per queste si convengono le seguenti caratteristiche:
- sono *uscenti da cariche di nome positivo ed entranti in quelle di nome negativo*.
- il loro numero è *proporzionale all'intensità* del campo.
- tangenti al vettore $\vec{E}$ agente nello stesso punto.
- non si intersecano in nessun punto.

> È detto **campo uniforme quello in cui le linee di forza sono parallele**. Praticamente si può ottenere un campo pressoché uniforme nella parte centrale tra due dischi conduttori elettrizzati di segno contrario con le facce parallele e sufficientemente vicine.

### Flusso e Teorema di Gauss

> Il **flusso del campo elettrico** attraverso una superficie, misura “quante” linee di forza attraversano quella superficie.

Per una superficie piana $S$ attraversata da un campo $vec{E}$ uniforme, il flusso è definito come:

$$
\Phi_S(\vec{E}) = \vec{E} \cdot \vec{S} = ES\cos\theta
$$

dove $\vec{S}$ è il vettore normale e di modulo pari alla superficie, e $\theta$ l'angolo tra questo e $\vec{E}$

#### Teorema di Gauss
> Stabilisce che il flusso totale del campo elettrico attraverso una superficie chiusa è proporzionale alla carica racchiusa:

$$
\Phi_S(\vec{E}) = \frac{Q}{\epsilon_0}
$$


---

### Tipi di Campi Elettrici per Distribuzione

> A seconda della geometria della distribuzione di carica, il campo elettrico assume forme e intensità differenti.  

##### considerando
- $k = \frac{1}{4\pi\epsilon_0}$
- $\lambda = \frac{Q}{l}$ densità lineare di carica
- $\sigma = \frac{Q}{S}$ densità superficiale di carica
- $\rho = \frac{Q}{V}$ densità volumica di carica


| **Distribuzione di Carica** | **Simmetria** | **Andamento del Campo $E$** | **Note Caratteristiche** |
|-----------------------------|---------------|-------------------------------|---------------------------|
| **Punto** | Sferica | $$E = k\frac{Q}{r^2}$$| Radiale; identico a quello di una massa puntiforme in gravità |
| **Piano infinito uniformemente carico** | Planare | $$E = \frac{\sigma}{2\epsilon_0}$$ | Campo **costante** e indipendente dalla distanza |
| **Condensatore piano** | Planare | $$E = \frac{\sigma}{\epsilon_0}$$ tra le armature | Campo uniforme nella regione centrale |
| **Sfera dielettrica uniformemente carica** | Sferica | Interno: $$E = k\frac{Q}{R^3}r$$   Esterno: $$E = k\frac{Q}{r^2}$$ | Interno cresce linearmente; esterno come carica puntiforme |
| **Sfera conduttrice uniformemente carica** | Sferica | Interno: $$E = 0$$ Esterno: $$E = k\frac{Q}{r^2}$$ | Carica sulla superficie; schermo elettrostatico |
| **Filo infinito uniformemente carico** | Cilindrica | $$E = k\frac{\lambda}{r}$$ | Decresce come $1/r$ |
| **Cilindro dielettrico uniformemente carico** | Cilindrica | Interno: $$E = \frac{\rho r}{2\epsilon_0}$$ Esterno: $$\frac{\rho}{2\epsilon_0} \frac{R^2}{r}$$ | Analogo alla sfera dielettrica |
| **Cilindro conduttore uniformemente carico** | Cilindrica | Interno: $$E = 0$$ • Esterno: $$E = \frac{1}{2\pi\epsilon_0}\frac{\lambda}{r}$$ | Carica sulla superficie |

---
## Energia Potenziale di Carica e Potenziale Elettrico
> La $\vec{F_e}$ è conservativa. Analogamente alla Forza di Gravità è possibile associare a ciascuna posizione un valore di energia potenziale $U$.

- In un **Condensatore** (campo elettrico uniforme nella parte interna)
$$U_e = qEh = q{\sigma \over \epsilon_0}h$$

come $U_p = mgh$ in un corpo sospeso a distanza $h$ da un camnpo gravitazionale presunto uniforme.
Si può generalizzare per entrambi i casi che l'energia potenziale di un corpo in una determinata posizione è il *prodotto tra la sua misura caratteristica, il valore del campo uniforme in cui è sito e la distanza tra tale posizione e un punto a cui può essere opportunamente associato un valore neutro* ($U_c = cCh$ & $U_0 = 0$).

- Tra **$n$ cariche puntiformi**
si individuano ${n(n-1) \over 2}$ coppie, e per queste:
avendo la distanza tra le carice $d \propto {1 \over F}$, si avrà $U_0 = 0$ con $d \to \infin$
$$ U_e = {1 \over 4\pi\epsilon_0}{qq' \over d} $$
$U_e$ è quindi pari al lavoro $W$ necessario a disgregare il sistema.

### Potenziale Elettrico ($V$)

> Misurato in **Volt** ($V = {J \over C}$), è il rapporto tra l'energia potenziale in un punto e una carica di prova posta nello stesso.

$$V = {U \over q_0}$$

Si definisce come **differenza di potenziale elettrico** di un corpo elettrizzato, *il lavoro che può eseguire l'unità di elettricità passando dalle condizioni in cui si trova nel corpo al potenziale zero.*

$$\Delta V = - {W_{A,B} \over q_0} = -\vec{E} \cdot \Delta \vec{s}$$

Una carica negativa accelera verso un $V$ maggiore, mentre una positiva verso un $V$ minore. Questo è dato matematicamente dal segno della forza. 
Per convenzione si considera il moto di una carica positiva ma è importante notare che sono gli elettroni a muoversi.

Il lavoro necessario per trasportare un punto elettrizzato lunga una superficie equipotenziale è nullo.

**Elettronvolt:** unità pratica di potenziale elettrico equivalente al lavoro compiuto da un elettrone per attraversare una $\Delta V$ di 1 Volt

#### Messa a Terra ⏚

>L'equilibrio di potenziale si ha quando la zona considerata presenta tutti i punti con potenziale eguale. Si può ottenere collegando il conduttore a un potenziale nullo (messa a terra ⏚)