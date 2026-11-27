# DevSecOps CodeQL Demo

This repo integrates **CodeQL (SAST)** into GitHub Actions to detect vulnerabilities before code reaches production.

## What it does
- Scans the Python code automatically on every pull request.
- Detects vulnerabilities like SQL injection and flags the exact line.
- Blocks the merge if the security check fails.

## Tech stack
Python · Flask · GitHub Actions · CodeQL

## Next steps
- Add DAST with OWASP ZAP.
- Add secret scanning and dependency scanning (SCA).
