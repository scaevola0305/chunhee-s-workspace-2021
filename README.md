# chunhee-s-workspace-2021

class Ex1{
	public static void main(String[] args){
		System.out.println("hello world");
	}
}




package day1020;

public class Hello {

	public static void main(String[] args) {
		//hello 문자열 출력
		System.out.println("hello");
		System.out.println("hello"); //sysout + ctrl + spacebar
	}

}





package day1026.sample.app;
//숫자 10을 10진수, 2진수, 8진수, 16진수로 출력
public class BinaryTestEx1 {

	public static void main(String[] args) {

	     int num = 10;
	     int bNum = 0B1010; //0B는 뭐지?? 2진수라는 표시인가...
	     int oNum = 012; //0은 뭐지?? 8진수라는 표시인가...
	     int hNum = 0XA; //0X는 뭐지?? 16진수라는 표시인가...

	    System.out.println(num);
	    System.out.println(bNum);
            System.out.println(oNum);
            System.out.println(hNum);
		
	}

}




package day1026.sample.app;
//숫자 12를 10진수, 2진수, 8진수, 16진수로 출력
public class BinaryTestEx1 {

	public static void main(String[] args) {

	     int num = 12;
	     int bNum = 0B1100;
	     int oNum = 014;
	     int hNum = 0XC;

	    System.out.println(num);
	    System.out.println(bNum);
            System.out.println(oNum);
            System.out.println(hNum);
		
	}

}



package day1026.sample.app;
//양수 5와 음수 5 더하기
public class BinaryTestEx2 {

	public static void main(String[] args) {

		int num1 = 0B00000000000000000000000000000101;
		int num2 = 0B11111111111111111111111111111011;
		
		int sum = num1 + num2;
		System.out.println(num1);
		System.out.println(num2);
		System.out.println(sum);
		
	}

}



package day1027.operator.sample;

import java.util.Scanner;

//두개의 정수를 입력받아 a, b에 저장하고 
//둘 중 더 큰 수를 출력한다. 만약 같다면 같다고 출력한다.
public class OperEx8 {

	public static void main(String[] args) {

		System.out.print("첫번째 정수를 입력해 주세요 :");
		Scanner s = new Scanner(System.in);
		int a = s.nextInt();
		
		System.out.print("두번째 정수를 입력해 주세요 :");
		int b = s.nextInt();
		
		if(a > b) {
			System.out.println("더 큰 수는 "+a+"입니다.");
		}
		
		if(a < b) {
			System.out.println("더 큰 수는 "+b+"입니다.");
		}else {
			System.out.println("두 수는 같습니다.");
		}
		
		
	}

}



package day1027.operator.sample;

import java.util.Scanner;

//두개의 정수를 입력받아 a, b에 저장하고 
//둘 중 더 큰 수를 출력한다. 만약 같다면 같다고 출력한다.
public class OperEx8 {

	public static void main(String[] args) {

		Scanner s = new Scanner(System.in);
		
		System.out.print("첫번째 숫자 : ");
		int a = s.nextInt();
		System.out.print("두번째 숫자 : ");
		int b = s.nextInt();
		
		
		if(a == b) {
			System.out.println("두 개의 값은 같습니다.");
		}else if(a > b) {
			System.out.println(a);
		}else{
			System.out.println(b);
		}
		
	
		}
		
		
	}



package day1027.operator.sample;

public class OperEx9 {

	public static void main(String[] args) {

		int a = 10;
		int b = 20;
		
		boolean c = (a = a + 10) == b && b++ == a;
		
		System.out.println(a); //20
		System.out.println(b); //21
		System.out.println(c); //true



package day1027.operator.sample;

public class OperEx9 {

	public static void main(String[] args) {

		int a = 10;
		int b = 20;
		
		boolean c = !((a = a + 10) == b) && b++ == a;
		
		System.out.println(a); //20
		System.out.println(b); //20
		System.out.println(c); //false




package day1028.ifex.sample;
//성적을 입력하면 성적에 맞는 학점을 출력하세요
//90~100 : "A", 80~89 : "B", 70~79 : "C", 그 외 나머지는 "F"

import java.util.Scanner;

public class IfEx5 {

	public static void main(String[] args) {

		int score;
		char grade;
		
		Scanner s = new Scanner(System.in);
		
		System.out.print("성적을 입력하세요 : ");
		score = s.nextInt();
		
		if(score >= 90) {
			grade = 'A';
		}else if(score >= 80) {
			grade = 'B';
		}else if(score >= 70) {
			grade = 'C';
		}else {
			grade = 'F';
		}
		
		System.out.println("당신의 학점은 "+ grade +" 등급입니다.");
	}

}


package day1028.switchcase.sample;

import java.util.Scanner;

//여러 케이스가 같은 수행문을 가지고 있다면 케이스를 동시에 사용함
public class SwitchEx2 {

	public static void main(String[] args) {
		//입력한 월이 몇일까지 있는지 알려주는 코드
		Scanner s = new Scanner(System.in);
		
		System.out.print("해당 월을 입력하세요 : ");
		int month = s.nextInt();
		String day;
		
		switch(month) {
		case 1: case 3: case 5: case 7: case 8: case 10: case 12: day = "31"; break;
		case 4: case 6: case 9: case 11: day = "30"; break;
		case 2: day = "28"; break;
		default : day = "해당 달은 존재하지 않습니다.";
		}
		
		if(1<= month && month <= 12) {
		System.out.printf("%d월은 %s일까지입니다.", month, day);	
		}else {
			System.out.println(day);
		}
		 
		 
	}

}
