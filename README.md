# KeybaseLogin
Prompts the user for their Keybase username and password, then follows Keybase's login API by making a [getsalt](https://keybase.io/docs/api/1.0/call/getsalt) call, then a [login](https://keybase.io/docs/api/1.0/call/login) call.
Gets a session cookie and a bundle that contains data which will be decrypted into the secret key.
