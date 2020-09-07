# SoftwareThreads


Pasos para implementar el metodo START de la clase Thread

1-Creamos una clase que implemente la intefaz Runnable, con el metodo RUN()
2-Escribimos el codigo de la tarea dentro del metodo RUN
3-(Dentro del metodo InciarJuego)Instanciamos la clase creada y almacenamos la instancia en la variable del tipo RUNNABLE
Runnable r= new miClaseImplementRunable
4-Creamos la instancia de la clase THREAD pasando como parametros al constructor el OBJETO Runnable anterior
Thread T= new Thread(r);
5-Ponemos en marcha el Hilo de ejecucion con el metodo start de la clas Thread
T.start(); => con start estoy llamando al Metodo RUN()
