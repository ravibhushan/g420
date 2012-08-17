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
 **/
public class InputBoxes {

     /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        String first_name;
        
        //Ask First Name
        first_name = JOptionPane.showInputDialog("First Name");



        //Ask Family Name
        String family_name;
        family_name = JOptionPane.showInputDialog("Family Name");


        /Display both the firstname and the full name
        String full_name;
        full_name = "You are " + first_name + " " + family_name;
        JOptionPane.showMessageDialog( null, full_name );
        System.exit(0);
        
    }
}
