# CrackMe Keygen (Reversed and Patched)


This repo contains a keygen created by **patching the original binary**. It now generates a valid key for any given username.

## 🔍 What Was Done

- Decompiled the original `crackme.exe` using x64dbg
- Found the key-checking logic using `strcmp`
- Patched conditional jumps to always validate input
- Modified messages to display correct key
- Saved as `keygen.exe` which now acts like a legit key generator

## 🗂 Files

| File | Description |
|------|-------------|
| `crackme(officialversion).exe` | Original binary |
| `crackedversion.exe` | Fully patched app that accepts any username/password |
| `keygen.exe` | The patched binary acting as a key generator |
| `readme.1st` | Original CrackMe file |

## 🧠 Tools Used

- x64dbg


## ⚠️ Disclaimer

For educational purposes only. Do not use this on real-world software.

