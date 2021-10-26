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






