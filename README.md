# Sensitive Information Detection in Audio Files

**Description**  

This project implements a lightweight and customizable system for detecting sensitive information (PII) in audio recordings. It leverages OpenAI's powerful Whisper model for speech-to-text transcription and employs tailored regex-based detection to identify structured PII such as phone numbers, email addresses, account numbers, and IDs.

----------------------------------------------------------------------------------------------------------------------------------

##  Table of Contents
1. [Features]  
2. [Getting Started] 
   - [Prerequisites] 
   - [Installation]
3. [Usage]
4. [Regex Patterns Used]
5. [Testing & Sample Data]  
6. [Design & Architecture]  
7. [Future Enhancements]
8. [License]  
9. [Acknowledgements])

---------------------------------------------------------------------------------------------------------------------------------
## Features
- **Robust Transcription**: Uses Whisper to convert audio to text, offering high accuracy even with noise or accented speech.  
- **Custom Regex Detection**: Powerful pattern-matching rules capture structured PII formats like phone numbers, emails, national IDs, etc.  
- **Modular & Transparent**: Easily add or modify regex patterns. The system is designed to be clear and extendable.  
- **Privacy-Focused**: Intended for in-line detection and redaction workflows to ensure sensitive data does not remain in clear form.

---------------------------------------------------------------------------------------------------------------------------------

## Getting Started

### Prerequisites
- Python 3.8 or higher  
- Required libraries: `openai`, `pydub`, `re`, `argparse`, `json`  
- (Optional) A GPU-enabled environment for faster Whisper inference
----------------------------------------------------------------------------------------------------------------------------------
### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Tejas90219/Sensitive-Information-Detection-in-Audio-Files-Datasets.git
   cd Sensitive-Information-Detection-in-Audio-Files-Datasets
----------------------------------------------------------------------------------------------------------------------------------
