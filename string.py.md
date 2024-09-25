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
# 12 Replace string in python
```jsx
challenge="thirty days of python"
print(challenge.replace('python','coding'))
output: thirty days of coding
```
# 13 Spliting the string or split string into list 
```jsx
challenge="thirty days of python"
print(challenge.split())
```
# 14 swapcase() is the methord is striing convert upper to lower or lower to upper case
```jsx
challenge='kaif kaif'
print(challenge.swapcase())
output:KAIF KAIF
``
# Questions
```jsx
concatenate=['thirty','days','of','python']
print(" ".join(concatenate)) # joining string concatenate
company="Airtel"
name="kaif"
print(len(company)) # length of string
print(company.upper()) # convert whole string to upper
print(company.lower()) # convert whole strinfg to lower
print(company.capitalize()) # convert firsy world capitalize
print(company.title())
print(company.swapcase()) # convert whole string to upper or upper to lower case
print(company[0:3]) # spliting string 
print(name.replace('kaif','shaikh')) # replace in string 
firstletter=company[0] # accssesing word in string
print(firstletter)
last=len(company)-1
lastletter=company[last]
print(last)
kaifstring="hello my name is kaif"
print(kaifstring.split())
# Original sentence
sentence = "You cannot end a sentence with because because because is a conjunction"

# Remove the phrase
modified_sentence = sentence.replace("because because because", "")

# Print the result
print(modified_sentence.strip()) 
print(company.find('A')) # give the first accurence of string 
substring="hello my name is kaif"
print(substring.startswith("hello")) # check weather the string is start with or not 
print(substring.endswith("kaif"))

```
