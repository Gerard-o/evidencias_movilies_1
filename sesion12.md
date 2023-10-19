<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 12 


<!-- Su documentación aquí -->





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

