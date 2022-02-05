# Neg-pos-elements-one-side-without-changing-the-order

import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner op = new Scanner(System.in);
		System.out.println("Enter the size of array:- ");
		int n = op.nextInt();
		int i=0;
		
		
		
		
		int A[] = new int[n];
		System.out.println("Enter the elements of array:- ");
		
		for( i=0;i<n;i++)
		{
		    A[i]=op.nextInt();
		}
		
		System.out.println("The elements after required arrangement are:- ");
		System.out.println(" ");
		for(i=0;i<n;i++)
		{
		    if(A[i]>=0)
		      System.out.print(A[i]+" ");
		    
		}
		
		for(i=0;i<n;i++)
		{
		    if(A[i]<0)
		      System.out.print(A[i]+" ");
		}
		
	}
}
