# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: Pillow
1. Which package or library are you addressing?
    Pillow: A critical vulnerability in the Pillow image-processing library (version ≤ 9.4.0) allows remote attackers to trigger memory corruption during image decoding.

2. Which CVE is linked to this vulnerability?
    CVE-2023-50447

3. What remediation steps do you suggest?
    Upgrade Pillow to version 10.2.0 or later

### Vulnerability 2: Werkzeug
1. Which vulnerability are you addressing?
    A HIGH severity vulnerability in Werkzeug (version ≤ 2.1.2) allows attackers to craft malicious HTTP requests that bypass request handling logic

2. Which CVE is linked to this vulnerability?
    CVE-2023-25577

3. What remediation steps do you suggest? 
    Upgrade Werkzeug to version 2.2.3 or lateR