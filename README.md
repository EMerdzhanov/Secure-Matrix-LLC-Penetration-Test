Summary of Weaknesses

Secure Matrix successfully found several critical vulnerabilities that should be immediately addressed in order to prevent an adversary from compromising the network. These findings are not specific to a software version but are more general and systemic vulnerabilities.

CVE Vulnerabilities in Apache Servers: Multiple Common Vulnerabilities and Exposures (CVEs) were found in Megacorpone’s Apache servers. These vulnerabilities can potentially be exploited by an attacker to compromise the servers.
Exposed Domain Server IP Addresses: The IP addresses of Megacorpone's domain servers are publicly accessible, making them vulnerable to DNS poisoning or spoofing.
Weak Passwords and Basic Authentication on Public Web Application: The web application at vpn.megacorpone.com uses basic authentication and allows weak passwords, making it susceptible to dictionary attacks and unauthorized access.
Open FTP Port with Vulnerable Service: The FTP service running on port 21 of a target machine uses a vulnerable version of vsFTPd software, and the port is open to the public. This vulnerability allows unauthorized users to gain root access.
Unencrypted Admin Credentials: Administrative credentials were found stored in plain text, which was used to gain further unauthorized access to the system.
Weak Password Policy and Lack of Account Lockouts: The use of weak, easily guessable passwords by Megacorpone staff and the lack of an account lockout policy allowed for successful password spraying attacks and unauthorized access to multiple machines.
Overly Permissive Privileges: Inadequate privilege management allowed immediate root access to systems, indicating a failure to implement the principle of least privilege.
Enabled LLMNR Protocol: The LLMNR (Local Link Multicast Name Resolution) protocol is enabled on a Windows 10 machine, which can be exploited by an attacker to intercept credentials.

The key weaknesses identified revolve around poor password policies, lack of encryption for sensitive data, lack of proper privilege management, exposed critical information, and use of outdated or vulnerable services and protocols. These findings indicate a need for substantial improvements in Megacorpone's security posture to mitigate potential threats and attacks.
