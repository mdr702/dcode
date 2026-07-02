# Hashcat Guide | راهنمای Hashcat

## 🇺🇸 English

### Installation
```bash
# Linux
sudo apt install hashcat

# Windows: Download from https://hashcat.net/hashcat/
```

### Basic Usage
```bash
# Crack MD5
hashcat -m 0 -a 0 hash.txt rockyou.txt

# Crack SHA-256
hashcat -m 1400 -a 0 hash.txt rockyou.txt
```

---

## 🇮🇷 فارسی

### نصب
```bash
# لینوکس
sudo apt install hashcat

# ویندوز: دانلود از https://hashcat.net/hashcat/
```

### استفاده پایه
```bash
# کرک MD5
hashcat -m 0 -a 0 hash.txt rockyou.txt

# کرک SHA-256
hashcat -m 1400 -a 0 hash.txt rockyou.txt
```