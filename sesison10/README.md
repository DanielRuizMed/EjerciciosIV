## Ejercicio 1

**Instalar etcd3, averiguar qué bibliotecas funcionan bien con el lenguaje que estemos escribiendo el proyecto (u otro lenguaje), y hacer un pequeño ejemplo de almacenamiento y recuperación de una clave; hacer el almacenamiento desde la línea de órdenes (con etcdctl) y la recuperación desde el mini-programa que hagáis.**

Primero instalamos etcdtl tanto cliente como servidor

![1_1](./img/1_1.png)

![1_2](./img/1_2.png)

Primero instalamos etcdtl guardamos la clave desde la línea de comandos

![1_3](./img/1_3.png)

instalamos en nuestro proyecto etcd para utilizarlo

![1_4](./img/1_4.png)

y hacemos el programa que muestra la clave insertada anteriormente desde la línea de comandos

![1_5](./img/1_5.png)
                   
## Ejercicio 2
**Realizar una aplicación básica que use express para devolver alguna estructura de datos del modelo que se viene usando en el curso.**

Primero creamos la aplicación básica que usa express y que devuelve un json.

![2_1](./img/2_1.png)

Aplicación funcionando

![2_2](./img/2_2.png)
 
## Ejercicio 3
**Programar un microservicio en express (o el lenguaje y marco elegido) que incluya variables como en el caso anterior.**

Esta es la aplicación creada que utiliza las variables mencionadas anteriormente.

![3_1](./img/3_1.png)

Resultado correcto

![3_2](./img/3_2.png)

Resultado no se recibe lo esperado

![3_3](./img/3_3.png)
 
## Ejercicio 4
**Crear pruebas para las diferentes rutas de la aplicación.**

Creamos el programa y añadimos las librerías necesarias para hacer los test de integración

![4_1](./img/4_1.png)

creamos los test y los ejecutamos

![4_2](./img/4_2.png)
 
## Ejercicio 5
**Experimentar con diferentes gestores de procesos y servidores web front-end para un microservicio que se haya hecho con antelación, por ejemplo en la sección anterior.**

Instalamos pm2 

![5_1](./img/5_1.png)

y arrancamos 4 instancias 

![5_2](./img/5_2.png)

vemos los logs de los procesos

![5_3](./img/5_3.png)

![5_4](./img/5_4.png)

![5_5](./img/5_5.png)

probamos otro gestor de procesos forever

![5_6](./img/5_6.png)
 
## Ejercicio 6
**Usar rake, invoke o la herramienta equivalente en tu lenguaje de programación para programar diferentes tareas que se puedan lanzar fácilmente desde la línea de órdenes.**

Instalamos grunt y creamos nuestro fichero Gruntfile con todas las tareas a ejecutar start/test...

![6_1](./img/6_1.png)

y las probamos

![6_2](./img/6_2.png)
