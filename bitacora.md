# FisicosInteractivos1-2026-20

Hola, esta es mi bitácora para Sistemas Físicos Interactivos,
En la siguiente bitácora podrás encontrar pequeños fragmentos de lo que hice en el curso, unas breves explicaciones de qué se hace y de qué se trata cada elemento visto durante el curso, espero sea útil para el que esté leyendo esto.






# 1. Audio
Strudel REPL es una de nuestras principales herramientas, es una página de creación de audio online con la que puedes realizar pistas de audio, es relativamente sencillo, solo es cuestión de guiarte de tu vena musical y formar una pequeña pista, no te presiones, experimenta lo que necesites.

```
Con .sound() modificamos el sonido de las notas por la caja de ritmos
Con setcpm() definimos el tempo
Con - o ~ agregamos silencios en una secuencia
Con <> podemos controlar los ciclos que se demora en sonar la secuencia
Con [] añadimos secuencias secundarias, son un complemento
Con la multiplicación podemos aumentar la velocidad, con la división podemos bajarla
Con , podemos hacer que las notas suelen en paralelo
Con ` podemos distribuir las notas en párrafos

```
Un pequeño ejemplo que hice :
````
// Your New Home - The Amazing Digital Circus
setcpm(90/6)

let melody = 
note
 (
    ` 59 66 63 63 61 59 - - -
      66 63 63 [61 [62 - - - 63]] - - - -
      66 63 63 61 59 56 59 61 66 56 59 61 59 - -
      59 66 63 63 61 59 - - - 
      66 63 63 [61 [62 - - - 63]] - - - -
      66 63 63 [61 [62 - - - 63]] - - - -
      63 - 63 - 56 - - 63 60 60 58 56 - - - 
      63 60 60 [58 [59 - - - 60]] - - - -
      63 60 60 58 56 53 56 58 63 53 56 58 56 - -
      68 67 67 64 65 - - - 63 60 60 [58 [59 - - - 60]] - - - -  
      63 60 60 56 58 52 56 58 63 53 56 58 56 - - 56 55 54 53 - - - -
      53 52 51 50 - - - -  50 49 48 47 - - - 47 48 51 55 61 - - - - 
      [56]/12 - - - - - - - - - - - -
    `
 )   
  .sound("piano")
  .slow(12)

$melody : melody
  
  )
````




# 2. Visual
Estamos usando TouchDesigner, un programa para la creación de visuales, este tiene varios tipos de operadores con el fin de estructurar lo que se va a realizar en el programa, estos son:

```
COMP - Son contenedores, sirven para jerarquizar / organizar en "cajas" los demás operadores
TOP  - Se encargan de manejar imágenes y vídeos, con el fin de controlar o renderizar texturas
CHOP - Se encargan de datos numéricos, principalmente control, sensores y audio
SOP  - Se encargan de manejar geometría 3D (vertices, figuras geométricas)
ROP  - Con estos se exporta el resultado final renderizado.
MAT  - Se usan para definir los materiales en 3D, por ejemplo: Color, Brillo, Transparencia, etc.
DAT  - Manejan los datos estructurados, como texto o código escrito en Python
Custom - Está para que los usuarios organicen sus shaders según su preferencia y los guarden

```


# 3. Integración audiovisual

# 4. Open Stage Control

# 5. MediaPipe performer

# 6. Prototipo

# 7. Performance

# 8. Conclusión del curso: ¿Qué se aprendió?

