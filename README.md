# defcrypt
string encryptor/decryptor using xor operation for Defold games.

# usage
The first arg is the string you want to en/decrypt.
The second arg is the key.

```
local crypt = require "main.crypt"

function init(self)
    print(crypt("www.sina.com","123")) --encrypt
    print(crypt("FED AZ_S R]^","123")) --decrypt
end
