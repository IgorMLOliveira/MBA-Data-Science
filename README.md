# MBA-Data-Science
Aulas de iniciação a linguagem Java
import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    Scanner entrada = new Scanner(System.in);
    System.out.println("Escolha uma opção");
    System.out.println("1 - Cadastrar Aluno");
    System.out.println("2 - Cadastrar Notas");
    System.out.println("3 - Listar Alunos e Notas");

  int numero = entrada.nextInt();
  switch (numero){
    case 1:
      System.out.println(" Vamos Cadastrar Aluno");
      break;
    case 2:
      System.out.println(" Vamos Cadastrar Nota");
      break;
    case 3:
      System.out.println(" Listar Alunos");
      break;
    default:
      System.out.println("O Numero é Invalido");
      
  } 
}
}
