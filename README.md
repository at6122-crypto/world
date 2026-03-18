# world
public class UC2 {
    public static void main(String[] args) {

        // Check if user provided input
        if (args.length > 0) {
            String userName = args[0];
            System.out.println("Hello " + userName);
        } else {
            System.out.println("Hello User");
        }
    }
}
 
