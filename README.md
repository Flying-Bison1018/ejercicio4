# ejercicio4
actividad
package ejercicio.pkg4;

/**
 *
 * @author PC
 */
import java.util.Scanner;
public class Ejercicio4 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner rd = new Scanner (System.in);
        
        double radio;
        double largo;
        double area;
        double PI;
        PI = 3.14;
        System.out.println("Digite el radio\n");
        radio =rd.nextDouble();
        
        area = PI*(radio*2);
        largo = 2*PI*radio;
        
        System.out.println("el largo es:"+largo);
        System.out.println("\nel area es:"+area);
        // TODO code application logic here
    }
    
}
