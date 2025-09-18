# Secret Calculator - Reverse Engineering Challenge

## Description
This is a **Reverse Engineering (RE) challenge** designed to test binary analysis skills.  

It is a fully functional calculator with a hidden trigger:  

- Performs basic arithmetic operations: `+`, `-`, `*`, `/`.  
- **Hidden trigger**: when the user inputs `77 + 88`, the program prompts for a **password**.  
- If the correct password is entered, a hidden file (image, audio, or video) will be opened.  
- The password is **obfuscated** in the binary to prevent easy static inspection.

The goal of the challenge is to **analyze the binary** and find the correct password or understand the hidden behavior.

---

## Instructions

1. Download the repository.  
2. Make the binary executable (Linux):
```   bash
      "chmod +x calculator"
3. Run the binary:
      "./calculator"
4. Use the calculator normally for basic arithmetic.
5. To trigger the hidden functionality, input:
     "77 + 88"




FOR EDUCATIONAL PURPOUSE

