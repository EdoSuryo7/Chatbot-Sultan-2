# AI Chatbot Kasultanan Bulakan 🧠

Sebuah chatbot interaktif dengan tema kerajaan yang dibangun menggunakan Streamlit dan OpenRouter API.

![Preview](https://img.shields.io/badge/Platform-Streamlit-FF4B4B)
![Preview](https://img.shields.io/badge/Language-Python-3776AB)

## Fitur

- 👑 Tampilan dengan tema kerajaan yang elegan
- 💬 Interface chat yang interaktif seperti WhatsApp
- 🔄 Riwayat chat yang tersimpan secara permanen
- ⚡ Respon real-time dari AI
- 👤 Avatar untuk pengguna dan chatbot
- 🕒 Timestamp untuk setiap pesan
- 📱 Tampilan responsif untuk berbagai ukuran layar

## Teknologi yang Digunakan

- **Frontend**: Streamlit
- **AI Model**: DeepSeek Chat via OpenRouter
- **Penyimpanan**: JSON (local storage)
- **Styling**: Custom CSS

## Cara Menjalankan

1. Pastikan Python sudah terinstall di sistem Anda
2. Install dependencies yang diperlukan:
   ```bash
   pip install streamlit requests
   ```
3. Atur API key OpenRouter Anda di file `chatbot.py`
4. Jalankan aplikasi:
   ```bash
   streamlit run chatbot.py
   ```

## Struktur Project

```
fun_project_2_REAPYTHON1GXVBT/
├── chatbot.py          # File utama aplikasi
├── chat_history.json   # Penyimpanan riwayat chat
└── README.md          # Dokumentasi project
```

## Fitur UI

- Header dengan latar belakang merah royal
- Background chat dengan pattern kerajaan
- Bubble chat user di kanan (biru muda)
- Bubble chat AI di kiri (merah muda)
- Avatar pengguna dan AI
- Timestamp di setiap pesan
- Input box yang tetap di bagian bawah

## Konfigurasi

Beberapa pengaturan yang bisa dimodifikasi di `chatbot.py`:

- `MODEL`: Model AI yang digunakan
- `HEADERS`: Konfigurasi API
- Styling CSS untuk mengubah tampilan
- Format timestamp

## Kontribusi

Silakan berkontribusi dengan membuat pull request atau melaporkan issues.

## Lisensi

Project ini bersifat open source dan tersedia untuk digunakan secara bebas.

---
Dibuat dengan ❤️ untuk Kasultanan Bulakan
