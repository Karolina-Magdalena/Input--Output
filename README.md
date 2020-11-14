# Input--Output

Input format in java:

Scanner scan = new Scanner(System.in);
int i = scan.nextInt();
double d = scan.nextDouble();

with String:

scan.nextLine();
String s = scan.nextLine();

When we add an int and hit the enter, program takes this '/n' as a string.
So when we take input string after int/double ... we must add an extra scan().



