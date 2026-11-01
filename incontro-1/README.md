# Incontro 1 · Dal neurone al percettrone

**La logica della rete: come pensa una rete neurale** · martedì 3 novembre 2026

Il kit dell'incontro: tre attività da rifare in classe, ognuna con i materiali per gli studenti e una guida per il
docente.

## 1 · Il percettrone a mano (senza computer)

Un percettrone impara a decidere «esco stasera?» da sei serate: si parte da pesi a zero e si corregge dopo ogni
errore, finché non sbaglia più. Poi lo stesso percettrone prova lo XOR e non si ferma mai.

| File | A che cosa serve |
|---|---|
| [percettrone_a_mano_scheda.pdf](schede/percettrone_a_mano_scheda.pdf) | La scheda da stampare |
| [percettrone_a_mano_guida_docente.pdf](schede/percettrone_a_mano_guida_docente.pdf) | La soluzione passo per passo e le domande per il confronto |

## 2 · Un percettrone con Gemini (AI-assisted coding in Colab)

Il codice lo scrive Gemini, l'assistente di Google Colab: noi chiediamo bene e controlliamo il risultato. Tre tappe
e una sfida: il percettrone da zero, il confine di decisione che si sposta a ogni giro, il limite dello XOR, una rete
con uno strato nascosto.

| File | A che cosa serve |
|---|---|
| [percettrone_guida.ipynb](notebook/percettrone_guida.ipynb) · [**apri in Colab**](https://colab.research.google.com/github/matteolimoncini/la-logica-della-rete/blob/main/incontro-1/notebook/percettrone_guida.ipynb) | Il notebook da completare: consegne, prompt di esempio, celle vuote |
| [percettrone_soluzione.ipynb](notebook/percettrone_soluzione.ipynb) · [**apri in Colab**](https://colab.research.google.com/github/matteolimoncini/la-logica-della-rete/blob/main/incontro-1/notebook/percettrone_soluzione.ipynb) | La soluzione già eseguita, con i risultati |

Aperto in Colab, il notebook va salvato con *File → Salva una copia in Drive*: senza la copia le modifiche non si
salvano.

## 3 · TensorFlow Playground (no-code, nel browser)

Un neurone solo funziona sui dati separabili da una retta e fallisce sullo XOR; con uno strato nascosto il confine
si piega.

| File | A che cosa serve |
|---|---|
| [playground_consegne.pdf](schede/playground_consegne.pdf) | Il percorso guidato, con la schermata spiegata e i link alle prove già impostate |
| [playground_guida_docente.pdf](schede/playground_guida_docente.pdf) | Che cosa aspettarsi a ogni prova, con le schermate; domande per il confronto |

Lo strumento: [playground.tensorflow.org](https://playground.tensorflow.org).

## Crediti

- **TensorFlow Playground:** Daniel Smilkov e Shan Carter, licenza Apache 2.0.
