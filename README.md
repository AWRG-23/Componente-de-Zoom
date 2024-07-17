# Componente-de-Zoom

Descripción general.
Este componente creado en java nos peremite tener en la paleta de componenetes un panel para hacer zoom fácil de implementar en los proyectos.

API
La clase ZoomPanel nos permite crear un componenete de zoom

Solo tenemos como variables globales  a
double zoomFactor;

Como metodos:
public void Zoom(double zoomfactor): este metodo hace posible el cambio de zoom en la pantalla
protected void paintComponent(Graphics g): con este método haces posible el cambio de zoom en los componentes que integra el panel
protected void paintChildren(Graphics g):se hace posible que los compnentes del panel no se dupliquen.

Dentro del constructor de la clase  tenemos programado el evento mouseclicked  





