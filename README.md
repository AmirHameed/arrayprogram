import java.util.Scanner;

public class count{
	public static void main(String[] args){
		int loop=0,count=0;
		Scanner obj=new Scanner(System.in);
	while(loop<=1)	{
		
		System.out.print("You Want ");
		String input=obj.nextLine();
		
		if (input.equals("yes")){
			
			//count++;
			//continue;
	
		if(count==0){
		System.out.print("Q no 1");
		String input1=obj.nextLine();
		if (input1.equals("yes")){
			System.out.print("ok");
			count++;
		}else{
			System.out.print("Wrong");
			count++;
		}
		}
		if(count==1){
		System.out.print("q no 2");
		String input2=obj.nextLine();
		if (input2.equals("yes")){
			System.out.print("ok");
			count++;
		}else{
			System.out.print("Wrong");
			count++;
		}
		}
		if(count==2){
		System.out.print("Q no 3");
		String input3=obj.nextLine();
		if (input3.equals("yes")){
			System.out.print("ok");
			count++;
		}else{
			System.out.print("Wrong");
			count++;
		}
		}
		if(count==3){
		System.out.print("Q no 4");
		String input4=obj.nextLine();
		if (input4.equals("yes")){
			System.out.print("ok");
			count++;
		}else{
			System.out.print("Wrong");
			count++;
		}
		}
		if(count==4){
		System.out.print("Q no 5");
		String input5=obj.nextLine();
		if (input5.equals("yes")){
			System.out.print("ok");
			count++;
		}else{
			System.out.print("Wrong");
			count++;
		}
		}
		}else{
				System.out.println("u again then 4 marks");
				count++;
			}	
			
			loop++;
						continue;
		
	}
	}
	
}
