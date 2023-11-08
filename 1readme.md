**HTML**
HTML sta  per HyperTest MarkUp Language che consiste in diversi elementi che possiamo utilizzare per strutturare una pagina web

- - - - - - - - - - - - - - - - - - - - -

**COSA SONO GLI ELEMENTI HTML?**

Un elemento HTML inizia di solito con un tag di apertura che consiste nel nome dell'elemento rinchiuso in parentesi angolari. Il tag di apertura indica dove l'elemento inizia

Il tag di chiusura è chiuso anch'esso in parentesi angolari ma include anche uno slash prima del nome dell'elemento

Tutto ciò che è circoscritto fra il tag di apertura e quello di chiusura è il contenuto 

Non tutti gli elementi HTML seguono questo tipo di pattern alcuni hanno un solo tag come 

<img>
<input>

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

**NESTING**

Gli elementiu possono essere posizionati dentro altri eleementi questo processo si chiama NESTING, vediamo un esempio: 

<div class="my-list">
  <h4>My list:</h4>

  <ul>
     <li>Apple</li>
     <li>Orange</li>
     <li>Banana</li>
  </ul>
</div>

- - - - - - - - - - - - - - - - - - - - - - - - - -

**ATTRIBUTI**

Gli elementi HTML possono avere degli attributi che contengono informazioni extra sull'elemento che non apparirano nel contenuto 

<img src="https://images.unsplash.com/photo" width="50">

in questo caso l'elemento IMG contiene 2 attributi 

1. src= -> che specifica il percorso sorgente dell'immagine 
2. width = -> che specifica la larghezza dell'immagine in pixel 

Una attributo è caratterizzato da: 

1. lo spazio fra l'attributo e il nome dell'elemento
2. sono aggiunti nel tag di apertura
3. possono essereci n attributi
4. gli attributi solitamente hanno un nome e un valore

alcuni attributi possono non avere valore e sono booleani:

<button onclick=“alert('Submit')" disabled>Button</button>

se vogliamo disabilitare questo bottone basterà passare l'attributo disabled senza valori

- - - - - - - - - - - - - - - - - - - - - - - - - - 

**ELEMENTI HTML COMUNI**

1. Section Elements
<div>
<span>
<header>
<footer>
<nav>
<main>
<section>

Questi sono utilizzati per organizzare il contenuto in diverse sezioni 

2. Text element 

<h1> to <h6>
<p>
<div>
<span>
<ul>
<ol>
<li>

Organizzano il contenuto in blocchi di testo, sono importanti per l'accessibilità e la SEO

3. Forms

<form>
<input>
<button>
<label>
<textarea>

Questi elementi combinati creano dei form che possono essere riempiti e invati

4. Immagini e link

<img>
<a>

elementi utilizzati per inserire un immagine o creare un hyperlink

5. Altri

<br>
<hr>

Utilizzati per aggiungere uno spazio 

- - - - - - - - - - - - - - - - - - - - - - -

**Block Level / Inline**

Gli elementi block level sono elementi che sono su una linea e ne prendono tutto lo spazio

Gli inline element sono element che non iniziano su una nuova riga e non prendono tutto lo spazio 

- - - - - - - - - - - - - - - - - - - - - - -

**Commenti**

I commenti permettono di inserire delle note e sono contenuti in questo modo

<! - - - - - -> sono ignorati e invisibili sono nell'editor di codice

- - - - - - - - - - - - - - - - - - - - - - - - - - 

**Tips**

1. gli elementi sono case insensitive ma è best practice scriverli in lowercase

2. chiudere i tag!

3. fare nesting in modo corretto

4. non si possono mettere insieme apici singoli e doppi apici




