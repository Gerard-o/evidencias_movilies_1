<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->


<pre>
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

    
       
    }
    



