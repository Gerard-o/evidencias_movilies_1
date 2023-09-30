<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->

##### Actividad: Clases y métodos abstractos de la superclase "Musica" en Java

<pre>


package com.mycompany.actividad8;


public class Album extends Musica  {
   private String canciones;

    public Album(String canciones) {
        this.canciones = canciones;
        this.titulo = titulo;
    }

    @Override
    public void play() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public void stop() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public void pause() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public void next() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    @Override
    public void previous() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }
   
   
}


  
    
    
package com.mycompany.actividad8;


public abstract class BandaSonora extends Musica {
   private String pelicula;
   
}

  
    
    
package com.mycompany.actividad8;


public class Cancion extends Musica{
    private String artista ;
     private String album ;

    public Cancion(String artista, String album) {
        this.artista = artista;
        this.album = album;
        super.titulo;
    }

   

    public String getArtista() {
        return artista;
    }

    public void setArtista(String artista) {
        this.artista = artista;
    }

    public String getAlbum() {
        return album;
    }

    public void setAlbum(String album) {
        this.album = album;
    }

    public String getTitulo() {
        return titulo;
    }

    public void setTitulo(String titulo) {
        this.titulo = titulo;
    }
    
     
    
   @Override
   public void play(){
       System.out.println("Reproduce la Cancion" + titulo);
   }   

    @Override
    public void stop() {
       System.out.println("Deten la Cancion" +titulo); 
    }

    @Override
    public void pause() {
        System.out.println("Pausa la Cancion"); 
    }

    @Override
    public void next() {
        System.out.println("Siguiente Cancion"); 
    }

    @Override
    public void previous() {
        System.out.println("Devuelve la Cancion"); 
    }
}
  
    
    
package com.mycompany.actividad8;


public abstract class  Musica {
    
     String titulo ;
    
    public abstract void play();
    
    public abstract void stop();
    
    public abstract void pause();
    
    public abstract void next();
    
    public abstract void previous();

    

   
    
    
}
  
    
    

package com.mycompany.actividad8;


public class Actividad8 {

    public static void main(String[] args) {
        
    }
}
  
    
    




