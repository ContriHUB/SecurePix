
# SecurePix

https://docs.google.com/presentation/d/12xXd34a_39wlrjpMBhulqnkBisfMJV0S/edit?usp=drive_link&ouid=116428939172762510058&rtpof=true&sd=true

SecurePix is a cutting-edge blockchain-powered web application designed to provide users with a secure and private platform for storing and sharing their photos and files. Leveraging the Ethereum blockchain and IPFS (InterPlanetary File System), SecurePix ensures data integrity, permanence, and decentralized storage.

With its intuitive interface, users can easily upload their images and files, confident in the knowledge that their data is safely stored on the blockchain. Access to the files is restricted to authorized users with designated Metamask addresses, adding an extra layer of security and control over shared content.

SecurePix is built using ReactJS for the frontend, offering a seamless and user-friendly experience. On the backend, Hardhat and Pinata APIs are utilized to facilitate smart contract development and efficient interaction with the IPFS network.

By providing a secure and privacy-focused solution, SecurePix empowers users to protect their digital assets while fostering collaboration and sharing within their trusted network. Whether it's cherished memories, sensitive documents, or creative work, SecurePix ensures that users' data is safeguarded and accessible only to those they choose to share with.


## Appendix

A. Smart Contract Architecture:

FileStorage.sol:
This smart contract is responsible for storing the file hashes securely on the Ethereum blockchain using IPFS. It includes functions to upload and retrieve file hashes, ensuring the integrity and permanence of user data.

AccessControl.sol:
The AccessControl contract manages the permissions and access control for shared files. It includes functions for adding and removing authorized Metamask addresses to allow access to specific files.

B. Frontend Technologies:

ReactJS:
SecurePix's frontend is built using ReactJS, a popular JavaScript library for building user interfaces. ReactJS provides a responsive and interactive user experience, enabling seamless interactions with the blockchain and smart contract functionalities.

Web3.js:
Web3.js is utilized to interact with the Ethereum blockchain from the frontend. It enables communication with smart contracts, allowing users to upload and retrieve files securely.

C. Backend Technologies:

Hardhat:
SecurePix's backend is developed using Hardhat, a development environment for Ethereum smart contracts. Hardhat offers testing capabilities and ensures efficient integration with Metamask for transaction signing during file uploads and access management.

Pinata API:
The Pinata API is used in conjunction with IPFS to store and retrieve files on the decentralized IPFS network. Pinata's reliable and scalable infrastructure ensures robust file storage and retrieval capabilities.

D. Security Measures:

Smart Contract Auditing:
Prior to deployment, the smart contracts undergo rigorous auditing and testing to identify and address potential vulnerabilities. Security best practices are followed to ensure the smart contracts are resilient against attacks.

Encryption:
All data transmitted between the frontend and backend is encrypted using industry-standard encryption protocols to protect user data from unauthorized access.

E. Privacy and Data Protection:

Metamask Integration:
SecurePix leverages Metamask for user authentication, allowing users to maintain control over their private keys and ensure secure access to their files.

User Consent:
Prior to sharing files with other addresses, users are prompted to provide explicit consent to grant access to their data.

F. Future Enhancements:

Enhanced Sharing Features:
Future updates may include additional sharing options, such as time-limited access and multi-level access permissions, to offer more flexibility in managing shared files.

Mobile Application:
Expanding SecurePix into a mobile application would enable users to access their files securely on the go, enhancing accessibility and convenience.


## Documentation

SecurePix Documentation

Introduction:
SecurePix is a state-of-the-art blockchain-based web application designed to provide users with a secure and private platform for storing and sharing photos and files. This documentation aims to provide users and developers with a comprehensive understanding of the features, functionalities, and technologies employed in SecurePix.

Table of Contents:

Getting Started

Introduction to SecurePix
System Requirements
Installation Guide
User Registration and Authentication
Uploading and Managing Files

Uploading Photos and Files
File Storage on IPFS
File Retrieval and Download
Managing Uploaded Files
Sharing Files

Granting Access to Metamask Addresses
Revoking Access to Shared Files
Smart Contract Architecture

Overview of Smart Contracts
FileStorage.sol
AccessControl.sol
Frontend Technologies

ReactJS
Web3.js
Backend Technologies

Hardhat
Pinata API
Security Measures

Smart Contract Auditing
Data Encryption
Metamask Integration
Privacy and Data Protection

User Consent for File Sharing
Metamask Authentication
Future Enhancements

Upcoming Features and Improvements
Mobile Application Development
1. Getting Started:
This section provides an overview of SecurePix, outlines the system requirements, guides users through the installation process, and explains user registration and authentication procedures.

2. Uploading and Managing Files:
Learn how to upload photos and files securely on SecurePix, understand how files are stored on IPFS, and manage your uploaded files efficiently.

3. Sharing Files:
Discover how to share your files with other Metamask addresses, grant access to specific files, and revoke shared access when needed.

4. Smart Contract Architecture:
Understand the structure and functionalities of the smart contracts used in SecurePix, including FileStorage.sol for file storage and AccessControl.sol for access management.

5. Frontend Technologies:
Explore the frontend technologies employed in SecurePix, such as ReactJS for building a responsive user interface and Web3.js for interacting with the Ethereum blockchain.

6. Backend Technologies:
Get insights into the backend technologies, including Hardhat, a development environment for Ethereum smart contracts, and the Pinata API for efficient IPFS integration.

7. Security Measures:
Learn about the security measures implemented in SecurePix, including smart contract auditing, data encryption, and secure Metamask integration.

8. Privacy and Data Protection:
Understand how SecurePix ensures user privacy and data protection, including user consent for file sharing and secure Metamask authentication.

9. Future Enhancements:
Get a glimpse of the upcoming features and improvements planned for SecurePix, such as enhanced sharing options and the development of a mobile application.

This documentation is intended to assist users and developers in leveraging the capabilities of SecurePix, ensuring a seamless and secure experience for storing and sharing files on the blockchain. Whether you are a user seeking secure file storage or a developer interested in the underlying technologies, SecurePix strives to provide a cutting-edge solution for your digital asset management needs.


## Video Demo
PFB the link for video demo:
1) https://drive.google.com/file/d/1DmuaFOAtFvHRmc4fu0cC95B86wpx8Amr/view?usp=sharing
2) https://drive.google.com/file/d/16KZpOVfqXGwNUAiwm1-GOIwv1K5cnHbD/view?usp=sharing
## Installation

SecurePix Installation Procedures

Prerequisites:
Before installing SecurePix, ensure that your system meets the following requirements:

Node.js: Install the latest version of Node.js from the official website (https://nodejs.org) to run the application.

Metamask: SecurePix requires the Metamask extension for accessing the Ethereum blockchain and signing transactions. Install Metamask on your web browser (Chrome/Firefox) and set up an Ethereum account.

Step 1: Clone the Repository

Open your terminal or command prompt.
Change the current working directory to the location where you want to install SecurePix.
Clone the SecurePix repository from GitHub using the following command:
bash
Copy code
git clone https://github.com/securepix/securepix.git
Navigate into the project directory:
bash
Copy code
cd securepix
Step 2: Install Dependencies

Install the required Node.js packages by running the following command:
Copy code
npm install
Step 3: Set Up Ethereum Network

Open the hardhat.config.js file located in the project's root directory.
Configure the Ethereum network settings (e.g., Rinkeby, Ropsten) under the networks section.
Step 4: Deploy Smart Contracts

Compile and deploy the smart contracts to the specified Ethereum network using Hardhat:
arduino
Copy code
npx hardhat compile
npx hardhat run scripts/deploy.js --network <network_name>
Replace <network_name> with the network you want to deploy the contracts to (e.g., rinkeby, ropsten).
Step 5: Set Environment Variables

Create a .env file in the root directory of the project.

Define the following environment variables in the .env file:

makefile
Copy code
REACT_APP_API_URL=<api_url>
REACT_APP_CONTRACT_ADDRESS=<contract_address>
<api_url>: The API URL for the Pinata IPFS service.
<contract_address>: The Ethereum address where the smart contracts are deployed.
Step 6: Start the Application

Start the SecurePix application using the following command:
sql
Copy code
npm start
Step 7: Access SecurePix

Open your web browser and visit http://localhost:3000.
Metamask will prompt you to connect your Ethereum account. Allow the connection to access the application.
You are now ready to use SecurePix! You can upload photos and files, manage your content, and securely share files with other Metamask addresses.
Congratulations! You have successfully installed SecurePix on your system and can now securely store and share photos and files using blockchain technology. Remember to keep your Metamask account secure and never share your private keys with anyone to ensure the safety of your assets. Enjoy using SecurePix!
    
## Optimizations

Optimizations in SecurePix aim to enhance performance, user experience, and security. Here are some potential optimizations that could be implemented:

IPFS Caching: Implement caching mechanisms to store frequently accessed files locally, reducing the need for repeated retrieval from IPFS and improving file loading times.

Lazy Loading: Adopt lazy loading techniques for images and files, loading them only when they come into the viewport, reducing initial page load times and conserving bandwidth.

Compression: Compress files before uploading to IPFS to reduce storage costs and improve retrieval speed.

Pagination: Implement pagination for file listings to display files in smaller chunks, reducing the load time for large file collections.

User Access Control Indexing: Optimize the user access control data structure to enable efficient indexing and searching for authorized users.

Server-Side Rendering (SSR): Consider incorporating SSR to improve initial page load times and SEO friendliness.

IPFS Pinning Service: Integrate with an IPFS pinning service to ensure files remain accessible even if the original uploader's node goes offline.

IPFS Cluster: Implement IPFS cluster to increase file availability and redundancy through multiple nodes.

Background Jobs: Use background jobs for heavy computations or tasks that do not require immediate user feedback, allowing a smoother user experience.

Gas Optimization: Optimize smart contract gas costs by employing efficient data storage and minimizing transaction complexity.

Caching Metadata: Cache metadata, such as file descriptions and access permissions, to reduce repetitive queries to the smart contract.

Image and File Processing: Consider integrating image and file processing libraries to handle resizing, thumbnail generation, and format conversions to provide better user experiences.
## Roadmap

SecurePix Roadmap

Welcome to the SecurePix project! This roadmap outlines our vision and planned milestones for the future development of SecurePix. We are committed to providing a secure and user-friendly platform for storing and sharing photos and files using blockchain technology. Below is an overview of our planned features and enhancements:

Phase 1: Minimum Viable Product (MVP)

Smart Contract Deployment: Complete the development and deployment of smart contracts for secure file storage and access control.
File Upload and Retrieval: Allow users to upload and retrieve files securely using IPFS integration.
Access Management: Implement basic access control, enabling users to share files with other Metamask addresses.
Phase 2: User Experience and Performance

IPFS Caching: Optimize file retrieval with caching mechanisms to enhance loading times for frequently accessed files.
Lazy Loading: Implement lazy loading for images and files to improve initial page load times and overall performance.
Pagination: Introduce pagination for file listings to handle large collections efficiently.
Phase 3: Enhanced Sharing and Collaboration

Advanced Access Control: Enhance access management with time-limited sharing and multi-level access permissions.
Collaboration Features: Enable collaborative sharing for multiple users to access and manage files together.
Activity Notifications: Implement real-time notifications for file sharing and updates.
Phase 4: Mobile Application Development

Mobile Application: Develop a mobile application for SecurePix, allowing users to access their files securely on the go.
Phase 5: Security and Privacy

Smart Contract Auditing: Conduct thorough security audits to ensure robustness and resistance against potential attacks.
Data Encryption: Strengthen data protection with advanced encryption measures for user data.
Metamask Authentication: Enhance user authentication using Metamask to secure account access.
Phase 6: Performance Optimization

Server-Side Rendering (SSR): Implement SSR to further improve initial page load times and SEO friendliness.
IPFS Cluster Integration: Integrate with IPFS cluster to increase file availability and redundancy.
Phase 7: Incentive Mechanism

IPFS Pinning Rewards: Introduce a pinning rewards system to incentivize users to pin popular files, enhancing decentralization.
Phase 8: Internationalization (i18n)

Language Support: Implement internationalization to support multiple languages and cater to a global user base.
Phase 9: Further Enhancements

Rate Limiting and Throttling: Implement usage limits to ensure fair usage of resources and prevent abuse.
Image and File Processing: Integrate processing libraries for image resizing, thumbnail generation, and format conversions.
Please note that this roadmap is subject to change based on user feedback, community suggestions, and emerging technologies. We are committed to continuous improvement and will actively engage with the community to prioritize and implement new features.

We appreciate your interest in SecurePix and look forward to delivering a secure and user-centric platform for your photo and file storage needs. Join us on this exciting journey as we revolutionize decentralized file sharing and collaboration!


## Screenshots and videos

![image](https://github.com/TechTonicShift/SecurePix/assets/95674894/5118cf73-e0a6-45b6-8554-62a684237f4a)


