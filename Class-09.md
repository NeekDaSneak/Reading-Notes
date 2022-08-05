# **Class 09 Reading Notes**

## EMAIL

### **_Why is this topic important?_**

Email is something we use everyday. Hackers defenitely take to email too. These notes show you what email is and how they deliver the messages.

- Why do we need to practice email service and client sdetup?

  - common computer operation

  - Major form of business communication

  - Major attack vector for scammers phising and ransomware

- Popular email clients
  - Outlook

  - Gmail

  - 365

- Email
  - Defined as a method of exchanging messages electonically

## Email Protocols

- Webmail
  - An email service accessible via web browser

- POP3 (Post office protocol 3)  
  - An inbound configuration that will deliver messages to your client then delete them off the mail server immediately

  - Messafes can be read offline
  - Defailt POP Port number: 110
  - POP3 port number witySSL/TLS:995

- IMAP (Internet MEssage Access Protocol) *Newer than POP3
  - An inbound configuration that will allow you to manage a mailbox from multiple devices and synchronize with the mail server which keeps a copy of the recieved emails.

  - Defualt IMAP Port number 143
  - IMAP over sSSL (Imaposs ports number 993)

- MAPI

  - Protocol used by Microsoft Exchange servers that comminicate with their clienrts Microsoft Outlook

  - Uses RPC encryption
  - Dynamically- assigned port numbers

- SMTP (Simple Mail Transfer Protocol)

  - Outbound configuration that lets your email client send emails.
  - Defualt port: 25
  - Secondary port 26
  - SSL/TLS:465

- What file esxtensions do emails use
  - .eml
  - .emlx
  - .msg
  - .mbx

- How is email monitored to prevent abuse.
  - Law enforcement
  - Corporaste policy, monitoring and systems adminstration.
  - Domain reputation mx toolbox domain email blacklist
