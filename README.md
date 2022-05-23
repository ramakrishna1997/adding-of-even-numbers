# adding-of-even-numbers
import java.util.Scanner;

public class printingnumber {
	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		System.out.println("Enter Starting Number");
		int SN = scanner.nextInt();
		System.out.println("Enter Ending Number");
		int EN = scanner.nextInt();
		int a = SN;
		int sum =0;
		while(a<=EN) {
			if(a%2==0)
				sum += a;
			a++;

		}scanner.close();
		System.out.println("the sum of the Even Numbers : " +sum);
	}
}
