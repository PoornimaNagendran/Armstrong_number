# Armstrong_number
import java.util.Scanner;
class armstrong_number
{
public static void main()
{
Scanner s=new Scanner(System.in);
System.out.println("Enter a number");
int g;
int sum;
int k;
int n=s.nextInt;
for(int i=1;i<=n;i++)
{
g=i;
sum=0;
while(g!=0)
{
k=g%10;
sum=sum+k*k*k;
g=g/10;
}
if(i==sum)
{
System.out.println(sum);
}
}
}
}
