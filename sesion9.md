<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->

##### Actividad: Ejericio POO


<pre>

package com.mycompany.ejercicio9;

public class Ejercicio9 {

    public static void main(String[] args) {
        
        System.out.println("TEMPERATURAS");
        
        System.out.println("");
        System.out.println("");
         
        Temperatura tem = new Temperatura("Celsius", "Fahrenheit");
        double resultado = tem.convertir(1);
        System.out.println("Celsius a Fahrenheit : " + resultado);
        System.out.println("----------------------------------------------------------");

       Temperatura tem1 = new Temperatura("Fahrenheit", "Celsius");
        resultado = tem1.convertir(3);
        System.out.println("Fahrenheit  a Celsius  : " + resultado);
        System.out.println("----------------------------------------------------------");

        Temperatura tem2 = new Temperatura("Celsius", "Kelvin");
        resultado = tem2.convertir(5);
        System.out.println("Celsius  a Kelvin  : " + resultado);
        System.out.println("----------------------------------------------------------");

        Temperatura tem3 = new Temperatura("Kelvin", "Celsius");
        resultado = tem3.convertir(1);
        System.out.println("Kelvin  a Celsius  : " + resultado);
        System.out.println("----------------------------------------------------------");

        Temperatura tem4 = new Temperatura("Fahrenheit", "Kelvin");
        resultado = tem4.convertir(2);
        System.out.println("Fahrenheit  a Kelvin  : " + resultado);
        System.out.println("----------------------------------------------------------");

        Temperatura tem5 = new Temperatura("Kelvin", "Fahrenheit");
        resultado = tem5.convertir(1);
        System.out.println("Kelvin  a Fahrenheit  : " + resultado);
        System.out.println("----------------------------------------------------------");
 
        System.out.println("LONGITUDES");
       
        Longitud longi = new Longitud("Metros", "Pies");
         resultado = longi.convertir(2);
        System.out.println("Metros a Pies : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi1 = new Longitud("Pies", "Metros");
        resultado = longi1.convertir(5);
        System.out.println("Pies a Metros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi2 = new Longitud("Metros", "Pies");
        resultado = longi2.convertir(2);
        System.out.println("Metros a Pies : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi3 = new Longitud("Kilómetros", "Millas");
        resultado = longi3.convertir(1);
        System.out.println("Kilómetros a Millas. : " + resultado);
        System.out.println("----------------------------------------------------------");

        
        Longitud longi4 = new Longitud("Millas", "Kilómetros");
        resultado = longi4.convertir(1);
        System.out.println("Millas a Kilómetros. : " + resultado);
        System.out.println("----------------------------------------------------------");
        
        Longitud longi5 = new Longitud("Centímetros", "Pulgadas");
        resultado = longi5.convertir(1);
        System.out.println("Centímetros a Pulgadas. : " + resultado);
        System.out.println("----------------------------------------------------------");
              
        Longitud longi6 = new Longitud("Pulgadas", "Centímetros");
        resultado = longi6.convertir(1);
        System.out.println("Pulgadas a Centímetros : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi7 = new Longitud("Yardas", "Metros");
        resultado = longi7.convertir(1);
        System.out.println("Yardas a Metros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi8 = new Longitud("Metros", "Yardas");
        resultado = longi8.convertir(2);
        System.out.println("Metros a Yardas : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi9 = new Longitud("Millas Náuticas", "Kilómetros");
        resultado = longi9.convertir(2);
        System.out.println("Millas Náuticas a Kilómetros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi10 = new Longitud("Kilómetros", "Millas Náuticas");
        resultado = longi10.convertir(2);
        System.out.println("Kilómetros a Millas Náuticas. : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi11 = new Longitud("Micrómetros", "Milímetros");
        resultado = longi11.convertir(5);
        System.out.println("Micrómetros a Milímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi12 = new Longitud("Milímetros", "Micrómetros");
        resultado = longi12.convertir(8);
        System.out.println("Milímetros a Micrómetros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi13 = new Longitud("Decímetros", "Metros");
        resultado = longi13.convertir(10);
        System.out.println("Decímetros a Metros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        Longitud longi14 = new Longitud("Metros", "Decímetros");
        resultado = longi14.convertir(5);
        System.out.println("Metros a Decímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        System.out.println("PESO");
        
        /*System.out.println("");
        System.out.println("");
        
        peso pesoo = new peso("Metros", "Pies");
        resultado = pesoo.convertir(5);
        System.out.println("Metros a Pies : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso1 = new peso("Pies", "Metros");
        resultado = peso1.convertir(6);
        System.out.println("Pies a Metros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso2 = new peso("Metros", "Pies");
        resultado = peso2.convertir(5);
        System.out.println("Metros a Pies : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso3 = new peso("Kilómetros", "Millas");
        resultado = peso3.convertir(5);
        System.out.println("Kilómetros a Millas. : " + resultado);
        System.out.println("----------------------------------------------------------");

        
        peso peso4 = new peso("Millas", "Kilómetros");
        resultado = peso4.convertir(1);
        System.out.println("Millas a Kilómetros. : " + resultado);
        System.out.println("----------------------------------------------------------");
        
        peso peso5 = new peso("Centímetros", "Pulgadas");
        resultado = peso5.convertir(2);
        System.out.println("Centímetros a Pulgadas. : " + resultado);
        System.out.println("----------------------------------------------------------");
              
        peso peso6 = new peso("Pulgadas", "Centímetros");
        resultado = peso6.convertir(9);
        System.out.println("Pulgadas a Centímetros : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso7 = new peso("Yardas", "Metros");
        resultado = peso7.convertir(3);
        System.out.println("Yardas a Metros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso8 = new peso("Metros", "Yardas");
        resultado = peso8.convertir(8);
        System.out.println("Metros a Yardas : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso9 = new peso("Millas Náuticas", "Kilómetros");
        resultado = peso9.convertir(3);
        System.out.println("Millas Náuticas a Kilómetros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso10 = new peso("Kilómetros", "Millas Náuticas");
        resultado = peso10.convertir(2);
        System.out.println("Kilómetros a Millas Náuticas. : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso11 = new peso("Micrómetros", "Milímetros");
        resultado = peso11.convertir(1);
        System.out.println("Micrómetros a Milímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso12 = new peso("Milímetros", "Micrómetros");
        resultado = peso12.convertir(3);
        System.out.println("Milímetros a Micrómetros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso13 = new peso("Decímetros", "Metros");
        resultado = peso13.convertir(2);
        System.out.println("Decímetros a Metros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso14 = new peso("Metros", "Decímetros");
        resultado = peso14.convertir(6);
        System.out.println("Metros a Decímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");

        peso peso15 = new peso("Metros", "Decímetros");
        resultado = peso15.convertir(2);
        System.out.println("Metros a Decímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");
        
        peso peso16 = new peso("Metros", "Decímetros");
        resultado = peso16.convertir(1);
        System.out.println("Metros a Decímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");
          
        peso peso17 = new peso("Metros", "Decímetros");
        resultado = peso17.convertir(3);
        System.out.println("Metros a Decímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");
        
        peso peso18 = new peso("Metros", "Decímetros");
        resultado = peso18.convertir(2);
        System.out.println("Metros a Decímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");
        
        peso peso19 = new peso("Metros", "Decímetros");
        resultado = peso19.convertir(4);
        System.out.println("Metros a Decímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");
        
        peso peso20 = new peso("Metros", "Decímetros");
        resultado = peso20.convertir(1);
        System.out.println("Metros a Decímetros. : " + resultado);
        System.out.println("----------------------------------------------------------");
        */
        System.out.println("DIVISAS");
        
        System.out.println("");
        System.out.println("");
        
        
        Divisas Divisass = new Divisas("Dólar estadounidense", "Euro");
        resultado = Divisass.convertir(1);
        System.out.println("Dólar estadounidense a Euro : " + resultado);
        System.out.println("----------------------------------------------------------");
               
         Divisas Divisas1 = new Divisas("Euro", "Dólar estadounidense");
        resultado = Divisas1.convertir(1);
        System.out.println("Euro a Dólar estadounidense. : " + resultado);
        System.out.println("----------------------------------------------------------");
        
         Divisas Divisas2 = new Divisas("Dólar estadounidense", "Peso colombiano");
        resultado = Divisas2.convertir(1);
        System.out.println("Dólar estadounidense a Peso colombiano. : " + resultado);
        System.out.println("----------------------------------------------------------");
        
         Divisas Divisas3 = new Divisas("Peso colombiano", "Dólar estadounidense");
        resultado = Divisas3.convertir(1000);
        System.out.println("Peso colombiano a Dólar estadounidense. : " + resultado);
        System.out.println("----------------------------------------------------------");
        
         Divisas Divisas4 = new Divisas("Euro", "Peso colombiano");
        resultado = Divisas4.convertir(2);
        System.out.println("Euro a Peso colombiano. : " + resultado);
        System.out.println("----------------------------------------------------------");
    
         Divisas Divisas5 = new Divisas("Peso colombiano", "Euro");
        resultado = Divisas5.convertir(5000);
        System.out.println("Peso colombiano a Euro. : " + resultado);
        System.out.println("----------------------------------------------------------");
    
        System.out.println("programador");
        
        System.out.println("");
        System.out.println("");
        
         programador progra = new programador("Decimal", "Binario");
        resultado = progra.convertir(5);
        System.out.println("Decimal a Binario : " + resultado);
        System.out.println("----------------------------------------------------------");
        
         programador progra1 = new programador("Decimal", "Hexadecimal");
        resultado = progra1.convertir(4);
        System.out.println("Decimal a Hexadecimal : " + resultado);
        System.out.println("----------------------------------------------------------");
        
         programador progra2 = new programador("Binario", "Decimal");
        resultado = progra2.convertir(1001);
        System.out.println("Binario a Decimal : " + resultado);
        System.out.println("----------------------------------------------------------");
        
         programador progra3 = new programador("Hexadecimal", "Binario");
        resultado = progra3.convertir('b');
        System.out.println("Hexadecimal a Binario : " + resultado);
        System.out.println("----------------------------------------------------------");
    }
}
  
    
    package com.mycompany.ejercicio9;


public abstract class Conversor {
    protected String unidadOrigen;
    protected String unidadDestino;

    public Conversor(String unidadOrigen, String unidadDestino) {
        this.unidadOrigen = unidadOrigen;
        this.unidadDestino = unidadDestino;
    }
    
     public abstract double convertir(double cantidad);
}  
  
  package com.mycompany.ejercicio9;


public class Temperatura extends Conversor {

    public Temperatura(String unidadOrigen, String unidadDestino) {
        super(unidadOrigen, unidadDestino);
    }

    @Override
    public double convertir(double cantidad) {
        if (unidadOrigen.equals("Celsius") && unidadDestino.equals("Fahrenheit")) {
            // Celsius a Fahrenheit
            return (cantidad * 9 / 5) + 32;
        } else if (unidadOrigen.equals("Fahrenheit") && unidadDestino.equals("Celsius")) {
            // Fahrenheit a Celsius
            return (cantidad - 32) * 5 / 9;
        } else if (unidadOrigen.equals("Celsius") && unidadDestino.equals("Kelvin")) {
            // Celsius a Kelvin
            return cantidad + 273.15;
        } else if (unidadOrigen.equals("Kelvin") && unidadDestino.equals("Celsius")) {
            // Kelvin a Celsius
            return cantidad - 273.15;
        } else if (unidadOrigen.equals("Fahrenheit") && unidadDestino.equals("Kelvin")) {
            // Fahrenheit a Kelvin
            double celsius = (cantidad - 32) * 5 / 9;
            return celsius + 273.15;
        } else if (unidadOrigen.equals("Kelvin") && unidadDestino.equals("Fahrenheit")) {
            // Kelvin a Fahrenheit
            double celsius = cantidad - 273.15;
            return (celsius * 9 / 5) + 32;
        } else {
            throw new IllegalArgumentException("Unidades de temperatura no compatibles");
        }
    }
}  
  
  package com.mycompany.ejercicio9;

public class Longitud extends Conversor {

    public Longitud(String unidadOrigen, String unidadDestino) {
        super(unidadOrigen, unidadDestino);
    }

    @Override
    public double convertir(double cantidad) {
        if (unidadOrigen.equals("Metros") && unidadDestino.equals("Pies")) {
            // Metros a Pies.

            return cantidad * 3.28084;

        } else if (unidadOrigen.equals("Pies") && unidadDestino.equals("Metros")) {
            // Pies a Metros.
            
            return cantidad  * 3.28084;

        } else if (unidadOrigen.equals("Kilómetros") && unidadDestino.equals("Millas")) {
            // Kilómetros a Millas.
            
            return cantidad  * 0.621371;

        } else if (unidadOrigen.equals("Millas") && unidadDestino.equals("Kilómetros")) {
            // Millas a Kilómetros.
            
            return cantidad  * 1.60934;

        } else if (unidadOrigen.equals("Centímetros") && unidadDestino.equals("Pulgadas")) {
            // Centímetros a Pulgadas.
            
            return cantidad * 0.393701;

        } else if (unidadOrigen.equals("Pulgadas") && unidadDestino.equals("Centímetros")) {
            //Pulgadas a Centímetros.
            
            return  cantidad * 2.54;
            
            // ------------------------------------------------------------------------   */
            
        } else if (unidadOrigen.equals("Yardas") && unidadDestino.equals("Metros")) {
            // Yardas a Metros.
            
            return cantidad  * 0.9144;

        } else if (unidadOrigen.equals("Metros") && unidadDestino.equals("Yardas")) {
            // Metros a Yardas.
            
            return cantidad * 1.09361;

        } else if (unidadOrigen.equals("Millas Náuticas") && unidadDestino.equals("Kilómetros")) {
            // Millas Náuticas a Kilómetros.
            
            return cantidad * 1.852;

        } else if (unidadOrigen.equals("Kilómetros") && unidadDestino.equals("Millas Náuticas")) {
            // Kilómetros a Millas Náuticas.
            
            return cantidad / 1.852 ;

        } else if (unidadOrigen.equals("Micrómetros") && unidadDestino.equals("Milímetros")) {
            //Micrómetros a Milímetros.
            
            return cantidad /1000;
            
            } else if (unidadOrigen.equals("Milímetros") && unidadDestino.equals("Micrómetros")) {
            // Milímetros a Micrómetros.
            
            return cantidad  * 1000;
            
            } else if (unidadOrigen.equals("Decímetros") && unidadDestino.equals("Metros")) {
            // Decímetros a Metros.
            return cantidad * 0.1;
            
            } else if (unidadOrigen.equals("Metros") && unidadDestino.equals("Decímetros")) {
            // Metros a Decímetros.
            
            return cantidad * 10;

        } else {
            throw new IllegalArgumentException("Unidades de Longitud no compatibles");
        }
    }
}
  
    
    package com.mycompany.ejercicio9;

public class peso extends Conversor {

    public peso(String unidadOrigen, String unidadDestino) {
        super(unidadOrigen, unidadDestino);
    }

    @Override
    public double convertir(double cantidad) {
        if (unidadOrigen.equals("Kilogramos") && unidadDestino.equals("Libras")) {
            // Kilogramos a Libras.
            return cantidad * 2.20462;

        } else if (unidadOrigen.equals("Libras") && unidadDestino.equals("Kilogramos")) {
            // Libras a Kilogramos.

            return cantidad *0.453592;

        } else if (unidadOrigen.equals("Gramos") && unidadDestino.equals("Libras")) {
            // Gramos a Libras.
            return cantidad *0.00220462;

        } else if (unidadOrigen.equals("Libras") && unidadDestino.equals("Gramos")) {
            // Libras a Gramos.
            return cantidad *453.592;

        } else if (unidadOrigen.equals("Kilogramos") && unidadDestino.equals("Gramos")) {
            // Kilogramos a Gramos.
            return cantidad * 1000;

        } else if (unidadOrigen.equals("Gramos") && unidadDestino.equals("Kilogramos")) {
            // Gramos a Kilogramos.
            return  cantidad / 1000;
            
             } else if (unidadOrigen.equals("Toneladas") && unidadDestino.equals("Kilogramos")) {
            // Toneladas a Kilogramos.
            return cantidad *1000;
            
             } else if (unidadOrigen.equals("Kilogramos") && unidadDestino.equals("Toneladas")) {
            // Kilogramos a Toneladas.
            return cantidad / 1000;
            
             } else if (unidadOrigen.equals("Libras") && unidadDestino.equals("Onzas")) {
            // Libras a Onzas.
            return cantidad * 16;
            
             } else if (unidadOrigen.equals("Onzas") && unidadDestino.equals("Libras")) {
            // Onzas a Libras.
            return cantidad /16;
            
             } else if (unidadOrigen.equals("Gramos") && unidadDestino.equals("Onzas")) {
            // Gramos a Onzas.
            return cantidad *0.035274;
            
             } else if (unidadOrigen.equals("Onzas") && unidadDestino.equals("Gramos")) {
            // Onzas a Gramos.
            return cantidad *28.3495;
            
             } else if (unidadOrigen.equals("Toneladas") && unidadDestino.equals("Libras")) {
            // Toneladas a Libras.
            return cantidad *2204.62;
            
             } else if (unidadOrigen.equals("Libras") && unidadDestino.equals("Toneladas")) {
            // Libras a Toneladas.
            return cantidad /2204.62;
            
             } else if (unidadOrigen.equals("Toneladas") && unidadDestino.equals("Gramos")) {
            // Toneladas a Gramos.
            return cantidad *1.000000;
            
             } else if (unidadOrigen.equals("Gramos") && unidadDestino.equals("Toneladas")) {
            // Gramos a Toneladas.
            return cantidad / 1.000000;
                             
             } else if (unidadOrigen.equals("Toneladas") && unidadDestino.equals("Miligramos")) {
            // Toneladas a Miligramos......
            return cantidad * 1.000000000;
            
             } else if (unidadOrigen.equals("Miligramos") && unidadDestino.equals("Toneladas")) {
            // Miligramos a Toneladas.
            return cantidad /1.000000000;
            
             } else if (unidadOrigen.equals("Kilogramos") && unidadDestino.equals("Miligramos")) {
            // Kilogramos a Miligramos.
            return cantidad *1.000000;
            
             } else if (unidadOrigen.equals("Miligramos") && unidadDestino.equals("Kilogramos")) {
            // Miligramos a Kilogramos.

            return cantidad /1.000000;
            
        } else {
            throw new IllegalArgumentException("Unidades de peso no compatibles");
        }
    }
}
  
    
    package com.mycompany.ejercicio9;



 public class Divisas extends Conversor{
    
    public Divisas(String unidadOrigen, String unidadDestino) {
        super(unidadOrigen, unidadDestino);
    }

    @Override
    public double convertir(double cantidad) {
        if (unidadOrigen.equals("Dólar estadounidense") && unidadDestino.equals("Euro")) {
            // Dólar estadounidense a Euro.
            return cantidad *0.95;
            
        } else if (unidadOrigen.equals("Euro") && unidadDestino.equals("Dólar estadounidense")) {
            // Euro a Dólar estadounidense.
            return cantidad *1.05;
            
        } else if (unidadOrigen.equals("Dólar estadounidense") && unidadDestino.equals("Peso colombiano")) {
            // Dólar estadounidense a Peso colombiano.
            return cantidad + 273.15;
            
        } else if (unidadOrigen.equals("Peso colombiano") && unidadDestino.equals("Dólar estadounidense")) {
            // Peso colombiano a Dólar estadounidense.
            return cantidad *0.00023;
            
        } else if (unidadOrigen.equals("Euro") && unidadDestino.equals("Peso colombiano")) {
            // Euro a Peso colombiano.
            return cantidad *4.50993;
            
        } else if (unidadOrigen.equals("Peso colombiano") && unidadDestino.equals("Euro")) {
            // Peso colombiano a Euro.
            return cantidad * 0.00022;
            
        } else {
            throw new IllegalArgumentException("Unidades de Divisas no compatibles");
        }
    }
}

 
   
   
package com.mycompany.ejercicio9;


public class programador extends Conversor{

public programador(String unidadOrigen, String unidadDestino) {
        super(unidadOrigen, unidadDestino);
    }    

    @Override
    public double convertir(double cantidad) {
        
        if (unidadOrigen.equals("Decimal") && unidadDestino.equals("Binario")) {
            // Decimal a Binario
            return cantidad /2;
            
        } else if (unidadOrigen.equals("Decimal") && unidadDestino.equals("Hexadecimal")) {
            // Decimal a Hexadecimal
            return cantidad *1.05;
            
        } else if (unidadOrigen.equals("Binario") && unidadDestino.equals("Decimal")) {
            // Binario a Decimal
            return cantidad + 273.15;
            
        } else if (unidadOrigen.equals("Hexadecimal") && unidadDestino.equals("Binario")) {
            // Hexadecimal a Binario
            return cantidad *0.00023;
  
        }
        throw new UnsupportedOperationException("convertidor de unidades no compatibles");
    }
}




