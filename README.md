MainScanner 
package cuenta;

import java.util.Scanner;

public class MainScanner {
        public static void main(String[] args) {
            Scanner sc = new Scanner(System.in);
            String nombre;
            String apellido;
            String universidad;
            int edad;

            System.out.print("Ingrese el nombre: ");
            nombre = sc.nextLine();

            System.out.print("Ingrese el apellido: ");
            apellido = sc.nextLine();

            System.out.print("Ingrese la edad: ");
            edad = sc.nextInt();
            sc.nextLine();
            System.out.print("Ingrese la universidad: ");
            universidad = sc.nextLine();

            System.out.println("El nombre es: "+nombre);
            System.out.println("El apellido es: "+apellido);
            System.out.println("La edad es: "+edad);
            System.out.println("La universidad es: "+universidad);

        }
    }

