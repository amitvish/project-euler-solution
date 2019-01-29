# project-euler-solution
//it is the answer of the first question of project euler maths problems
/* package whatever; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Ideone
{
	public static void main (String[] args) throws java.lang.Exception
	{
		Scanner sc= new Scanner(System.in);
	int n,sum=0;
	n=sc.nextInt();
	for(int i=1;i<n;i++){
		if((i%3==0)||(i%5==0))
		sum=sum+i;
	}
	System.out.println(sum);
	}
}
