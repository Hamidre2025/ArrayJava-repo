public class Test1
{
    public static void main(String[] args)
    {
        String[ ] names = {"Jamal", "Emily", "Destiny", "Mateo", "Sofia"};

        int index = 2;
        System.out.println(names[index - 1]);
        index++;
        System.out.println(names[index]);
        System.out.println(names[index/2]);
        names[index] = "Rafi";
        index--;
        System.out.println(names[index+1]);
    }
}
