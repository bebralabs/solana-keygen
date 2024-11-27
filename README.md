
# Solana Keys Generator

[Solana Keys Generator](https://scripts.bebralabs.com/solana-keygen/) is a script for generating thousands of Solana wallets quickly and efficiently. It outputs public and private keys in a CSV file and creates individual JSON key files for each wallet. Perfect for batch wallet creation!

## How to Use:
1. [Download](https://scripts.bebralabs.com/solana-keygen/) & unzip the script.
2. Install Python & Rust & Solana CLI
3. Install required dependencies:
   ```bash
   pip3 install base58
   ```
4. Run the script in your terminal:
   ```bash
   python3 keygen.py --amount <number_of_wallets> --output <folder_name>
   ```

### Example:
```bash
python3 keygen.py --amount 10 --output my_wallets
```
- This will generate 10 wallets and save their keys in a folder named `my_wallets`.

### Output:
- **CSV File**: A file containing public and private keys in the format:  
  `PublicKey1, PrivateKey1`  
  `PublicKey2, PrivateKey2`  
- **JSON Files**: Each wallet’s keys saved as a `.json` file.

### Additional Resources:
+ [Full documentation & video guide](https://splashy-celery-733.notion.site/Solana-Keys-Generator-Setup-Guide-87c33a2faba24b689c1c5bd54a2589e8)
+ [Buy with crypto](https://app.hel.io/pay/671a8b221646423c879d9c4e)
+ [Buy with card](https://t.me/bebra_scripts/4)

---

**Tips for Use**:
- 💡 Save your `.csv` file in Google Sheets for easy organization and access.
- 🔒 Always store your keys securely and create backups.

---

Thank you for using Bebra Scripts. For support, contact us: [https://t.me/bebralabs_bot](https://t.me/bebralabs_bot)

**Web3 Development Services** – [https://t.me/bebralabs_bot](https://t.me/bebralabs_bot)

Created with ❤️ by **Bebra Labs**  
[https://bebralabs.com](https://bebralabs.com)
