# unison-md5

Implementation of the MD5 message-digest algorithm in Unison. Based on [pureMD5 Haskell library](https://github.com/TomMD/pureMD5).


## Installation

```
.> pull https://github.com/asoltysik/unison-md5:.releases._v1 .external.md5.v1 
```


## Usage


```
use external.md5

md5EncodeAscii "foo"  -- returns ""acbd18db4cc2f85cedef654fccc4a4d8"

md5Encode (Bytes.fromList [97]) -- returns (Bytes.fromList [12, 193, 117, 185, 192, 241, 182, 168, 49, 195, 153, 226, 105, 119, 38, 97])
```
