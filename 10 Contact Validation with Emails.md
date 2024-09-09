# Contact Validation with Emails

The primary focus is on verifying contact information, especially email addresses, discovered during OSINT investigations.

## Key points discussed include:

#### EmailRep.io 
- The use of ***EmailRep.io*** to analyse an email's digital footprint based on various factors like domain age, traffic rankings, social media presence, data breaches, and more. It provides a detailed report indicating if an email address is part of a data breach, its online reputation, whether it's disposable, and its presence on social media platforms.
- https://https://emailrep.io/
  - provides an API service to review details of an email account
  - Primary use case is to see if the email is legitimate and if you can pivot into other areas fro searching

#### Google Account Finder
- The ***Google Account Finder*** from ***EPIEOS*** is introduced, which verifies if an email address is linked to a Google account. It can provide valuable insights, especially from Google Maps reviews, about an individual's behaviors and interests.
- https://epieos.com/
  - Google account finder will show you in the requested email address is linked to a google account, and if the person has left reviews on google maps
  - Retrieve details without notifying the user 

#### Have I Been Pwned
- ***Have I Been Pwned, a website that enables users to check if their personal data has been compromised by data breaches. It serves multiple functions, including personal security assessment, OSINT investigations, and threat intelligence.
- https://haveibeenpwned.com
  - Quickly identify if data has appeared in any data breaches - personal security, investigations and threat intelligence in cyber security. 

------------------------------------------------------------------------------------------------------------
We need constant adaptation of validation techniques in the expanding digital world as such, other tools you might need to use include:

#### Phonebook.cz
- ***Phonebook.cz***: Requiring an account, this tool provides data on domains, email addresses, and URLs associated with a given input. It allows wildcard searches, helping to identify all occurrences of a specific domain extension. This tool is beneficial for listing all domains and emails associated with a given domain, analysing email naming conventions, and generating additional selectors for investigations.

#### Whoxy.com
- ***Whoxy.com***: A comprehensive domain name research tool offering information about a domain's ownership, registration history, and associated email accounts. The email feature enables reverse engineering of domain names using an email address. This can be vital for uncovering a subject's digital footprint, mapping connections, identifying business associations, and conducting risk assessment.

#### ViewDNS.info
- ***ViewDNS.info***: This versatile platform provides multiple tools. One standout feature is its ability to reverse engineer domain names using an email address, which helps in mapping a subject's digital footprint across different websites. It also facilitates uncovering websites hosted on a specific IP and identifying sites using the same mail server.

As always - A reminder of the importance of verification in any OSINT investigation to ensure the accuracy and validity of findings.
