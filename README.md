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
