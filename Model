import java.util.Random;

public class ListaArraysModel {

    // 1. Contar pares e ímpares em um array de 20 números inteiros
    public static void contarParesImpares() {
        Random random = new Random();
        int[] numeros = new int[20];
        int pares = 0, impares = 0;

        System.out.println("Array gerado:");
        for (int i = 0; i < numeros.length; i++) {
            numeros[i] = random.nextInt(100); // números aleatórios de 0 a 99
            System.out.print(numeros[i] + " ");
            if (numeros[i] % 2 == 0) pares++;
            else impares++;
        }
        System.out.println("\nQuantidade de pares: " + pares);
        System.out.println("Quantidade de ímpares: " + impares);
    }

    // 2. Verificar se um número está no array e sua posição
    public static void buscarNumero(int[] numeros, int busca) {
        boolean encontrado = false;
        for (int i = 0; i < numeros.length; i++) {
            if (numeros[i] == busca) {
                System.out.println("Número encontrado na posição: " + i);
                encontrado = true;
            }
        }
        if (!encontrado) {
            System.out.println("Número não encontrado no array.");
        }
    }

    // 3. Remover um nome (substituir por "---")
    public static void removerNome(String[] nomes, String remover) {
        boolean encontrado = false;
        for (int i = 0; i < nomes.length; i++) {
            if (nomes[i].equalsIgnoreCase(remover)) {
                nomes[i] = "---";
                encontrado = true;
            }
        }

        if (encontrado) {
            System.out.println("Nome removido! Lista atualizada:");
        } else {
            System.out.println("Nome não encontrado!");
        }

        for (String nome : nomes) {
            System.out.print(nome + " | ");
        }
        System.out.println();
    }

    // 4. Contar quantas vezes cada número aparece em um array
    public static void contarFrequencia(int[] numeros) {
        System.out.println("Frequência dos números:");
        for (int i = 0; i < numeros.length; i++) {
            int contador = 0;
            for (int j = 0; j < numeros.length; j++) {
                if (numeros[i] == numeros[j]) {
                    contador++;
                }
            }
            System.out.println(numeros[i] + " aparece " + contador + " vez(es).");
        }
    }

    // 5. Ordenar um array com Bubble Sort
    public static void bubbleSort(int[] numeros) {
        for (int i = 0; i < numeros.length - 1; i++) {
            for (int j = 0; j < numeros.length - 1 - i; j++) {
                if (numeros[j] > numeros[j + 1]) {
                    int temp = numeros[j];
                    numeros[j] = numeros[j + 1];
                    numeros[j + 1] = temp;
                }
            }
        }

        System.out.println("Array ordenado:");
        for (int num : numeros) {
            System.out.print(num + " ");
        }
        System.out.println();
    }
}

