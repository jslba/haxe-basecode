# [BaseCode][01] implement of [haxe.crypto.BaseCode][02]
Allows  one to  encode / decode  String and  bytes  using a  power  of two  base
dictionary.

## Static methods
```haxe
static decode(s: String, base: String): String
```
```haxe
static encode(s: String, base: String): String
```
## Constructor
```ts
new BaseCode(base: Bytes)
```
## Methods
```haxe
decodeBytes(b: Bytes): Bytes
```
```haxe
decodeString(s: String): String
```
```haxe
encodeBytes(b: Bytes): Bytes
```
```haxe
encodeString(s: String): String
```

[01]: /source/index.js
[02]: https://api.haxe.org/haxe/crypto/BaseCode.html