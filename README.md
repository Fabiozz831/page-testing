
### 3. **Gunakan Tag dan Button**
- Tambahkan label atau button seperti `DEV HUB`, `FEEDBACK` menggunakan format Markdown:
  ```markdown
  [![DEV HUB](https://img.shields.io/badge/DEV-HUB-green)](https://link.to.devhub)
  [![FEEDBACK](https://img.shields.io/badge/Feedback-blue)](https://link.to.feedback)
  ```

### 4. **Simpan dan Upload ke GitHub**
- Buat repository baru di GitHub.
- Upload file `README.md` ke dalam repository tersebut.

### 5. **Tampilkan dengan Menarik**
- Pastikan gambar-gambar yang digunakan (seperti diagram) diunggah ke dalam repository dan referensinya disertakan dalam Markdown.
- Contoh menambahkan gambar:
  ```markdown
  ![Diagram](./path-to-image.png)
  ```

### Contoh Markdown:
```markdown
# NEAR Protocol Developer Guide

[![DEV HUB](https://img.shields.io/badge/DEV-HUB-green)](https://link.to.devhub)
[![CALENDAR](https://img.shields.io/badge/CALENDAR-yellow)](https://link.to.calendar)
[![DEV SUPPORT](https://img.shields.io/badge/DEV-SUPPORT-red)](https://link.to.support)
[![FEEDBACK](https://img.shields.io/badge/Feedback-blue)](https://link.to.feedback)

NEAR is dedicated to providing the best developer experience possible for building an open web. This mission is next to impossible to achieve without feedback and contributions from people like you. 🙌

## Architecture
![Diagram](./diagram.png)

- **Protocol**: Secure public database and smart contracts.
- **API**: Libraries that interact with the protocol via RPC.
- **Wallet/Auth Layer**: User authentication via wallet or email.
- **Application**: Frontend interface for decentralized apps.
