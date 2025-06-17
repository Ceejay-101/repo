# Ceejay Mlangeni - ST10474095
Programming - Portfolio of evidence

Begin
import javax.swing.JOptionPane;

public class NamePrompt {
    public static void main(String[] args) {
        // Show input dialog asking for the user's name
        String username = JOptionPane.showInputDialog(null, "Please enter a username", "Username", JOptionPane.QUESTION_MESSAGE);

        // Optional: Show a greeting message with the entered name
        if (name != null && !name.trim().isEmpty()) {
            JOptionPane.showMessageDialog(null, "Hi, " + name +"!", "Welcome", JOptionPane.INFORMATION_MESSAGE);
        } else {
            JOptionPane.showMessageDialog(null, "Please enter a valid username.", JOptionPane.WARNING_MESSAGE);
        }
    }
}

End
