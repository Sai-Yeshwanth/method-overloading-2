class Add{
	public void add(int a,int b)
	{
		System.out.println(a+b);
	}
	public void add(String a, String b, String c)
	{
		System.out.println(a+b+c);
	}
}
public class Jala {
	public static void main(String[] args) {
		Add a = new Add();
		a.add(5,6);
		a.add("Sai ","Yeshwanth ","Reddy");
	}
}
