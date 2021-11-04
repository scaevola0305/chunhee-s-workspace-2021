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




package day1028.forex.sample;

import java.util.Scanner;

public class ForEx3 {

	public static void main(String[] args) {

		System.out.print("원하는 숫자를 입력하세요 : ");
		
		Scanner s = new Scanner(System.in);
		int num = s.nextInt();
		int i;
		int result = 0;
		
		for(i = 1; i <= 9; i++) {
		result = num * i;
		System.out.println(num+" * "+i+" = "+result);
	}


	}
}



package day1028.whileex.sample;

import java.util.Scanner;

public class ExampleEx1 {

	public static void main(String[] args) {

		Scanner s = new Scanner(System.in);

		
		int balance = 0;
		
		boolean stop = false;
		
		while(!stop) {
			System.out.print("번호를 입력하세요(1, 2, 3, 4) : ");
			int num = s.nextInt();
			
			if(num == 1) {
				System.out.print("예금액을 입력하세요 : ");
				balance += s.nextInt();
				System.out.println("계좌잔액은 "+balance+"입니다.");
			}else if(num == 2) {
				System.out.print("출금액을 입력하세요 : ");
				balance -= s.nextInt();
				System.out.println("계좌잔액은 "+balance+"입니다.");
			}else if(num == 3) {
				System.out.println("계좌잔액은 "+balance+"입니다.");
			}else if(num == 4) {
				stop = true;
			}
		}
		System.out.println("프로그램 종료");
		
	}

}


//

package ncs.test1;

public class Goods {
	private String name;
	private int price;
	private int quantity;

	public Goods() {
	}

	public Goods(String name, int price, int quantity) {
		this.name = name;
		this.price = price;
		this.quantity = quantity;
	}

	@Override
	public String toString() {
		return "Goods [name=" + name + ", price=" + price + ", quantity=" + quantity + "]";
	}

	public String getName() {
		return name;
	}

	public void setName(String name) {
		this.name = name;
	}

	public int getPrice() {
		return price;
	}

	public void setPrice(int price) {
		this.price = price;
	}

	public int getQuantity() {
		return quantity;
	}

	public void setQuantity(int quantity) {
		this.quantity = quantity;
	}	
	
	
	
}




package ncs.test1;

import java.util.Scanner;

public class GoodsTest {
	public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);
		System.out.println("다음 항목의 값을 입력하세요");
		System.out.print("상품명 : ");
		String name = scan.nextLine();
		System.out.print("가격 : ");
		int price = scan.nextInt();
		System.out.print("수량 : ");
		int quantity = scan.nextInt();
		
		Goods goods = new Goods(name, price, quantity);
		
		System.out.println("입력한 결과는 다음과 같습니다.");
		System.out.println(goods);
		
		System.out.println("총 구매가격 : "+ goods.getPrice() * goods.getQuantity());
		
	}

}



package ncs.test1;

public class Employee {
	
	private String no;
	private String name;
	private String dept;
	private String job;
	private int sal;
	
	
	
	public Employee() {}
	
	public Employee(String no, String name, String dept, String job, int sal) {
		this.no = no;
		this.name = name;
		this.dept = dept;
		this.job = job;
		this.sal = sal;
	}

	public String getNo() {
		return no;
	}
	public void setNo(String no) {
		this.no = no;
	}
	public String getName() {
		return name;
	}
	public void setName(String name) {
		this.name = name;
	}
	public String getDept() {
		return dept;
	}
	public void setDept(String dept) {
		this.dept = dept;
	}
	public String getJob() {
		return job;
	}
	public void setJob(String job) {
		this.job = job;
	}
	public int getSal() {
		return sal;
	}
	public void setSal(int sal) {
		this.sal = sal;
	}
}



package ncs.test1;

import java.util.Scanner;

public class EmployeeTest {

	public static void main(String[] args) {
		Employee e1 = new Employee();
		
		e1.setNo("A1892");
		e1.setName("이미주");
		e1.setDept("AI개발부");
		e1.setJob("사원");
		e1.setSal(3500);
		
		Employee e2 = new Employee("B8077","유재석","Web개발부", "부장",7000);
		Employee e3 = new Employee("F5691","신미나","총괄개발부", "전무",9000);
		
		Employee[] employees = {e1, e2, e3};
		
		EmployeeTest et = new EmployeeTest();	
		et.search(employees);
	}
	// 사원이 있으면 사원 정보 출력, 사원이 없으면 "해당 사원은 없습니다" 출력 후 
	// 다시 사원번호를 입력(반복)
	// exit 라고 입력시 종료
	public void search(Employee[] emps) {
		Scanner scan = new Scanner(System.in);
		
		boolean run = true; //true : 반복, false : 중지
		
		while(run) {
	
		System.out.println("사원번호를 입력하세요");
		System.out.println("exit입력시 종료됩니다.");
		System.out.print("사원번호 > ");
		
		String input = scan.next();
		int x = 0; // 0 : 사원이 없음, 0 아니면  : 사원 있음
		
		for(Employee e : emps) {
			if(input.equals(e.getNo())){
				System.out.println(
				e.getNo()+" : "+e.getDept() +" "+e.getName() +" "+e.getJob());
				x++;
			}
		}
		if(x == 0) {
			if(input.equals("exit")) {
				System.out.println("종료됩니다.");
				run = false;
			}else {
				System.out.println("해당 사원은 없습니다.");
			}
		}
		
		}//while
	}//search
	
}
