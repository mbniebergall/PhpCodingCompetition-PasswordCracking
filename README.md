# PHP Coding Competition

## Challenge 5: First to complete hash cracker
- 1,000 hashes to crack
- Passwords to crack
  - src/Password/Hash/PasswordsToCrack.txt
- Output to file
  - src/Password/Hash/CrackedPasswords.csv
- CSV formatted as:
```csv
 hash,plaintext,algorithm
 5f4dcc3b5aa765d61d8327deb882cf99,password,md5
 ...,...,...
```
- Use PHP to crack the passwords
- hash_algos(): array
- Only used algorithms available since PHP 7.1
- Must show me the code used