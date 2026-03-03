# Proposal:  Nostromo Smart Contract Update

## 1. Overview

This update for the Nostromo Smart Contract (SC) is led by @flechar and aims to provide the Smart Contract with a new structure and enhanced functionalities.

The update is built upon 4 key pillars:

- **Project Hub:** A decentralized space where any user can showcase or sell their ideas/intellectual property.
- **Fundraising:** Enabling capital raises through direct sales or auction-based models.
- **Auction House:** A platform where any user or project can auction their digital assets.
- **Governance:** Implementation of a framework for community-led decision-making.


**Total Funding Required:** $23.8K USD


---

## 2. Project Hub
### 2.1 Key Features
This is a structured place where people can present or sell their ideas in an organized way.
Here we Transform project concepts or ideas into tradable assets. 
Anyone can acquire and further develop those projects.

There are two main categories:

**IDEA**

This category is sellable and has three purchase tiers:

- Title
- Short Project Introduction
- Detailed Project Specification

**SUGGESTION**

This category is not sellable. It is simply a project suggestion.

It includes:

- Problem Statement
- Proposed Solution

### 2.2 Benefits

- Increased creativity
- Generate new project ideas
- Generate new funded projects
  
### 2.3 Business Model
**IDEA**

To list a project as sellable, the creator must complete all required fields.
After submission, the creator defines the total price of the project.
Buyers can purchase access depending on the level of detail they are interested in.
The more detailed the content, the higher the cost.

Value Distribution of the Total Price:

- Title – 0%
- Short Project Introduction – 10%
- Detailed Project Specification – 90%

**SUGGESTION**

Free of charge.

---

## 3. Fundraising
### 3.1 Key Features

Three types of fundraising will be implemented.

- Donation Campaigns  
- Traditional IDOs  
- Auction-based IDOs  

**DONATION CAMPAINGS**

After filling out some required fields, such as: 
- who is running the campaign 
- who the campaign is for
- the reason for the campaign

a fundraising will be conducted with reduced fees.

**TRADITIONAL IDOs**

Projects must describe:

- The project  
- The team  
- Tokenomics/ Dividend distribution
- Define parameters  
- Upload optional documents (litepaper/whitepaper)
- The amount allocated to each area of ​​the project (marketing, SC, legal, etc.)
- Milestones for building the SC

After that, fundraising begins, similar to QIP.
The funds will be distributed as milestones are completed.


**AUCTION-BASED IDOs** 

Projects must describe the same points/parameters as the "Traditional IDOs".
Bidding and token acquisition are conducted based on batch auction logic (described further below).
As with traditional IDOs, funds will only be released after each milestone is completed.

### 3.2 Benefits

- Support for solidarity campaigns
- Dynamism
- Versatility
- Greater fundraising (possibility of price discovery)

### 3.3 Business Model

**DONATION CAMPAINGS FEES**

- 3% Shareholders
  
Additional:

+ 0.5% to Management
+ 0.5% to Development

**IDOs FEES**

Shareholders:
- ≤ 5B → 5.0%
- 5B and ≤ 50B → 4.5%
- 50B and ≤ 200B → 4.0%
- 200B → 3.5%
    
Additional:

+ 0.5% to Management
+ 0.5% to Development
---

## 4. Auction House
### 4.1 Key Features

At this stage, there will be 2 types of auctions: 

- Batch auction
- Standard auction

Batch auction is designed for sellers who wish to sell identical assets in quantity, aiming to obtain the best possible price.

The logic of Standard auction is: the highest bid wins.

It is intended for: 
- A single asset
- A bundle of different assets (lot)


**BATCH AUCTION**

The seller must already hold the assets in their wallet before initiating the auction.

**The seller defines:**
- Auction name / description
- The asset and total quantity for sale
- Minimum purchase amount
- Auction duration (in days)
- Public or Private visibility

**Bidding Process**

During the auction, each bidder defines:
    • The quantity of assets they wish to purchase
    • The price they are willing to pay per token

All bids exceeding the available asset quantity are automatically refunded.

**Auction Finalization**

At the end of the auction:
- Bids are ordered from highest to lowest
- Tokens are distributed sequentially until:
  
  ◦ The supply runs out, or
  
  ◦ The minimum selling price is reached
  
Participants whose bids fall within the sold allocation:
- Pay the amount they committed
- Receive the corresponding number of tokens


  <img width="384" height="454.5" alt="batch auction" src="https://github.com/user-attachments/assets/a9e2d664-c3bb-4747-aa5f-e0a0904905ed" />


**STANDARD AUCTION**


Standard auction will have 2 types of configurable parameters.

**Simple Mode**
The seller defines:
- Name / description
- Auction duration
- Sale price
- Minimum bid increment

**Advanced Mode**
The seller defines:
- Name / description
- Auction duration (in days)
- Initial price (starting bid)
- Sale price (price at which the asset may be sold)
- Visibility (public / private)
- Minimum bid increment
- Buy Now option
  
  ◦ If a bid matches the Buy Now value, the auction closes automatically and the asset is sold immediately.

During the Auction
- Each wallet may place bids.
- If a bid is surpassed, the previous bidder is automatically refunded.
- If a bid is placed in the final 5 minutes, the auction is extended by 5 minutes.
- This continues until no bids are placed in the last 5 minutes.

### 4.2 Benefits

The auction house's objective is to provide versatility to IDOs while giving the community a new way to buy and sell assets.

### 4.3 Business Model

**AUCTIONS FEES**

Shareholders:
- ≤ 5B → 5.0%
- 5B and ≤ 50B → 4.5%
- 50B and ≤ 200B → 4.0%
- 200B → 3.5%
    
Additional:

+ 0.5% to Management
+ 0.5% to Development
  

A 50M fee is required for private auctions.

---

## 5. Governance 

### 5.1 Overview

The governance of the Nostromo Smart Contract (SC) is structured around two entities:

- The Manager
- The Shareholders
  
This structure ensures operational coordination while preserving decentralized decision-making power.
Final authority and decision-making power reside with the Shareholders.

### 5.2 Key Features

**MANAGER**

The Manager is responsible for operational coordination, development oversight, and ecosystem communication related to the Nostromo Smart Contract.

**Responsibilities**

- Coordinate Smart Contract updates and improvements
- Submit governance proposals
- Resolve minor conflicts of interest
- Improve and optimize the Smart Contract
- Manage marketing and promotional activities
- Manage the official X (Twitter) account
- Manage the official Discord channel

**Initial Appointment**

For the initial operational phase, the role of Manager is proposed to be assumed by Flechar, ensuring continuity, vision alignment, and structured execution during the early stage of the Smart Contract upgrade.
Future changes to the Manager role may be subject to governance voting.

**SHAREHOLDERS**

The Shareholders are the ultimate decision-making body of the Nostromo Smart Contract.
All major decisions, disputes, and governance changes require shareholder voting.

**Responsibilities**

- Submit governance proposals
- Vote on proposals
- Vote in dispute resolution cases
- Vote when a project is not approved by the network computers
- Vote on proposals submitted by the Manager


### 5.3 Proposal Framework

To ensure clarity and structure, every governance proposal must include:
- Title
- Problem Statement
- Proposed Changes
- Voting Options (maximum of three)

The option receiving the highest number of votes will be considered the final decision.

### 5.4 Governance Objectives

The governance structure is designed to:
- Ensure transparency
- Preserve decentralization
- Protect shareholder interests
- Maintain operational efficiency
- Enable structured growth of the Nostromo ecosystem

---

## 6. Roadmap & Milestones

**SMART CONTRACT**

| Milestone | Description | Timeline |
| :--- | :--- | :--- | 
| **1** | Full SC Update | 3 weeks | 
| **2** | Testing & bug fixing | 1 week |
| **3** | CLI update & testnet testing | 2 weeks|
| **4** | PR & release  | 1 weeks|

**BACKEND/FRONTEND/INTEGRATION**

| Milestone | Description | Timeline |
| :--- | :--- | :--- | 
| **1** | Frontend | 3 weeks | 
| **2** | Backend | 2 week |
| **3** | Integration | 1 weeks|
| **4** | Test   | 1 weeks|

---

## 7. Budget & Commitment
### 7.1 Requested Funding

**SMART CONTRACT:** 14 000 USD (2 000 USD/week)

**BACKEND/FRONTEND/INTEGRATION:** 9 800 USD (1 400 USD/week)


**TOTAL:** 23.8K USD

### 7.2 Payments

The developers will be paid for milestones completed.

**SMART CONTRACT**

|MILESTONE | PAYMENT (USD) |
|:--- |:--- |
| 1 | 6 000  |
| 2 | 2 000  | 
| 3 | 2 000 |
| 4 | 4 000 |

**BACKEND/FRONTEND/INTEGRATION**

|MILESTONE | PAYMENT (USD) |
|:--- |:--- |
| 1 | 4 200  |
| 2 | 2 800  | 
| 3 & 4 | 2 800 |

**Note:** The last two weeks will be paid together at the end to ensure greater security in the completion of the project.

---

### 8. FUTURE UPDATES

• New auction models  
• Evaluation of fees in practice and possible adjustment if necessary. 

---

## 9. Team
- **LEADER:**
  
  Flechar
  
- **DEVELOPERS:**
  
  **Smart Contract** - L_Wen
  
  **Backend/Frontend/Integration** - SerendıpıtчSeeker

---

## 10. Links & Contacts
- **Repository:** https://github.com/flechar/Nostromo_SC.git
- **More Detailed Documentation:** https://github.com/flechar/Nostromo_SC/issues/1
- **Contact:** @flechar
