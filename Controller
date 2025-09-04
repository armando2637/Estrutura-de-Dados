import java.util.Scanner;

public class ListaArraysController {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.println("=== Lista de Exercícios com Arrays ===");
        System.out.println("1 - Contar pares e ímpares");
        System.out.println("2 - Buscar número no array");
        System.out.println("3 - Remover nome do array");
        System.out.println("4 - Contar frequência de números");
        System.out.println("5 - Ordenar array (Bubble Sort)");
        System.out.print("Escolha o exercício: ");
        int opcao = sc.nextInt();

        switch (opcao) {
            case 1 -> ListaArraysModel.contarParesImpares();

            case 2 -> {
                int[] numeros = new int[10];
                System.out.println("Digite 10 números:");
                for (int i = 0; i < numeros.length; i++) {
                    numeros[i] = sc.nextInt();
                }
                System.out.print("Digite um número para buscar: ");
                int busca = sc.nextInt();
                ListaArraysModel.buscarNumero(numeros, busca);
            }

            case 3 -> {
                sc.nextLine(); // limpar buffer
                String[] nomes = new String[10];
                System.out.println("Digite 10 nomes:");
                for (int i = 0; i < nomes.length; i++) {
                    nomes[i] = sc.nextLine();
                }
                System.out.print("Digite um nome para remover: ");
                String remover = sc.nextLine();
                ListaArraysModel.removerNome(nomes, remover);
            }

            case 4 -> {
                int[] numeros = new int[10];
                System.out.println("Digite 10 números:");
                for (int i = 0; i < numeros.length; i++) {
                    numeros[i] = sc.nextInt();
                }
                ListaArraysModel.contarFrequencia(numeros);
            }

            case 5 -> {
                int[] numeros = new int[10];
                System.out.println("Digite 10 números para ordenar:");
                for (int i = 0; i < numeros.length; i++) {
                    numeros[i] = sc.nextInt();
                }
                ListaArraysModel.bubbleSort(numeros);
            }

            default -> System.out.println("Opção inválida!");
        }

        sc.close();
    }
}


