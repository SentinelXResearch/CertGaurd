# CertGuard: SSL Certificate Security Scanner

CertGuard is a lightweight tool designed to enhance the security of SSL certificates by detecting vulnerabilities such as Heartbleed. Leveraging OpenSSL commands, CertGuard extracts SSL certificates from specified domains and conducts thorough scans to identify potential vulnerabilities, empowering users to fortify their digital defenses against cyber threats.

## Features

- Detects Heartbleed vulnerability in SSL certificates.
- Lightweight and easy to use.
- Provides detailed reports of scan results.

## Usage

1. Download the compiled binary from the Releases page.

2. Make the binary executable:

   ```bash
   chmod +x certguard
   ```
   Run CertGuard with a domain name as an argument
```bash
  ./certguard example.com
```
CertGuard will extract the SSL certificate from the specified domain and scan it for the Heartbleed vulnerability. The scan results will be displayed in the terminal.
