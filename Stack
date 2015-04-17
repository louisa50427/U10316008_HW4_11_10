import java.util.*;

public class Stack{
  //main method
	public static void main(String[] args){
		//建立一個MyStack的物件
		MyStack stack = new MyStack();
		
		//Scanner
		Scanner input = new Scanner(System.in);
		String value;
		
		//請使用者輸入五個字串
		System.out.println("Please enter 5 string:");
		
		//一個迴圈讓使用者輸入的字串存到陣列裡
		for(int i = 0 ; i < 5 ; i++){
			value = input.next();
			stack.push(value);
		}
		
		//輸出pop()的值
		while(!stack.isEmpty()){
			System.out.print(stack.pop() + " ");
		}
		
	}
}
