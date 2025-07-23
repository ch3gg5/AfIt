# 🛡️ AfIt Privacy Policy

_Last update: April 5, 2025_  
_Version: 1.0_

> This policy applies to **AfIt**, an open-source nutrition and wellness tracker built on the Energize codebase.

AfIt is designed to be **privacy-first**, **ethical**, and **open-source by design**. We believe that your health data belongs to you — not corporations or third parties.

Below is a breakdown of what data we collect, why, and how it's used.

---

## 📱 Data Stored Locally (By Default)

All core tracking data — including:
- Food logs
- Water intake
- Macros
- Body metrics
- Goals and history

is stored **on your device only**, unless you choose to enable syncing or backup features.

There are **no hidden trackers, no ads, no telemetry**, and **no cloud storage by default**.

---

## 🔌 Network Use Cases (Optional)

The app uses network connectivity only in the following optional cases:

### 1. **Open Food Facts Integration**
If you have not opted out, and:
- You search for food by name
- You scan a barcode

The following minimal data is sent to Open Food Facts:
- Your device's external IP address (technical requirement)
- App name and version
- Search string (barcode or product name)

🔗 [Open Food Facts Legal & Terms](https://world.openfoodfacts.org/legal)  
🔗 [Open Food Facts Terms of Use](https://world.openfoodfacts.org/terms-of-use)

---

### 2. **USDA FoodData Central Integration**
If you use the USDA database feature (optional):
- Your device's external IP address
- A shared API key (not unique per user)
- The search string (product name)

🔗 [USDA Privacy Policy](https://www.usda.gov/privacy-policy)

---

### 3. **OCR Label Scanning (Future Feature)**
If you enable local or cloud-based OCR scanning:
- Image data may be processed locally (if using on-device AI)
- If using cloud OCR, image data will be sent to the OCR service only during processing and not retained

We will clearly indicate when data leaves the device.

---

### 4. **Wearable Sync (Google Fit / Apple Health)**
If you connect to Google Fit or Apple Health:
- Only basic health data like steps, heart rate, and sleep data is read
- No personal data is sent back to any server outside of your control

You can disconnect at any time.

---

### 5. **Remote Backups (WebDAV + Encryption)**
If you configure a remote WebDAV server for backups:
- Encrypted backup file
- Server credentials (username/password)
are transmitted to your chosen server.

⚠️ Please note: There is no default server configured — **you or your provider are fully responsible for how this data is handled**.

📘 Learn more about encrypted backups: [Encrypted Backup Guide](https://codeberg.org/epinez/Energize/src/branch/main/docs/backup-encryption/README.md)

---

## 🤖 AI Assistant Integration (Planned)

When available, AI assistant integration (e.g., ChatGPT, Llama, Ollama) will follow these principles:
- Cloud-based models will require explicit opt-in
- Local models will process everything **on-device**
- You will always be able to view, edit, or disable AI features
- No personal data will be saved without consent

---

## 🧑‍⚖️ Our Commitment to You

- We do **not sell or monetize your data**
- We do **not track users or serve ads**
- We aim to keep as much data **local as possible**
- All network use is **optional and clearly explained**
- We respect the licenses and policies of services we integrate with

---

## 📄 License Notice

AfIt builds on the GPLv3-licensed [Energize](https://codeberg.org/epinez/Energize) codebase, which remains under its original license.

All **new code** in AfIt is released under the **Apache License 2.0** — see [LICENSE](LICENSE).

Contributions must also follow these dual licensing terms.

---

## 🙌 Thank You for Reading

Your trust means everything to us. If you have questions or suggestions regarding our privacy practices, please open an issue on GitHub or reach out via our community channels.

Together, we’re building something special — a **private, open, ethical nutrition tracker** that helps people improve their health — not exploit them.
