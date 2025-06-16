# repo
Programming - Portfolio of evidence

Begin
import javax.swing.JOptionPane;

public class NamePrompt {
    public static void main(String[] args) {
        // Show input dialog asking for the user's name
        String name = JOptionPane.showInputDialog(null, "What is your name?", "Name Prompt", JOptionPane.QUESTION_MESSAGE);

        // Optional: Show a greeting message with the entered name
        if (name != null && !name.trim().isEmpty()) {
            JOptionPane.showMessageDialog(null, "Hello, " + name + "!", "Greeting", JOptionPane.INFORMATION_MESSAGE);
        } else {
            JOptionPane.showMessageDialog(null, "You didn't enter a name.", "Warning", JOptionPane.WARNING_MESSAGE);
        }
    }
}

End
