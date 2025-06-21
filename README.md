# 🔬 JupyterLite Deployment

Αυτός ο φάκελος περιέχει το περιβάλλον **JupyterLite** που ενσωματώνεται στο [nlholden.github.io](https://nlholden.github.io). Μέσα από αυτό μπορούν οι επισκέπτες να εκτελούν Python κώδικα απευθείας από τον browser, χωρίς εγκατάσταση.

> ✅ Χρησιμοποιεί τεχνολογία **WebAssembly**, ώστε όλα να τρέχουν client-side — καμία ανάγκη για server ή backend.

---

## 🚀 Live Demo

🔗 [**Άνοιξε το JupyterLite στο browser**](https://nlholden.github.io/jupyterlite-deployment/lab/index.html)

---

## 📁 Περιεχόμενα

```bash
jupyterlite-deployment/
├── content/               # Jupyter notebooks για κάθε blog post
├── index.html             # Landing page του JupyterLite
├── lab/                   # Web build του JupyterLite (JupyterLab-like UI)
├── retro/                 # Retro UI (πιο απλό interface)
├── lite.json              # Config αρχείο του JupyterLite
└── requirements.txt       # Αν απαιτούνται εξαρτήσεις (π.χ. για local dev)
