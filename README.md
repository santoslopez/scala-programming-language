## Aprendiendo programación en el lenguaje Scala

La estructura de programación del lenguaje Scala es similar a Java y de está forma no debería ser un problema para nuestros amigos que llevan tiempo programando en Java, aunque es fácil de aprender sino sea tenido experiencia en este hermoso mundo de la programación, pueden buscar vídeos tutoriales en [Youtube](https://www.youtube.com/watch?v=e2E7D7DTzKw) 

### Instalando lo necesario

Si nuestro sistema operativo es Ubuntu deben instalar lo siguiente:

```markdown
santoslopez@harvard:~$ sudo apt-get install scala
[sudo] password for santoslopez: 

Seguramente les pide que ingresen su contraseña, una vez puesto empezara con la descarga de los archivos y los instalara, esto nos va servir para poder compilar nuestros archivos.scala

```
Si nuestro sistema operativo es Windows (o cualquier otro) probablemente te interese descargar el archivo para su instalación desde el sitio oficial de [Scala](https://www.scala-lang.org/download/).

### Compilando

Para compilar nuestro archivo.scala solo necesitamos escribir lo siguiente: 
```markdown
santoslopez@harvard:~$ scalac HolaMundo.scala

```
Puede hacerles familiar esto, en java su equivalente es
```markdown
santoslopez@harvard:~$ javac HolaMundo.java
```

### Mostrando nuestros resultados
Para poder visualizar lo que escribimos en el archivos necesitamos escribir lo siguiente: 
```markdown
santoslopez@harvard:~$  scala -classpath . HolaMundo
```

### Nota
Donde HolaMundo hace referencia al nombre de nuestro archivo.scala
