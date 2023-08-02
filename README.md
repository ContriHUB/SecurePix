<b>*Terms to Know*</b>:
IPFS:
IPFS stands for InterPlanetary File System. It is a distributed and peer-to-peer protocol designed to create a decentralized and permanent method of storing and sharing files on the internet. IPFS aims to replace the traditional client-server model with a content-addressed system, where files are identified by their content, rather than their location. In IPFS, each piece of data is assigned a unique cryptographic hash, and users can retrieve the content by requesting it using its hash, ensuring data integrity and immutability. IPFS also utilizes a distributed network of nodes, allowing files to be cached and served from multiple locations, increasing data availability and reducing the reliance on centralized servers. This technology has applications in various domains, including blockchain, content distribution, and decentralized applications.
In simpler words: Imagine you have a big toy box at home, and you want to share your toys with your friends who live far away. Instead of sending the toys through the mail, you take pictures of each toy and put those pictures in a magic toy-sharing book. Your friends can look at the book, find the picture of the toy they want, and use the picture to ask someone else to get the real toy from their own toy box. That way, everyone can share toys without having to send them through the mail. IPFS works kind of like that magic toy-sharing book for sharing files and pictures on the internet. It helps people all over the world share and find files easily without relying on just one place to keep everything.

 Pinata:
Pinata is like a magic cloud storage service for files on the internet. It's a special place where you can put your pictures, documents, or any files you want to keep safe and share with others. Just like a real pinata that holds lots of treats, Pinata holds your files in a way that everyone can see and use them. It also makes sure that your files don't get lost or broken, so you can always find them whenever you need them. With Pinata, you can share your files with your friends and let them enjoy the treats inside your digital pinata!
In simpler words: Imagine Pinata is like a special treasure box in the sky where you can put all your favorite pictures and toys. You can keep them safe up there so you don't lose them. And the best part is, you can also show your friends the cool things you put inside the treasure box. So, it's like having a magic cloud that keeps your stuff safe and lets you share it with your friends whenever you want!

The smart contract algorithm that we are going to use can be pictorially represented as:
![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/6ddfd249-233f-46c1-9b6e-c39b81990481)

What is Smart contract?:
Imagine a smart contract as a special kind of agreement that works automatically, like magic! It's a computer program that runs on a blockchain, which is like a big digital ledger that keeps track of everything.In a smart contract, you can set up rules and conditions for something to happen. For example, let's say you and your friend want to bet on the winner of a game. You can create a smart contract that says, "If your favorite team wins, your friend will give you a candy, but if the other team wins, you will give your friend a toy."Once the smart contract is set up, it can't be changed or cheated. When the game ends, the smart contract checks who won, and it automatically gives the candy or toy to the right person, just like magic! Smart contracts are super cool because they make agreements fair and transparent, and you don't need to rely on anyone to make sure everyone follows the rules. Everything happens automatically and securely on the blockchain. That's why people use smart contracts for all sorts of things, like betting, buying and selling, and even voting!

What is Solidity?
Solidity is a programming language used to write smart contracts on blockchain platforms like Ethereum. It allows developers to create secure and decentralized applications with transparent rules and automatic execution.

The data types that we will be using in Solidity which is a backend langugage to write smart contracts are as follows:
![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/40325427-21fc-4e6c-b1d9-6116b054d530)
![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/e99d6d70-f8d1-4066-bc0a-7797b84dc403)
![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/47209ce3-d1bc-4c1c-af53-b7ed256f5bb6)
![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/c1bdec2f-d881-4cd4-bd79-635064c5002f)

The various functions used in backend is as follows:
![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/17321894-a4a0-421e-9b3f-55b0dbc40870)

 We will first write our smart contract in Remix ethereum IDE and test it there (it would be easy to test in such a handy runtime environment of blockchain)
![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/9f7ec00e-e7c0-4c7a-9dce-e5fc70076cdc)

![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/af594415-04d9-4415-b792-bb22f42623fd)

The transactions of storing and sharing the file will be successful according to the code
![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/fc6b780b-f921-4c1b-93d1-af6b546bd005)

Now you can bring this code into your local machine and install hardhat using npm install hardhat
The other packages that need to be installed are given in package.json. You can directly install them using npm install --legacy peer deps

![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/8153f584-084f-4dc9-aacf-1d8535626a98)

We can then use test accounts from hardhat and send transactions through it, we also need to configure our metamask for the Hardhat network. Below are the steps

![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/ce79bb3d-c51b-4a4f-aad6-40eeaf46af3a)

![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/2ad9a939-2086-4c2e-9491-d402be934563)

![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/15087780-bf51-48b7-9e44-bc0532607e55)








