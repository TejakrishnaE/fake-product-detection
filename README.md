# Fake Product Detection using Blockchain

This project provides a simple implementation of a blockchain-based system for detecting fake product identification. The project is written in Python and uses the hashlib and json libraries for hashing and serialization.

# Prerequisites
. Python 3.x

# Usage
1.Clone the repository:

git clone https://github.com/<your_username>/fake-product-detection-blockchain.git

2.Install the required libraries:

pip install -r requirements.txt

3.Run the program:

main.py

# Code Structure
The code is structured into the following files:

block.py: Defines the Block class representing a block in the blockchain.

blockchain.py: Defines the Blockchain class representing the blockchain and its associated functions.

product.py: Defines the Product class representing a single product with a name, manufacturer, and serial number.

main.py: Implements the main function to test the blockchain.

# Sample Output


Adding products to the blockchain...

Product added: Apple iPhone 12, Apple Inc., 123456

Product added: Samsung Galaxy S21, Samsung Electronics, 789012

Product added: Microsoft Surface Laptop 3, Microsoft Corporation, 345678

Product added: Sony PlayStation 5, Sony Corporation, 901234

Verifying products on the blockchain...

Product verified: Apple iPhone 12, Apple Inc., 123456

Product verified: Samsung Galaxy S21, Samsung Electronics, 789012

Product verified: Microsoft Surface Laptop 3, Microsoft Corporation, 345678

Product verified: Sony PlayStation 5, Sony Corporation, 901234

Checking for fake products...

No fake products found.

Adding a fake product to the blockchain...

Fake product added: Apple iPhone 13, Apple Inc., 555555

Verifying products on the blockchain...

Product verified: Apple iPhone 12, Apple Inc., 123456

Product verified: Samsung Galaxy S21, Samsung Electronics, 789012

Product verified: Microsoft Surface Laptop 3, Microsoft Corporation, 345678

Product verified: Sony PlayStation 5, Sony Corporation, 901234

Product NOT verified: Apple iPhone 13, Apple Inc., 555555

#Checking for fake products...

Fake product found: Apple iPhone 13, Apple Inc., 555555

# License
This project is licensed under the MIT License. See the LICENSE file for details.

# Acknowledgments
This project was inspired by this article on how blockchain can end the counterfeit drug trade.




