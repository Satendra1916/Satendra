import java.util.JOptionPane;
import java.util.Scanner;
class MyName
{
public void Name(int a)
{
int b;
 for(b=1;b<=a;b++)
 {
 JOptionPane.showMessageDialog(null,"Satendra Patel");
 }
}
 public static void main(String arg[])
 {
  int a;
  Scanner sc=new Scanner(System.in);
  a=sc.nextInt();
  MyName mn;
  System.out.println(" ");
  mn.Name(a);
}

  } 
