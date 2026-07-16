# e-Relief STS

Aplikasi statik mesra GitHub Pages untuk menjana jadual guru ganti Sekolah Tinggi Segamat.

## Cara muat naik ke GitHub
1. Cipta repository baharu, contoh `e-relief-sts`.
2. Upload semua fail dan folder dalam pakej ini ke bahagian utama repository.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch**, branch `main`, folder `/root`, kemudian **Save**.
5. Tunggu pautan GitHub Pages dipaparkan.

## Penggunaan kali pertama
1. Klik **Tetapan**.
2. Tetapkan guru yang memegang jawatan Pengetua, GPK 1, GPK HEM, GPK Kokurikulum dan GKMP.
3. Pilih tarikh dan hari.
4. Masukkan semua guru tidak hadir.
5. Klik **Jana Relief Automatik**.
6. Hidupkan **Mod manual** untuk menukar guru ganti.
7. Klik **Preview / Cetak PDF**, kemudian pilih `Save as PDF`.

## Catatan
- Jadual guru telah diekstrak daripada fail `Relief STS (220626).mdb`.
- Data tetapan dan jadual relief disimpan dalam `localStorage` pelayar.
- Aplikasi tidak memerlukan Netlify, server atau pangkalan data luaran.
- Untuk berkongsi rekod antara banyak peranti, versi seterusnya boleh disambungkan kepada Google Sheet melalui Apps Script.
