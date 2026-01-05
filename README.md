The Sovereign Bureau 🕵️‍♂️

Just the Facts. On the Immutable Record.

"All we want are the facts, ma'am." — Sgt. Joe Friday

The Sovereign Bureau is a decentralized evidence locker for the Permaweb. It functions as a client-side interface for filing immutable reports to the Arweave blockchain. Once filed, these records cannot be redacted, shredded, or tampered with by any agency, government, or corporation.

🗄️ Case File Features

🛡️ Tamper-Proof Custody: A single HTML file (index.html) containing the entire Bureau. No central HQ, no servers to raid.

📂 Permanent Record: Evidence is stored on Arweave. The chain of custody is absolute and eternal.

🕵️ Civilian Informant (Visitor Mode): Users can connect their own credentials (ArConnect/Wander) to fund their own case files.

💼 Field Office (Kiosk Mode): Officers can load a budget keyfile to subsidize reports for informants in the field.

🔒 Classified Status: Client-side AES/RSA encryption. Only the holder of the private key can decrypt the evidence.

🚨 Internal Affairs (DAO): A restricted governance layer. Holders of the $BADGE Credential gain access to secure channels and oversight committees.

🚀 Induction Procedure (Quick Start)

Enter the Bureau: Go to https://alexandrianode.ar.io (or any active field office).

Show Badge: Click "Show Badge" (Connect Wallet) in the top right.

File Report: Drag and drop physical evidence or type a statement.

Optional: Toggle "Classified" for encrypted data.

Optional: Toggle "Graphic Material" for sensitive content.

Stamp & Pay: Authorize the transfer to file the report.

Verify: Receive your permanent Case ID and Permaweb link.

⚔️ How to Establish a Field Office

To ensure the record remains unstoppable, we encourage you to fork this project and run your own independent Bureau.

Method 1: The Web2 Wire (GitHub Pages) - Easiest

Fork this repository (Click the "Fork" button in the top right).

Go to your forked repo's Settings.

Click Pages on the left sidebar.

Set Source to Deploy from a branch and select main (or master).

Click Save. Your office is live at https://[your-username].github.io/unstoppable-archive.

Method 2: The Sovereign Drop (Arweave) - Best

Download index.html from this repository.

Go to ArDrive or Akord.

Upload the index.html file to a Public Drive.

Copy the Transaction ID (TXID).

Share your immutable link: https://arweave.net/[YOUR_TXID].

Method 3: The Frequency (ArNS) - Advanced

Purchase an ArNS name (e.g., thebureau.ar) at ar.io.

In the ArNS Dashboard, set the Target ID to the Transaction ID of your uploaded index.html.

Your node is now accessible at https://thebureau.ar.io.

⚙️ Bureau Configuration

If you are running a node, you can configure the revenue stream. Open index.html in a text editor and find the APP_CONFIG section at the bottom:

const APP_CONFIG = {
    // WALLET ADDRESS to receive Badge Fees & Bureau Donations
    FEE_DESTINATION: "YOUR_WALLET_ADDRESS_HERE", 
    
    // Cost (in AR) to issue a $BADGE Credential
    MEMBERSHIP_PRICE: "5.00", 
    
    // Cost (in AR) to unlock the Field Office (Kiosk) for a session
    KIOSK_PRICE: "0.5",
    
    // Default Royalty Fee for Universal Data License (UDL)
    UDL_FEE: "0.1" 
};


Replace YOUR_WALLET_ADDRESS_HERE with your own Arweave address to receive funds when users buy Badges or donate to your office.

🤝 Contributing

The record belongs to the public.

Fork the Project.

Create your Feature Branch (git checkout -b feature/NewProtocol).

Commit your Changes (git commit -m 'Add new protocol').

Push to the Branch (git push origin feature/NewProtocol).

Open a Pull Request.

📜 License

This project is released under the Unlicense. The code is public domain.
It belongs to the chain now.

Official Repository: https://github.com/servicecoinrwb/unstoppable-archive
