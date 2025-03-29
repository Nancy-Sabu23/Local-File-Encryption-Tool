# Local-File-Encryption-Tool

We'll build a Local File Encryption Tool using JavaScript and AES encryption. Since I'm using a Chromebook, we'll ensure that the project is web-based and runs in the browser.


---

Step-by-Step Plan

Step 1: Define Project Requirements

A web-based tool that allows users to:

Select a file from their device.

Encrypt the file using AES encryption (CryptoJS).

Decrypt the file back to its original form.

Download the encrypted/decrypted file.




---

Step 2: Set Up the Project

Since I'm using a Chromebook, i done my coding on an online platform:

CodePen (Online development)


Use CodePen for simplicity.

1. Go to CodePen: https://codepen.io


2. Create a New Pen:

Title: "Local File Encryption Tool"

Add HTML, CSS, and JavaScript sections.





---

Step 3: Install Dependencies

We'll use CryptoJS for AES encryption.

In CodePen:

Add this script in the JavaScript section (or in <head> of HTML if using a file-based setup):

<script src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.1.1/crypto-js.min.js"></script>



---

Step 4: Create the UI (HTML + CSS)

We'll create a simple UI with:

File input

Password input (for AES encryption)

Encrypt & Decrypt buttons

Download link for encrypted/decrypted files


HTML:

enter the html code.

CSS (optional for styling):

enter the css code.

---

Step 5: Implement File Encryption Logic (JavaScript)

We'll:

1. Read the file as a binary string.


2. Encrypt using AES with the user-provided password.


3. Convert to Base64 and allow downloading.




---

Step 6: Implement Decryption Logic

We'll:

1. Read the encrypted file as a string.


2. Decrypt using the password.


3. Convert back to a downloadable format.


---

Step 7: Test the Tool

1. Run the tool in CodePen.


2. Select a file, enter a password, and encrypt it.


3. Download the encrypted file.


4. Try decrypting it back and check if it matches the original.




---

Next Steps

✅ Basic encryption & decryption complete!
Possible improvements:

Show a success message after encryption/decryption.

Support for different file formats.

UI enhancements.

---
