# Caesar Cipher | رمزنگاری سزار

## 🇺🇸 English

### What is Caesar Cipher?
One of the simplest encryption techniques, shifting letters by a fixed number.

### Encryption Example
**Shift: 3**
```
Plaintext:  HELLO
Ciphertext: KHOOR
```

### Python Implementation
```python
def caesar(text, shift):
    result = ""
    for char in text:
        if char.isupper():
            result += chr((ord(char) + shift - 65) % 26 + 65)
        elif char.islower():
            result += chr((ord(char) + shift - 97) % 26 + 97)
        else:
            result += char
    return result

print(caesar("HELLO", 3))  # KHOOR
print(caesar("KHOOR", -3)) # HELLO
```

---

## 🇮🇷 فارسی

### رمز سزار چیست؟
یکی از ساده‌ترین تکنیک‌های رمزنگاری که حروف رو با تعداد ثابتی جابه‌جا می‌کنه.

### مثال رمزنگاری
**جابه‌جایی: ۳**
```
متن اصلی:  HELLO
متن رمز:   KHOOR
```

### پیاده‌سازی در پایتون
```python
def caesar(text, shift):
    result = ""
    for char in text:
        if char.isupper():
            result += chr((ord(char) + shift - 65) % 26 + 65)
        elif char.islower():
            result += chr((ord(char) + shift - 97) % 26 + 97)
        else:
            result += char
    return result

print(caesar("HELLO", 3))  # KHOOR
print(caesar("KHOOR", -3)) # HELLO
```