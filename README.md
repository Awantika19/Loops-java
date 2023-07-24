# Loops-java
com.java.basics

package com.java.basics;

public class Loops3 {

	public static void main(String[] args) {
		for (int i = 0; i<20; i++) {
			if(i%2 ==0)
				continue;
			System.out.println(i);
		}
		
		for (int i = 0;i <100; i++) {
			if(i>50)
				break;
			System.out.println(i);
			
		}

	}

}
