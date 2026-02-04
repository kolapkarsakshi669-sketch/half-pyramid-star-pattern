# half-pyramid-star-pattern
This is a java code to print half pyramid of stars often asked in interview.
public class starpattern {
    public static void main(String[] args) {
        int n = 4;
        //outter loop 
        for (int i=1 ; i<=n ; i++) {
            //inner loop
            for (int j=1 ; j<=i ; j++){
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
