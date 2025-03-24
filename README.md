# loop-in-python

**Here my sloving basic question on loop:**

**while loop**

1. **Basic Counting with while Loop**:
   - Write a program that counts from 1 to 10 using a while loop.
 **code:** 
  ```python
i=0
while  i<=10:
    print(i)
    i+=1
    
```
**output**
```python
0
1
2
3
4
5
6
7
8
9
10
```
2. **Odd Numbers Printer**:
   - Create a program that prints all odd numbers between 1 and 20 using a while loop.
**code**
```python
i=1
while i<=20:
    print(i)
    i=i+2
```
---
**output**
```python
1
3
5
7
9
11
13
15
17
19
```
3. **Ticket Booking Simulation**:
   - Write a program that simulates a bus ticket booking system. The bus has 8 seats. Each time a seat is booked, the available seats decrease. When there are no seats left, the loop stops and displays a message saying "All seats are booked."

**code:**
```python
   bus_seat=8
while bus_seat>0:
    print (f"available seat:{bus_seat}.")
    seat = input ("do you want to book your seat (yes/no):").lower()
    if seat == "yes":
        bus_seat -= 1
        print ("your seat is booked")
    else:
        print ("no seat are booked")
```
---
**output**
```python
available seat:8.
do you want to book your seat (yes/no): yes
your seat is booked
available seat:7.
do you want to book your seat (yes/no): no
no seat are booked
available seat:7.
do you want to book your seat (yes/no): yes
your seat is booked
available seat:6.
do you want to book your seat (yes/no): yes
your seat is booked
available seat:5.
do you want to book your seat (yes/no): yes
your seat is booked
available seat:4.
do you want to book your seat (yes/no): yes
your seat is booked
available seat:3.
do you want to book your seat (yes/no): yes
your seat is booked
available seat:2.
do you want to book your seat (yes/no): yes
your seat is booked
available seat:1.
do you want to book your seat (yes/no): yes
your seat is booked
seat are not available
```
4. **Countdown Timer**:
   - Write a program that counts down from 10 to 1 using a `while` loop and prints "Happy New Year!" after the countdown is over.
**code:**
```python
i=11
while  i>=1:
    i-=1
    print(i)
    
print("happy new year")
```
---
**output**
```python
10
9
8
7
6
5
4
3
2
1
0
happy new year!!
```

**For loop**

1. **Multiples of 3**:
   - Write a for loop that prints all multiples of 3 between 1 and 30.
  
   **code:**
   ```python
   for i in range(1,11):
    print (f"{3}*{i}={3*i}")
   ```
   **output**
   ```python
3*1=3
3*2=6
3*3=9
3*4=12
3*5=15
3*6=18
3*7=21
3*8=24
3*9=27
3*10=30
```
2. **Sum of First 10 Numbers**:
   - Write a program using a for loop that calculates the sum of numbers from 1 to 10.
**code:**
```python
for i in range(1, 11):
    print(int(sum(range(1, i+1))))
```
**output**
```python
1
3
6
10
15
21
28
36
45
55
```
3. **Print Your Name Letter by Letter**:
   - Write a program that takes your name as input and prints each letter of your name using a for loop.
**code:**
```python
name = input("enter your name") 
for i in name:
    print(i)
```
**output**
```python
enter your name manaswin
m
a
n
a
s
w
i
n
```
4. **Count Vowels in a String**:
   - Write a program that counts how many vowels are in a given string using a for loop.

**code:**
```python
string = input("Enter a string: ")
vowels = "aeiouAEIOU"
vowel_count = 0
for char in string:
    if char in vowels:
        vowel_count += 1
print(f"The number of vowels in the string is: {vowel_count}")
```
**output**
```python
Enter a string:  manohar
The number of vowels in the string is: 3
```

