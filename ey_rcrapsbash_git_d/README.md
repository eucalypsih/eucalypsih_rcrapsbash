# ey_rcrapsbash_git



- `'!/*'` (sembunyikan file root)
  Tanda seru `!` berarti negasi atau pengecualian. Garis miring `/` di awal merujuk pada direktori utama (root). Perintah ini menginstruksikan Git untuk menyembunyikan semua file lepasan di folder utama.


- `git sparse-checkout add 'folder_baru/'`: Menambahkan `'folder_baru/'` ke dalam daftar. Aturan `'!/*'` (sembunyikan file root) yang Anda buat sebelumnya **tetap aktif**.

- `git sparse-checkout set 'folder_baru/'`: Menghapus seluruh aturan lama. Akibatnya, aturan `'!/*'` hilang, dan file di root directory akan otomatis terunduh/muncul kembali semua.

Perintah `add` akan **mempertahankan** aturan filter lama Anda (`!/*`) dan hanya **menambahkan** jalur (path) baru ke dalam daftar unduhan. Jika Anda menggunakan `set`, aturan lama Anda (`!/*`) akan terhapus dan ditimpa.

---

- `git sparse-checkout set --no-cone '!/*' 'cmake_cmakelists/cmake_qc/'`: Memasang kunci filter terlebih dahulu. Di sini Git diperintahkan untuk mengabaikan isi root (`!/*`) dan hanya menerima isi folder target.


- `--no-checkout` (`-n`)

- `--no-cone`
  diterapkan sebelum melakukan proses checkout.
  Mengaktifkan pembacaan berbasis baris per baris (*wildcard pattern*) seperti aturan pada .gitignore.

- `--sparse` pada saat kloning bertujuan untuk menyiapkan repositori dengan hanya menyertakan file yang ada di direktori utama (root) terlebih dahulu.





<br>
