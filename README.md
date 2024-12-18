# FUTURE_CS_01
# 2FA Implementation in Node.js

## Importance and Benefits of Two-Factor Authentication
Two-Factor Authentication (2FA) adds an extra layer of security to your online accounts by requiring not only a password but also a one-time code generated by an app on your phone. This prevents unauthorized access, even if someone manages to steal your password.

## How to Use
- Start the server with `node app.js`.
- Set up 2FA by sending a POST request to `/2fa/setup`.
- Verify 2FA by sending a POST request to `/2fa/verify`.

## Dependencies
- Express
- Express-session
- Speakeasy
- QRCode
