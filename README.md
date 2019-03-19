•	To start with Ethereum these installation steps must be followed: 

1.	Install Node version 8 - https://nodejs.org/en/download/.
2.	Install metamask extension in the chrome browser. 
3.	Install Visual Studio Code - https://code.visualstudio.com/download
4.	Install Ganache- https://truffleframework.com/ganache 
5.	To write solidity contract - http://remix.ethereum.org

Details about pet-shop use-case:

•	This use case is for adopting the pet from pet-shop.
•	The adoption amount will be transferred to the pet-shop owner account directly.
•	The adoption contract will be created for adopting the pet from shop.

Execution of contract:
a.	Create a folder named pet-shop-master
b.	Open the PowerShell terminal, go to the pet-shop folder.
c.	Install the truffle using command- npm install -g truffle –save.
d.	Clone the repository, use the command- git clone https://github.com/mirzafurqaan/pet-shop.git. 
e.	Start the ganache.
f.	In PowerShell, enter command- truffle compile
g.	In PowerShell, enter command- truffle deploy. Note: make sure the ganache is running else error will occur.
h.	Install light-server – npm install lite-server -g
i.	Now execute the command- npm run dev 
