### Key terms
**Class** - template for objects
**Object** - instance of a class 
**Method** - 
**Constructor method:** "_ _ init _ _ " is to used for object initialiation
**Self** refrence to the current object
**Instance variables**


### Examples
```
"A Large Taro bubble tea with sweetness level Medium"
"A Medium Matcha bubble tea with sweetness level Low"
"A Small Mango bubble tea with sweetness level High"
"Sweetness level adjuste to Low"
"Sweetness level adjusted to High"
"A Large Taro bubble tea with sweetness level Low"
"A Medium Matcha bubble tea with sweetness level High"
```

### OOP
- Organized modular code
- code resulability 
- easier to scale

# Encapsulation
### What is it
- bundle methods/data into class
- interacts through methods rather than attributes
- restricts access to protect data/proper usage
### Anology
>Encapsulation is like a vending machine:
>- You can’t open the machine and take out a snack (direct access to  
    data).
>- Instead, you press a button (use a method), and the machine safely  
    gives you the snack (controlled access).
>- This protects the machine’s inner workings and ensures it functions  
    correctly

### How it works
- Use methods to controll access
- restricting direct modification
#### ccess mod in python
- Python does not contain strict access control like (jave,)
![[Pasted image 20250320093600.png]]````


```
class Bank Account:
	def init (self, account_holder, balance):
		= account holder # Public attribute
		self.account holder
		self._balance = balance # Protected attribute
		self.__Pin = "1234" # Private attribute
	
#object initialisation
account01 = BankAccount("Labubu",
leee)
print(f"We1come to your account, {accountel.account_holder}")
print(f"Your current balance is
print (accountel._pin)
```

# Abstraction
### What is it
- hides complexity to show basic only

### How it work
- Provides template
- subclasses implement specific methods
- hides unnecessary details


