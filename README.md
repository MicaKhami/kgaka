public class Addition{
  public int add(int one,int two)
   {
    return one+two;
}
 public static void main(String[] args)
{
  Addition addAll=new Addition();
   int answer;
   answer=addAll.add(Integer.parseInt(args[0]),Integer.parseInt(args[1]));
   System.out.println("One + Two ="+ answer);
}
}

