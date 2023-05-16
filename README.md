# CryptSend

As the world progresses, people are more likely to access and share files any place and time. But such applications have problems such as low data integrity and low security.

CryptSend is a service that allows users to send and receive sensitive messages with end-to-end encryption, using just their web browsers. Encryption takes place in the sender's web browser, and decryption takes place in the recipient's web browser, via client-side JavaScript running in both users' web browsers. Only encrypted information is sent to CryptSend's servers. Unencrypted information and the keys used to encrypt/decrypt this information never leave the sender's web browser or the recipient's web browser.

## Features

- End-to-end encryption for secure message transmission.
- Encryption and decryption process performed in the users' web browsers.
- Encrypted data is sent to the servers, while unencrypted data remains in the respective user's web browser.
- High data integrity and security.

## Technologies Used

- HTML
- CSS
- JavaScript
- Server-side technologies (e.g., Node.js, Express.js)
- Cryptographic libraries (e.g., Web Crypto API)

## Installation

To run CryptSend locally, follow these steps:

1. Clone the repository:

`git clone https://github.com/your-username/cryptsend.git`

2. Install the dependencies:

`cd cryptsend`
`npm install`

3. Start the development server:

`npm start`

4. Open your web browser and visit `http://localhost:3000` to access CryptSend.
