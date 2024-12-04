# Medrec

AFYAREC is a Decentralized Medical Record Management App



## Motivation

AFYAREC on Arbitrum: Revolutionizing Medical Records with Blockchain

The management of medical records is in urgent need of innovation. Patients often leave behind fragmented data as they transition between healthcare providers, spanning various jurisdictions. This creates a scenario where past medical information becomes inaccessible, as healthcare providers traditionally hold primary control over patient records. As a result, patients are left interacting with their own data in a fragmented and inefficient manner, with no unified system to address the growing complexity of managing extensive medical histories.

Patients and providers face additional challenges due to "health information blocking," driven by economic incentives that hinder seamless data retrieval and sharing. In an era where online banking and social media thrive on accessibility and user-centric design, patients increasingly desire greater control and portability of their medical records. However, any system addressing this issue must remain flexible to accommodate exceptions, such as psychotherapy notes or physician intellectual property, which may not be appropriate for patient access.

AFYAREC leverages the Arbitrum blockchain to create a decentralized and secure infrastructure for medical record management. By employing a peer-to-peer network with Ethereum for data storage and smart contracts for data logic, the system ensures the following key features:

Zero Downtime: Patient data is always available for retrieval and updates.
Privacy: Sensitive information is secured and accessible only to authorized individuals.
Complete Data Integrity: Records remain unalterable by unauthorized entities.
AFYAREC seeks to eliminate the fragmentation of patient data by organizing it into a blockchain-based ledger. This approach creates a unified, accessible breadcrumb trail of medical history, ensuring that patients maintain control over their information while enjoying the benefits of decentralization, security, and transparency provided by blockchain technology.

With AFYAREC, the future of medical records is one of empowerment, accessibility, and trust.

## Features
-   Open Access: Anyone can register as a patient or doctor on the platform.
- Controlled Prescription Access: Only authorized doctors can issue prescriptions to patients.
- Patient Authorization: Patients can grant access to a doctor, but only after paying the doctor's fee through the DApp.
- Automated Fee Management: Once a doctor prescribes to a patient, the fee is automatically credited to the doctor's account.
- Dynamic Pricing: Doctors can update their fees at any time, ensuring flexibility.
- Smart Contract Reliability: All operations are governed by smart contracts, ensuring trust, transparency, and automation.
- Comprehensive History: Patients can view their prescription history presented in an organized, card-based format.

## How to Run Locally

### Software Requirements

- Node
- Ganache
- Truffle  
- Metamask Extension

### Start Local Blockchain

```
ganache
```

### Compile Contracts

```
truffle migrate 
cd utils 
node helper.js 
```

- Please verify each of deployed contract's address in Config/config.js is similar to that in build folder.

### Start Frontend

```
npm i
npm run start
```

## Tech Used

- React.js
- Web3.js
- Solidity
- Truffle
- Ganache
