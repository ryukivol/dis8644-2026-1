# sesion-04a

# Apuntes 31/03

### Sobre el primer gran proyecto

Se nos informó que el gran proyecto 1 (solemne 1) sería en grupos de tres personas, por lo que se dio el espacio para poder formar grupos (si alguien no tenía grupo al final de la clase, no podía salir). También se informó que estos grupos no son definitivos por todo el semestre, por lo cual podemos cambiar de grupo para los siguintes proyectos grupales.

---

### Circuito astable y monostable

Nos volvieron a mencionar los circuitos astables y monostables, recordando el cómo unimos los dos para lograr hacer el atari punk, y ésta vez íbamos a hacer algo parecido solo que ésta vez teníamos que invertir los circuitos. 

- Atari punk : ``Astable -> Monostable``
- Circuito de hoy: ``Monostable -> Astable``

Misa nos dibujó el esquemático en la pizarra para que podamos recrear los circuitos y nos indicó el cómo teníamos que unirlos.

![Esquemático en pizarra](./imagenes/esquematico-misa.jpg)

Con mi compañero nos dividimos el trabajo, por lo que uno trabajó en el monostable (yo) y el otro en el stable (mi compañero) para después conectarlos. En el primer intento a mi compañero le prendía el LED pero no le funcionaba el parlante, y a mi directamente no me prendía el LED, por lo que partimos un poco mal y decidimos volver a hacerlo desde cero y de manera más ordenada siguiendo el orden de los pins del chip. En el segundo intento se volvieron a repetir los mismos errores pero no lograbamos identificar en dónde estabamos fallando, por lo que volvimos a hacerlo desde cero. En el tercer intento, a mi compañero le dejó de prender el LED y yo seguía sin poder prender el mio, por lo que nos empezamos a desesperar un poco ya que podíamos escuchar a compañeros que ya les estaba funcionando y nosotros no podíamos lograr que ninguna de las dos partes funcione, y volvimos a hacerlo desde cero. En el cuarto intento por fin me prendió el LED, pero este se apagaba cuando presionaba el botón y no estoy seguro de si tenía que ser así o al revés (que se prenda cuando se apreta el botón), pero lo consideré una victoria de igual manera.

![Circuito monostable funcionando, o eso creo](./imagenes/monostable.gif)

Como aún lo funcionaba el circuito de mi compañero, probamos cambiando el chip ya que existía la posibilidad de que haya muerto en el proceso, pero al hacer el cambio tampoco funcionó por lo que decimos que era momento de pedir ayuda y mi compañero fue a hablar con Misa. Cuando volvió, nos dimos cuenta de que el problema es que estabamos conectando los dos caimanes al mismo capacitor en vez de tirar un caimán a tierra, y la razón por la cual el LED no prendía es porque se había quemado. Cuando se hicieron todos los cambios, funcionó el circuito astable y por fin pudimos conectar los dos circuitos.

![Circuitos interconectados](./imagenes/astable-monoestable-bueno.jpg)

Fue un proceso un poco frustrante ya que tuvimos que volver a hacer los circuitos varias veces desde cero sin lograr identificar el problema, por lo que al poder lograrlo se sintió como una liberación de la cárcel llamada 555 (broma, adoro al chip).
