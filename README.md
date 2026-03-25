# Author Guardian

A mobile-first web app designed to help board game designers protect their rulebooks by combining authorship validation, digital signature guidance, and OpenTimestamps proofs.

## 🚀 What this tool does

* Validates that your rulebook includes author information
* Detects whether a digital signature is present
* Guides you to sign your document (e.g. with CIE) if needed
* Generates a cryptographic timestamp using OpenTimestamps
* Builds a complete proof package (file + timestamp + metadata)

## 🧠 Why this exists

OpenTimestamps proves that a file existed at a certain point in time.

However, it does **not** prove who created it.

This tool helps bridge that gap by:

* encouraging proper author metadata
* suggesting digital signature when appropriate
* packaging all evidence coherently

## 🔐 How it works (simple flow)

1. Enter your author details
2. Upload your rulebook
3. Validate document content
4. Check for digital signature
5. (Optional) Sign the document
6. Generate OpenTimestamps proof
7. Download your proof package

## 📱 Key features

* Mobile-first PWA (works on phone)
* Fully client-side (privacy-friendly)
* No account required
* No file upload to external servers
* Simple guided workflow

## ⚠️ Important notes

* OpenTimestamps proves **when a file existed**, not who created it
* Digital signature helps link the file to your identity
* This tool does **not replace legal copyright registration**

## 🧪 Status

🚧 Work in progress — early development stage

## 🛠️ Planned features

* PDF and DOCX parsing
* Digital signature detection
* OpenTimestamps integration in-browser
* Proof package export (ZIP)
* GitHub Pages deployment

## 📄 License

MIT
