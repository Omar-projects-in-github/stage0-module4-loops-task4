Tasks:
1. Fix me.
   Change the program code so that it compiles and prints everything as it is in expected output.

public class FixMe {
public static void main(String[] args) {
for (int i = 0; i < 100; i++) {
if (i % 2 == 0) {
System.out.println(i);
} else if (i == 7) {
System.out.println("last");
break;
System.out.println("will I be printed?");
}
}
}
}
//Expected output: 0 2 4 6 last will I be printed?

2. Skipping third.
   Write a program that will print all numbers from one up to given(inclusive), skipping each 3rd.

public class SkippingThird {
public void printUntilButThird(int lastPrinted) {
}
}
3. Sum of skipped.
   Write a program that will consume 2 args: the first is number to skip, the second to iterate till. You should consider the cases: 3.1. when numberToSkip is greater than lastInRow -> output is:"number to skip is bugger then the last" 3.2. when lastInRow is negative -> output is:"last number in row is negative" 3.3. for the rest cases output is: "skipped sum is number" "counted sum is number", where number is an actual sum of them:

public class TwoRangesSum {
public void printSumOfTwoRanges(int numberToSkip, int lastInRow) {
}
}
4. Number to break.
   Write a program that will consume 2 args: the first is number to break on, the second to iterate till, if number to iterate till is less than to break with -> sout("iterating till the end") and print all the numbers till the end, otherwise all numbers till toBreakWith.

public class NumberToBreakOn {
public void printNumbersUntilWithBreakOn(int toBreakWith, int numberToGoUntil) {
}
}