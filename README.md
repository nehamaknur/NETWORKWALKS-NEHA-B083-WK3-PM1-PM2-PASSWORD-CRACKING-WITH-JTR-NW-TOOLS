# PASSWORD CRACKING WITH JTR & NETWORK TOOLS

Building an authorized password recovery and security assessment framework combining offline hash extraction via John the Ripper and browser-based dictionary attacks via Networkwalks utilities.

<p align="center">
  <img src="https://img.shields.io/badge/PROJECT-PASSWORD_CRACKING-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/TARGETS-ENCRYPTED_PDF-orange?style=for-the-badge">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/OS-WINDOWS_%2F_KALI_LINUX-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/TOOLKIT-JTR_%2F_JOHNNY_%2F_NETWORKWALKS-blue?style=for-the-badge">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/SKILL-PASSWORD_RECOVERY_%2F_HASHING-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/INTERNSHIP-NETWORKWALKS_B083-yellowgreen?style=for-the-badge">
</p>
<p align="center">
  <img src="https://img.shields.io/badge/GITHUB-CORTEXNEHA-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/AUTHOR-NEHA_MAKNUR-blueviolet?style=for-the-badge">
</p>

---

## 📋 Table of Contents
* [Tools & Technologies](#-tools--technologies)
* [Methodology & Execution](#-methodology--execution)
  * [Method 1: Password Cracking with John the Ripper & Johnny GUI](#method-1-password-cracking-with-john-the-ripper--johnny-gui)
* [Key Security Concepts & Takeaways](#-key-security-concepts--takeaways)
* [References](#-references)

---

## 🧰 Tools & Technologies

| Tool / Technology | Category | Description |
| :--- | :--- | :--- |
| **John the Ripper (JTR)** | Password Cracker | Open-source multi-format password recovery tool supporting various hashes[cite: 6]. |
| **Johnny GUI** | Graphical Interface | Graphical point-and-click interface wrapper for John the Ripper[cite: 6]. |

---

## ⚙️ Methodology & Execution

### Method 1: Password Cracking with John the Ripper & Johnny GUI

* **JTR & Johnny Download:** Downloaded John the Ripper and the Johnny GUI setup package (`johnny-2.2-win.zip`) from the official Openwall website, mirror links, or the course Google Drive folder.
* **Application Installation:** Located and ran the Johnny installer setup file (`johnny-installer.exe`) from the `Downloads` folder to install Johnny on the Windows PC.
* **Binary Path Configuration:** Configured Johnny by navigating to `Settings` and mapping the executable path to `john.exe` inside the JTR run folder.
* **PDF Hash Extraction:** Uploaded the locked PDF file (`My Locked PDF1.pdf`) to an online PDF hash extractor to obtain the string starting with `$pdf$`.
* **Hash File Preparation:** Pasted the extracted hash into Notepad, ensured no extra leading characters remained, and saved it as `hash1.txt`.
* **Attack Initialization:** Opened Johnny, selected `Open password file` to load `hash1.txt`, and initiated the process using `Start new attack`.
* **Credential Recovery:** Retrieved and copied the recovered cleartext password (`password1`) to successfully unlock and view the PDF document.

## 📌 Key Security Concepts & Takeaways
* **Encryption vs. Hashing:** Encryption is a two-way reversible function for data protection, whereas hashing is a one-way mathematical function used for verification[cite: 6].
* **Password Vulnerability:** Short or common patterns (such as dictionary words or simple character strings) can be compromised in minutes via automated dictionary attacks[cite: 6].

---

## 🔗 References
* GitHub Repository: [github.com/ketankamblee/-Password-Cracking](https://github.com/ketankamblee/-Password-Cracking)
* Networkwalks Training Academy: [www.networkwalks.com](https://www.networkwalks.com)[cite: 6]
