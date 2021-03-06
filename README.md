# ft_ssl_md5

My realization of ```MD5```, a widely used message-digest algorithm (in other words, a hash function).

---

## Installation

To get the executable `ft_ssl`, simply run ```make```

---

## Usage

```
usage: ft_ssl [md5 | sha[224 | 256 | 384 | 512]] [-pqr] [-s string] [files ...]
```

Program's behaviour is totally identical to `md5`, only with additional hash functions, so

```
man md5
```

---

## Algorithms

Besides ```MD5``` itself, next ```SHA2``` family hash functions are implemented:

- `SHA256`
- `SHA224`
- `SHA512`
- `SHA384`

(Sorry, guys, no ```Whirlpool```:disappointed:)

---

## Features

```md5``` Linux terminal command is almost fully repeated (with flags -[pqrs]),  
with all hash functions compliant to ```md5```command standard parsing behaviour

Futhermore, ```openssl``` standard input is implemented

---

## So, guys, I hope you will find this project useful and, in case any questions occur, feel free to connect with me by any of the emails listed below

- [Artemkupriyanets@yahoo.com](https://www.yahoo.com)  
- [mr.tyomka.97@gmail.com](https://www.gmail.com)  

## Thanks for attention:kissing_heart:
