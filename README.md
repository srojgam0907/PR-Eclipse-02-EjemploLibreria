# PR-Eclipse-02-EjemploLibreria

## Reflexión final

### 1. ¿Qué pasaría si exporto el proyecto a un .zip y se lo paso a un amigo o me lo llevo al ordenador de casa? ¿Funcionaría? Razona la respuesta.
  Depende de como este añadida la libreria al proyecto. Si se ha añadido con una ruta absoluta no funcionará porque la libreria esta fuera de la carpeta del proyecto, pero si se añade con una ruta relativa si funcionará porque la libreria está dentro del proyecto.

### 2. ¿Qué pasaría si eliminas el archivo .jar de la carpeta lib? (puedes moverla a otro directorio para probarlo) ¿Qué ha pasado y por qué?
  Eclipse ya no encuentra la ruta a la libreria y en las partes del codigo donde se usan métodos de esta da error al ejecutarlo.

### 3. Y si agrego la librería con Add External JARs.... ¿Observas alguna diferencia en la configuración del Build Path? ¿Crees que si lo exporto a .zip y se lo paso a un compañero le funcionaría?
  Cuando añades así la librería, la ruta de guardado que aparece es más larga porque pertenece al ordenador con el que estes trabajando. Si se lo pasas a otro compañero y lo abre en otro ordenador no funciona porque esa ruta solo existe en el ordenador en el que es añadida esa libreria. 

### 4. ¿Por qué no es recomendable usar Add External JARs… en proyectos que vas a compartir?
  Al usar una ruta absoluta, esa ruta donde esta la libreria solo existe en mi ordenador, por lo que si se pasa el proyecto a otro ordenador no funcionaría porque no encontraría la ruta. 
