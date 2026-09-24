Public class ("média do aluno: ")
    leia(nome)

     public static void main(String[] args) {

            Scanner entrada = new Scanner(System.in);

            String nome;
            double nota1, nota2, nota3, media;

            System.out.print("Digite o nome do aluno: ");
            nome = entrada.nextLine();

            System.out.print("Digite a nota da primeira prova: ");
            nota1 = entrada.nextDouble();

            System.out.print("Digite a nota da segunda prova: ");
            nota2 = entrada.nextDouble();

            System.out.print("Digite a nota da terceira prova: ");
            nota3 = entrada.nextDouble();

            media = (nota1 + nota2 + nota3) / 3;

            System.out.println("\nNome do aluno: " + nome);
            System.out.println("Média: " + media);

            entrada.close();
