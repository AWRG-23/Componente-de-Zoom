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

Descargar el archivo:

![image](https://github.com/user-attachments/assets/6165e465-988b-4021-b6a8-f64277904685)




