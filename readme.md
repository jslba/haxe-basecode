# [BaseCode][index] implement of [haxe.crypto.BaseCode][02]

![npm](https://img.shields.io/npm/v/haxe-basecode?color=blue&style=flat)
![tests](https://img.shields.io/static/v1?label=tests&message=0%20passed&color=brightgreen&style=flat)
![GitHub](https://img.shields.io/github/license/jslba/haxe-basecode?style=flat)

Allows  one to  encode / decode  String and  bytes  using a  power  of two  base
dictionary.

> **Note**   
> If you are looking  for how to  use it, you  can look at some  examples in the
> [unit tests][unittests].

## Constructor

```hx
new BaseCode(base: Bytes)
```

## Variables

```hx
public base: Bytes
```

```hx
public nbits: Int
```

```hx
public tbl: Array
```

## Methods

```hx
static decode(s: String, base: String): String
```

```hx
static encode(s: String, base: String): String
```

```hx
public initTable(): void
```

```hx
public encodeBytes(b: Bytes): Bytes
```

```hx
public decodeBytes(b: Bytes): Bytes
```

```hx
public encodeString(s: String): String
```

```hx
public decodeString(s: String): String
```

[index]: /source/index.js
[unittests]: /test/
[02]: https://api.haxe.org/haxe/crypto/BaseCode.html