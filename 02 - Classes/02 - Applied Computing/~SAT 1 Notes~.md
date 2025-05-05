#### Syntax
Example of a function:
````
def greet()
	print('Hello World!')
````
#### For loops
```
for i in range(10):
	print(i)

//Output//
1
2
3
4
5
6
7
8
9
```
- note for loops using range doesn't use final value
#### Accessing a slice
![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe8uKulimW8raUGrCqcDz_kNewv3f3gEV10oyPUdVUeki5R8nC6WywjIhkSGS2sk6odHeEdI9o3fjc6Mpc8_YSzbbuUWKw3Nd1Pw8_z7FWEnomkBaWlWlDl8GJeFoBoySAFwf5pZw?key=Ytt7FcPV5_DDDP594fKahHeT)
Output:<br>![[{CBF6E0D1-3482-4351-8918-0B8F320CCDB9}.png]]
to access slice it is same as accessing it from a string
#### Is element present
![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeYf4fWcYUORtFW7QLXAXSwvowurSIDkx6ybUbWnR6Ld2KQcEFORFS0ww18AvTGRa2JMUSZUGumOsx8ilCZUg3wDFSV01hWVmn_lwbP8GZlT3Q_fEiwri3ok3Ouhh4vRHViCmRjVA?key=Ytt7FcPV5_DDDP594fKahHeT)
Output:
![[{BBD53ED2-66FC-4084-A7EF-B055F22CEBF1}.png]]
#### Insert element to specific spot
![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdM57N_jTpD5tPJ4IkcebFTOJEc3EalvMgFIu6YiV7qU5F5al3qJFsZ5RDTRtScMcHMKDxj04YbYQyX1H4B8P4MH8BXT3129D07xDwySSWPaYNvHJjF0FmG8_zLdL-GFgMS5JZ3?key=Ytt7FcPV5_DDDP594fKahHeT)
Output:
![[{A9FB6C9C-12F9-4423-9777-682001C3B709}.png]]
insert is same as appended but you can pick where to place the element in the table
#### Header doc
Should contain:
- Name of file
- Brief description
- Author (full) name
- Date of creation
- Date last modified
- Version No.
#### Naming conventions
- **Variables** use **snake_case**
- **Class** names should use **UpperCammelCase**
- **Constant** name should use **ALL_UPPERCASE**

#### OOP example
```
class Bank Account:
	def init (self, account_holder, balance):
		self.account_holder = account_holder #public attribute
		self._balance = balance # Protected attribute
		self.__Pin = "1234" # Private attribute
	
#object initialisation
account01 = BankAccount("Labubu",
leee)
print(f"We1come to your account, {accountel.account_holder}")
print(f"Your current balance is
print (accountel._pin)

```
#### Subclasses
```
class Animal:
    def __init__(self, name):
      
      	# Storing the name of the animal
        self.name = name  

    def sound(self):
      
        # This method should be implemented by subclasses
        raise NotImplementedError("Subclasses must implement this method")

class Dog(Animal):
    def sound(self):
      
        # Dog-specific sound
        return "Woof!"

```
#### Reverse String index
```
greet = 'hello'

# access 4th last element
print(greet[-4]) # "e"
```
#### String Slicing
```
greet = 'Hello'

# access character from 1st index to 3rd index
print(greet[1:4])  # "ell" (final is not inclusive)
```
#### Join strings
```
greet = "Hello, "
name = "Jack"

# using + operator
result = greet + name
print(result)

# Output: Hello, Jack
```
#### Tuples:
```
thistuple = ("apple", "banana", "cherry")  
print(thistuple) #('apple', 'banana', 'cherry')
```
#### Del items from dictionaries
```
thisdict = {  
  "brand": "Ford",  
  "model": "Mustang",  
  "year": 1964  
}  

del thisdict["model"]  
print(thisdict)
```