# Activity 4 — DIDLab ERC-20 DApp UI

This repository contains the tiny DApp UI built for the **CampusCredit (CAMP)** ERC-20 token on the DIDLab network.

---

## 📌 Project Overview
The goal of this activity is to build a single-file web application that:
- Connects to **MetaMask** and switches to the DIDLab network
- Loads the ERC-20 token metadata (name, symbol, decimals)
- Displays the connected account’s balance
- Allows sending token transfers
- Updates the balance automatically on transfers

---

## ⚙️ Configuration
- **Team:** 01  
- **RPC URL:** `https://hh-01.didlab.org`  
- **Chain ID:** `31337`  
- **Token Address:**  
  ```
  0x5fbdb2315678afecb367f032d93f642f64180aa3
  ```

---

## ▶️ Running the DApp
1. Clone this repo:
   ```bash
   git clone <your-repo-url>
   cd didlab-dapp
   ```
2. Start a local web server:
   ```bash
   python3 -m http.server 8000
   ```
   or
   ```bash
   npx http-server -p 8000
   ```
3. Open the DApp in your browser:
   ```
   http://localhost:8000
   ```

---

## 🖥 Usage
1. **Connect & Switch Network** → Approve MetaMask prompt.  
2. **Load Token** → Displays name, symbol, decimals, and balance.  
3. **Refresh Balance** → Manually update balance.  
4. **Send** → Enter recipient `0x...` and amount, then approve in MetaMask.  
5. **Add Token to MetaMask** → Shows CAMP balance directly inside MetaMask.

---

## 📸 Screenshots
Here are screenshots showing the working DApp:

## 📸 Screenshots

### 1. Smart Contract Deployment
![Deploy App](screenshots/deploy_app.png)

### 2. DApp Loaded Successfully
![DApp Loaded](screenshots/dapp_loaded.png)

### 3. Token Added to MetaMask
![ERC Token Added](screenshots/ERCtoken_added.png)

### 4. Transfer in MetaMask Popup
![Transfer MetaMask](screenshots/Transfer_meta.png)

### 5. Transfer Submitted (Success 1)
![Transfer Successful 1](screenshots/transfer_successful1.png)

### 6. Transfer Submitted (Success 2)
![Transfer Successful 2](screenshots/transfer_successful2.png)

### 7. Transfer Confirmed in MetaMask
![Transfer MetaMask](screenshots/transfer_metamask.png)

### 8. Updated Balances After Transfer
![Updated Balances](screenshots/updated_balances.png)


---

## ✅ Submission
- Token Address: `0x5fbdb2315678afecb367f032d93f642f64180aa3`  
- DApp UI: `index.html`  
- Evidence: Screenshots in repo  

---
