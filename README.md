# D1--Pantalla-en-Salida

# Python

     nombre = input("ingresa un nombre: ")

     edad = input("ingresa un edad: ")

     programa = input("ingresa un programa")

     print(f"nombre: {nombre}, edad: {edad}, programa: {programa}")

     

# Java

     import java.util.Scanner;

     public class Main {
        public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

       
        System.out.println("Ingresa tu nombre:");
        String nombre = sc.nextLine();
        System.out.println("Ingresa tu edad:");
        int edad = sc.nextInt();
        sc.nextLine(); 
        System.out.println("Ingresa un programa:");
        String carrera = sc.nextLine();
        
     System.out.println("nombre: " + nombre + ", edad:  " + edad + " programa: " + programa);
    }
}
 
