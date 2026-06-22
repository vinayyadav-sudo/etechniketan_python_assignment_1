# etechniketan_python_assignment_1
# 1. Print all Python keywords
import keyword
print("Python Keywords:")
print(keyword.kwlist)

# 2. Create a variable x = 10 and print its type
x = 10
print("\nType of x:", type(x))

# 3. Create a tuple with 4 numbers and print its last and second element
t = (10, 20, 30, 40)
print("\nLast element:", t[-1])
print("Second element:", t[1])

# 4. Convert string "123" into integer and add 10
num = int("123")
result = num + 10
print("\nResult:", result)

# 5. Convert a float number into an integer
f = 12.75
integer_value = int(f)
print("\nInteger value:", integer_value)

# 6. Join two strings and find length
str1 = "Hello"
str2 = "World"
new_string = str1 + " " + str2
print("\nJoined String:", new_string)
print("Length:", len(new_string))

# 7. Boolean variable and its type
flag = True
print("\nType of flag:", type(flag))

# 8. Find length of tuple
tuple1 = (10, 20, 30, 40, 50)
print("\nLength of tuple:", len(tuple1))

# 9. Create result = "Python3.13"
language = "Python"
version = 3.13
result = language + str(version)
print("\nResult:", result)

# 10. Student details and percentage calculation
name = input("\nEnter Student Name: ")
age = int(input("Enter Age: "))
city = input("Enter City: ")
course = input("Enter Course Name: ")

sub1 = float(input("Enter Marks in Subject 1: "))
sub2 = float(input("Enter Marks in Subject 2: "))
sub3 = float(input("Enter Marks in Subject 3: "))

total = sub1 + sub2 + sub3
percent = (total / 300) * 100

print("\nStudent Name:", name)
print("Age:", age)
print("City:", city)
print("Course:", course)
print("Percentage:", percent, "%")

# 11. List Operations
subjects = ["Python", "SQL", "Excel", "Tableau"]

# a
print("\nComplete List:", subjects)

# b
print("First Subject:", subjects[0])
print("Last Subject:", subjects[-1])

# c
subjects.insert(1, "Power BI")
print("After Adding Power BI:", subjects)

# d
subjects.remove("Excel")
print("After Removing Excel:", subjects)

# e
new_list = subjects.copy()
print("Copied List:", new_list)

# f
new_list.sort()
print("Sorted List:", new_list)

# g
print("Is Excel Present?", "Excel" in subjects)

# 12. Logical Operators
attendance = True
assignment_submitted = False

# a
print("\na. Operator for True:", attendance or assignment_submitted)

# b
print("b. Operator for False:", attendance and assignment_submitted)

# c
print("c. NOT attendance:", not attendance)
