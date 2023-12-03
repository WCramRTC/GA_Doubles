
# Guided Assignment - Introduction to Doubles in C#

## Tutorials

### Starting Code
```csharp
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Decimal Number: 0.0");
    }
}
```

**Understanding the Code:** This code snippet prints a decimal number to the console. We will modify this to explore the `double` data type.

**Write this code**  
- Add a comment above the `Main` method for better readability.

```csharp
    // Entry point of our C# program
    static void Main(string[] args)
    {
        Console.WriteLine("Decimal Number: 0.0");
    }
```

---

### **Step 1: Display a Decimal Number**

**Objective:** Learn to print a decimal number.

Replace `"Decimal Number: 0.0"` with a decimal number. Decimal numbers in C# don't need quotes.

```csharp
static void Main(string[] args)
{
    Console.WriteLine(10.5);
}
```

**Run your code**  
You should see `10.5` printed.

**Understanding Doubles:** The `double` data type in C# is used to represent numbers with decimal points.

---

### **Step 2: Declaring a Double Variable**

**Objective:** Understand how to store decimal numbers in variables.

1. Declare a `double` variable named `myHeight` and assign a decimal number to it.

```csharp
    double myHeight = 5.8; // Replace 5.8 with your height
```

2. Update `Console.WriteLine` to use `myHeight`.

```csharp
    Console.WriteLine(myHeight); 
```

**Run your code**

The number assigned to `myHeight` will be displayed.

**Understanding Variables:** Variables can hold decimal numbers too. In `double myHeight = 5.8;`, `myHeight` is the variable name, and `5.8` is the value.

---

### **Step 3: Arithmetic with Doubles**

**Objective:** Learn to use `double` in arithmetic operations.

1. Declare a `double` variable `halfHeight` and calculate half of your height.

```csharp
    double halfHeight = myHeight / 2;
    Console.WriteLine(halfHeight);
```

**Run your code**  

You should see half of your height displayed.

**Understanding Arithmetic with Doubles:** C# performs arithmetic operations with doubles, allowing for decimal precision.

---

### **Step 4: Combining Double Variables**

**Objective:** Learn to combine `double` variables.

Combine two `double` variables to see their sum.

1. Declare another `double` `myWeight` and assign a value.
2. Add `myHeight` and `myWeight` and store it in a new variable `total`.

```csharp
    double myWeight = 150.5; // Replace with your weight
    double total = myHeight + myWeight;
    Console.WriteLine(total);
```

**Run The Code**

You should see the sum of your height and weight.

---

### **Step 5: Precision with Doubles**

**Objective:** Understand precision in decimal numbers.

Explore the precision of `double` by dividing one number by another.

1. Divide `myWeight` by 3 and print the result.

```csharp
    double thirdWeight = myWeight / 3;
    Console.WriteLine(thirdWeight);
```

**Run your code**

You'll see a decimal number with multiple digits after the decimal point.

**Understanding Double Precision:** The `double` data type can handle a high degree of precision, making it suitable for scientific calculations.

---

### Additional Tips and Resources

- **Debugging:** Watch out for common issues like accidental integer division when using doubles.
- **Challenge:** Try working with more complex arithmetic operations like square roots or trigonometric functions.
- **Further Learning:** Visit [Microsoft's C# documentation](https://docs.microsoft.com/en-us/dotnet/csharp/) for more on `double` and other numeric data types.
- **Syntax Highlighting:** If online, notice how the syntax highlighting distinguishes different parts of the code.

---
