# Gmail-Body-Extractor
We need to extract information from the email body because it does not arrive in the attachments. This automation can give us a lot "copy-paste" time work 


## Overview
This project connects to a Gmail inbox via IMAP and extracts data **only from the email body**.


## Features
- IMAP connection to Gmail
- MIME decoding for email subjects
- Parsing of plain text email body
- Regex-based tracking extraction
- Structured output in a Pandas DataFrame
- Deduplication of values


## How It Works
1. Connects to Gmail using IMAP
2. Iterates over emails
3. For each email:
   - Decodes the subject. I used parser code. So, you cand edit that code with your objetive. 
   - Extracts the plain text body
   - Applies regex to find objetive values
4. Stores results in a DataFrame
5. Outputs a clean dataset and export to xlsx

