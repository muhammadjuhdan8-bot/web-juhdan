# DevStudio Landing Page

Situs statis (HTML + Tailwind CDN), siap di-host di GitHub Pages.

## Deploy
1. Buat repo di GitHub, upload seluruh isi folder ini (index.html harus di root).
2. Settings → Pages → Source: **Deploy from a branch** → Branch `main` / folder `/ (root)` → Save.
3. Situs aktif di `https://<username>.github.io/<nama-repo>/`.

## Catatan
- Backend Flask (`app.py`) tidak bisa jalan di GitHub Pages. Tombol "Login Mathify" memakai konstanta `MATHIFY_URL` di bagian bawah `index.html`; isi dengan URL aplikasi yang sudah di-hosting (Render, Railway, dll).
- Jangan ikut meng-upload `.venv` / `.idea`.
