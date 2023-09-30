<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 7 


<!-- Su documentación aquí -->


##### Actividad: Clase Producto con Métodos Sobrecargados  

<pre>   
  
  package com.mycompany.producto1;


public class Producto1 {

   
    private String nombre;
    private double precio;
    private int cantidad;

    public Producto1() {
        this.nombre = "Desconocido";
        this.precio = 0.00;
        this.cantidad = 0;
    }

    public Producto1(String nombre, double precio) {
        this.nombre = nombre;
        this.precio = precio;
        this.cantidad = 0;
    }

    public Producto1(String nombre, double precio, int cantidad) {
        this.nombre = nombre;
        this.precio = precio;
        this.cantidad = cantidad;
    }

    public double calcularValorTotal() {
        return this.precio * this.cantidad;
    }

    public void mostrarInformacion() {
        System.out.println("Informacion Producto");
        System.out.println("Nombre" + nombre);
        System.out.println("Precio" + precio);
        System.out.println("Cantidad" + cantidad);
        System.out.println("Valor tototal : $" + calcularValorTotal());

    }

    public void incrementarCantidad() {
        cantidad++;
    }

    public void incrementarCantidad(int cantidadIncrementar) {
        cantidad += cantidadIncrementar;
    }

    public void actualizarPrecio(double actualizarPrecio) {
        precio = 4500;
        System.out.println("El precio del dolar para el dia es de $4.500");
    }

    public void actualizarPrecio(double nuevoPrecio, String moneda, double tasaCambio) {
        if (moneda.equals("400")) {
            precio = nuevoPrecio * tasaCambio;
        } else if (moneda.equals("0")) {
            precio = nuevoPrecio * tasaCambio;
        } else {
            System.out.println("Moneda no admitida");
        }
        
    }



