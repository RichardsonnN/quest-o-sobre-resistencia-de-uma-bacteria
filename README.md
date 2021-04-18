import java.util.*;
import java.util.Scanner;
class questaodois{
  public static void main (String [] args){
    Scanner input = new Scanner (System.in);
    while (true){
      String option;
      String optionTwo;
      String codigo;
      String codigoTwo;
  //---Inputs-- 
      System.out.println("\nGenetic Code:  ");
      option = input.nextLine();
      System.out.println("Sequence");
      codigo = input.nextLine();
      System.out.println("Genetic Code:  ");
      optionTwo = input.nextLine();
      System.out.println("Sequence");
      codigoTwo = input.nextLine();
   //---Comparação 
      if (option.contains (codigo)){
        System.out.println("Resists");    
      }else if (!option.contains(codigo)){
        System.out.println("Dont resists");
      }
      if (optionTwo.contains (codigoTwo)){
        
        System.out.print("Resists");
      }else if (!optionTwo.contains(codigoTwo)){
        System.out.println("Dont resists");
      }
   }    
  }
}
