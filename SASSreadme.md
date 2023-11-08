**SINTATICALLY AWESOME STYLESHEETS**

SASS:

1. Linguaggio che estende il CSS 

2. Sass provvede un compiler

3. file .scss


**VARIABILI**
è possibile utilizzare le variabili 

$red: hsl(0, 100%, 50%)

.button.danger {
    color: $red
    border: 1px solid $red
}

- - - - - - - - - - - - - -

**NESTING**

.btn {
    &:focus{}
    &:hover{}
    &:active{}
}

creo un nesting di regole CSS al posto di richiamre tre selettori, in questo nesting associato alla classe .btn definisco le regole CSS con gli pseudoselettori per quando il bottone avrà tre diversi stati

- - - - - - - - - - - - - - - - 

**MIXIN**

processo inverso in cui definiamo una regola CSS e la applichiamo con la stessa dicitura agli elementi 

1. definisco la regola CSS con @mixin
@mixin flex-column {
    display: flex;
    flex-direction: column
    background: gray
}

2. la applico agli elementi identificati con le classi che ci interessano con la keyword include nella regola CSS

.card{
    @include flex-column
}

.aside{
    @include flex-column
}

il MIXING può anche prendere argomenti: 

@mixin cool-button($color, $bg){
    display: flex;
    color: $color
    background: $bg;
}

.btn-orange{
    @include cool-button(black, orange);
}

in questo modo ho creato un mixin con delle variabili che vado a definire quando applico il mixin a un elemento HTML -> utilizziamo la stessa regola ma ne cambiamo le specifiche

- - - - - - - - - - - - - - - -

**FUNCTIONS**

