## Library Yang Perlu Di Install

1. **install PIL**
   ```bash
   pip install pillow
   ```

## Fragile-Watermarking

Program ini mengimplementasikan Fragile Watermarking menggunakan metode Least Significant Bit (LSB).

### Cara Menggunakannya

1. **Insert Image**
   Jalankan perintah ini pada terminal:

   ```bash
   python fragilewatermark.py host.jpg itera.png <nama_file_bebas_untuk_output>
   ```

2. **Mengekstrak Fragile-Watermarking:**
   Untuk mengekstrak fragile watermarking dari gambar, jalankan perintah berikut:
   ```bash
   python fragilewatermark.py <nama_gambar_yang_sudah_diwatermark> <nama_file_bebas_untuk_output_ekstraksi>
   ```
