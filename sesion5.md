<!-- No borrar o modificar -->

[Inicio](./index.md)

## Sesión 5

<!-- Su documentación aquí -->

<pre>

package com.mycompany.programaprincipal;


 class Motocicleta extends Vehiculo  {
    private String tipo;
    private String cilindraje ;

    public Motocicleta(String tipo, String cilindraje, String marca, String modelo, int año) {
        super(marca, modelo, año);
        this.tipo = tipo;
        this.cilindraje = cilindraje;
    }
    public void mostrarInformacionMotocicleta (){
        
        System.out.println("tipo de motocicleta :"+tipo);
        System.out.println("cilindraje motocicleta :"+cilindraje);
        System.out.println("marca :"+marca);
        System.out.println("modelo :"+modelo);
        System.out.println("año :"+año);
        System.out.println("----------------");
        System.out.println("----------------");
    
    
    }
    
}

   
     
   <pre>  

     
package com.mycompany.programaprincipal;


 class Automovil extends Vehiculo {
    private int numPuertas ;
    private String tipoTransmision ;

    public Automovil(int numPuertas, String tipoTransmision, String marca, String modelo, int año) {
        super(marca, modelo, año);
        this.numPuertas = numPuertas;
        this.tipoTransmision = tipoTransmision;
    }
     
    public void mostrarInformacionAutomovil(){
        System.out.println("marca de vehiculo :"+marca);
        System.out.println("modelo vehiculo :"+ modelo);
        System.out.println("año de de vehiculo :"+ año);
        System.out.println("numero de puertas :"+numPuertas);
        System.out.println("tipo de transmicion :"+tipoTransmision);
 }
    
    
}


          
     <pre>   

       package com.mycompany.programaprincipal;

class Vehiculo {

    protected String marca;
    protected String modelo;
    int año;

    public Vehiculo(String marca, String modelo, int año) {
        this.marca = marca;
        this.modelo = modelo;
        this.año = año;
    }

    public void mostrarInformacion() {
        System.out.println("Marca: " + marca);
        System.out.println("Modelo: " + modelo);
        System.out.println("Año: " + año);

        
        
        }
    }



     <pre>  


          

package com.mycompany.programaprincipal;


public class Programaprincipal {

    public static void main(String[] args) {

Automovil automovil1 = new Automovil (5, "mecanica", "chevrolet", "lj", 2024);
   
        automovil1.mostrarInformacionAutomovil();
        
        System.out.println("------------------------------------------------------");
        
        Motocicleta motocicleta1 = new Motocicleta("cross", "200", "akt", "tt", 2020);
        
        motocicleta1.mostrarInformacionMotocicleta();
    }
}
