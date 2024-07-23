# Componente-de-Zoom

Descripción general.
Este componente creado en java nos permite la posibilidad de realizar zoom en nuestros proyectos.

# API
La clase ZoomPanel nos permite crear un componenete de zoom, esto se logra modificando el tamaño de los componenetes.

Se tiene como vaiables globales a zoom  de tipo de double que almacena el valor inicial del zoom aplicado a la ventana, y a la variable ariginalBounds de tipo Map<Component, Rectangle> que nos sirve para alacenar el tamaño de los componentes usados.


Como metodos:
private void Original(): nos sirve para guardo los valores del tamaño de un componente en la variable originalBounds.

public void setZoom(double newZoomFactor): a este métod se le pasa el valor de zoom a aplicar, llama al método Ajustar() para modificar el tamaño de los componentes.

private void Ajustar(): con este método se asignan los nuevos valores del tamaño de los componentes.



Dentro del constructor de la clase se tiene programado el evento mouseclicked para modificar el tamaño, a la hora de pulsar con el botón derecho disminuye y con el botón izquierdo aumenta.

# Agregar como componente:

Descargar el archivo ZIP.

Descomprimir y abrir en el IDE (en este caso Netbeans).

La clase ZoomPanel es la que nos va a servir para crear el componente:
![image](https://github.com/user-attachments/assets/5c49336e-570c-4f9f-93f8-8b1c4de52936)
![image](https://github.com/user-attachments/assets/4c38202a-27cd-4566-9cbf-7132419c3e8a)


Des esta manera tendremos el componente en nuestra paleta:
![image](https://github.com/user-attachments/assets/b9320ff6-521a-4812-85ab-7bc7e91b8c04)

Para su uso solo basta con arrastrarlo al JFrame y adaptarlo a su tamaño.

# Uso
Video demostrativo:









