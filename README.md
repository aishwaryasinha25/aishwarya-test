# aishwarya-test
 This is a demo repository

class Adder{
	static int sum(int a,int b) {
		return(a+b);
	}
	static int sum(int a,int b,int c) {
		return(a+b+c);
	}
}

public class OverloadingDemo {

	public static void main(String[] args) {

		System.out.println(Adder.sum(12,78));
		System.out.println(Adder.sum(45,65,16));
	}

}
