---
theme: "white"
---

<style>
    .reveal h1 {
        font-size: 1.25em;
        color: #666666;
    }

    .reveal li {
        font-size: 0.8em;
    }

    .reveal code {
        background-color: #66b3ff;
        color: #000000;
        padding: 0.2em 0.25em 0.2em 0.25em;
    }

    .language-bash {
        background-color: #000000;
        color: #00ff00;
    }
</style>


# Programma
- Insieme coordinato e strutturato di istruzioni atte a `risolvere un dato problema` mediante un `calcolatore` {: .fragment}

---

# Problema 
- Un `problema` è una questione in base alla quale si devono trovare uno o più elmenti ignoti (che costituiscono la `soluzione`) partendo dagli elementi noti contenuti nell'enunciato della questione stessa {: .fragment}

---

# Risolvere un problema
- Mettere in atto una `strategia` per giungere alla soluzione del problema
- La strategia è chiamata generalmente `algoritmo`

---

# Algoritmo
- Un insieme finito non ambiguo di istruzioni elementari che servono per eseguire un calcolo o per risolvere un problema. {: .fragment}

---

# Parti logiche di un problema
- dati di entrata (*input*)
- elaborazione (*algoritmo*)
- dati di uscita (*output* - **soluzione**)

---

![problema.pdf](/problema.svg)

---

# Esempi di problemi
  - Effettuare un'addizione
  - Trovare il Massimo Comun Divisore di due numeri
  - Contare il numero di parole in un testo
  - Calcolare la traiettoria di un priettile
  - Generare una sinusoide
  - Fare una telefonata

---

# Problema
|descrizione|input|elaborazione|output|
|---|---|---|---|
|sommare i numeri 4 e 5|4, 5| 4 + 5 | 9 |
|trovare il numero delle occorrenze della sillaba "el"| "Nel mezzo del cammin di nostra vita, mi ritrovai per una selva oscura" | search("el") | 3 |

---

# Algoritmo
## Cuocere la pasta
Ingredienti: sale, pasta, acqua
1. Riempi d'acqua la pentola 
2. Aggiungi un cucchiaio di sale 
3. Metti la pentola sul fornello finché l'acqua bolle 
4. Getta la pasta nella pentola 
5. Fai cuocere per 7 minuti 
6. Assaggia: se è cotta vai al punto (9) altrimenti vai al punto (7)
7. Fai cuocere per 1 minuto
8. Assaggia: se è cotta vai al punto (9) altrimenti torna al punto (7)
9. Scola la pasta

---

# Linguaggio di programmazione
- I programmi sono sequenze di istruzioni espresse in `linguaggio macchina`, quindi stringhe binarie (0 e 1) {: .fragment}
- Per scrivere un programma si usa un Linguaggio di programmazione che viene `tradotto` in linguaggio macchina da un compilatore {: .fragment}
- Si tratta di un `linguaggio formale`  che consente di scrivere il `codice sorgente`, che verrà convertito in linguaggio macchina {: .fragment}

---

# Compilato o Interpretato
- Un linguaggio di programmazione si dice compilato, quando viene scritto e poi compilato nella sua interezza da un compilatore, prima di essere reso eseguibile {: .fragment}
- Un linguaggio di programmazione si dice interpretato quando viene compilato riga per riga, al momento dell'esecuzione {: .fragment}

---

# Basso o alto livello

- Il livello di un Linguaggio di programmazione definisce la `distanza` del linguaggio dal linguaggio macchina
- Più il livello è basso più il linguaggio è vicino al linguaggio macchina, quindi dipendente dall'implementazione del processore
- I linguaggi di alto livello sono più astratti rispetto alle caratteristiche della macchina, quindi più vicini alla logica del linguaggio umano
- La maggior parte dei linguaggi usati oggi sono ad alto livello, al limite cambia l'`altezza` del livello. `c` è più basso del `perl`

---

# Python: caratteristiche
- interpretato
- alto livello
- free
- multi-paradigma
- portabile 
- facile da imparare
- ricco di librerie
- molto documentato