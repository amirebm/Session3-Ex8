# Session3-Ex8

// ب ن ک عددی از ورودی گرفته و فاکتوریل آن را حساب کند

package com.personal.ex8;

import java.util.Scanner;

public class ex8 {

	public static void main(String[] args) {

		Scanner sc= new Scanner(System.in);
		System.out.println("Enter a Number");
		long fact= sc.nextLong();
		
		System.out.println("factoriele addad :"+ fact+ "  barabar ast ba = "+ factorial(fact));
	
	}
	
	static long factorial(long f) {
		if (f<=1)
			return 1;
		else
			return f * factorial(f-1);
		
		}

}
