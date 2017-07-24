package prac1;
import java.util.* ;
/**
 *
 * @author BUSER
 */
public class Prac1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int i=0,j=0,k=0,m=0 ;
        char s1[]=new char[100] ;
        char s2[]=new char[100] ;
        char s3[]=new char[100] ;
        System.out.print("Enter Orignal String: ");
        String s=sc.next() ;
        int n=s.length() ;
        System.out.print("Encrypted String: ");
        for(i=0;i<n;i++)
        {
           if(i%3==0)
            s1[j++]=s.charAt(i) ;
           else if(i%3==1)
               s2[k++]=s.charAt(i) ;
           else
               s3[m++]= s.charAt(i);
               
        }
        String en1=new String(s1,0,j) ;
        String en2=new String(s2,0,k) ;
        String en3=new String(s3,0,m) ;
        System.out.print(en1);
        System.out.print(en2);
        System.out.println(en3);
        s=en1+en2+en3 ;
        
        n=s.length() ;
        int n1=n/3 ;
        int n2=n/3 ;
        if(n%3==1)
            n1++ ;
        if(n%3==2)
            n2++ ;
        j=0 ;
        k=n1 ;
        m=n1+n2 ;
        for(i=0;i<n;i++)
        {
            if(i%3==0)
                s1[i]=s.charAt(j++) ;
            else if(i%3==1)
                s1[i]=s.charAt(k++) ;
            else
                s1[i]=s.charAt(m++) ;
        }
         en3=new String(s1,0,n) ;
          System.out.print("Orignal String: ");
          System.out.println(en3);
    }
    
}
