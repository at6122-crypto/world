# world
public class HelloWorld {
    public static void main(String[] args) {

        // Default message if no arguments
        if (args.length == 0) {
            System.out.println("Hello, World!");
            return;
        }

        // Build greeting using enhanced for loop
        String names = "";

        for (String name : args) {
            names += name + ", ";
        }

        // Remove trailing ", " using substring
        names = names.substring(0, names.length() - 2);

        // Print final greeting
        System.out.println("Hello, " + names + "!");
    }
}
