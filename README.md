# Resumen

Tener instalado node.js
nom init -y
npm install sass --save-dev
npm install -g sass
sass --watch sass:css (si detengo el terminal ya no muestra cambios)
<link rel="stylesheet" href="./css/style.css">

$variable:red (crea variable)

_nav(crear archivo partials)

@use 'nav' (llamar partials)

variables.$color(llamar una variable del partials variables)

==nesting(anidado)==
ul{
    li{
        a{
        }
    }
}
====

&(representa al padre)

#{$variable}(para usar variables como propiedad o selector)(interpolacion)

@for $iterador from 1 through 5{ } (para crear ciclos)

@if $iterador == 5{ } (para condicionales)

@mixin nombredelmixin{ } (para reutilizar codigo repetido)

@include nombredelmixin (para llamar al mixin)

@function size($value){
    @return $value*$unit;
}
