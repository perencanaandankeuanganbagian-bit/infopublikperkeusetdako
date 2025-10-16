Publikasi Informasi Publik - Bagian Perencanaan & Keuangan (Static Site)

Isi paket:
- index.html
- logo-pemkot-parepare.png  (placeholder — ganti dengan versi resmi jika ada)
- /images/slide1.jpg, slide2.jpg, slide3.jpg (placeholder slider images)

Panduan singkat — Deploy ke Netlify (manual drag & drop):
1. Buka https://app.netlify.com and login.
2. On the Netlify dashboard click "Add new site" -> "Deploy manually".
3. Drag & drop the ZIP file (publikasi-informasi-publik.zip) into the upload area OR
   drag the contents (index.html + assets) into the upload area.
4. Wait a minute. Netlify will assign a default URL (e.g. https://something.netlify.app).
5. (Optional) Add a custom domain via Site Settings -> Domain management.

Catatan:
- Ini adalah situs statis sederhana (HTML/CSS/JS). Untuk mengubah teks, edit index.html.
- Untuk dokumen: letakkan file PDF di folder 'docs/' dan tambahkan tautan di tabel dokumen.
- Jika ingin integrasi CMS atau fitur dinamis (upload dokumen via web), sarankan menggunakan Netlify CMS, Strapi, atau Vercel + headless CMS.
