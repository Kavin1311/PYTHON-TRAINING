
# QN:
Write a Python program which accepts a sequence of comma separated 4 digit
binary numbers as its input and then check whether they are divisible by 5 or not.
The numbers that are divisible by 5 are to be printed in a comma separated
sequence.
Example:
0100,0011,1010,1001
Then the output should be:
1010
# CODE:
```
nums=input().split(",")
for num in nums:
    if(int(num,2)%5==0):
        print(num)
```
# OUTPUT:
<img width="363" height="99" alt="image" src="https://github.com/user-attachments/assets/dd2f701d-cbc2-4a09-8945-4848478a725c" />


# QN:
Write a Python program that accepts a sentence and calculate the number of
letters and digits.
Suppose the following input is supplied to the program:
hello world! 123
Then, the output should be:
LETTERS 10
DIGITS 3

# CODE:
```
sentence = input().lower()
c_d=0
c_l=0
for word in sentence:
    if('a'<=word<='z'):
        c_L+=1
    elif('0'<=word<='9'):
        c_d+=1
print(c_l)
print(c_d)
   ```     
# Output:
<img width="520" height="132" alt="image" src="https://github.com/user-attachments/assets/4d5a38f5-bd27-48a6-be96-a1afec78afe3" />

# QN:
Write a program which can compute the factorial of a given numbers.The
results should be printed in a comma-separated sequence on a single
line.Suppose the following input is supplied to the program:8
Then, the output should be:40320
# CODE:
```
a=int(input())
fact=1
for i in range(1,a+1):
    fact*=i
print(fact)
```

# OUTPUT:
<img width="483" height="107" alt="image" src="https://github.com/user-attachments/assets/a14d4608-d746-4db0-95af-85c4eb388958" />

