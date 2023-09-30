<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->


<pre> __
package com.mycompany.sesion4;


public class Producto {

    
    
    public String nombrepro;
    private double preciopro;
    protected int cantidad;
    private String fabricante;
     public String marca;
    String categoria;

    public Producto(String nombrepro, double preciopro, int cantidad, String fabricante, String marca, String categoria) {
        this.nombrepro = nombrepro;
        this.preciopro = preciopro;
        this.cantidad = cantidad;
        this.fabricante = fabricante;
        this.marca = marca;
        this.categoria = categoria;
    }

    public String getNombrepro() {
        return nombrepro;
    }

    public void setNombrepro(String nombrepro) {
        this.nombrepro = nombrepro;
    }

    public double getPreciopro() {
        return preciopro;
    }

    public void setPreciopro(double preciopro) {
        this.preciopro = preciopro;
    }

    public int getCantidad() {
        return cantidad;
    }

    public void setCantidad(int cantidad) {
        this.cantidad = cantidad;
    }

    public String getFabricante() {
        return fabricante;
    }

    public void setFabricante(String fabricante) {
        this.fabricante = fabricante;
    }

    public String getMarca() {
        return marca;
    }

    public void setMarca(String marca) {
        this.marca = marca;
    }

    public String getCategoria() {
        return categoria;
    }

    public void setCategoria(String categoria) {
        this.categoria = categoria;
    }

    
       
    } __
      
        
          
            
            package com.mycompany.sesion4;

public class Sesion4 {

    public static void main(String[] args) {

        Producto producto1 = new Producto("cuaderno", 2000, 10, "norma", "elcid", "papeleria");

        System.out.println("nombre del producto : " + producto1.getNombrepro());
        System.out.println("precio del producto : " + producto1.getPreciopro());
        System.out.println("cantidad del producto : " + producto1.getCantidad());
        System.out.println("fabricante del producto : " + producto1.getFabricante());
        System.out.println("marca del produtco : " + producto1.getMarca());
        System.out.println("categoria del producto : " + producto1.getCategoria());

        producto1.setCantidad(8);
        producto1.setCategoria("estudiantes");
        producto1.setFabricante("lope");
        producto1.setMarca("paperama");
        producto1.setNombrepro("borradores");
        producto1.setPreciopro(1.000);

        System.out.println("");
        System.out.println("");
        System.out.println("--------------------------------------------------Actualizacion de inventarios-------------------------------------------------- : ");
        System.out.println("");
        System.out.println("");

        

        System.out.println("nuevo nombre : " + producto1.getNombrepro());
        System.out.println("nuevo preciopro : " + producto1.getPreciopro());
        System.out.println("nuevo cantidad : " + producto1.getCantidad());
        System.out.println("nuevo fabricante : " + producto1.getFabricante());
        System.out.println("nuevo marca " + producto1.getMarca());
        System.out.println("nuevo categoria " + producto1.getCategoria());
    }
}
    



