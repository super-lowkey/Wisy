# Encrypted download

1. Download this branch as a ZIP and extract it completely.
2. Open `download.html` in current Chrome or Edge.
3. Select all four `part-*.bin` files, paste the decryption key from your chat, and click **Unlock and download ZIP**.
4. Choose Downloads if prompted. The page verifies the exact original ZIP before downloading it.

The original ZIP is protected using AES-256-GCM with an independent nonce for each part. The decryption key is not stored in this repository. The HTML uses only built-in browser features and makes no network requests. Keep the key private; anyone holding both the package and the key can decrypt it.
