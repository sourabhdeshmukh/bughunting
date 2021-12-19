
Course Focus - 
  1. Fundamentals of owasp
  2. Installation of burp suit.
    Attacks
    a. xss - Reflected, Stored, Dom
    b. authentication bypass - otp bypass, two factor authentication bypass, email verification bypass.
    c. csrf - how to find injection points and perform account takeover
    d. no rate limit - signup creation, otp bruteforce, account takeover. 
    e. cors - exfiltrate sensitive data of other users, access sensitive data of other users. 
    f. bypass filters and manual balancing
    g. polyglots and blind xss
    
OWASP TOP 10 2013
1. Injection 
2. BASM - Broken authentication and session management.
3. xss - cross site scripting
4. IDOR - Insecure direct object reference.
5. Security Misconfiguration
6. SDE - sensitive data exposure.
7. MFLAC - Missing function level access control.
8. CSRF - Cross site request forgery.
9. Using components with known vulnerabilities.
10. Unvalidated Redirect and forwards


OWASP TOP 10 2017
1. Injection 
2. BA - Broken authentication.
3. xss - cross site scripting
4. IDOR - Insecure direct object reference.  --- broken access control ---
5. Security Misconfiguration
6. SDE - sensitive data exposure.
7. MFLAC - Missing function level access control. --- broken access control ---
8. CSRF - Cross site request forgery. -- insufficient logging and monitoring ---
9. Using components with known vulnerabilities.
10. Unvalidated Redirect and forwards --- XML External Entities and insecure deserialisation ---

    Injection - 
        1. SQL
        2. LDAP
        3. OS
        4. Command Execution
        5. Ruby
        6. Shell Shock

    Broken Authentication -
        1. OTP Bypass
        2. captcha Bypass
        3. Common Passwords
        4. 2FA bypass

    XML Enternal Entities (XXE) -
        1. Disclosure of Sensitive Data
        2. SSRF
        3. Port Scanning
        4. DOS
        5. RCE

    Broken Access Control -
        1. Priviledge escalation
          a. Horizontal - user to user
          b. Vertical - user to admin
        2. Cross origin sharing
        3. Metadata manipulation.
    
    Security Misconfiguration -
        1. Account Takeover
        2. RCE
        3. Malware Injection
        4. Email Spoofing (Misconfigured TXT/DND records)
        5. Server Injection

    Cross Site Scripting -
        1. Reflected
        2. dom
        3. stored

    Insecure Desearlization -
        1. RCE
        2. Sensitive data exposure
    
    Using componenet with known velnerabilities -
        1. Outdated Soft.
        2. Zero day vulnerability

    Insufficient logging and Monitoring -
        
    