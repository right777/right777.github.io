---
title: 221208Welcome
tags: Java Javascript
---
![이미지등록](/assets/images/3.PNG)

'''java

import java.io.FileInputStream;
import java.io.FileOutputStream;
import java.io.IOException;
import java.io.PrintStream;
import java.util.Scanner;


package ex2.test;

public class OmokTest {
	public static void main(String[] args) {
		for(int i=0;i<10;i++) {
			for(int j=0;j<10;j++)
		System.out.printf("%c",'†');
		System.out.println("");}
		
		
		System.out.println("");
//		-----------------------------------------------------
		for(int i=0;i<100;i++) {
		
		if(i==12)
			System.out.printf("%c", '○');
			
		else
			System.out.printf("%c", '†'); 
			
		if(i%10==9)
			System.out.println();
		}
		
		//"\n" 추가 10번째 마다
}
}



package ex2.test;

public class ForTest {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
		for(int i=0; i<5 ;i++){

		if(i!=2) //위치 인덱스
		continue;
			
		
		System.out.print("☆");
		System.out.printf("%d", + i+1);
		
		if(i!= 4) // != 
		System.out.print(",");
	
//		if(i==2) 
//			break;
	}

}}





package ex2.test;

public class iftest {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		// 0이 +를 대신해서 출력
		// if(i!=5) //위치 인덱스
		
		
		for (int i = 0; i < 10; i++) {
			if(i == 5) 
				System.out.printf("%c", '○');
			
			else if(i%2==1)
				System.out.printf("%c", '☆');
			else
				System.out.printf("%c", '†');
		
}}}

'''
