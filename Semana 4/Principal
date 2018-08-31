import java.util.Scanner;

public class Principal {

    public static void main(String[] args) {
        int opcion;
        int n;

        Scanner sc = new Scanner(System.in);

        System.out.println("\t*** Bienvenido ***");
        System.out.print("\t> Ingrese el tamaño del arreglo a crear para poder operar:    ");
        n = sc.nextInt();
        Arreglo a = new Arreglo(n);

        do {
            System.out.println("1. Cargar en un arreglo n elementos numéricos aleatorios y  ordenarlo en forma ascendente. ");
            System.out.println("2. Mostrar el arreglo y chequear si esta ordenado ascendentemente.");
            System.out.println("3. Buscar un elemento x dentro del arreglo (x se ingresa por teclado). Si no existe, informarlo. Si existe, cambiar su signo.");
            System.out.println("0. Salir.");

            System.out.print(">>> Ingrese opcion:    ");
            opcion = sc.nextInt();

            switch (opcion) {
                case 1:
                    a.cargarArreglo();
                    System.out.println("\n---------------------------------------------------------\n");
                    break;
                case 2:
                    System.out.println("\t> " + a.toString());
                    if (a.estaOrdenado()) {
                        System.out.println("\t> El arreglo esta ordenado ascendentemente!!!");
                    } else {
                        System.out.println("\t> El arreglo NO esta ordenado ascendentemente!!!");
                    }
                    System.out.println("\n---------------------------------------------------------\n");
                    break;
                case 3:
                    break;
            }
        } while (opcion != 0);

    }
}
