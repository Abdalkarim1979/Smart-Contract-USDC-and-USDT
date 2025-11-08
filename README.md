
# USDC / USDT ERC20 Token Contract  

📖 **Project Description**  
This smart contract is written in **Solidity** and built using [OpenZeppelin](https://openzeppelin.com/contracts/) libraries to create a simplified stablecoin on the **Ethereum blockchain** (or any EVM‑compatible network). It mimics the behavior of popular stablecoins like **USDC** or **USDT**, with core functionalities such as minting and burning tokens.  

---

## ✨ Features
- 🪙 **ERC20 Standard**: Fully compliant with the ERC20 token standard for compatibility with wallets and dApps.  
- 🔑 **Ownable**: Only the contract owner can mint new tokens.  
- 💵 **Decimals = 6**: Matches the decimal precision of real stablecoins (USDC/USDT).  
- ➕ **Mint Function**: Allows the owner to issue new tokens to any address.  
- ➖ **Burn Function**: Enables any user to burn their own tokens, reducing total supply.  
- 🚀 **Initial Supply**: 10,000,000 tokens are minted to the deployer upon contract deployment.  

---

## 🛠️ Technologies Used
- **Solidity ^0.8.0**  
- **OpenZeppelin ERC20 & Ownable**  

---

## 🚀 How to Use
1. Deploy the contract on Ethereum or a test network (e.g., Goerli, Sepolia).  
2. Upon deployment, 10 million tokens are minted to the owner’s address.  
3. Use `mint(address to, uint256 amount)` to issue new tokens (owner only).  
4. Use `burn(uint256 amount)` to destroy tokens from your own balance.  

---

## 🎯 Goals
- Provide a simple ERC20 stablecoin contract for learning and experimentation.  
- Demonstrate minting and burning mechanics in a secure way.  
- Support developers in building dApps or testing with stablecoin‑like tokens.  


## Contact
  avrmicrotech@gmail.com
