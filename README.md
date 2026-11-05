# CyberLord Security Toolkit

A beginner-friendly, browser-based cybersecurity learning project.

## Features
- Local password-strength estimate (password stays in the browser)
- SHA-256 and SHA-512 text hash generator
- Public IP information lookup (uses ipapi.co)
- Basic URL format/security quick check
- Common TCP/UDP port reference
- HTTP security-header learning guide

## Run locally
1. Download and extract this project.
2. Open `index.html` in a modern browser.
3. For Web Crypto features, use HTTPS or localhost if your browser requires a secure context.

No build tools or package installation are required.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `cyberlord-security-toolkit`.
2. Upload `index.html` and `README.md` to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait for GitHub Pages to publish. The site link will appear in the Pages section.

## Safety and limitations
- Use security tools only on systems you own or have explicit permission to assess.
- The URL checker is a basic local heuristic, not a malware scanner.
- The IP lookup sends the requested IP to ipapi.co.
- The toolkit does not scan ports, exploit websites, or guarantee that a target is secure.
- Password strength scoring is educational and is not a substitute for a password manager or breached-password screening.

## Portfolio description
Built a responsive browser-based cybersecurity toolkit featuring client-side password assessment, Web Crypto hashing, public IP information lookup, URL structure checks, and a common network-port reference. Implemented with HTML, CSS, and vanilla JavaScript.
