public class BuggyProgram {
    public static void main(String[] args) {
        String input = "Hello World"
        int count = 0;
        for (char c : input.toCharArray()) {
            if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u') {
                count++;
            }
        }
        System.out.println(count);
    }
}
