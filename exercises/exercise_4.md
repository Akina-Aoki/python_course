# Exercise 4 - working with text and files

## NOT FINISHED YET

In this exercise, you get to familiarize yourself with strings, file handling, error handling and strings. This exercise covers 07-09

## 0. Counting words (*)

Count the number of words in this sentence: "A picture says more than a thousand words, a matematical formula says more than a thousand pictures." (*) 

## 1. Counting letters (*)

Let the user input a word: 

a) print out the number of letters in the word. (*) 

b) print out the number of **uppercase** and **lowercase** letters of the word (*)   

## 1. Palindrome (*)

A palindrome is a sequence of characters that is the same, when read forward as backwards (ignoring spaces). For example:
- "Anna" is a palindrome
- "Ni talar bra latin"
- bjkjb 

Here is a flowchart of the algorithm. 

<img src="https://github.com/kokchun/assets/blob/main/python/palindrome_flowchart.png?raw=true" width = 300 style="display:inline-block; text-align:left;">

Let the user input a sequence of characters and check if it is a palindrome. (*)


## 2. Vowels (**)

Count the number of vowels in this sentence: "Pure mathematics is, in its way, the poetry of logical ideas"


## 3. Encryption (**)

Let the user input a word and: 

&nbsp; a) &nbsp; encrypt the message by replacing each letter with the next letter. If the letter is in the end of the alphabet, use the first letter instead. 

e.g. in Swedish: "höst" $\rightarrow$ "iatu"

## 4. Find and fix errors (*)

Find the errors in this code to compute the distance between the point $(x,y)$ and the origin in a cartesian coordinate system.

```python
impor numpy as np

def distance(x,y)
    reurn np.sqrt(x+y)

print(distance([0.5, 0.5]))

```


## 5. Find and fix errors (*)

Find the errors in this code. Just change the function, don't touch the test program.

```python

def is_fourdigit(number):
    if number//1000 < 10
        return true
    else 
        return false

# test program
test_numbers = [231, 3124, -4124, -1000,-999, 1001, 10000, -10000, 999]

for number in test_numbers:
    if is_fourdigit(number):
        print(f"{number} is four-digit")
    else:
        print(f"{number} is not four-digit")

```

---
## 6. Tram (*)

Kokchun is a **clumpsy** computer user that doesn't take trams too often. Write a program to prompt the user for: 
- number of times he/she wants to take tram in one month
- cost for one ticket
- cost for monthly card

The program should calculate if it's worth for him to buy  monthly card or not. Make the program user friendly with clear error messages and ask again in case of input errors. 

---

## 7. Dice rolls (*)
Create a textfile called **dice_rolls.txt** using Python. Also for each subtask, write adequate headers. 

&nbsp; a) &nbsp; Simulate 20 dice rolls and write them to your textfile. (*)

&nbsp; b) &nbsp; Sort the dice rolls from a) and write them to a separate row in the same textfile. (*)

&nbsp; c) &nbsp; Count the number of fours in the dice rolls and write them to a separate row in the same textfile. (*)


## 8. Test results (*)
Read in the file test_result.txt (located in the data folder of this repo) in Python.

[test_result]: https://github.com/kokchun/Programmering-med-Python-21/blob/main/Files/test_result.txt

&nbsp; a) &nbsp; Print out the text in the terminal (*)

&nbsp; b) &nbsp; Create new rows in the same file and write the people and their corresponding scores in alphabetical order. (*)

&nbsp; c) &nbsp; Create additional rows in the same file and sort the people after their grades. The grade limits are: (**)

 <table style="display:inline-block; text-align:left;">
    <tr style="background-color: #174A7E; color: white;">
      <th>Grade</th>
      <th>Range</th>
    </tr>
    <tr>
      <td>F</td>
      <td>&lt; 20</td>
    </tr>
    <tr>
      <td>E</td>
      <td>20-29</td>
    </tr>
    <tr>
      <td>D</td>
      <td>30-39</td>
    </tr>
    <tr>
      <td>C</td>
      <td>40-49</td>
    </tr>
    <tr>
      <td>B</td>
      <td>50-59</td>
    </tr>
    <tr>
      <td>A</td>
      <td>60-70</td>
    </tr>
  </table>


## 9. National test (*)
Read in the file NPvt19Ma2A.txt and NPvt19Ma2C.txt (located in the data folder of this repo) in Python. Use **matplotlib** to plot pie charts for each grade categories in each file.


## 10. Dice roll experiment (**)
Simulate 10, 100, 1000, 10000, 100000 dice rolls and count the freqencies and probabilities for each number in each simulation. Create a new text file using Python with the name "simulation.txt" and write the results to that text file.



## 11. Theory

a) What is the difference between = and == in Python?

b) Explain the meaning of truthy and falsey values

c)

## Glossary

Fill in this table either by copying this into your own markdown file or copy it into a spreadsheet if you feel that is easier to work with.

| terminology   | explanation |
| ------------- | ----------- |
|               |             |
|               |             |
| concatenation |             |
