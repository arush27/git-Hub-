``` python
student_marks = {
    "Alice": 85,
    "Bob": 92,
    "Charlie": 78,
    "Daisy": 89,
    "Eve": 94
}


student_name = input("Enter the student's name: ")

if student_name in student_marks:
    print(f"{student_name}'s marks: {student_marks[student_name]}")
else:
    print(f"Student named '{student_name}' not found in the records.")
```
OUTPUT:
Enter the student's name: Bob
Bob's marks: 92
```

``` 
Enter the student's name: John
Student named 'John' not found in the records.
```
TASK 2:
numbers = list(range(1, 11))
first_five = numbers[:5]


reversed_list = first_five[::-1]


print("Extracted List:", first_five)
print("Reversed List:", reversed_list)

OUTPUT:
Extracted List: [1, 2, 3, 4, 5]
Reversed List: [5, 4, 3, 2, 1]
