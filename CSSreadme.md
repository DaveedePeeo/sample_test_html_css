**CSS = Cascading Style Sheets**

Lo style sheet è il foglio sul quale definiamo lo stile estetico della pagina 

Per indicare sul foglio di stile quale elemento vogliamo modificare utilizziamo i selettori
- - - - - - - - - - - - -

**SELETTORI**

li {
    margin: 0; 
    list-style: circle inside;
}
**li** è il selettore di un elemento e tra le graffe un set di **regole css**

••••••••••••••••••••••
.important {
    font-weight: bold; 
    background: red
}

**.important** è un selettore di classe e selezione ogni elemento con quella classe assegnata nel foglio HTML

••••••••••••••••••••••
#main-nav{
    color: #333;
}
**#main-nav** è un selettore id e selezione ogni elemento con quell'ID nella classe, l'ID dovrebbe essere utilizzato poco

••••••••••••••••••••••
input[type='email']{
    border: 2px solid #333;
}
**input[type='email']**
in questo caso stiamo utilizzando un attributo come selettore CSS

- - - - - - - - - - - - - - - 

**PSEUDOSELETTORI**

1. ••••••••••••••••••••••
a:link{
    color: green;
}

Cambio il colore di link cliccabili con uno pseudoselettore

2. ••••••••••••••••••••••

a:visited {
    color: orange;
}

Cambio il colore di link cliccabili già visitati con uno pseudoselettore

3. ••••••••••••••••••••••

a:hover {
    text-decoration: underline
}
Cambio il colore di link cliccabili quando ci passo sopra con uno pseudoselettore

4. ••••••••••••••••••••••

a:active{
    border 1px solid;
}
Cambio il colore di link attivi quando ci clicco  con uno pseudoselettore







- - - - - - - - - - - - - -
**STRUTTURARE UNA REGOLA CSS**

h1 {
    color: red;
}


1. h1 è un selettore che indica quale elemento vogliamo modificare

2. tra le graffe abbiamo il corpo di tutte le modifiche che vogliamo eseguire

3. tra le graffe inseriamo il tipo di modifica/ la decorazione e il valore
- - - - - - - - - - - - - - - - -

