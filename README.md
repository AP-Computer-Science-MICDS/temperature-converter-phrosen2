# Temp Converter

## Description/Instructions

The goal of this assignment is to write a program that converts from a user's Fahrenheit temperature to Celsius using the following formula:

$$\text{Celsius} = \frac{5}{9} \times (\text{Fahrenheit} - 32)$$


1. Line 1 of the program output **MUST** ask the user for the temperature in Fahrenheit. This will be an integer.
2. Line 2 of the program output **MUST** provide the temperature in Celsius. This can be a decimal number. This value does not need to be rounded.
3. **Hint:** You will need what is called a `Scanner` to receive input from a user in the console. See ScannerExample.java for an example.

Keep in mind that you may need to declare variables to hold intermediate values or store input and output. Your program can have as many lines as you would like inside the `.java` file.

---

## Output

Your output **MUST** exactly match the following example (using an input of 70°F):

```
Please give me a temperature in fahrenheit: 70
The temperature in celsius is: 21.11111111111111
```

---

## Hints / Common Issues

1. **Integer division:** A common issue is getting `0°C` or `-0°C` no matter what you type. This happens because you may have used integer division instead of double division.

---

## How to Submit

## TODO: Write instructions based on student experience.

---

## Important: Multiple Test Cases

From here on out, **assignments will have different outputs for different inputs!** This means you can't just look at your program running one time to tell if it works — it may work on some inputs but not others. **Try your code against all of the grading criteria test cases** below and see if your program gives correct results.

The last test is hidden. For now, you can assume that if your code passes the first five by doing the calculation, it will pass the hidden one. However, it is important to start thinking about how you could be more sure to account for *all possible* inputs.

---

## Grading Criteria

| Test         | Description                                              |
|--------------|----------------------------------------------------------|
| `test1`      | Checks the program with an input of 70°F                 |
| `test2`      | Checks the program with an input of 32°F                 |
| `test3`      | Checks the program with an input of 0°F                  |
| `test4`      | Checks the program with an input of 102°F                |
| `test5`      | Checks the program with an input of -32°F                |
| `hiddenTest` | Checks the program with an input unknown to the student  |
| `checkHeader`| Checks to see if the header is on top of the code        |

---

## Running Tests

Type the following and then hit enter in your Terminal window in Github Codespaces to run the given tests:

bash test.sh
