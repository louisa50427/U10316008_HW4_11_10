import java.util.*;

public class MyStack extends ArrayList<String>{
	
	//確認陣列是否為空的
	public boolean isEmpty(){
		return super.isEmpty();
	}
	//回傳陣列大小
	public int getSize(){
		return super.size();
	}
	//回傳陣列最後一個值
	public String peek(){
		return super.get(getSize() - 1);
	}
	//回傳陣列最後一個值並在陣列中刪除最後一值
	public String pop(){
		String o = super.get(getSize() - 1);
		super.remove(getSize() - 1);
		return o;
	}
	//把值加進陣列中
	public void push(String o){
		super.add(o);
	}
	//字串
	@Override
	public String toString(){
		return "stack:" + super.toString();
	}
}
	
