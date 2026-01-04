The Alexandria Node 🏛️

History Written in Permanent Ink.

"Civilization is the progress toward a society of privacy. The savage's whole existence is public, ruled by the laws of his tribe. Civilization is the process of setting man free from men." — Ayn Rand

The Alexandria Node is a sovereign, client-side interface for the Permaweb. It allows anyone to upload files to the Arweave blockchain, creating an immutable, censorship-resistant library that cannot be burned, deleted, or altered by any government or corporation.

🌟 Features

🛡️ Sovereign Architecture: A single HTML file (index.html) containing the entire application. No servers, no backend, no master switch.

📜 Immutable Ledger: Files are stored on Arweave. Once uploaded, they exist forever.

🕵️ Anonymous Drop (Pilgrim Mode): Users can connect their own wallets (ArConnect/Wander) to fund their own uploads.

🤝 Archivist Mode (Kiosk): Operators can load a keyfile to subsidize uploads for others (useful for field ops, protests, or whistleblowers).

🔒 Seal of Confession: Client-side AES/RSA encryption. Only the holder of the private key can decrypt the file.

⚖️ The High Council (DAO): A built-in governance layer. Holders of the $ALEX Signet gain access to private channels and voting rights.

🚀 Quick Start (For Visitors)

Visit a Node: Go to https://alexandrianode.ar.io (or any active mirror).

Connect Wallet: Click "Connect" in the top right.

Inscribe: Drag and drop a file.

Optional: Toggle "Encryption" for private data.

Optional: Toggle "Sensitive" for graphic content.

Confirm: Sign the transaction.

Verify: Receive your permanent Permaweb link.

⚔️ How to Deploy Your Own Node

To ensure the library remains unburnable, we encourage you to fork this project and host your own node.

Method 1: The Web2 Bridge (GitHub Pages) - Easiest

Fork this repository (Click the "Fork" button in the top right).

Go to your forked repo's Settings.

Click Pages on the left sidebar.

Set Source to Deploy from a branch and select main (or master).

Click Save. Your node is now live at https://[your-username].github.io/alexandria-node.

Method 2: The Sovereign Drop (Arweave) - Best

Download index.html from this repository.

Go to ArDrive or Akord.

Upload the index.html file to a Public Drive.

Copy the Transaction ID (TXID).

Share your immutable link: https://arweave.net/[YOUR_TXID].

Method 3: The Decentralized Domain (ArNS) - Advanced

Purchase an ArNS name (e.g., mynode.ar) at ar.io.

In the ArNS Dashboard, set the Target ID to the Transaction ID of your uploaded index.html.

Your node is now accessible at https://mynode.ar.io.

⚙️ Configuration (For Operators)

If you are hosting a node, you can configure the revenue stream. Open index.html in a text editor and find the APP_CONFIG section at the bottom:

const APP_CONFIG = {
    // WALLET ADDRESS to receive Membership Fees & Tips
    FEE_DESTINATION: "YOUR_WALLET_ADDRESS_HERE", 
    
    // Cost (in AR) to mint a Membership Signet
    MEMBERSHIP_PRICE: "5.00", 
    
    // Cost (in AR) to unlock the Kiosk for a session
    KIOSK_PRICE: "0.5",
    
    // Default Royalty Fee for Universal Data License (UDL)
    UDL_FEE: "0.1" 
};


Replace YOUR_WALLET_ADDRESS_HERE with your own Arweave address to receive funds when users buy memberships or donate to your node.

🤝 Contributing

The library belongs to everyone.

Fork the Project.

Create your Feature Branch (git checkout -b feature/NewFeature).

Commit your Changes (git commit -m 'Add some NewFeature').

Push to the Branch (git push origin feature/NewFeature).e

Open a Pull Request.

📜 License

This project is released
