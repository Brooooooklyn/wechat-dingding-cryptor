```
npm run compile
npm run test
```
### demo

```

var cryptor = new WxCrypt(config.corpid, config.token, config.encodingAESKey);

@param timestamp [string]
@param nonce     [string]
@param encrypt   [string]
cryptor.getSHA1(timestamp, nonce, encrypt);

@param str       [string]  string to encrypt
cryptor.encrypt(str);

@param encoded [string]    encoded string
cryptor.decrypt(encoded);

```
