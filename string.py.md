# 1 String in Python 
```jsx
nname="kaif"
print(name)
```
# 2 Length of string in python 
```jsx
name="kaif"
print(name)
print(len(name)) #4
first="kaif"
last="shaikh"
print(len(last)>len(first)) # true
```
# 3 String formating in python
```jsx
%s string
%d integers
%f float
'%.2f'

```
# 4 Accesing Character in a string
```jsx
language='python'
firstletter=language[0]
print(firstletter)

last=len(language)-1
lastletter=language[last]
print(last)
```
# 5 Slicing in a python
```jsx
language='python'
first=language[0:3]
print(first)
lastthree=language[3:6]
print(lastthree)
output:
pyt
hon
```
# 6 Reverse a String in python
```jsx
greeting='hello kaif'
print(greeting[::-1])
```
# 7 Skiping of character
```jsx
language='python'
print(language[0:6:2])
pto
```
# 8 Capitalize letter in python
```jsx
challenge="kaif"
print(challenge.capitalize())
output: Kaif
```
# 9 counter in python string
```jsx
challenges="kaif kaif kaif"
print(challenges.count('k'))
output:3
```
# 10 string endwith()
```jsx
print(hello.endswith('o'))
hellos="hello kaif hello"
```
# 10 some more methords
```jsx
challenges='kaifshaikh'
challengez='1234'
chall="KAIF"
print(challenges.isalpha()) # check whole string is containe the character or not
print(challengez.isdigit()) # check whole string contains only number on not
print(challenges.islower()) # check string is lowercase
print(chall.isupper()) # check string is in uppercase
output
True
True
True
True
```
# 11 join() in python
```jsx
webtech=['html','css','js','node']
print(" ".join(webtech))
html css js node
```
# Replace string in python
```jsx
challenge="thirty days of python"
print(challenge.replace('python','coding'))
output: thirty days of coding
```
