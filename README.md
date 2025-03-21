# Assignment Pemrograman Web - Parsing File

## Deskripsi

Proyek ini merupakan tugas pemrograman web menggunakan bahasa Go yang mengimplementasikan parsing file dengan template HTML. Aplikasi ini berfungsi sebagai web server sederhana yang menangani beberapa endpoint.

## Fitur

- Menggunakan `html/template` untuk render halaman web.
- Menyediakan beberapa route:
  - `/` -> Halaman utama
  - `/about` -> Halaman About
  - `/contact` -> Halaman Contact
  - `/login` -> Halaman Login
- Menggunakan `http.ListenAndServe` untuk menjalankan server pada port 8080.

## Struktur Direktori

```
D:/Golang/belajar-golang/pertemuan3/
│-- templates/ (folder berisi file HTML template)
│-- go.mod (file modul Go)
│-- go_template.go (kode utama aplikasi)
│-- README.md (dokumentasi proyek ini)
│-- Screenshot 2025-03-18 231008.png
│-- Screenshot 2025-03-18 231034.png
│-- Screenshot 2025-03-18 231101.png
│-- Screenshot 2025-03-18 231117.png
│-- Screenshot 2025-03-18 231219.png
```

## Cara Menjalankan

1. Clone repositori:
   ```sh
   git clone https://github.com/najimuhammad67/asigmentpemrogamanweb-parsingfile.git
   ```
2. Masuk ke direktori proyek:
   ```sh
   cd asigmentpemrogamanweb-parsingfile
   ```
3. Jalankan server:
   ```sh
   go run go_template.go
   ```
4. Buka browser dan akses `http://localhost:8080`

## Screenshot

Berikut beberapa tampilan dari aplikasi:

- ![Screenshot 1](Screenshot%202025-03-18%20231008.png)
- ![Screenshot 2](Screenshot%202025-03-18%20231034.png)
- ![Screenshot 3](Screenshot%202025-03-18%20231101.png)
- ![Screenshot 4](Screenshot%202025-03-18%20231117.png)
- ![Screenshot 5](Screenshot%202025-03-18%20231219.png)

## Lisensi

Proyek ini dibuat untuk keperluan pembelajaran dan tidak memiliki lisensi resmi.
