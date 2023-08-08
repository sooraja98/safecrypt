
# SafeCrypt Usage

## Installation

```bash
npm install safecrypt

## Usage
const SafeCrypt = require('safecrypt');

// Generate a hashed password
const plainPassword = 'mySecurePassword';
const hashedPassword = SafeCrypt.generateHash(plainPassword);

// Compare a password with the hashed password
const isMatch = SafeCrypt.compareHash(plainPassword, hashedPassword);
console.log('Password Match:', isMatch);

.Note: Replace 'mySecurePassword' with the actual password you want to hash and compare.



