# Python untuk Pemula

Praktikum Materi 02 berdasarkan kursus Python untuk Pemula di Santrikoding.

## Isi Materi

| Bab | Topik | File |
|-----|-------|------|
| 1 | Pengenalan & Instalasi Python | `01-hallo.py` |
| 2 | Variabel dan Tipe Data | `02-variable_*.py` |
| 3 | Operator | `03-operators_*.py` |
| 4 | Kondisi If Else | `04-if.py`, `04-elif.py`, `04-else.py` |
| 5 | Perulangan | `05-loop_*.py` |
| 6 | Lists dan Dictionaries | `06-lists_*.py`, `06-dictionaries_*.py` |
| 7 | Function | `07-function_*.py` |
| 8 | Class dan Object | `08-class_*.py` |
| 9 | PIP dan Virtual Environments | Bukti di `screenshots/` |

Semua kode ada di folder `python pemula/`.
Screenshot hasil eksekusi ada di folder `screenshots/`.

## Cara Menjalankan

1. Clone repositori:
   ```
   git clone https://github.com/RIDANRPLA/python-untuk-pemula.git
   cd python-untuk-pemula
   ```
2. Buat dan aktifkan virtual environment.

   Windows (PowerShell):
   ```
   python -m venv .venv
   .venv\Scripts\activate
   ```
   Linux / WSL:
   ```
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Install dependensi:
   ```
   pip install -r requirements.txt
   ```
4. Jalankan salah satu contoh:
   ```
   python "python pemula/01-hallo.py"
   ```
5. Nonaktifkan virtual environment setelah selesai:
   ```
   deactivate
   ```

## Dependensi

- Flask (dipakai pada contoh Bab 9 beserta dependensinya)
- colorama

## Lingkungan

- Python 3.12 (Windows) dan Python 3.14 (WSL Arch Linux)
- Editor: Visual Studio Code
- Version control: Git dan GitHub

## Catatan

Setiap bab di-commit dan di-push terpisah, sehingga riwayat commit mengikuti urutan materi.