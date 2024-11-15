# OTP Authentification Service

A lightweight OTP generation and verification service for mobile applications.

## Features
- Generate secure, time-bound OTPs.
- Abstract SMS delivery providers.
- Configurable OTP length and expiration.

## Endpoints
- `POST /generate-otp`: Generate an OTP snd sends it to the user
- `POST /verify-otp`: Verifies the OTP against stored records
