
package act1;
import java.util.*;
import java.math.*;
        public class Act1 {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the size of array:");
        int x = sc.nextInt();
        int[] array;
        array= new int[x]; 
        mean(array);
        System.out.println("     ");
        mode(array);
    }
    public static double mean(int[] m) {     
        Scanner sc = new Scanner(System.in);
    double sum = 0;  
    for (int i = 0; i < m.length; i++) {
        System.out.println("Enter next num"+i+":");
        int g = sc.nextInt();
        m[i]=g;
        sum += m[i];
    }
    double mean =  sum / m.length;
        System.out.println("     ");
        System.out.printf("Mean: %.2f" ,mean);
        
            return 0;
}
public static int mode(int[] array){
    int mode = array[0];
    int maxCount = 0;
    for (int i = 0; i < array.length; i++) {
        int value = array[i];
        int count = 1;
        for (int j = 0; j < array.length; j++) {
            if (array[j] == value) count++;
            if (count > maxCount) {
                mode = value;
                maxCount = count;
            }
        }
    }
    System.out.println("Mode: %.2f"+ mode);
    return mode;
}

}

