
import java.util.*;
class Main {
    public static int nthfibonaci(int n){
        if(n==0||n==1){
            return n;
        }else{
            int n1=0,n2=1;
           for(int i=2;i<=n;i++){
       int n3=n1+n2;
        n1=n2;
        n2=n3; 
        }
        return n2;
    }
    }
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        System.out.print(nthfibonaci(n));
    }
    } 
