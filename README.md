# Java-program-for-Sum-of-Digits
Java program for Sum of Digits 
import java.util.*;
class Main{
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int rem=n%9;
        if(n%9==0){
            System.out.print(9);
        }
        else{
            System.out.print(rem);
        }
    }
}
