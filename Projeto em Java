
import java.util.Scanner;

public class project {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("QUal o valor que você quer do fibonacci");
        int valor = sc.nextInt();
        int[] fibonacci = new int[valor+1];
        int i = 0;
        fibonacci[0]=0;
        fibonacci[1]=1;
        System.out.println(0);
        for(i=1; i <= valor; i++){
            if(i >=2){
                fibonacci[i]= i;
                int ant = fibonacci[i-1];
                int Antan = fibonacci[i-2];
                fibonacci[i] = ant+Antan;
                for(int j = 0; j <= i; j++){
                    System.out.print(fibonacci[j]+" ");
                }
                System.out.println();

                if(i==valor){
                    for(int x = valor-1;x>=0;x--){
                        for(int j = 0; j <= x; j++){
                            System.out.print(fibonacci[j]+" ");
                        }
                        System.out.println();
                    }
                }
            }else{
                fibonacci[0]=0;
                fibonacci[1]=1;

                System.out.print(fibonacci[0]+" "+fibonacci[1]+" ");
                System.out.println();
            }
        }
        
    }
}
