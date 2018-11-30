Matematica Discreta
===================

Insiemistica
------------

Il concetto di insieme è primitivo, nel senso di intuitivo e non è necessario
ricorrere ad altri concetti per definirlo.

Insieme
    È una raccolta di oggetti ben definiti che costituiscono gli elementi
    dell'insieme.

    Gli insiemi si indicano con lettere maiuscole (:math:`A, B, C, \dots`). Gli
    elementi si indicano con lettere minuscole (:math:`a, b, c, \dots`).

    Gli insiemi possono essere finiti o infiniti se rispettivamente contengono
    un numero finito o infinito di elementi.

Notazione logica
    Notazioni usate nella enunciazioni di proposizioni logiche:

    * Quantificatore universale (:math:`\forall`) (si legge *per ogni*)
    * Quantificatore esistenziale (:math:`\exists`) (si legge *esiste*)
    * Quantificatore unico (:math:`\exists!`) (si legge *esiste uno ed uno solo*)
    * Implica (:math:`\implies`)
    * Doppia implicazione (:math:`\iff`) (si legge *se e solo se*)
    * Dichiarazione (:math:`:` o :math:`|`) (si legge *tale che*)
    * Congiunzione (:math:`\land`)
    * Disgiunzione (:math:`\lor`)

Dichiarazione
    Gli insiemi si possono dichiarare o descrivere mediante:

    * Elencazione (:math:`A = \{a, b, c\}`)
    * Proprietà caratteristica (:math:`A = \{n \in N : 0 \leq n \leq 5\}`)
    * Diagramma di Venn

Appartenenza (:math:`\in` e :math:`\notin`):
    :math:`A = \{a, b, c\} \implies a, b, c \in A`
    :math:`A = \{a, b\} \implies c \notin A`

Insieme vuoto
    È un insieme privo di elementi. Si indica con :math:`\varnothing`.

    :math:`A = \varnothing = \{\}`.

Insieme continuo
    È un insieme di elementi ordinabili in cui dati due elementi è possibile
    sempre individuare un elemento compreso tra essi.

    :math:`\forall x, y \in A \implies \exists z \in A : x < z < y`

Insieme discreto
    È un insieme non continuo. Tutti gli insiemi finiti sono discreti.

Esempi di insiemi:

* :math:`A = \{x \in N : 1 \leq x \leq 10\} = \{1, 2, 3, \dots, 10\}`
  (insieme dei numeri naturali compresi tra uno e dieci estremi inclusi)
* :math:`B = \{2n : n \in N\} = \{0, 2, 4, 6, \dots, 2n, \dots\}`
  (insieme dei numeri naturali pari)
* :math:`C = \{2n : n \in Z\} = \{0, 2, -2, 4, -4, \dots\}`
  (insieme dei numeri interi pari)
* :math:`D = \{2n + 1 : n \in N\} = \{1, 3, 5, 7, \dots, 2n + 1, \dots\}`
  (insieme dei numeri naturali dispari)
* :math:`E = \{2n + 1 : n \in Z\} = \{1, -1, 3, -3, \dots\}`
  (insieme dei numeri interi dispari)
* :math:`F = \{n^2 : n \in N\} = \{0, 1, 4, 9, , 16, \dots, n^2, \dots\}`
  (insieme delle potenze di numeri naturali)
* :math:`G = \{n^2 : n \in Z\} = \{0, 1, 4, 9, , 16, \dots, n^2, \dots\} = F`
  (insieme delle potenze di numeri interi, uguale a :math:`F`)
* :math:`Q = \{\frac{m}{n} : m, n \in Z, n \neq 0\}
  = \{0, 1, 4, 9, , 16, \dots, n^2, \dots\} = F`
  (insieme dei numeri razionali)

Sottoinsieme
    Si dice che X è sottoinsieme di A se si verifica uno dei seguenti casi:

    * Inclusione debole (:math:`\subseteq`):
      :math:`X \subseteq A \iff \forall x \in X \implies x \in A`
    * Inclusione stretta (:math:`\subset`):
      :math:`X \subset A \iff \forall x \in X \implies x \in A
      \land \exists y \in A : y \notin X`

    Ogni sottoinsieme :math:`A` ha due sottoinsiemi **impropri**, che sono
    :math:`\varnothing` e l'insieme :math:`A` stesso. Tutti gli altri
    sottoinsiemi si dicono **propri**.

Proprietà degli insiemi
    Tutti gli insiemi godono delle seguenti proprietà:

    * :math:`\varnothing \subseteq A, \forall A`
    * :math:`A = B \iff A \subseteq B \land B \subseteq A` (**doppia inclusione**)

Confronto
    Due insiemi :math:`A, B` si dicono confrontabili se si verifica una delle
    seguenti condizioni:

    * :math:`A = B`
    * :math:`A \subset B`
    * :math:`B \subset A`

    Esempi:

    * :math:`N \subset Z \subset Q` quindi :math:`N, Z, Q` sono confrontabili
    * :math:`A = \{a, 2, 3\}, B = \{1, a, b\}, C = \{1, 2\}, D = \{a, b\}`

      * :math:`A \neq B, A \not\subset B, B \not\subset A`
        quindi :math`A, V` non sono confrontabili
      * :math:`A \neq C, A \not\subset C, C \subset A`
        quindi :math:`A, C` sono confrontabili
      * :math:`B \neq D, B \not\subset D, D \subset B`
        quindi :math:`B, D` sono confrontabili
      * :math:`C \neq D, C \not\subset D, D \not\subset C`
        quindi :math:`C, D` non sono confrontabili

Aritmetica modulare
-------------------
Lorem ipsum.