# OpenCore EFI for HP EliteBook 830 G5 (i5‑8350U / UHD 620) — macOS Sequoia

This repository contains a pre‑configured OpenCore EFI folder to install and run macOS Sequoia (15.x) on the HP EliteBook 830 G5 with Intel i5‑8350U, UHD 620 graphics, Intel Dual‑Band Wi‑Fi, and Intel Ethernet.

---


## ⚙️ Prerequisites

1. **OpenCore** v1.0.0 (or ≥ 0.9.9)  
2. A USB drive formatted GPT with a 200 MB EFI partition  
3. `iasl` compiler for building any custom SSDTs  
4. GenSMBIOS (or CorpNewt’s GenSMBIOS) to generate:
   - SystemSerialNumber
   - MLB
   - ROM
   - SystemUUID

---

## 🛠 BIOS Settings

- **Boot Mode**: UEFI Only  
- **Secure Boot**: Disabled  
- **VT‑d**: Disabled  
- **CFG‑Lock**: Disabled (or unlock via quirks)  
- **Fast Boot**: Disabled  
- **Legacy Support**: Disabled  
- **SATA Mode**: AHCI  

---

## License

This project is released under the [MIT License](LICENSE)