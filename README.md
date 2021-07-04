# defcrypt
string encrypt/decrypt tool for Defold

# usage

```
local crypt = require "main.crypt"

function init(self)
    print(crypt("www.sina.com","123")) --encrypt
    print(crypt("FED AZ_S R]^","123")) --decrypt
end
