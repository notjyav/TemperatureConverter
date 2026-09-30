# Temperature Converter

A simple command-line Java program that converts temperatures between Fahrenheit and Celsius.

## How It Works

1. Enter a temperature.
2. Enter the unit you want to convert **to**: `C` for Celsius or `F` for Fahrenheit.
3. The program prints the converted temperature.

## Formulas

```
Fahrenheit to Celsius: (F - 32) * 5 / 9
Celsius to Fahrenheit: (C * 5 / 9) + 32
```

## Requirements

- Java JDK 11 or newer
- IntelliJ IDEA (optional)

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open the project in IntelliJ IDEA.
3. Run `Main.java`.
4. Enter a temperature and a target unit when prompted.

## Example

```
Enter the temperature: 212
Convert to Celsius or Fahrenheit? (C or F): C
100.0 Degrees in C
```

## Concepts Used

- `Scanner` for user input
- Ternary operator (`? :`)
- `toUpperCase()` for case-insensitive input
- `printf` for formatted output
