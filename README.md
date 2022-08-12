# Aprendiendo _Markdown_

Esto es un parrafo

It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

Aplicando _cursiva_ y **negrita** y ahora **_junto_**

# Encabezado nivel 1
## nivel 2
--- 
### nivel 3
---
#### nivel 4
---
###### 6
---

Para crear enlaces: [Youtube](https://youtube.com)

Para crear un enlace que nos lleve a un mismo lugar de la pagina, por ejemplo a una seccion: [Aprendiendo _Markdown_](#aprendiendo-markdown)

Para mostrar una imagen local:
![Un pokemon](img/Scorbunny.png)

Para mostrar una imagen de internet:
![Un pokemon](https://www.purina-latam.com/sites/g/files/auxxlc391/files/styles/kraken_generic_max_width_960/public/purina-10-datos-curiosos-sobre-los-gatos.png)

---
Listas y sublistas:
### listas ordenadas

1. Lista 1
1. lista 2

### listas desordenadas
* lista 1
    * sublista  0.1
        * sublista de sublista
* lista 2
    * sublista 0.2
        * sublista de sublista
---
Citas

* cita en linea:
    > siempre tienes opcion de no tener opinion. - Marco Aurelio
* Cita en bloque:
    >Todo lo que escuchamos es una opinión, no un hecho
    >
    >Todo lo que vemos es una perspectiva, no la realidad
    >
    >Marco Aurelio
---
### Tablas

| nombre | edad | estado civil |
|---     |---   |---           | 
Alexander| 28   | soltero      |
Carla    | 25   |  casada      |
Jaime | 35 | Divorciado| 

---
### Para colocar codigo
* En linea:
    * Para declarar una variable en JS se hace asi: `let`

* en bloque: Una funcion en js:
    ``` js
    function sumar(a,b){
        return a+b
    }
    ```
* Markdown tambien puede interpretar el lenguaje html:
    <form>
        <label for="q">Buscar:</label>
        <input  type="search" id= "q" name= "q"></input>
    </form>

<!-- Comenterio -->
----
### Escape de caracteres
por ejemplo, quisiera mostrar como se hacen las _cursivas_ y **negrita** en markdown:
    \*\*negrita** y \_cursiva_ 
 