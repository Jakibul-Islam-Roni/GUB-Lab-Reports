# Green University of Bangladesh

**Department of Computer Science and Engineering (CSE)**  
Faculty of Sciences and Engineering  

**Semester:** Spring 2026  
**Program:** B.Sc. in CSE (Day)  

---

## Assignment Information

- **Assignment No.:** 01  
- **Course Title:** Computational Thinking and Problem Solving  
- **Course Code:** CSE 100  
- **Section:** D8  

---

## Student Details

| Name                         | ID        |
|------------------------------|-----------|
| MD. JAKIBUL ISLAM RONI       | 261002140 |

- **Assigned Date:**  
- **Submission Date:**  
- **Course Teacher:** Md. Sabbir Hosen Mamun  

---

# Title of the Lab Experiment

**Reversing the Digits of a Given Number Using C Programming**

---

## Objectives

- To understand number manipulation techniques  
- To learn how to use loops in C programming  
- To apply arithmetic operators (division and modulus)  
- To develop logical thinking and problem-solving skills  

---

## Concepts

Reversing a number means changing the order of its digits.

**Example:**

- Input: 1234  
- Output: 4321  

**We use:**

- Modulus (%) → to get last digit  
- Division (/) → to remove last digit  

**Process:**

1. Take last digit  
2. Add it to reversed number  
3. Repeat until number becomes 0  

---

## Procedure

### Algorithm

1. Start  
2. Input a number  
3. Initialize `reverse = 0`  
4. While number ≠ 0  
   - digit = number % 10  
   - reverse = reverse * 10 + digit  
   - number = number / 10  
5. Display reverse  
6. End  

---

## Pseudocode

```
START
INPUT number
reverse = 0
WHILE number != 0
    digit = number % 10
    reverse = reverse * 10 + digit
    number = number / 10
PRINT reverse
END
```

---

## Implementation (C Code)

```c
#include <stdio.h>

int main() {
    int number, reverse = 0, digit;

    printf("Enter a number: ");
    scanf("%d", &number);

    while (number != 0) {
        digit = number % 10;
        reverse = reverse * 10 + digit;
        number = number / 10;
    }

    printf("Reversed Number: %d\n", reverse);

    return 0;
}
```

---

## Input

```
Enter a number: 1234
```

## Output

```
Reversed Number: 4321
```

---

## Test Result

| Input | Output |
|------|--------|
| 1234 | 4321   |
| 56789 | 98765 |
| 100  | 1      |

---

## Discussion

This program demonstrates how loops and arithmetic operations can be used to manipulate numbers.  

- Modulus (%) helps extract digits  
- Division (/) reduces the number step by step  

This experiment improves understanding of:

- Loop control  
- Number processing  
- Logical thinking  

---

## Conclusion

The experiment was successful. The program correctly reverses the digits of a given number and strengthens understanding of loops and arithmetic operations in C programming.