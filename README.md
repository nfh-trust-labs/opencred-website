# OpenVC Website

A "Launching Soon" website for **OpenVC** - an open Verifiable Credential service by [Networks for Humanity](https://networksforhumanity.org/).

## Overview

OpenVC democratizes credential issuance and verification, putting users in control of their digital identity while ensuring cryptographic trust.

### Key Features

- **Open Issuance** - Anyone can issue verifiable credentials
- **Zero Storage** - No credential storage (max 24hr temporary processing)
- **Transient Key Pairs** - Keys derived from user signature, never stored
- **Self-Contained Verification** - Local verification, no service calls needed
- **Verification Module** - Embeddable SDK for any application
- **Smart Revocation** - Payload-based revocation with embedded URLs

## Tech Stack

- HTML5
- Tailwind CSS (CDN)
- Font Awesome 6.4.0
- Plus Jakarta Sans font
- Vanilla JavaScript

## Files

```
openvc-website/
├── index.html          # Main single-page website
├── openvc-logo.svg     # Logo file
└── README.md           # This file
```

## Local Development

Simply open `index.html` in a web browser:

```bash
open index.html
# or
python -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

### Firebase Hosting

1. Install Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Initialize: `firebase init hosting`
4. Deploy: `firebase deploy`

### Netlify

1. Drag and drop the folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect to Git repository

### GitHub Pages

1. Push to a GitHub repository
2. Go to Settings > Pages
3. Select branch and folder

### AWS Amplify

1. Connect repository to AWS Amplify Console
2. Configure build settings (static site, no build required)
3. Deploy

## Design System

| Element | Value |
|---------|-------|
| Primary Blue | `#1a73e8` |
| Primary Green | `#34a853` |
| Gradient | `linear-gradient(135deg, #1a73e8, #34a853)` |
| Font | Plus Jakarta Sans |
| Framework | Tailwind CSS |

## Standards Compliance

OpenVC follows open standards:
- W3C Verifiable Credentials Data Model
- Decentralized Identifiers (DIDs)
- JSON Web Tokens (JWT)
- Selective Disclosure

## License

Copyright 2025 Networks for Humanity. All rights reserved.

## Contact

- Website: [networksforhumanity.org](https://networksforhumanity.org/)
- Email: hello@openvc.global
