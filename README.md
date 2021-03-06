# Sleep Easy Backups
Java program that creates compressed backups for your cloud accounts (Google, Dropbox, OneDrive, etc)

## Background
Imagine the following scenarios: 
- Someone gets the credentials to your cloud account (Google, Dropbox, OneDrive), deletes all your documents, and empties the trash. 
- You permanently delete an email, certain that you'll never need it again. A few days later, you realize that you do, in fact, need the email.
- You need to access a document saved in the cloud, but your cloud provider's website is down and you have no local copy of the document.

What now? 

The best option might be to recover from a physical backup that is stored locally or on a separate cloud account. Unfortunately, many cloud providers do not natively support this sort of backup, and creating them manually can be time-consuming and tedious. This program intends to solve this problem by automating backups for many popular cloud services, allowing users to sleep easy again.

----

## Goal
- Introduce an intuitive, effective program that requires no technical knowledge to use

### Features
- Compressed backups
- Incremental and full backups
- Option to configure backup schedule
- Summary and alerts emails

### Cloud Providers
- Google GSuite (GDrive, Gmail)
- Microsoft OneDrive (OneNote)
- Dropbox
- Facebook
- Twitter
- Instagram

----

## Roadmap
#### Implement primary features
- [ ] Compressed backups for each API [In progress]
- [ ] Interactive CLI
#### Implement secondary features
- [ ] Incremental backups
- [ ] Automate backups
- [ ] Summary and alert emails
#### Implement tertiary features
- [ ] GUI
- [ ] User configuration
#### Leverage existing codebase to create an Android App
