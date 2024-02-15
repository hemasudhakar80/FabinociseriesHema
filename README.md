# FabinociseriesHema
public class Fabbinoseries {

	public static void main(String[] args) {
		int range=19;
		int firstno=0;
		int secondno=1;

		System.out.println(firstno);
		for(int i=1;i<=range;i++) {
			 int sum=firstno+secondno;
			 firstno=secondno;
			 secondno=sum;
			System.out.println(secondno);
		}
	}

}
