# Bug Bounty
## PortSwigger's Web Security Academy
### 1. SQL Injection
#### Blind SQL injection
##### Exploiting blind SQL injection using out-of-band (OAST) techniques:

* Lab: Blind SQL injection with out-of-band interaction
* Lab: Blind SQL injection with out-of-band data exfiltration

<br />

### 2. Authentication
#### Vulnerabilities in multi-factor authentication LABS
##### Brute-forcing 2FA verification codes

* Lab: 2FA bypass using a brute-force attack

#### Vulnerabilities in other authentication mechanisms
##### Keeping users logged in

* Lab: Offline password cracking

<br />

### 4. Command Injection
#### Exploiting blind OS command injection using out-of-band (OAST) techniques

* Lab: Blind OS command injection with out-of-band interaction
* Lab: Blind OS command injection with out-of-band data exfiltration

<br />

### 6. Information Disclosure
#### How to find and exploit information disclosure vulnerabilities
##### Version control history

* Lab: Information disclosure in version control history (use wget on Linux)

<br />

### 8. File Upload Vulnerabilities
#### Flawed validation of the file's contents

* Lab: Remote code execution via polyglot web shell upload (use exiftool on linux)

#### Exploiting file upload race conditions

* Lab: Web shell upload via race condition

<br />

### 9. Server-Side Request Forgery (SSRF)
#### Blind SSRF vulnerabilities

* Lab: Blind SSRF with out-of-band detection
* Lab: Blind SSRF with Shellshock exploitation

<br />

### 10. XXE Injection
#### Blind XXE vulnerabilities
##### Detecting blind XXE using out-of-band (OAST) techniques

* Lab: Blind XXE with out-of-band interaction
* Lab: Blind XXE with out-of-band interaction via XML parameter entities

##### Exploiting blind XXE to exfiltrate data out-of-band
* Lab: Exploiting blind XXE to exfiltrate data using a malicious external DTD

<br />

### 11. Cross-Site Scripting (XSS)
#### Exploiting cross-site scripting vulnerabilities
##### Exploiting cross-site scripting to steal cookies

* Lab: Exploiting cross-site scripting to steal cookies

##### Exploiting cross-site scripting to capture passwords

* Lab: Exploiting cross-site scripting to capture passwords

##### Exploiting cross-site scripting to perform CSRF

* Lab: Exploiting XSS to perform CSRF

#### Content security policy
##### Mitigating XSS attacks using CSP

* Lab: Reflected XSS protected by very strict CSP, with dangling markup attack

<br />

### 12. Cross-Site Request Forgery (CSRF)
#### Bypassing SameSite cookie restrictions

* Lab: SameSite Strict bypass via sibling domain

<br />

### 13. Cross-Origin Resource Sharing (CORS)
#### Server-generated ACAO header from client-specified Origin header

* Lab: CORS vulnerability with basic origin reflection

#### Whitelisted null origin value

* Lab: CORS vulnerability with trusted null origin

#### Intranets and CORS without credentials

* Lab: CORS vulnerability with internal network pivot attack

<br />

### 15. DOM-Based Vulnerabilities
#### Which sinks can lead to DOM-based vulnerabilities?
##### Document-domain manipulation --- check
##### WebSocket-URL poisoning --- check
##### Link manipulation --- check
##### Web message manipulation --- check
##### Ajax request-header manipulation --- check
##### Local file-path manipulation --- check
##### Client-side SQL injection --- check
##### HTML5-storage manipulation --- check
##### Client-side XPath injection --- check
##### Client-side JSON injection --- check
##### DOM-data manipulation --- check
##### Denial of service --- check
#### DOM clobbering
##### How to exploit DOM-clobbering vulnerabilities

* Lab: Exploiting DOM clobbering to enable XSS
