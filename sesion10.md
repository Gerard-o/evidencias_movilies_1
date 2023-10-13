<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

##### Actividad: Polimorfismo en Java - Ejercicios prácticos

<pre>

package com.mycompany.polimorfismo10;

public class Polimorfismo10 {

    public static void main(String[] args) {
        Vehículo Coche=new Coche();
        Coche.acelerar();
        Coche.frenar();
        Coche.girar();
        System.out.println("");
        System.out.println("////////////////////////////////////////////////////////////////////////////////");
        System.out.println("");
        Vehículo Moto=new Moto();
        Moto.acelerar();
        Moto.frenar();
        Moto.girar();
        System.out.println("");
        System.out.println("////////////////////////////////////////////////////////////////////////////////");
        System.out.println("");
        Vehículo Bicicleta=new Bicicleta();
        Bicicleta.acelerar();
        Bicicleta.frenar();
        Bicicleta.girar();

    }
}
  
    
    package com.mycompany.polimorfismo10;


 abstract class Vehículo {
    
   public abstract void acelerar();
   public abstract void frenar();
   public abstract void girar();
    
            
}
  
    
    package com.mycompany.polimorfismo10;

public class Coche extends Vehículo {

    @Override
    public void acelerar() {
        System.out.println("el coche esta acelerando");
    }

    @Override
    public void frenar() {
        System.out.println("el coche esta frenando");
    }

    @Override
    public void girar() {
        System.out.println("el coche esta girando ");
    }

}  
  
  package com.mycompany.polimorfismo10;

public class Moto extends Vehículo {

    @Override
    public void acelerar() {
        System.out.println("la moto esta acelerando");
    }

    @Override
    public void frenar() {
        System.out.println("la moto esta frenando");
    }

    @Override
    public void girar() {
        System.out.println("la motro esta girando");
    }

}
  
    
    package com.mycompany.polimorfismo10;


public class Bicicleta extends Vehículo {

    @Override
    public void acelerar() {
        System.out.println("la bicicleta esta pedaleando");    }

    @Override
    public void frenar() {
System.out.println("la bicicleta esta frenando");    }

    @Override
    public void girar() {
System.out.println("la bicicleta esya girando");    }
    
}


