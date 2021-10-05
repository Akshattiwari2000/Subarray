# Subarray
import java.util.*;
class Subarray
{
	public static void main(String[] args) 
	{
		Scanner ac=new Scanner(System.in);
		int n=ac.nextInt();
		int[] arr=new int[n];
		for (int i=0;i<arr.length;i++) 
		{
			arr[i]=ac.nextInt();
		}

		for (int i=0;i<arr.length;i++) 
		{
			for (int j=i;j<arr.length;j++) 
			{
				for (int k=i;k<=j;k++) 
				{
					System.out.print(arr[k]+"\t");
				}
				System.out.println();
			}
		}
	}
}
