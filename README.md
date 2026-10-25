# GDG Cloud Thessaloniki — Meetup Presentations & Code 🇬🇷 ☁️

[![Community Page](https://img.shields.io/badge/GDG-Community_Page-4285F4?logo=google&logoColor=white)](https://gdg.community.dev/gdg-cloud-thessaloniki/)
[![Meetup](https://img.shields.io/badge/Meetup-GDG_Cloud_Thessaloniki-ED1C40?logo=meetup&logoColor=white)](https://www.meetup.com/gdg-cloud-thessaloniki/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Follow_Us-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/company/gdg-cloud-thessaloniki)

Καλωσήρθατε στο αποθετήριο παρουσιάσεων και κώδικα της κοινότητας **GDG Cloud Thessaloniki**!  
Welcome to the presentations and code repository of the **GDG Cloud Thessaloniki** community!

---

## 📖 Σχετικά με το Αποθετήριο / About this Repository

### 🇬🇷 Ελληνικά
Αυτό το αποθετήριο φιλοξενεί το υλικό από τις συναντήσεις, τα workshops και τα events του GDG Cloud Thessaloniki:
- **Διαφάνειες & Παρουσιάσεις (Slides):** Αρχεία σε μορφή PDF / PPTX από τους ομιλητές της κοινότητας.
- **Κώδικας & Demos:** Πηγαίος κώδικας, παραδείγματα εφαρμογών, Jupyter notebooks και αρχεία ρυθμίσεων (IaC, Docker, κ.ά.) που παρουσιάστηκαν στις εκδηλώσεις.
- **Σημειώσεις & Πηγές:** Χρήσιμοι σύνδεσμοι, βιβλιογραφία και επιπλέον υλικό μελέτης.

### 🇬🇧 English
This repository hosts material from GDG Cloud Thessaloniki meetups, workshops, and community events:
- **Slide Decks & Presentations:** PDF / PPTX files delivered by community speakers.
- **Code & Demos:** Source code, demo projects, Jupyter notebooks, and configuration files (IaC, Docker, etc.) showcased during sessions.
- **Notes & Resources:** Useful links, references, and additional learning materials.

---

## 📂 Δομή Φακέλων / Repository Structure

Κάθε εκδήλωση οργανώνεται σε δικό της αυτόνομο φάκελο με βάση την ημερομηνία διεξαγωγής και τον τίτλο της εκδήλωσης:

```text
meetup-presentations/
│
├── YYYY-MM-DD <Event-Title>/
│   ├── README.md                                  # (Προαιρετικό) Περιγραφή ομιλιών, demos & οδηγίες εκτέλεσης
│   ├── <Speaker-Name> - <Talk-Title>.pdf          # Διαφάνειες σε PDF
│   ├── <Speaker-Name> - <Talk-Title>.pptx         # Διαφάνειες σε PPTX
│   └── code/                                      # Συνοδευτικός κώδικας, scripts, Dockerfiles κ.λπ.
│       ├── demo-app/
│       └── README.md
│
└── README.md                                      # Το παρόν αρχείο
```

---

## 📅 Κατάλογος Παρουσιάσεων / Presentations Archive

| Ημερομηνία / Date | Εκδήλωση / Event | Ομιλητής / Speaker | Θέμα / Topic | Υλικό / Materials |
| :--- | :--- | :--- | :--- | :--- |
| **2026-10-19** | Code, Community & AI | Efstathios Iosifidis | Code, Community & AI | [📁 Φάκελος / Folder](./2026-10-19%20Code,%20Community%20%26%20AI) <br> • [PDF](./2026-10-19%20Code,%20Community%20%26%20AI/Efstathios%20Iosifidis%20-%20Code,%20Community%20%26%20AI.pdf) <br> • [PPTX](./2026-10-19%20Code,%20Community%20%26%20AI/Efstathios%20Iosifidis%20-%20Code,%20Community%20%26%20AI.pptx) |

---

## 🤝 Οδηγίες για Ομιλητές & Συνεισφορά / Speaker Guidelines & Contributing

### 🇬🇷 Ελληνικά
Εάν ήσασταν ομιλητής σε κάποιο από τα meetups μας ή θέλετε να προσθέσετε διορθώσεις και βελτιώσεις στον κώδικα:

1. **Δημιουργία Branch / Fork:** Κάντε fork το αποθετήριο ή δημιουργήστε νέο branch (`git checkout -b feature/event-YYYY-MM-DD`).
2. **Ονοματοδοσία Φακέλου:** Δημιουργήστε φάκελο με τη μορφή `YYYY-MM-DD <Τίτλος Εκδήλωσης>`.
3. **Ονοματοδοσία Παρουσίασης:** Χρησιμοποιήστε το format `<Όνομα Ομιλητή> - <Τίτλος Παρουσίασης>.(pdf|pptx)`.
4. **Συνοδευτικός Κώδικας:** 
   - Εάν υπάρχει κώδικας, τοποθετήστε τον σε υποφάκελο (π.χ. `code/` ή `demo/`).
   - Συμπεριλάβετε ένα σύντομο `README.md` με προαπαιτούμενα και οδηγίες εκτέλεσης (π.χ. `npm install`, `python -m venv ...`, `docker compose up`).
5. ⚠️ **Ασφάλεια & Secrets (ΠΟΛΥ ΣΗΜΑΝΤΙΚΟ):**
   - **ΜΗΝ ανεβάζετε ποτέ** πραγματικά API keys, μυστικά (secrets), κωδικούς πρόσβασης ή `.env` αρχεία.
   - Χρησιμοποιείτε αρχεία `.env.example` με dummy τιμές.
6. **Pull Request:** Ανοίξτε ένα Pull Request με περιγραφή της ομιλίας σας και των αρχείων που προστίθενται.

### 🇬🇧 English
If you were a speaker at one of our meetups or would like to contribute improvements and code samples:

1. **Create Branch / Fork:** Fork the repository or create a new branch (`git checkout -b feature/event-YYYY-MM-DD`).
2. **Folder Naming:** Create a directory following the format `YYYY-MM-DD <Event-Title>`.
3. **Presentation Naming:** Use the format `<Speaker-Name> - <Talk-Title>.(pdf|pptx)`.
4. **Accompanying Code:** 
   - Place code or demos in a dedicated subfolder (e.g., `code/` or `demo/`).
   - Include a brief `README.md` with prerequisites and run instructions (e.g., `npm install`, `python -m venv ...`, `docker compose up`).
5. ⚠️ **Security & Secrets (CRITICAL):**
   - **NEVER commit** real API keys, secrets, credentials, or `.env` files.
   - Always use `.env.example` files with dummy values.
6. **Pull Request:** Open a Pull Request describing your session and the files included.

---

## 🌐 Σύνδεσμοι Κοινότητας / Community Links

- 📅 **Google Developer Groups Portal:** [gdg.community.dev/gdg-cloud-thessaloniki](https://gdg.community.dev/gdg-cloud-thessaloniki/)
- 📅 **Meetup.com:** [meetup.com/gdg-cloud-thessaloniki](https://www.meetup.com/gdg-cloud-thessaloniki/)
- 💼 **LinkedIn:** [linkedin.com/company/gdg-cloud-thessaloniki](https://www.linkedin.com/company/gdg-cloud-thessaloniki)
- 🔒 **Security Policy:** [SECURITY.md](https://github.com/gdg-cloud-thessaloniki/.github/blob/main/SECURITY.md)

---

## ⚠️ Αποποίηση Ευθύνης Κώδικα / Code & Safety Disclaimer

### 🇬🇷 Ελληνικά
- **Εκπαιδευτικός Σκοπός:** Όλος ο κώδικας, τα σενάρια (scripts) και οι παρουσιάσεις που φιλοξενούνται στο αποθετήριο προορίζονται **αποκλειστικά για εκπαιδευτικούς σκοπούς, μελέτη και πειραματισμό**. Παρέχονται «ως έχουν» (AS IS) και η εκτέλεσή τους γίνεται με δική σας ευθύνη.
- **Αναφορά Ευπαθειών:** Βρήκατε εκτεθειμένα διαπιστευτήρια ή ευπάθεια ασφαλείας; **Μην ανοίξετε δημόσιο issue.** Ακολουθήστε τις οδηγίες στην [Πολιτική Ασφάλειας (SECURITY.md)](https://github.com/gdg-cloud-thessaloniki/.github/blob/main/SECURITY.md).

### 🇬🇧 English
- **Educational Purpose:** All source code, configuration scripts, and presentation decks hosted across this repository are provided **strictly for educational, research, and experimental purposes**. Everything is provided "AS IS", and execution is at your own risk.
- **Vulnerability Reporting:** Found an exposed secret or security vulnerability? **Please do not open a public issue.** See our [Security Policy (SECURITY.md)](https://github.com/gdg-cloud-thessaloniki/.github/blob/main/SECURITY.md).

---

## 📌 GDG Disclaimer

GDG Cloud Thessaloniki is an independent group; our activities and the opinions expressed here should in no way be linked to Google, the corporation. To learn more about the GDG program, visit [developers.google.com/community/gdg](https://developers.google.com/community/gdg/).

`#Google` `#GDG` `#GDGCloudThessaloniki` `#Thessaloniki` `#TechThessaloniki` `#CloudNative` `#DevOps` `#BuildWithAI` `#OpenSource`
