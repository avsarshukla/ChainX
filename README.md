# ChainX
decentralized supply chain management system built on the Ethereum blockchain
 Key Features
Complete Transparency: Every transaction and movement is recorded on an immutable ledger, ensuring traceability from start to finish and building trust among stakeholders
.
Smart Contracts: Self-executing agreements powered by Solidity automate interactions, such as payment releases and product deliveries, eliminating the need for intermediaries
.
Real-time Tracking: Businesses and consumers can track products in real-time, gaining valuable insights into inventory, logistics, and supply chain performance
.
Decentralized Security: User authentication is managed by Ethereum stakeholder addresses, leveraging the inherent security of the blockchain
.
⚙️ How It Works
Stakeholder Registration: The process begins with the registration of supply chain entities (Raw Material Supplier, Manufacturer, Distributor, Retailer, and Customer). Their Ethereum addresses are verified and registered on the blockchain
.
Product Initialization: The manufacturer registers a new product at the root level of the system
.
Supply Chain Flow: The product moves through the traditional supply chain flow (Supplier ➔ Manufacturer ➔ Distributor ➔ Retailer ➔ Customer)
.
Transaction Recording: As the product is handed along and sold to retailers or customers for predefined prices, every transaction is digitally recorded as a block on the shared ledger
.
Verification and Interface: Clients communicate seamlessly with the blockchain using Web3.js
. The entire history of the product is displayed on an intuitive React JS frontend, allowing users to verify authenticity and trace the journey of the product
.
🛠 Technology Stack
Ethereum
Solidity
MetaMask
Instructions to Run
 Use the Truffle environment to compile the Solidity smart contracts and deploy them to your local Ganache network
 Connect MetaMask with Ganache: Integrate your MetaMask wallet and connect it to your local Ganache network. This will allow you to authenticate users and facilitate simulated financial transactions within the Ethereum environment
