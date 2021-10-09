public class DisplayMatrix {

  public static void main(String[] args) {
    // declare and initialize a 3x3 matrix
    int matrix[][] = 
      { { 1, 2, 3 }, { 4, 5, 6 }, { 7, 8, 9 } };
    
    // display 2D array using for-each loop
    for(int[] i : matrix) {
      for(int j : i) {
        System.out.print(j + " ");
      }
      System.out.println(); // new line
    }
  }

}
