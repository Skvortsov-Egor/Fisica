# Gas Perfetto

Il **gas perfetto** è un metodo utilizzato per descrivere in modo semplice il comportamento di un gas. Un gas è perfetto sotto certe condizioni:

- Ha un numero elevato di particelle 
- Bassa densità
- T alta rispetto $T_{eb}$
- dimensioni delle molecole trascurabile rispetto alla distanza media
- moto disordinato ed in ogni direzione 
- gli urti sono elastici
- $E$ è solo cinetica e quindi le forze intermolecolari sono trascurabili

Un gas che sodisfa queste condizioni si comporta allo stesso modo indipendentemente dalla sua composizione chimica. Un gas è studiato sia macroscopicamente che microscopicamente. 

Macroscopicamente un gas è studiato in funzione delle sue **variabili di stato**. Microscopicamente invece si studiano le proprietà delle singole particelle ed il legame con le variabili di stato. 

## Rapporto tra P e T e tra V e T

Se dovessimo tracciare il grafico della pressione in funzione della temperatura, otterremmo una retta che incontra l'asse x nel punto (-273.15;0). Questo valore è lo zero assoluto, punto di raffreddamento massimo raggiungibile da qualsiasi sostanza. Tracciando i grafici PT e VT, mantenendo la prima volta V costante e la seconda P costante e variando l'altra funzione di stato si ottiene un grafico formato da molte rette, tutte che si incontrano nello zero assoluto. P e V sono direttamente proporzionali alla temperatura. 

## Leggi di Gay-Lussac

Prima legge di **Gay-Lussac**:
> Il volume di un gas mantenuto a pressione costante varia linearmente con la temperatura: $$V_T=V_0(1+\alpha T_c)$$

Seconda legge di **Gay-Lussac**:
> La pressione di un gas mantenuto a volume costante varia linearmente con la temperatura: $$P_T=P_0(1+ \alpha T_C)$$

Le temperature sono espresse in gradi centigradi. $\alpha$ corrisponde a:

$$\alpha={1\over 273.15}°C^{-1}$$

Sostituendo le due espressioni con i gradi kelvin si ottiene:$$V={V_0\over 273.15}T$$ e $$P={P_0\over 273.15}T$$
## Legge di Boyle

> Fissata la temperatura ed il numero di moli: $$K=PV$$

$K$ dipende dalla temperatura e dal numero di moli. Se avviene una trasformazione in un sistema chiuso a temperatura costante:$$P_iV_i=P_fV_f$$
P e V sono inversamente proporzionali e la curva è una proporzionalità inversa ed è detta **isoterma** (stessa $T$).

## Legge dei Gas ideali

Se uniamo la relazione che si ottiene dalla ***seconda legge di Gay-Lussac*** ($P\alpha T$), la ***legge di Boyle*** ($K=PV$) e che la pressione aumenta se si aumenta il numero di moli ($P\alpha n$) si ottiene la seguente relazione: $$P={nT\over V}$$ e quindi $$PV = nT$$ Introduzione la **costante dei gas** $R= 8.31{J\over mol\cdot K}$ si ottiene la **legge dei gas ideali:**$$PV=nRT$$
Spesso è conveniente esprimere la legge dei gas ideali attraverso il numero di particelle $N$: 
$$PV=NkT$$

dove $k$ è la **costante di Boltzmann** che equivale a $1.38\times10^{-23}$. Questa equazione si ottiene considerando la seguente uguaglianza $N=N_a\cdot n$. Tramite questa legge è possibile dimostrare che il $V$ occupato a STP è di $22.4L$.

Spesso $n$ rimane costante quindi fissate 2 variabili di stato, l'altra può essere determinata:
- **Trasformazione ISOCORA**: $V$ costante $P_A\over T_A$
- **Trasformazione ISOBARA**: $P$ costante $V_A\over T_A$
- **Trasformazione ISOTERMA**: $T$ costante $P_A\cdot V_A$

## Teoria Cinetica

La teoria cinetica analizza il comportamento microscopico dei gas e si basa sul fatto che le molecole si muovono costantemente e casualmente. Essa stabilizza un legame con le funzioni di stato. 

Un contenitore a STP contiene un numero abnorme di molecole e queste molecole continuando a muoversi urtano e si scambiano velocità. La percentuale P di molecole che hanno il modulo della velocità compreso tra $v$ e $v+∆v$ è costante nel tempo. All'intervallo $v;v+∆v$ si associa la percentuale P di molecole che hanno il modulo della velocità compreso tra questo intervallo si ottiene la distribuzione delle velocità delle molecole del gas. 

Le molecole possono essere considerate puntiformi, e urtano contro una parete con le stesse leggi della quantità di moto che valgono per i corpi rigidi. Considerando $N$ particelle in una scatola di lato $L$. La Forza esercitata dalla parete sulla molecola: 
$$F={∆p\over ∆t}=-{2m\vec v\over {2L\over \vec v}}=-{m\vec v^2\over L}$$ 
$2L$ è lo spazio percorso da una molecola. 

La forza esercitata dalla molecola sulla parete sarà: 

$$F={m\vec v^2\over L}$$

La forza totale su tutti e 3 i piani:
$$F={\sum m\vec v^2\over 3L}$$

$$\vec v^2 = (\vec v^2_x+\vec v^2_y+\vec v^2_z)$$

La pressione sara uguale a:
$$P={F\over A}={\sum m\vec v^2\over 3L^3} = {\sum m\vec v^2\over 3V}$$

Portiamo fuori dalla radice $m$ e $v$

$$P={Nm\cdot\sum \vec v^2\over N\cdot 3V}$$

$$P={ Nm\cdot v^2\over 3V}$$

$$PV={Nm\over 3} v^2$$

$$v_{qm}=\sqrt{v^2}=\sqrt{\sum (\vec v^2_x+\vec v^2_y+\vec v^2_z)\over N}$$

$$PV={Nm\over 3} v_{qm}^2$$

$$PV={2\over 3}N({1\over 2}mv_{qm}^2)$$

$$PV={2\over 3}NK$$ 

$K$ è l'energia cinetica media.

$$NkT={2\over 3}NK$$

$$K={3\over2}kT$$

$${3\over2}kT={1\over 2}mv_{qm}^2$$

$$v_{qm}=\sqrt{3kT\over m}$$

L'energia cinetica media dipende direttamente solo dalla temperatura. La velocità quadratica media invece dalla temperatura e dalla massa. 

## U di un gas perfetto monoatomico
