# Cybersecurity Fundamentals

## CIA Triad - Core Principles

### Confidentiality
- **Definition:** Ensuring that information is not disclosed to unauthorized individuals
- **Examples:** Encryption, Access Controls, Data Classification
- **Tools:** AES, RSA, PGP, VPN

### Integrity
- **Definition:** Maintaining and assuring the accuracy and completeness of data
- **Examples:** Hashing, Digital Signatures, Checksums
- **Tools:** SHA-256, MD5, HMAC

### Availability
- **Definition:** Ensuring information and systems are accessible when needed
- **Examples:** Redundancy, Backups, DDoS Protection
- **Tools:** Load Balancers, RAID, Cloud Services

## Common Cyber Threats

### 1. Phishing
- **Description:** Social engineering attack to steal sensitive information
- **Types:** Email phishing, Spear phishing, Whaling, Smishing
- **Prevention:** Employee training, Email filters, Multi-factor authentication

### 2. Malware
- **Types:**
  - **Virus:** Self-replicating malware that attaches to clean files
  - **Worm:** Spreads without user intervention
  - **Trojan:** Disguised as legitimate software
  - **Ransomware:** Encrypts files and demands payment
  - **Spyware:** Secretly monitors user activity

### 3. DDoS Attacks
- **Description:** Overwhelming a system with traffic to make it unavailable
- **Types:** Volume-based, Protocol attacks, Application layer attacks
- **Mitigation:** DDoS protection services, Rate limiting, CDN

### 4. SQL Injection
- **Description:** Injecting malicious SQL code into database queries
- **Impact:** Data theft, data manipulation, unauthorized access
- **Prevention:** Prepared statements, Input validation, ORM

### 5. Brute Force Attacks
- **Description:** Trying all possible combinations to guess passwords
- **Tools:** Hydra, John the Ripper, Hashcat
- **Prevention:** Strong passwords, Account lockout, CAPTCHA

### 6. Man-in-the-Middle (MitM)
- **Description:** Intercepting communication between two parties
- **Types:** ARP spoofing, DNS spoofing, SSL stripping
- **Prevention:** Encryption, Certificate pinning, VPN

## Attack Vectors

### Social Engineering
- **Pretexting:** Creating false scenarios to obtain information
- **Baiting:** Offering something enticing to deliver malware
- **Quid pro quo:** Offering a benefit in exchange for information
- **Tailgating:** Unauthorized physical access

### Wireless Attacks
- **Evil Twin:** Rogue access point mimicking legitimate WiFi
- **WPS Attacks:** Exploiting WiFi Protected Setup vulnerabilities
- **Packet Sniffing:** Capturing unencrypted wireless traffic

### Insider Threats
- **Malicious Insiders:** Employees with harmful intent
- **Negligent Insiders:** Employees who make security mistakes
- **Compromised Insiders:** Employees whose credentials are stolen

## Risk Management

### Risk Assessment Steps
1. **Identify Assets:** What needs protection?
2. **Identify Threats:** What could go wrong?
3. **Assess Vulnerabilities:** Weaknesses that could be exploited
4. **Calculate Risk:** Probability × Impact
5. **Implement Controls:** Security measures
6. **Monitor and Review:** Continuous improvement

### Security Controls
- **Administrative:** Policies, procedures, training
- **Technical:** Firewalls, encryption, access controls
- **Physical:** Locks, cameras, access cards

## Cybersecurity Frameworks

### NIST Cybersecurity Framework
1. **Identify:** Understand organizational context
2. **Protect:** Implement safeguards
3. **Detect:** Identify security events
4. **Respond:** Take action regarding incidents
5. **Recover:** Restore capabilities and services

### ISO 27001
- International standard for information security management
- Risk-based approach to security
- Continuous improvement cycle

## Legal and Ethical Considerations

### Laws and Regulations
- **GDPR:** General Data Protection Regulation (EU)
- **HIPAA:** Health Insurance Portability and Accountability Act (US)
- **PCI DSS:** Payment Card Industry Data Security Standard

### Ethical Hacking Principles
1. **Permission:** Always get proper authorization
2. **Scope:** Stay within agreed boundaries
3. **Documentation:** Keep detailed records
4. **Confidentiality:** Protect discovered information
5. **Responsibility:** Do no harm

## Security Awareness Best Practices

### For Individuals
- Use strong, unique passwords
- Enable multi-factor authentication
- Keep software updated
- Be cautious with emails and links
- Regular backups

### For Organizations
- Security training programs
- Incident response plans
- Regular security assessments
- Access control policies
- Network segmentation