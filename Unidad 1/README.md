# Abstracción y encapsulamiento
## 1.1 Clases
#### 1.1.1 Definición de clase
Una clase es básicamente una plantilla que sirve para crear un objeto, 
en la cual se definen atributos y métodos predeterminados de un tipo de objeto.

**Ejemplo**

``` 
public class Persona {
    private String nombre;
    private String fechaDeNacimiento;
    private int edad;
    private String genero;
}
```

#### 1.1.2 Miembros de una clase: variables de clase, métodos
 **Variable de clase:** Es una variable propia de la clase que la contiene y no 
de instancias de la misma esto quiere decir que todos los objetos que se creen de
esta clase comparten su valor, son llamadas variables estáticas, por ejemplo,
supongamos que hay una clase llamada perro y que tiene una variable llamada
patas, cuando hagamos una instancia de la clase perro esta variable tendrá
el mismo valor en todas las instancias creadas y es por eso que se dice
que comparten su valor, y en caso de que el valor cambie cambiara para
todas las instancias creadas de la clase perro.

**Ejemplo**
```
   public class Perro {
        static int patas = 4;
}
```
