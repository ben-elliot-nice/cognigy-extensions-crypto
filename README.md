# Crypto


This Extension exposes Node.JS's crypto functions to Cognigy.AI

## Node: createHash

This node creates a Hash. It stores the result in the context or input object:

```json
{ 
	"key": {
		"result":"5ae9b7f211e23aac3df5f2b8f3b8eada"
	},
	"iv": {
    		"result": "1234567890abcdef" // utf8
  	}
 }
```
## Node: encrypt

This node encrypts. It stores the result in the context or input object:

```json
{ 
	"encrypt": {
		"result":"69ce7bfa6a9381f4",
		"iv": "1234567890abcdef" // utf8
	}
 }
```

## Node: decrypt

This node decrypts. It stores the result in the context or input object:

```json
{
	"decrypt": {
		"result":"crypto"
	}
 }
```

## Node: hmac

This node creates an HMAC (Hash-based Message Authentication Code). It stores the result in the context or input object:

```json
{
	"hmac": {
		"result":"a7b3c4d5e6f7g8h9i0j1k2l3m4n5o6p7"
	}
 }
```

Supported algorithms: SHA256, SHA1, SHA384, SHA512, MD5
