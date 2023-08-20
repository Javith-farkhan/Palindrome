# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
Step 1: To start the C# program in visual Studio 2022.

Step 2: Create a class and declare two variable with string datatype.

Step 3: Loop over the entire string and reverse it.

Step 4: Use if condition to check whether the string and the reversed string is equal or not.

Step 5: print palindrome if it's equal else print not a palindrome.

Step 6: Save the program and run the program in visual studio 2022.
## Program:
```
namespace palindrome;

class palindrome
{
    static void Main(string[] args)
    {
        string str1;
        Console.WriteLine("Enter the string:");
        str1 = Console.ReadLine();
        
        string rev = "";
        for(int i=str1.Length-1; i>=0; i--)
        {
            rev += str1[i];
        }
        if(str1==rev)
        {
            Console.WriteLine("The string is palindrome");
        }
        else 
        {
            Console.WriteLine("The string is not palindrome");
        }
        Console.ReadLine(); 
    }
}
```
## Output:
![C#2](https://github.com/Guru-Guna/Palindrome/assets/93427255/a80ddc6a-ab1b-41c5-b0d1-e5f30ebf28c6)

## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
