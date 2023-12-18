## Topic 1

## *String* :

- String is a collection of alphabets, words or othe characters 

 - “It identify the quotation marks”

1.The given code is a simple Python script that concatenates two strings and then prints the result. Let me break down the code for you:

Program:1
```python 
S = 'Hello,'

S += ' World!'

print(S)
```
Output:
```python 
Hello, World!
```

2.Python script that takes input for a name and then prints the uppercase version of the inputted name

Program:2
```python
a=input("enter your name :") 
print(a.upper())
```
Output:
```python
enter your name :akhi 

AKHI
```
3.print a slice of this string

Program:3
```python
s='python'
print(s[0:5])
```
Output:
```
pytho
```

***

# Topic 2 :

## List:

- lists are defined by having values between `square brackets [ ]` 
- list is`` mutable``
- Use index get the value

1.Which type of this program

Program:
 ```python 
 n=[1,2,3,4,5] 
print(type(n))
 ```
 Output

 ```python
 <class “list”>
 ```

2.Empty list append the string value

Program:

```python 
a=[]
a.append("Akhi")
print(type(a))
```
Output:
 ```python
 ['Akhi']
 ```

3.The uppercase version of the first element in the list using the upper() method

Program:
```python
name=["akhi","lesh","esh"]
print(name[0].upper())
```
Output:
```python
AKHI
```

***

# Topic 3

## Tuple:

- Tuple are `` immutable `` so we cannot changes value 

-  Python tuples data are written in `` round brackets ``

1.Which type of this program.How to type convert the program.how to using index get the value
 
program :

```python
letters=('a','b','c','d','f')
print(type(letters))
lett=list(letters)  ###typecasting
print(type(lett))
print(letters[3])
```
Output
```python
<class 'tuple'>

 <class 'list'>

 d
```

***

# Topic 4

## Dictionary:

- A dictionary is a kind of data structure that stores items in `` key-value  pairs ``
- Python Dictionary are written in ``curly brackets``

1.How to get the value

Program

```python 
d_my = {'name': "akhi", 'age': "34"} 

print(d_my['age'])
```

Output:
```python
34
```

