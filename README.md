# PHP Coding Competition

## Challenge 5: First to complete hash cracker
- 100 hashes to crack: /src/Password/Hash/PasswordsToCrack.csv
- Use 100k common passwords list
- Use PHP to crack the passwords
  - hash_algos(): array
- Only used algorithms available since PHP 7.1
- Must show me the code used
- CSV sent to me formatted as:
```csv
hash,password,algorithm
5f4dcc3b5aa765d61d8327deb882cf99,password,algorithm
...,...,...
```