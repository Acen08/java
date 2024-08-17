public class VariableExamples {

    // Static variable (class variable)
    static int staticVar = 100;

    // Instance variables
    String instanceVar = "Instance Variable";

    public void demonstrateVariables() {
        // Local variables
        int localVar = 10;
        String localString = "Local String";

        // Print local variables
        System.out.println("Local Variable: " + localVar);
        System.out.println("Local String: " + localString);

        // Print instance variables
        System.out.println("Instance Variable: " + instanceVar);

        // Print static variable
        System.out.println("Static Variable: " + staticVar);
    }

    public static void main(String[] args) {
        VariableExamples example = new VariableExamples();
        example.demonstrateVariables();

        // Accessing static variable directly via class name
        System.out.println("Accessing Static Variable from Main: " + VariableExamples.staticVar);
    }
}
