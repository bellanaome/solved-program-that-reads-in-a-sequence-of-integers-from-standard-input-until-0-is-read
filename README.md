Download Link: https://assignmentchef.com/product/solved-program-that-reads-in-a-sequence-of-integers-from-standard-input-until-0-is-read
<br>
a program that reads in a sequence of integers from standard input <strong>until 0 is read</strong>, and store them in an array (including 0). This is done using iteration (choose one of for, while, or do while loop).

-compute the minimum number

-compute the smallest even integer

-compute count negative numbers

-compute the sum of the numbers that are divisible by 3 <strong>using recursion</strong>.

<u>Use recursive methods:</u><strong><u> </u></strong>

-findMin

-computeSmallestEven

-countNegativeNumbers

-computeSumOfNumbersDivisibleBy3




<u>the following recursive methods must be implemented (These methods should not contain any loop):</u>

<em>   public static int findMin(int[] elements, int startIndex, int endIndex)</em>

<em>   public static int computeSmallestEven(int[] elements, int startIndex, int endIndex)</em>

<em>   public static int countNegativeNumbers(int[] elements, int startIndex, int endIndex)</em>

<em>   public static int computeSumOfNumbersDivisibleBy3(int[] elements, int startIndex, int endIndex)</em>

<strong>DO NOT use any Static Variables.</strong>

You will need to use InputStreamReader and BufferedReader (they are in java.io package) to process input and also take care of IOException.

The program should output the results of those calculations to standard output. Your program will continue to read in numbers until the number 0 is entered.

At this point, the calculations will be outputted in the following format:

The minimum number is

The smallest even integer in the sequence is

The count of negative integers in the sequence is

The sum of numbers that are divisible by 3 is

Note that the result values will be different depending on test cases (not always 0).

<strong>Do not output a prompt to query for the numbers.</strong> The number 0 is included in the sequence of numbers and should be included in all of your calculations.