LA GUIA 5 SE LLAMA INTRO JAVA. te recomienda usar netbeans pero el curso se le hizo facil a los compañeros que intalaron intellij IDEA

es importante que descarguen la versión gratuita que es Intellij IDEA
Community edition.
https://download-cdn.jetbrains.com/idea/ideaIC-2023.1.3.exe

[link directo para descargar intellij community](https://download-cdn.jetbrains.com/idea/ideaIC-2023.1.3.exe)

# Ejercicio 2

Escribir un programa que pida dos números enteros por teclado y calcule la suma de los dos. El programa deberá después mostrar el resultado de la suma.

```java

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        // si usas mac quita el .useDelimiter("\n")
        Scanner miScanner = new Scanner(System.in).useDelimiter("\n");

        System.out.println("ingrese el primer número al sistema");
        int num1 = miScanner.nextInt();

        System.out.println("ingrese el segundo número al sistema");
        int num2 = miScanner.nextInt();

        int resultado = num1 + num2;

        System.out.println("El resultado de la suma es: "+ resultado);
        }
    }

```

# Ejercicio 3:
 Escribir un programa que pida tu nombre, lo guarde en una variable y lo muestre por pantalla

```java

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner miScanner = new Scanner(System.in).useDelimiter("\n");

        System.out.println("Escribé tu nombre");
        String name = miScanner.nextLine();
        System.out.println("Tu nombre es: "+ name);
    }
}

```

# Ejercicio 4
Escribir un programa que pida una frase y la muestre toda en mayúsculas y
después toda en minúsculas. Nota: investigar la función toUpperCase() y
toLowerCase() en Java.

```java

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner miScanner = new Scanner(System.in).useDelimiter("\n");

        System.out.println("Escribé una frase");
        String frase = miScanner.nextLine();
        System.out.println("Tu frase en mayúscula es: "+ frase.toUpperCase());
        System.out.println(); //salto de linea para una salida prolija
        System.out.println("Tu frase en minúscula es: "+ frase.toLowerCase());
    }
}


```