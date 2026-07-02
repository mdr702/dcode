# Hashes - Introduction | مقدمه‌ای بر هش‌ها

## 🇺🇸 English

### Common Hash Algorithms

| Algorithm | Output Size |
|-----------|-------------|
| MD5 | 128-bit |
| SHA-1 | 160-bit |
| SHA-256 | 256-bit |
| SHA-512 | 512-bit |

### Python Example
```python
import hashlib

text = "Hello, World!"

# MD5
md5_hash = hashlib.md5(text.encode()).hexdigest()
print(f"MD5: {md5_hash}")

# SHA-256
sha256_hash = hashlib.sha256(text.encode()).hexdigest()
print(f"SHA-256: {sha256_hash}")
```

---

## 🇮🇷 فارسی

### الگوریتم‌های رایج هش

| الگوریتم | اندازه خروجی |
|----------|--------------|
| MD5 | ۱۲۸ بیت |
| SHA-1 | ۱۶۰ بیت |
| SHA-256 | ۲۵۶ بیت |
| SHA-512 | ۵۱۲ بیت |

### مثال در پایتون
```python
import hashlib

text = "Hello, World!"

# MD5
md5_hash = hashlib.md5(text.encode()).hexdigest()
print(f"MD5: {md5_hash}")

# SHA-256
sha256_hash = hashlib.sha256(text.encode()).hexdigest()
print(f"SHA-256: {sha256_hash}")
```