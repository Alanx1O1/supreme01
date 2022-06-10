# supreme01
Coding is essential
# This is Alan's code using Java to program certain files



# Display Fibonacci Sequence
# Fibonacci Series: 0,1,1,2,3,5,6,13,21,34

# These are the first 2 terms in the Fibonnacci Series 
# firstTerm = 0
# secondTerm = 1

# Calculating the next sequences in the Fibonnacci Series as show below here in these 3 lines

# nextTerm = firstTerm + secondTerm; (0+1)
# firstTerm = secondTerm; (1)
# secondTerm = nextTerm; (1)

# Displaying the Fibonacci Series Using a For Loop, till 10 terms:
  
  class Main {
  public static void main(String[] args) {

    int n = 10, firstTerm = 0, secondTerm = 1;
    System.out.println("Fibonacci Series till " + n + " terms:");

    for (int i = 1; i <= n; ++i) {
      System.out.print(firstTerm + ", ");

      // compute the next term
      int nextTerm = firstTerm + secondTerm;
      firstTerm = secondTerm;
      secondTerm = nextTerm;
    }
  }
}


