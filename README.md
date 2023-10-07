# Python Code Example

This repository contains Python code snippets that perform various operations on data and dictionaries. Below, we provide a brief explanation of each code section.

## Reversing and Sorting a List of Tuples

### Code

```python
old = [("fareedi", "Talha"), ("Amaad", "Akram"), ("ijaz", "Aiza")]
new = []

for name in old:
    reverse_tuple = tuple(reversed(name))
    new.extend(reverse_tuple)

print("Printing the Reversed List of strings:\n")
print(new)

sorted_new = sorted(new)
print("Printing Sorted List:\n")
print(sorted_new)
This code takes a list of tuples old, reverses each tuple, and appends the reversed elements to a new list new. It then prints the reversed list and a sorted version of it

Searching for a Word in User Input
Code
python
Copy code
a = input("Enter a desired value: ")

for word in a.split():
    if word.lower() == 'python':
        print("Yes, the word 'Python' is found.")
    else:
        print("No 'Python' word found.")
In this code, the user is prompted to enter a string (a). The code then splits the input into words and checks if any of them are equal to 'python' (case-insensitive). It prints a message based on whether 'Python' is found in the input.

Dictionary Example
Code
python
Copy code
dic = {
    "Math_class": {
        "Ahmad": 80,
        "Aiza": 70,
        "Talha": 75
    },
    "English_class": {
        "Ahmad": 80,
        "Aiza": 70,
        "Talha": 75
    },
    "Physics_class": {
        "Ahmad": 80,
        "Aiza": 70,
        "Talha": 75
    }
}
This code snippet defines a nested dictionary dic representing student scores in different classes. Each class has a sub-dictionary with student names as keys and their corresponding scores as values.

