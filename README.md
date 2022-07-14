# Collections
import java.util.*;

public class IterateElements {
	public static void main(String[] args)
	{
		ArrayList<String> list=new ArrayList<String>();
		list.add("Krati");
		list.add("Shivani");
		list.add("Ishika");
		list.add("Gaurav");
		System.out.println(list);
		
		ListIterator<String> list1=list.listIterator(list.size());
		while(list1.hasPrevious())  
        {  
            String str=list1.previous();  
            System.out.println(str);  
        }  
		
		
	}


}
