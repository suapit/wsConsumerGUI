# wsConsumerGUI
Daemon para interactuar con el WS de suap.
El Daemon esta implementado en python 3 y a pesar de ser un ejemplo práctico de interacción, permite realizar un consumo completo del WS de suap.
El Daemon monitorea una carpeta a la espera de archivos que son mensajes para enviar al WS de suap y devuelve la respuesta en otra carpeta. Dependiendo de la configuración puede procesar la sección VIEW de la respuesta antes de devolver la respuesta. 
