# Exercise 5 - dictionary and functions

In this exercise, you get to familiarize yourself with strings, file handling, error handling and strings. This exercise covers 07-09

## 0. Area (\*)

Create a function that takes the base and height of a triangle as input parameters and returns the area of the triangle.

## 1. Euclidean distance (\*)

The formula for Euclidean distance in 2D between $P: (p_1, p_2)$ and $Q: (q_1, q_2)$ is:

$d(P,Q) = \sqrt{(p_1-q_1)^2 + (p_2-q_2)^2}$

a) Create a function that takes two points as input parameters and return the Euclidean between them. (\*)

b) Let the user input two points. Call the function using the users input points. (\*)

c) Use your function to calculate distances between the origin (0, 0) and each of these points: (10, 3), (-1, -9), (10, -10), (4, -2), (9, -10). (\*)

---

## 2. Mathematical functions (\*)

Make the following functions with **def** or **lambda** and plot their graphs in the same figure window, with $x\in [-10,10]$ :

&nbsp; a) &nbsp; $f(x) = x^2 -3$ (\*)

&nbsp; b) &nbsp; $g(x) = 4x-7$ (\*)

What could the relation between $f(x)$ and $g(x)$ be?

---

## 3. Name cleaner (\*)

Create a function that takes a name as an input and:

- removes all leading and trailing blank spaces
- make capitalize the first character of each name, and make the rest lowercase

Use your function on this list of strings:

```
["  MaRcUs ", " iDA aNderSon", "OLOF Olofsson            "  ]
```

---

## 4. Change (\*\*)

Create a function that takes a value as input parameter and print out the banknotes and coins in Swedish currency representing this value. For example 5289 would give the following printout:

- 5st 1000-lapp
- 1st 200-lapp
- 1st 50-lapp
- 1st 20-lapp
- 1st 10-krona
- 1st 5-krona
- 2st 2-krona

Now let the user input a value, and use the function to calculate the change.

## 11. Theory

a) Explain the difference between str.upper(), str.lower(), and str.title().

b) What is the result of "abc"[1:3]? How does slicing work with strings?

c) Why are strings considered sequences in Python?

d) What is the use of escape characters in strings? Give an example.

e) Explain how to reverse a string using slicing.

f) What is the purpose of a try...except block in Python?

g) What is the purpose of raise?

h) What is the difference between runtime errors and logical errors?

i) What does the with open(...) as f: syntax do, and why is it recommended?

j) Explain the difference between read(), readline(), and readlines().

k) Explain the different file modes: 'r', 'w', 'a', 'x', and 'r+'.

## Glossary

Fill in this table either by copying this into your own markdown file or copy it into a spreadsheet if you feel that is easier to work with.

| terminology        | explanation |
| ------------------ | ----------- |
| replace            |             |
| regular expression |             |
| concatenation      |             |
| split              |             |
| indexing           |             |
| escape charactrers |             |
| unicode            |             |
| exception          |             |
| try block          |             |
| except block       |             |
| finally block      |             |
| traceback          |             |
| open()             |             |
| with               |             |
| context manager    |             |
| close()            |             |


<div style="background-color: #FFF; color: #212121; border-radius: 20px; width:25ch; box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px; display: flex; justify-content: center; align-items: center;">
<div style="padding: 1em; width: 60%;">
    <h2 style="font-size: 1.2rem;">Kokchun Giang</h2>
    <a href="https://www.linkedin.com/in/kokchungiang/" target="_blank" style="display: flex; align-items: center; gap: .4em; color:#0A66C2;">
        <img src="https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg" width="20"> 
        LinkedIn profile
    </a>
    <a href="https://github.com/kokchun/Portfolio-Kokchun-Giang" target="_blank" style="display: flex; align-items: center; gap: .4em; margin: 1em 0; color:#0A66C2;">
        <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="20"> 
        Github portfolio
    </a>
    <span>AIgineer AB</span>
    <div>
</div>