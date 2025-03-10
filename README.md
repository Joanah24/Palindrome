package midterm;

public class palindrome_lumanas {
   
    public static void main(String[] args) {
        String name = "JOANAH";
        
        // Using StringBuilder to reverse the string
        String reversed = new StringBuilder(name).reverse().toString();
        
        System.out.println(reversed);
        System.out.println("Character at 1: " + name.charAt(1));
    }
}
