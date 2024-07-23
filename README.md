# Componente-de-Zoom

Este componente creado en java nos permite la posibilidad de realizar zoom en nuestros proyectos.

# API
La clase ZoomPanel nos permite crear un componenete de zoom, esto se logra modificando el tamaño de los componentes.

Se tienen como variables globales a zoom de tipo de double que almacena el valor inicial del zoom aplicado a la ventana, y a la variable originalBounds de tipo Map<Component, Rectangle> que nos sirve para almacenar el tamaño de los componentes usados.


Se tienen los siguientes métodos:

private void Original(): nos sirve para guardar los valores del tamaño de un componente en la variable originalBounds.

public void setZoom(double newZoom): a este método se le pasa el valor de zoom a aplicar llama al método Ajustar() para modificar el tamaño de los componentes.

private void Ajustar(): con este método se asignan los nuevos valores del tamaño de los componentes.

Dentro del constructor de la clase se tiene programado el evento mouseclicked para modificar el tamaño, a la hora de pulsar con el botón derecho disminuye y con el botón izquierdo aumenta.

# Agregar como componente:

Descargar el archivo ZIP.

Descomprimir y abrir en el IDE (en este caso Netbeans).

La clase ZoomPanel es la que nos va a servir para crear el componente:

![image](https://github.com/user-attachments/assets/8b18d49c-4c4d-46b4-9c09-d0fa9bfaef41)

![image](https://github.com/user-attachments/assets/82df3e2f-4feb-4ab3-8397-df7bdc7029a7)


Des esta manera tendremos el componente en nuestra paleta:

![image](https://github.com/user-attachments/assets/cc117932-eecd-471e-8e46-d0f84d451841)

Para su uso solo basta con arrastrarlo al JFrame y adaptarlo a su tamaño.

# Uso

Video demostrativo:









