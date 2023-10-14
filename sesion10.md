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
   

  ##### Ejercicio 2:
    <pre>
    package com.mycompany.polimorfismo101;


public class Polimorfismo101 {
    
public static void main(String[] args) {
    
    Libro Libro1=new Libro(32.000);
    CD CD1=new CD(15.000);
    DVD DVD1=new DVD(75.300);
    
    double precioLibro =Libro1.calcularPrecio() ;
    double impuestoLibro =Libro1.calcularImpuesto();
    
    double precioCD =CD1.calcularPrecio() ;
    double impuestoCD =CD1.calcularImpuesto();

    double precioDVD =DVD1.calcularPrecio() ;
    double impuestoDVD =DVD1.calcularImpuesto();
    
    System.out.println("precio libro es de "+ precioLibro);
    System.out.println("");
    System.out.println("impuesto de libro es de "+ impuestoLibro);
    System.out.println("");
    System.out.println("precio libro es de "+ precioCD);
    System.out.println("");
    System.out.println("impuesto de CD es de "+ impuestoCD);
    System.out.println("");
    System.out.println("precio libro es de "+ precioDVD);
    System.out.println("");
    System.out.println("impuesto de DVD es de "+ impuestoDVD);
    
    
 
    
    
  }  
}
  
    
    package com.mycompany.polimorfismo101;


public abstract class Producto {
    
    public abstract double calcularPrecio();

    public abstract double  calcularImpuesto();

}    

package com.mycompany.polimorfismo101;

public class Libro extends Producto {
    
    private final double precio;

    public Libro(double precio) {
        this.precio = precio;
    }

    @Override
    public double calcularPrecio() {
return precio;    }

    @Override
    public double calcularImpuesto() {
return precio * 0.19 ;
 }
    


}


    
    package com.mycompany.polimorfismo101;

public class CD extends Producto {
    private final double precio;

    public CD(double precio) {
        this.precio = precio;
    }

    @Override
    public double calcularPrecio() {
return   precio;  }

    @Override
    public double calcularImpuesto() {
return precio*0.9;    }

    
    
    
    
    

}  
  
    
    package com.mycompany.polimorfismo101;

public class DVD extends Producto {
    private double precio;

    public DVD(double precio) {
        this.precio = precio;
    }

    @Override
    public double calcularPrecio() {
 return   precio;    }

    @Override
    public double calcularImpuesto() {
return precio*0.19;    }

  


}
  
  #### Ejercicio 3:  

  
package com.mycompany.polimorfismo102;


public class Polimorfismo102 {

    public static void main(String[] args) {
        
        
        
          

            

            
package com.mycompany.polimorfismo102;


public class Polimorfismo102 {

    public static void main(String[] args) {
        
        
        
          
            
            package com.mycompany.polimorfismo102;


public class CuentaCorriente extends Cuenta {

    public CuentaCorriente(double saldo) {
        super(saldo);
    }

    @Override
    public double depositar() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public double retirar() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public double consultarSaldo() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }
    

    
}  
  
    
    public class CuentaAhorro extends Cuenta {

    public CuentaAhorro(double saldo) {
        super(saldo);
    }

   
        
    @Override
    public double depositar() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public double retirar() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public double consultarSaldo() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }
    
}
  
    
      
      package com.mycompany.polimorfismo102;


public class CuentaPlazoFijo extends Cuenta  {

    public CuentaPlazoFijo(double saldo) {
        super(saldo);
    }


    @Override
    public double depositar() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public double retirar() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public double consultarSaldo() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }
    
}


3ser punto aun en proceso
  





