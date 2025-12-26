# 🦊 Install LibreWolf on Fedora

LibreWolf is not included in Fedora’s default repositories, so you must add the official LibreWolf repository before installing it. These steps follow the official installation instructions.

---

## 1. Add the LibreWolf repository

```bash
curl -fsSL https://repo.librewolf.net/librewolf.repo | sudo tee /etc/yum.repos.d/librewolf.repo
```

---

## 2. Install LibreWolf

```bash
sudo dnf install librewolf
```

Fedora will automatically prompt you to import the correct GPG key.

---

## GPG Key Fingerprint

To verify the repository key, confirm it matches:

```
662E 3CDD 6FE3 2900 2D0C A5BB 4033 9DD8 2B12 EF16
```

---

LibreWolf is now installed and ready to use.
