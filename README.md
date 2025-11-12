# OPEN-SOURCE-EX-1
Create a repository file  http://classroom.example.com/content/rhel9.0/x86_64/dvd/AppStream http://classroom.example.com/content/rhel9.0/x86_64/dvd/BaseOS

## Name : Sharan Kumar G

## Register NO : 212224230260

## Dept : Artificial Intelligence and Data Science (AI-DS)


## Steps Involved : 
### Step 1: cd /etc/yum.repos.d/
### Step 2: sudo vi classroom.repo
### Step 3: 
```
[AppStream]
name=AppStream Repository
baseurl=http://classroom.example.com/content/rhel9/x86_64/dvd/AppStream
enabled=1
gpgcheck=0
[BaseOS]
name=BaseOS Repository
baseurl=http://classroom.example.com/content/rhel9/x86_64/dvd/BaseOS
enabled=1
gpgcheck=0
```
### Step 4: dnf clean all

### Step 5: dnf repolist

## Output:

![WhatsApp Image 2025-11-11 at 10 52 13_5b460d95](https://github.com/user-attachments/assets/7e1f7ca5-e575-4779-bcf8-b55eb2a91c7e)

## Result:
Thus the steps worked in Red hat lab (Terminal)
