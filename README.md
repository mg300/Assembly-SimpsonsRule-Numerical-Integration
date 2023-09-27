# Simpson's Rule - Numerical Integration of cos^2 x

This program is an example of x86 assembly code that calculates the approximate definite integral of a given function over a specified interval using Simpson's rule.

### Usage
1. Run 'Simpson.exe' file
2. The program starts by displaying a prompt where the user is asked to input 'a,' 'b,' and 'N,' which define the integration interval and the number of subintervals.
3. Program calculates the approximate integral value using Simpson's rule.
4. The result will be displayed.

### Code Structure

1. start: The program's entry point, where the user is prompted for input.
2. oblicz_dx: Computes the subinterval width 'dx' based on user input.
3. oblicz_x: Calculates the 'x' value for each subinterval.
4. oblicz_st: Approximates the function value for a given 'x' and accumulates them in 'st.'
5. oblicz_s: Computes the final integral result using Simpson's rule.
6. compare_n_with_counter: A loop that performs calculations for each subinterval.
7. enda: Program termination after displaying the result.

### Compilation
1. Download and install "Emu8086.exe".
2. Open "Emu8086".
3. Open "Simpson.asm" within the app.
4. Compile and debug.
