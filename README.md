# Java_basics1
package Basics;

public class CounterLogic {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int a=0;
		for(int i=0; i<=2; i++)
		{
			for(int j=0; j<=2; j++)
			{
				for(int k=0; k<=2; k++)
				{
					++a;
					System.out.println(a);
				}
			}
		}

	}

}
