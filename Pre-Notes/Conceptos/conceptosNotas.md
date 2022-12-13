# Conceptos 

## Expresiones vs Statements 
---

### Expressions

Es cualquier fragmento de código que se retorna algún valor. Por ejemplo:

    1 + 2 = 3

La operación 1 + 2 retorna el valor 3 y por eso es una expresión.


### Tipos básicos de expresiones

**Expresiones aritmeticas** son operraciones matemáticas, estas retornan un valor númerico. 

    4 + 3 = 7
    12 - 6 = 6
    6 * 5 = 30

**Strings** pueden ser cadenas de texto o concatenaciones.

    "hola"
    "hola" + "me llamo Alexa"

**Expresiones lógicas** son esas cuyo valor retornado es un valor booleano.

    2 < 3 = true
    
**Expresiones primitivas** cuando cosnstruimos una variable y le damos un valor es una expresion, porque al momento de mandar a llamar nuestra variable nos retorna el valor que definimos anteriormente.

    var nomnbre = "alexa"
    nombre = alexa

**Expresión de asignación**
1. Mixta (retorna un valor y hace algo). Ejemplo:

    a = 3 
    retorna = 3

**Exrpresión con efecto secundario**
 
 Eje 1:

    contador = 1;
    contador++ == 2;
    ++contador = 3; ...

Eje 2:
    contador = 1
    contador *= 2 == 2

---

## Staments
Es bloque de código que HACE ALGO, pero por si solo no hace nada. Por ejemplo:

    if(true) {}

El código no devuleve ningún valor, pero agregando expresiones puede REALIZAR UNA ACCIÓN.

### Tipos básicos de Statements

**Declaration statements**son aquellas que son declaradas, pero al comienzo no retornan nada. Por lo general se usan las keywords *var* y *function*

    var nombre; // se crea el espacio en memoria, pero no se le un valor, por lo tanto tampoco nos devuelve uno.

    function suma(a - b){ 
        *valores indefinidos 
    } // Al no definir los valores de a y b no retorna ningún resultado.

**Funtion expressions VS Funtions statements** a veces dependiendo del contexto las funciones peuden ser statements o expression.

*Function declarativa*

    function resta(a - b) {
    *bloque de código
    B 
     s}

*Function expression*

    var resta (esta es la expresión dado que es una variable y estas retornan un valor) = function suma(a + b) {
        bloque de código*
    }

### Condicional statements
