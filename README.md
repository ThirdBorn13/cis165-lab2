# cis165-lab2
homework
CIS 165 Lab 2

Initial Plans

Program 1 — Sum of Two Numbers

I will create two integer variables and store 50 and 100 in them. I will add the two values together and store the answer in a variable called `total`. Then I will display the value of `total` with a clear label.

Pseudocode:
1. Store 50 in a variable.
2. Store 100 in a variable.
3. Add the two variables together.
4. Store the answer in `total`.
5. Display `total`.

Program 2 — Miles Per Gallon

I will create variables for the number of miles and gallons of gasoline. I will store 312 miles and 16 gallons in the variables. I will divide the miles by the gallons to calculate miles per gallon and store the result in another variable. I will use a data type that allows the answer to contain a decimal. Finally, I will display the result with the MPG units.

Pseudocode:
1. Store 312 miles.
2. Store 16 gallons.
3. Divide miles by gallons.
4. Store the result in an MPG variable.
5. Display the MPG result with its units.

## Programs

### sum.cpp

The `sum.cpp` program stores the values 50 and 100 in integer variables. It adds those values together and stores the result in `total`. The program then displays the value stored in `total`.

mpg.cpp

The `mpg.cpp` program stores the car's distance and gasoline capacity in `double` variables. It divides the number of miles by the number of gallons to calculate miles per gallon. The result is stored in the `mpg` variable before being displayed.



Testing

I tested each program using the assigned values and then tested each program again using different values. Before each test, I calculated the expected result and compared it with the actual output from the program.

| Program | Values Used | Expected Result | Actual Output | Agree? |
|---|---|---|---|---|
| `sum.cpp` | 50 + 100 | 150 | 150 | Yes |
| `sum.cpp` | 25 + 75 | 100 | 100 | Yes |
| `mpg.cpp` | 312 miles / 16 gallons | 19.5 MPG | 19.5 MPG | Yes |
| `mpg.cpp` | 250 miles / 12 gallons | 20.8333 MPG | 20.8333 MPG | Yes |

Final Verification

After completing the different-value tests, I restored the original assigned values in both `.cpp` files. I reran both programs and confirmed that `sum.cpp` produced 150 and `mpg.cpp` produced 19.5 MPG.

Code Explanations

sum.cpp

The program starts by storing 50 in `number1` and 100 in `number2`. The program then adds those two variables together and stores the result in `total`. This means `total` contains 150 before anything is printed. I store the calculation in `total` before printing because the assignment requires the calculation to be completed first and then the result variable to be displayed. It also makes the program easier to understand because the variable clearly represents the answer.

mpg.cpp

The formula for miles per gallon is miles divided by gallons. In this program, 312 miles is divided by 16 gallons, giving a result of 19.5 MPG. I used the `double` data type because miles per gallon can have a fractional result. If C++ divides two integer values, it performs integer division and removes the decimal portion of the answer. For example, 250 divided by 12 would be approximately 20.8333, but using two integers would result in 20. In my changed-value test, I used 250 miles and 12 gallons, and the `double` variables allowed the program to produce the fractional result.
