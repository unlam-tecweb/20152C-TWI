# UNLaM-TallerWebI-Sanguchetto
Trabajo Pr�ctico final para la c�tedra Taller Web I. Universidad Nacional de La Matanza.

---

Enunciado
-

### Funcionalidades a desarrollar:
1. Una pantalla para que se agreguen productos al carrito.
  + ~~que se descuentan del stock.~~
  + que vaya mostrando el precio total del carrito a medida que se agregan cosas al mismo. 
  + Adem�s se puede agregar descuentos que pueden ser monto o porcentaje de descuento. 
    1. En este caso la pantalla muestra el total con descuento.
    2. y el ahorro acumulado en el carrito. 
  + Esta pantalla tiene dos botones: 
    1. cancelar, que elimina todo lo agregado al carrito y lo restituye al stock; 
    2. y confirmar, que lleva a una pantalla donde se muestra como queda el carrito y su precio final.
2. ~~Una pantalla que muestre el stock de todos los productos existentes.~~
3. ~~Una pantalla para dar de alta un producto.~~
4. ~~Una pantalla para agregar stock a determinado producto, es decir se suma a lo que tiene.~~
5. ~~Una pantalla para eliminar el stock de un producto.~~
6. ~~Implementar los test cases de la clase Carrito, se provee la clase con metodos sin implementar.~~

### Correcciones para entregar en el final:
- Validar que no se consuma m�s stock del que disponemos.
- ~~Arreglar los test case.~~
- Modificar la implementaci�n de la clase Descuento para que esta sea una lista dentro de Sangucheto.
- Implementar la baja de ingredientes.
- Implementar el bot�n que deshace el sangucheto.
- Implementar la pagina "gracias por comprar".

### Se provee:

- la clase Stock completa y 
- la clase Carrito con los metodos sin implementar, para completar por los alumnos.

### _La metodolog�a de trabajo es en grupos de 2 personas, sin excepci�n._

### Anotaciones:
- http://www.mkyong.com/spring-mvc/spring-mvc-how-to-include-js-or-css-files-in-a-jsp-page/
- aplicar primero monto y despues descuento
