# Grading-on-marks

## Aim:
To write a C# program to display the comment based on Grade obtained.

## Algorithm:
### Step1:
Start

### Step2:
Create a class and declare one variable with integer datatype

### Step3:
Get marks from the User.

### Step4:
Use if and elif condition to check the grade

### Step5:
print the grade for the given mark

### Step6:
stop
## Program:
```c#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
public class exercise19
{
    static void Main(string[] args)
    {
        string notes;
        char grd;
        Console.Write("Input the grade :");
        grd = Convert.ToChar(Console.ReadLine().ToUpper());
        switch (grd)
        {
            case 'E':
                notes = " Excellent";
                break;
            case 'V':
                notes = " Very Good";
                break;
            case 'G':
                notes = " Good ";
                break;
            case 'A':
                notes = " Average";
                break;
            case 'F':
                notes = " Fails";
                break;
            default:
                notes = "Invalid Grade Found.";
                break;
        }
        Console.Write("You have chosen  : {0}\n", notes);
    }
}
```
## Output:
![Screenshot (20)](https://user-images.githubusercontent.com/75234807/164182138-6e3facdb-74a7-411e-8d3f-afa4c7d72369.png)

## Result:
Thus the C# program to grade the marks is executed successfully.
