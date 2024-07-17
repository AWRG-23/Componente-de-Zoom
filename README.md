# Componente-de-Zoom

Descripción general.
Este componente creado en java nos permite tener en la paleta de componenetes un panel para hacer zoom fácil de implementar en los proyectos.

# API
La clase ZoomPanel nos permite crear un componenete de zoom

Se tiene como variable global a:
double zoomFactor: esta variable nos sirve de referencia para modificar el zoom de la pantalla.

Como metodos:
public void Zoom(double zoomfactor): este metodo hace posible el cambio de zoom en la pantalla.

protected void paintComponent(Graphics g): con este método haces posible el cambio de zoom en los componentes que integra el panel.

protected void paintChildren(Graphics g):se hace posible que los compnentes del panel no se dupliquen.

Dentro del constructor de la clase  tenemos programado el evento mouseclicked para modificar el tamaño de la pantalla, a la hora de pulsar con el botón derecho disminuye y con el botón izquierdo aumenta.

# Agregar como componente:

Descargar el archivo ZIP.
Descomprimirlo y abrirlo en nuestro IDE Netbean.
La clase ZoomPanel es la que nos va a servir para crear el componente:
![image](https://github.com/user-attachments/assets/e205c0b2-0b0a-495a-ad60-df88e6a72660)

![image](https://github.com/user-attachments/assets/5722f808-45f8-4b4b-832f-a71a2d32a66d)

Des esta manera tendremos el componente en nuestra paleta:
![image](https://github.com/user-attachments/assets/b9320ff6-521a-4812-85ab-7bc7e91b8c04)

Para su uso solo basta con arrastrarlo al JFrame y adaptarlo a su tamaño.









