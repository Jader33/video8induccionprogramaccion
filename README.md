# video8induccionprogramaccion
Curso  de Induccion a la progtamacion  video 8


package com.company;

public class Main {

    public static void main(String[] args) {
    Persona edad = new Persona();
    edad.setEdad(20);

    Persona nombre = new Persona();
    nombre.setNombre("mario");
    Persona telefono = new Persona();
    telefono.setTelefono(311.764534);


       System.out.println(nombre.getNombre());
       System.out.println(edad.getEdad());
       System.out.println(telefono.getTelefono());
    }
}
 class  Persona {

     private int edad;
     private String nombre;
     private  double telefono;



     public  void setTelefono(double telefono){
         this.telefono = telefono;
     }

     public double getTelefono() {
         return this.telefono;
     }

     public void setNombre(String nombre){
    this.nombre = nombre;
}
     public String getNombre(){
         return  this.nombre;
     }
  public void setEdad(int edad) {
         this.edad = edad;
     }

     public int getEdad() {
         return this.edad;

     }



     }
