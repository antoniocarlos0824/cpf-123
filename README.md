# cpf-123
package pct;  import java.util.Scanner;  /**  *  * @author manager  */ public class cpf {     public static void main(String[] args) {           // VARIAVEIS         int soma = 0, idx = 0, d1, d2;                String cpf;         //Scaner de entrada          Scanner entrada = new Scanner(System.in);                  System.out.println("\n\t\t validade de CPF\n");          // entrada                  System.out.print("informe o numero do CPF:");         cpf = entrada.next();                  if(cpf.length() == 11){               //Varrer a string para acumular o produto do digito pelo seu próprio índice                  for (int i = 10;i>+2;i-- ){           soma +=Character.getNumericValue(cpf.charAt(idx))*i;                                                          }                    }                       }                }
