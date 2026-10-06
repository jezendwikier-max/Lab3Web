# Lab3Web
1. Eksperimen Mengubah dan Menambah Properti CSS
   Eksperimen ini membuktikan bahwa penambahan properti CSS seperti CSS Box Model (padding, border-radius), Visual Effects (box-shadow), Typography (letter-spacing, text-transform), dan Interactivity (transition, :hover) secara signifikan meningkatkan estetika dan pengalaman pengguna (user experience) dibandingkan tampilan CSS dasar yang statis.
   <img width="1920" height="1080" alt="Screenshot (134)" src="https://github.com/user-attachments/assets/a3d6284e-4270-45fc-96d2-7f4024b63864" />
2. Perbedaan Pendeklarasian h1 {...} dan #intro h1 {...}
   h1 {...} (Type Selector / Tag Selector):
   Penjelasan: Mengaplikasikan gaya CSS ke semua elemen <h1> yang ada di dalam seluruh dokumen HTML tanpa terkecuali.
   Tingkat Spesifisitas (Specificity): Rendah (0, 0, 0, 1).
   #intro h1 {...} (Descendant Selector dengan ID):
   Penjelasan: Hanya mengaplikasikan gaya CSS khusus untuk elemen <h1> yang berada di dalam elemen yang memiliki id="intro".
   Tingkat Spesifisitas (Specificity): Tinggi (0, 1, 0, 1).
   <img width="1920" height="1080" alt="Screenshot (135)" src="https://github.com/user-attachments/assets/6407ccd9-050f-4e91-91bf-5bdfaebfe801" />

3. Urutan Prioritas Penerapan CSS (Internal, Eksternal, dan Inline)
   Jika suatu elemen diatur menggunakan Inline CSS, Internal CSS, dan Eksternal CSS sekaligus, aturan yang akan ditampilkan oleh browser adalah Inline CSS (dengan syarat tidak ada deklarasi !important).
   Urutan Hirarki Prioritas (dari yang tertinggi ke terendah):
   Inline CSS (ditulis langsung pada atribut style="" di tag HTML)
   Internal CSS (ditulis di dalam tag <style> pada <head>) / Eksternal CSS (dihubungkan via <link>) — Apabila spesifisitasnya sama, yang ditulis paling akhir/bawah di kode yang akan menang dan terakhir adalah
   Default Browser.
   <img width="1920" height="1080" alt="Screenshot (136)" src="https://github.com/user-attachments/assets/9d3c9852-82a0-4ddc-b657-0869fcb6831a" />
4. Prioritas Selector ID vs Class
   Deklarasi CSS yang akan ditampilkan oleh browser adalah deklarasi dari ID Selector (#paragraf-1).
   Penjelasan: Hierarki Spesifisitas (Specificity): Browser menentukan aturan mana yang diterapkan berdasarkan bobot/tingkat spesifisitas selector: ID Selector (#): Memiliki nilai spesifisitas 0, 1, 0, 0 (Sangat Tinggi). Class Selector (.): Memiliki nilai spesifisitas 0, 0, 1, 0 (Lebih Rendah).
   Karena nilai spesifisitas ID Selector lebih tinggi dibandingkan Class Selector, maka properti yang bertabrakan (seperti color dan font-size) akan memenangkan aturan dari ID Selector.
   <img width="1920" height="1080" alt="Screenshot (138)" src="https://github.com/user-attachments/assets/4ff66831-e6de-4d1d-a025-2be4bc16f47e" />
   <img width="1920" height="1080" alt="Screenshot (139)" src="https://github.com/user-attachments/assets/371fae2c-25cf-49c4-a63c-e8d02f3d953a" />

