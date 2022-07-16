# ChromeMiner

##### Table of Contents  
1. [Challenge Details](#headers)  
2. [Solution Write-up](#headers)  
## Headers

## 1. Challenge Details 
Discurd has filed a DMCA violation regarding a popular browser extension claiming to be conducting VIP giveaways on the company's product. The addon store has since taken down the extension to prevent any potential browser cryptomining malware from being distributed in the marketplace. Could you investigate what the 'Discurd Nitro Giveaway' addon does exactly?

### Challenge Category
Reversing

### Challenge Points
325 (easy)

### CTF Date
07/15/2022 - 07/17/2022

## Solution Write-up

1. The zip file we downloaded contains a file with the extension '.crx'. Quick Google search tells us that this is a _Chrome extension file_. 
2. We can visit [Ezyzip.com](https://www.ezyzip.com/open-extract-crx-file.html) to view the contents of the extension.
3. The extracted contents can be viewed in [Extracted/](Extracted/)
4. Investigating these files background.js seems to contain a sort of cipher. In order to determine the way the strings are built I have created a python script. [ChromeMiner.py/](ChromeMiner.py/)



