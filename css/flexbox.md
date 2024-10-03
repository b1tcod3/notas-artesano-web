# Flex Box

## Definición
: modelo unidimensional de layout. Puede manejar el layout en una sola dimensión a la vez- ya sea como fila o como columna


## Características

- Mejora la capacidad de alinear items
- Trabaja con dos ejes: principal y cruzado

## Ejes

## Principal (main axis)
:El cual corre en la misma dirección en que se colocan los elementos flexibles

## Transversal (cross axis)
:El cual corre penpendicular  a los elementos flexibles


## Propiedades

>flex-direction (defecto: row)
: define el eje principal y la dirección.

>flex-wrap (defecto: nowrap)
: Fluidez multilínea

>flex-flow (defecto: nowrap)
: Combina flex-direction y flex-wrap

>align-items (defecto: stretch)
: Controla dónde se ubican los elementos flexibles en el eje transversal

>justify-content (defecto: flex-start)
: Controla dónde se ubican los elementos flexibles sobre el eje principal


## Conceptos básicos

Flexbox Container
: Es el elemento Padre. Tiene la propiedad display: flex. 

Caja Flexible (Elemento flexible)
: Cada elemento hijo de un flexbox container 

# Código

- crear un elemento flex

```css
section {
  display: flex;
}
```

