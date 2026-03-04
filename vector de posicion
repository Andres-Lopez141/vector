import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);
        
        int[] vector = new int[10];
        
        int mayor, menor;
        int posMayor = 0;
        int posMenor = 0;
        
        // Llenar el vector
        for (int i = 0; i < vector.length; i++) {
            System.out.print("Ingrese el numero en la posicion " + i + ": ");
            vector[i] = sc.nextInt();
        }
        
        // Inicializamos mayor y menor con la primera posición
        mayor = vector[0];
        menor = vector[0];
        
        // Buscar mayor y menor
        for (int i = 1; i < vector.length; i++) {
            
            if (vector[i] > mayor) {
                mayor = vector[i];
                posMayor = i;
            }
            
            if (vector[i] < menor) {
                menor = vector[i];
                posMenor = i;
            }
        }
        
        // Mostrar resultados
        System.out.println("\nRESULTADOS:");
        System.out.println("El número mayor es: " + mayor);
        System.out.println("Está en la posición: " + posMayor);
        
        System.out.println("El número menor es: " + menor);
        System.out.println("Está en la posición: " + posMenor);
    }
}
