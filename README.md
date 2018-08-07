# Two-factor authentication (2FA)

> **Two-factor authentication** (also known as **2FA**) is a type (subset) of multi-factor authentication. It is a method of confirming users' claimed identities by using a combination of two different factors: 1) something they know, 2) something they have, or 3) something they are. 

[Authentication Cheat Sheet - OWASP][4]

[NIST SP 800-63 Digital Identity Guidelines][5]

## One-Time Password (OTP)

> A **one-time password or pin (OTP)** is a password that is valid for only one login session or transaction, on a computer system or other digital device.

[RFC 4226 - HOTP: An HMAC-Based One-Time Password Algorithm][1]

[RFC 6238 - TOTP: Time-Based One-Time Password Algorithm][2]

[RFC 6287 - OCRA: OATH Challenge-Response Algorithms][3]

#### [Spomky-Labs/otphp][6]

> A PHP library for generating one time passwords according to [RFC 4226 (HOTP)][1] and the [RFC 6238 (TOTP)][2].

#### [PyOTP - The Python One-Time Password Library][8]

> PyOTP is a Python library for generating and verifying one-time passwords.

## Universal 2nd Factor (U2F)

> **Universal 2nd Factor (U2F)** is an open authentication standard hosted by the [FIDO Alliance][9] that strengthens and simplifies two-factor authentication (2FA) using specialized USB or NFC devices, like [YubiKeys][10].

[U2F Server Libraries @ developers.yubico.com][11]

[1]: https://tools.ietf.org/html/rfc4226
[2]: https://tools.ietf.org/html/rfc6238
[3]: https://tools.ietf.org/html/rfc6287
[4]: https://www.owasp.org/index.php/Authentication_Cheat_Sheet
[5]: https://pages.nist.gov/800-63-3/
[6]: https://github.com/Spomky-Labs/otphp
[7]: https://tools.ietf.org/html/rfc4086
[8]: https://github.com/pyotp/pyotp
[9]: https://fidoalliance.org/approach-vision/
[10]: https://www.yubico.com/products/yubikey-hardware/
[11]: https://developers.yubico.com/U2F/