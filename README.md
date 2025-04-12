# SecureVault

SecureVault ek simple aur secure data storage aur retrieval system hai jo users ko unke data ko passkey ke saath encrypt aur store karne ka moka deta hai. Users apni encrypted data ko retrieve karne ke liye passkey provide karte hain.

## Features

- **Data Encryption & Decryption**: Users apne text ko secure encryption ke saath store kar sakte hain aur sahi passkey ke saath data retrieve kar sakte hain.
- **Security**: Galat passkey ke 3 attempts ke baad user ko re-login karna padta hai.
- **In-Memory Storage**: Data ek memory-based dictionary mein store hota hai, koi external database nahi use hota.
- **User Authentication**: Admin password ke through app ko access kiya jaa sakta hai.

## Installation

### Requirements
- Python 3.x
- Streamlit
- Cryptography

### Install Dependencies

```bash
pip install streamlit cryptography
