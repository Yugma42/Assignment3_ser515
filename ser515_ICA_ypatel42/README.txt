-> The 3 problems addressed in 2.1 are:

1) Problem #87 This statement should have braces
    if (s instanceof Savings)  { // FIXING #87 This statement should have braces
       ((Savings)s).withdraw(100.0f);
    }


2) Problem #17 The method 'getTax()' is missing an @Override annotation.
    @Override //FIXING #17 The method 'getTax()' is missing an @Override annotation.
    public int getTax() {
        return 250;
    }

3) Problem #65 Empty for statement

    for (int i = 0; i < pow; i++) { //FIXING #65 Empty for statement
	res *= n;
    }


-> The problem addressed for 2.2 is: 

Problem #62: "Unused import 'java.util.HashMap"

The reason why this would not be a problem is:

a. Unused imports do not affect the functionality, performance, or maintainability of the code.
b. They might have been left in the code temporarily or for future use.
c. Automated tools like linters or static analyzers can sometimes produce false positives in detecting unused imports.

-> The problem addressed for 3.1 is:

Problem #1: The method 'main(String[])' has an NPath complexity of 256, the current threshold is 200

