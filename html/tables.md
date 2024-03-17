# Le tabelle

Torna all'[indice](../toc.md)

---

Le tabelle sono utili per mostrare dati in formato tabulare. In passato sono state utilizzate anche per gestire il layout della pagina, ma questo tipo di utilizzo deve essere evitato.

Per creare una tabella utilizziamo il tag `table`. Al suo interno trovano posto le righe `tr` e all'interno delle righe inseriremo le celle, che possono essere di intestazione `th` o di dati `td`.
Per inserire una didascalia c'è `caption`.

```html
<table>
    <caption>Insert the caption here</caption>
    <tr>
        <th>Col 1</th>
        <th>Col 2</th>
        <th>Col 3</th>
    </tr>
    <tr>
        <td>Row 1, cell 1</td>
        <td>Row 1, cell 2</td>
        <td>Row 1, cell 3</td>
    </tr>
    <tr>
        <td>Row 2, cell 1</td>
        <td>Row 2, cell 2</td>
        <td>Row 2, cell 3</td>
    </tr>
</table>
```

### Sezioni

Le righe di una tabella non sono tutte uguali. Quelle di intestazione e quelle di chiusura non sono come quelle centrali che contengono i dati.
Il tag `thead` permette di raggruppare le righe di intestazione. Può essercene solo una per tabella e compare all'inizio. Allo stesso modo il tag `tfoot` permette di raggruppare le righe di chiusura, può essercene solo uno e compare dopo `thead`. Infine `tbody` raggruppa le righe centrali con i dati. In una tabella possono essere definiti anche più `tbody` se necessario per separare i dati in blocchi.

```html
<table>
    <caption>Insert the caption here</caption>
    <thead>
        <tr>
            <th>Col 1</th>
            <th>Col 2</th>
            <th>Col 3</th>
        </tr>
    </thead>
    <tfoot>
        <tr>
            <th>Insert the footer here</th>
        </tr>
    </tfoot>
    <tbody>
        <tr>
            <td>Row 1, cell 1</td>
            <td>Row 1, cell 2</td>
            <td>Row 1, cell 3</td>
        </tr>
        <tr>
            <td>Row 2, cell 1</td>
            <td>Row 2, cell 2</td>
            <td>Row 2, cell 3</td>
        </tr>
    </tbody>
</table>
```

### Letture

> [!TIP]
> C. Musciano, B. Kennedy, _HTML & XHTML, The Definitive Guide_, O'Reilly, 2006, 6th ed
>
> - Chap 10: Tables


> [!TIP] > _HTML Dog_, [www.htmldog.com](https://www.htmldog.com/)
>
> HTML Tutorial
>
> - [Tables](https://www.htmldog.com/guides/html/beginner/tables/)

---

Torna all'[indice](../toc.md)
