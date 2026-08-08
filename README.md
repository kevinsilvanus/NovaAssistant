# ✨ Nova Assistant

> Teman ngobrol harian yang siap bantu beresin kerjaan, nyari ide, atau sekadar nemenin kamu mikir.  
> *Dibuat oleh **Kevin***

---

## 💬 Kenapa Nova Assistant?

Nova Assistant didesain buat kamu yang butuh asisten harian tanpa harus ngobrol sama bot yang kaku dan formal. Tampilannya simpel, bersih, dan rasanya kaya lagi kirim pesan biasa di aplikasi *chatting*.

Beberapa hal yang bisa kamu tanyain ke Nova:
- 💡 **Sumpel ide kreatif:** Nyari topik konten, judul presentasi, atau ide proyek.
- 📝 **Bantu nulis:** Bikin draf email, pesan penting, sampai caption medsos.
- 📅 **Susun jadwal:** Rapiin rencana harian atau urutan tugas biar nggak pusing.
- 📖 **Rangkum bacaan:** Nyari poin-poin penting dari materi yang kepanjangan.

---

## 🛠️ Apa Saja di Belakang Layar?

Aplikasi ini berjalan dengan beberapa komponen utama:

- **Python & Streamlit:** Buat pondasi utama dan tampilan antarmuka (UI) berbaju *custom CSS*.
- **Google Gemini API (`gemini-2.5-flash`):** Otak dibalik jawaban-jawaban Nova.
- **Ngrok:** Buat jembatan biar aplikasinya bisa diakses lewat link publik.
- **Google Colab Secrets:** Tempat nyimpen Kunci API biar tetep aman dan nggak bocor.

---

## 🔑 Kunci Akses (Colab Secrets)

Biar aplikasinya jalan, pastikan dua kunci ini udah disimpen di menu **Secrets (🔑)** Google Colab:

| Nama Secret | Fungsi |
| :--- | :--- |
| `GEMINI` | Kunci API dari Google AI Studio |
| `NGROK` | Token otentikasi dari Ngrok |

---

## 🚀 Cara Menjalankan

1. Buka berkas notebook di **Google Colab**.
2. Pastikan izin akses **Secrets** untuk `GEMINI` dan `NGROK` sudah aktif.
3. Jalankan semua *cell* secara berurutan (dari Cell 1 sampai Cell 4).
4. Klik link Ngrok yang muncul di Cell 4 (`https://xxxx.ngrok-free.app`), dan Nova siap diajak ngobrol!

---

<p align="center">
  <b>Nova Assistant by Kevin</b>
</p>
