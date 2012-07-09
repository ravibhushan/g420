g420
/*
 * To change this template, choose Tools | Templates
 * and open the template in the editor.
 */
package inputboxes;
import javax.swing.JOptionPane;

/**
 *
 * @author ravi
 */
public class InputBoxes {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        String first_name;
        first_name = JOptionPane.showInputDialog("First Name");


        
        String family_name;
        family_name = JOptionPane.showInputDialog("Family Name");


        String full_name;
        full_name = "You are " + first_name + " " + family_name;
        JOptionPane.showMessageDialog( null, full_name );
        System.exit(0);
        
        
        
        
    }
}
