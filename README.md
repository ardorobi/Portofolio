# Ardo Portfolio — GitHub Pages

Template portfolio statis untuk GitHub Pages.

## Cara upload paling gampang
1. Extract ZIP ini.
2. Di repository GitHub kamu, klik **uploading an existing file**.
3. Upload:
   - index.html
   - style.css
   - script.js
4. Klik **Commit changes**.
5. Masuk ke **Settings → Pages**.
6. Source: **Deploy from a branch**
7. Branch: **main**
8. Folder: **/(root)**
9. Save.

## Yang perlu kamu ganti sebelum publish
Di `index.html`:
- `your@email.com`
- link LinkedIn
- link Behance
- judul / deskripsi project
- placeholder project card dengan thumbnail asli

## Cara menambahkan thumbnail
Taruh file gambar di folder `assets`, contoh:
`assets/project-01.jpg`

Lalu ganti:

```html
<div class="project-visual placeholder"> ... </div>
```

menjadi:

```html
<div class="project-visual">
  <img src="assets/project-01.jpg" alt="Project title">
</div>
```

Lalu tambahkan ke `style.css`:

```css
.project-visual img{
  width:100%;
  height:100%;
  object-fit:cover;
  display:block;
}
```

## Folder Drive yang sudah terhubung
- Start Here
- Selected Works
- Motion
- Graphic
- 3D & AI
- Other Creative Work

Jadi website sudah bisa dipakai sebagai landing page portfolio, sementara detail project tetap dibuka dari Google Drive.
