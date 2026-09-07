# Vegan-products-software
Data Science Master's: Python programming module project – Vegan product store software.

This project consists in developing a software to manage a vegan product store. The software must include the following features:

 - Register new products, including name, quantity, selling price, and purchase price.
 - List all current products.
 - Record sales transactions.
 - Display gross and net profits.
 - Display a help menu listing all available commands.  

The software is text-based and designed for use via the command line.

## Example of program interaction (user input in bold)   

Insert a command: **help**  
The available commands are as follows:

- add: add a product to the inventory
- list: list the products in the inventory
- sale: record a sale
- profits: show total profits
- help: show available commands
- close: exit the program

Insert a command: **add**  
Name of the product: **soy milk**  
Quantity: **20**  
Price of purchase: **0.80**  
Price of sale: **1.40**  
ADDED: **20 X soy milk**

Insert a command: **add**  
Name of the product: **tofu**  
Quantity: **10**  
Price of purchase: **2.20**  
Price of sale: **4.19**  
ADDED: **10 X tofu**

Insert a command: **add**  
Name of the product: **seitan**  
Quantity: **5**  
Price of purchase: **3**  
Price of sale: **5.49**  
ADDED: **5 X seitan**

Insert a command: **list**  
PRODUCT QUANTITY PRICE  
soy milk 20 €1.4  
tofu 10 €4.19  
seitan 5 €5.49

Insert a command: **sale**  
Name of the product: **soy milk**  
Quantity: **5**  
Add another product? (yes/no): **yes**  
Name of the product: **tofu**  
Quantity: **2**  
Add another product? (yes/no): **no**  
SALE RECORDED

- 5 X soy milk: €1.40
- 2 X tofu: €4.19

Total: €15.38

Insert a command: **list**  
PRODUCT QUANTITY PRICE  
soy milk 15 €1.4  
tofu 8 €4.19  
seitan 5 €5.49

Insert a command: **sale**  
Name of the product: **seitan**  
Quantity: **5**  
Add another product? (yes/no): **no**  
SALE RECORDED  

- 5 X seitan: €5.49

Total: €27.45

Insert a command: **list**  
PRODUCT QUANTITY PRICE    
soy milk 15 €1.4  
tofu 8 €4.19

Insert a command: **profits**  
Profit: gross=€42.83 net=€19.43

Insert a command: **storna**  
invalid command  
The available commands are as follows:

- add: add a product to the inventory
- list: list the products in the inventory
- sale: record a sale
- profits: show total profits
- help: show available commands
- close: exit the program

Insert a command: **close**  
Bye bye
