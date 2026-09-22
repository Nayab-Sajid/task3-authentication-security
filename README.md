# Task 3 – Authentication & Data Security

Internee.pk Cybersecurity Internship

## Objective
Strengthen user authentication and data security to protect sensitive information by implementing Two-Factor Authentication (2FA), OAuth 2.0 sign-in, and AES-256 encryption.

## What's in this repo
- **Task3_Auth_Security_Report.docx** – Full write-up covering all three parts, with screenshots
- Sample fake user dataset generated via Mockaroo
- Screenshots demonstrating each part working

## What was done
1. **2FA** – Demonstrated using a browser-based TOTP generator, functionally equivalent to Google Authenticator (RFC 6238 algorithm).
2. **OAuth 2.0** – Completed a full Authorization Code flow using Google's official OAuth 2.0 Playground, from consent through to fetching profile data with an access token.
3. **AES-256 Encryption** – Encrypted and decrypted sample sensitive data using CyberChef, verifying the round trip restored the original data correctly.

## Tools used
- [Mockaroo](https://www.mockaroo.com/) – fake dataset generation
- [totp.danhersam.com](https://totp.danhersam.com/) – TOTP/2FA demo
- [Google OAuth 2.0 Playground](https://developers.google.com/oauthplayground) – OAuth 2.0 flow
- [CyberChef](https://gchq.github.io/CyberChef/) – AES-256 encryption/decryption
