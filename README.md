# Tugas Tambahan Nilai UTS - Pemrograman Web (Pyramid Framework)

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Framework](https://img.shields.io/badge/Framework-Pyramid-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

Repositori ini berisi implementasi dan analisis dari **15 Topik Tutorial Resmi Pyramid Web Framework**. Tugas ini dikerjakan sebagai syarat pemenuhan Tugas Tambahan Nilai UTS mata kuliah Pemrograman Web.

## 👤 Identitas Mahasiswa

| Informasi | Detail |
| :--- | :--- |
| **Nama** | **Garis Rayya Rabbani** |
| **NIM** | **123140018** |
| **Kelas** | **RA** |
| **Prodi** | Teknik Informatika - ITERA |

---

## 📂 Daftar Percobaan (15 Topik)

Setiap folder di dalam repositori ini mewakili satu langkah tutorial yang berdiri sendiri (*standalone*), lengkap dengan kode program dan analisis (`README.md` per folder).

1.  **[01_single_file](./01_single_file)**: Aplikasi web minimal dalam satu file Python.
2.  **[02_package](./02_package)**: Mengubah struktur aplikasi menjadi Python Package.
3.  **[03_configuration](./03_configuration)**: Konfigurasi aplikasi menggunakan file `.ini`.
4.  **[04_debugtoolbar](./04_debugtoolbar)**: Mengintegrasikan alat debugging `pyramid_debugtoolbar`.
5.  **[05_unit_testing](./05_unit_testing)**: Penerapan *Unit Testing* dasar dengan `pytest`.
6.  **[06_functional_testing](./06_functional_testing)**: Penerapan *Functional Testing* menggunakan `WebTest`.
7.  **[07_basic_views](./07_basic_views)**: Pemisahan logika view ke file terpisah dengan konfigurasi deklaratif.
8.  **[08_templating](./08_templating)**: Pemisahan HTML dari Python menggunakan Template Engine (Chameleon).
9.  **[09_view_classes](./09_view_classes)**: Mengorganisir views menggunakan Class (Class-based Views).
10. **[10_request_response](./10_request_response)**: Manipulasi objek `Request` dan `Response` serta HTTP Redirect.
11. **[11_routing](./11_routing)**: Menggunakan URL Dispatch dinamis (contoh: `/howdy/{first}/{last}`).
12. **[12_jinja2](./12_jinja2)**: Mengganti template engine ke Jinja2.
13. **[13_static_assets](./13_static_assets)**: Menyajikan file statis (CSS/Gambar) melalui `add_static_view`.
14. **[14_json](./14_json)**: Membuat endpoint API dengan JSON Renderer untuk kebutuhan AJAX.
15. **[15_more_view_classes](./15_more_view_classes)**: Implementasi logika kompleks (Form Handling) menggunakan View Classes.

---

## 🚀 Cara Menjalankan (How to Run)

Karena setiap folder adalah *package* Python yang terpisah, Anda perlu menginstallnya dalam mode *editable* setiap kali berpindah topik.

### Prasyarat
* Python 3.x terinstall.
* Virtual Environment sudah aktif.

### Langkah Umum
Misalnya ingin menjalankan **Topik 15**:

1.  Masuk ke folder topik:
    ```bash
    cd 15_more_view_classes
    ```

2.  **Wajib:** Install package dalam mode development (agar dependensi sesuai):
    ```bash
    pip install -e .
    ```
    *(Atau `pip install -e ".[dev]"` jika ingin menjalankan testing)*

3.  Jalankan server:
    ```bash
    pserve development.ini --reload
    ```
    *(Atau `python -m pyramid.scripts.pserve development.ini --reload` jika pserve tidak terdeteksi)*

4.  Buka browser di: `http://localhost:6543`

5.  Untuk menjalankan Testing:
    ```bash
    pytest tutorial/tests.py -q
    ```

---

## 📝 Catatan Analisis

Setiap folder memiliki file `README.md` masing-masing yang berisi:
* Penjelasan singkat tentang topik tersebut.
* Analisis teknis mengenai apa yang dipelajari dan kode yang diimplementasikan.

---

**Terima Kasih.**
