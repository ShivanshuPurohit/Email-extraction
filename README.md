# Email-extraction

Scrape emails from an existing email address on basis of keywords, such as "Thank you for applying" and filtering
them into a custom "job" category using python.

### Requirements:
```
imaplib
email
re
getpass
```

### Usage:
* Enable IMAP in gmail settings to allow remote access of emails on websites other than gmail
* Turn on access to other apps
* Disable 2 step verification on google account

### Objective:
1. When user gives the number of emails to read, look for keywords
  ("thank you for applying", in this case).
2. Filter out these emails into a separate category ("job")
