# eucalypsih_rcrapsbash

```bash
owner="eucalypsih";repo="eucalypsih_rcrapsbash";git clone -q --filter=blob:none --no-checkout git@github.com:${owner}/${repo}.git && sleep 0.5 && cd $repo && sleep 0.5 && un="eucalypsih";ue="eucalypsih@gmail.com";git config user.name "$un" && sleep 0.5 && git config user.email "$ue" && sleep 0.5 && git config gpg.format ssh && sleep 0.5 && git config user.signingkey ~/.ssh/id_rsa.pub && sleep 0.5 && git config commit.gpgsign true && sleep 0.5 && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers && sleep 0.5 && git sparse-checkout set --no-cone '!/*' && sleep 0.5 && git checkout main

```
`owner="eucalypsih";repo="eucalypsih_rcrapsbash";git clone -q --filter=blob:none --no-checkout git@github.com:${owner}/${repo}.git && sleep 0.5 && cd $repo && sleep 0.5 && un="eucalypsih";ue="eucalypsih@gmail.com";git config user.name "$un" && sleep 0.5 && git config user.email "$ue" && sleep 0.5 && git config gpg.format ssh && sleep 0.5 && git config user.signingkey ~/.ssh/id_rsa.pub && sleep 0.5 && git config commit.gpgsign true && sleep 0.5 && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers && sleep 0.5 && git sparse-checkout set --no-cone '!/*' && sleep 0.5 && git checkout main
`

---

```bash
owner="eucalypsih";repo="eucalypsih_rcrapsbash";git clone -q --filter=blob:none --no-checkout git@github.com:${owner}/${repo}.git && sleep 0.5 && cd $repo && sleep 0.5 && un="eucalypsih";ue="eucalypsih@gmail.com";git checkout main && sleep 0.5 && git config user.name "$un" && sleep 0.5 && git config user.email "$ue" && sleep 0.5 && git config gpg.format ssh && sleep 0.5 && git config user.signingkey ~/.ssh/id_rsa.pub && sleep 0.5 && git config commit.gpgsign true && sleep 0.5 && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers && git sparse-checkout set --no-cone "cmake_cmakelists/cmake_qc/" && git checkout

```
`owner="eucalypsih";repo="eucalypsih_rcrapsbash";git clone -q --filter=blob:none --no-checkout git@github.com:${owner}/${repo}.git && sleep 0.5 && cd $repo && sleep 0.5 && un="eucalypsih";ue="eucalypsih@gmail.com";git checkout main && sleep 0.5 && git config user.name "$un" && sleep 0.5 && git config user.email "$ue" && sleep 0.5 && git config gpg.format ssh && sleep 0.5 && git config user.signingkey ~/.ssh/id_rsa.pub && sleep 0.5 && git config commit.gpgsign true && sleep 0.5 && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers && git sparse-checkout set --no-cone "cmake_cmakelists/cmake_qc/" && git checkout
`
- `git clone ... --no-checkout`: Menggantikan `--sparse`. Perintah ini memastikan folder hasil klon benar-benar kosong (hanya berisi folder tersembunyi `.git`).
- `git sparse-checkout set --no-cone "!/*" "cmake_cmakelists/cmake_qc/"`: Mendaftarkan aturan filter ke dalam sistem Git sebelum file fisik dipanggil.
- `&& git checkout`: Ditambahkan di paling akhir perintah. Langkah ini wajib dilakukan karena kita menggunakan `--no-checkout` di awal. Perintah ini akan memicu Git untuk mengisi direktori kerja Anda **hanya** dengan file yang lolos dari filter aturan sparse-checkout yang sudah kita pasang.
---



git checkout -b main
```bash
owner="eucalypsih";repo="eucalypsih_rcrapsbash";git clone -q --filter=blob:none --sparse git@github.com:${owner}/${repo}.git && sleep 0.5 && cd $repo && sleep 0.5 && un="eucalypsih";ue="eucalypsih@gmail.com";git checkout -b main && sleep 0.5 && git config user.name "$un" && sleep 0.5 && git config user.email "$ue" && sleep 0.5 && git config gpg.format ssh && sleep 0.5 && git config user.signingkey ~/.ssh/id_rsa.pub && sleep 0.5 && git config commit.gpgsign true && sleep 0.5 && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers
```
`owner="eucalypsih";repo="eucalypsih_rcrapsbash";git clone -q --filter=blob:none --sparse git@github.com:${owner}/${repo}.git && sleep 0.5 && cd $repo && sleep 0.5 && un="eucalypsih";ue="eucalypsih@gmail.com";git checkout -b main && sleep 0.5 && git config user.name "$un" && sleep 0.5 && git config user.email "$ue" && sleep 0.5 && git config gpg.format ssh && sleep 0.5 && git config user.signingkey ~/.ssh/id_rsa.pub && sleep 0.5 && git config commit.gpgsign true && sleep 0.5 && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers`

---


```
owner="eucalypsih";repo="eucalypsih_rcrapsbash";git clone -q --filter=blob:none --sparse git@github.com:${owner}/${repo}.git && sleep 0.5 && cd $repo && sleep 0.5 && un="eucalypsih";ue="eucalypsih@gmail.com";git checkout main && sleep 0.5 && git config user.name "$un" && sleep 0.5 && git config user.email "$ue" && sleep 0.5 && git config gpg.format ssh && sleep 0.5 && git config user.signingkey ~/.ssh/id_rsa.pub && sleep 0.5 && git config commit.gpgsign true && sleep 0.5 && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers
```
`owner="eucalypsih";repo="eucalypsih_rcrapsbash";git clone -q --filter=blob:none --sparse git@github.com:${owner}/${repo}.git && sleep 0.5 && cd $repo && sleep 0.5 && un="eucalypsih";ue="eucalypsih@gmail.com";git checkout main && sleep 0.5 && git config user.name "$un" && sleep 0.5 && git config user.email "$ue" && sleep 0.5 && git config gpg.format ssh && sleep 0.5 && git config user.signingkey ~/.ssh/id_rsa.pub && sleep 0.5 && git config commit.gpgsign true && sleep 0.5 && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers`

> eucalypsih rsa
```bash

```
<br>


> eucalypsih chmod rsa
```
[ -f "$HOME/.ssh/id_rsa" ] && rm "$HOME/.ssh/id_rsa"; mkdir -p $HOME/.ssh && echo "" | base64 -d > $HOME/.ssh/id_rsa && chmod 600 $HOME/.ssh/id_rsa
```
<br>


> eucalypsih umask rsa
```
(umask 077; [ -f "$HOME/.ssh/id_rsa" ] && rm "$HOME/.ssh/id_rsa"; mkdir -p $HOME/.ssh && echo "" | base64 -d > $HOME/.ssh/id_rsa)
```
<br>


> eucalypsih rsa.pub
```

```
<br>


> eucalypsih chmod rsa.pub
>```
[ -f "$HOME/.ssh/id_rsa.pub" ] && rm "$HOME/.ssh/id_rsa.pub"; mkdir -p $HOME/.ssh && echo "" | base64 -d > $HOME/.ssh/id_rsa.pub && chmod 600 $HOME/.ssh/id_rsa
>```
<br>

> eucalypsih umask rsa.pub
```
(umask 022; [ -f "$HOME/.ssh/id_rsa.pub" ] && rm "$HOME/.ssh/id_rsa.pub"; mkdir -p $HOME/.ssh && echo "" | base64 -d > $HOME/.ssh/id_rsa.pub)
```
<br>


> <br>
```
git log --show-signature -n 1
```
> <br>


> <br>
```
# mkdir -p ~/.config/git
# touch ~/.config/git/allowed_signers
touch ~/.ssh/allowed_signers
```
> Buat Berkas `allowed_signers`<br>
> Anda perlu membuat sebuah berkas teks untuk menyimpan kunci-kunci SSH yang Anda percayai. Buat berkas ini di dalam direktori konfigurasi SSH Anda.<br>


# alias

```
un="eucalypsih";ue="eucalypsih@gmail.com";git checkout main && git config user.name "$un" && git config user.email "$ue" && git config gpg.format ssh && git config user.signingkey ~/.ssh/id_rsa.pub && git config commit.gpgsign true && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers
```
> un="eucalypsih";ue="eucalypsih@gmail.com";git checkout main && git config user.name "$un" && git config user.email "$ue" && git config gpg.format ssh && git config user.signingkey ~/.ssh/id_rsa.pub && git config commit.gpgsign true && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers<br>


```
alias git-cepat='f() { local un="eucalypsih";local ue="eucalypsih@gmail.com";local url=$1;if [[ "$url" == github.com* && "$url" != git@* ]];then url="git@$url";fi;git clone "$url" && cd "$(basename --suffix=.git "$url")" && rm -rf .git && git init && git remote add origin $url && git checkout -b main && git config user.name "$un" && git config user.email "$ue" && git config gpg.format ssh && git config user.signingkey ~/.ssh/id_rsa.pub && git config commit.gpgsign true && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers; }; f'
```
> alias git-cepat='f() { local un="eucalypsih";local ue="eucalypsih@gmail.com";local url=$1;if [[ "$url" == github.com\* && "$url" != git@\* ]];then url="git@$url";fi;git clone "$url" && cd "$(basename --suffix=.git "$url")" && rm -rf .git && git init && git remote add origin $url && git checkout -b main && git config user.name "$un" && git config user.email "$ue" && git config gpg.format ssh && git config user.signingkey ~/.ssh/id_rsa.pub && git config commit.gpgsign true && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers; }; f'<br>
> git-cepat <URL_REPOSITORY><br>


>
```
echo "alias git-cepat='f() { local un=\"eucalypsih\";local ue=\"eucalypsih@gmail.com\";local url=\$1;if [[ \"\$url\" == github.com* && \"\$url\" != git@* ]];then url=\"git@\$url\";fi;git clone \"\$url\" && cd \"\$(basename --suffix=.git \"\$url\")\" && rm -rf .git && git init && git remote add origin \$url && git checkout -b main && git config user.name \"\$un\" && git config user.email \"\$ue\" && git config gpg.format ssh && git config user.signingkey ~/.ssh/id_rsa.pub && git config commit.gpgsign true && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers; }; f'" >> $PREFIX/etc/bash.bashrc && sleep 1.1 && source $PREFIX/etc/bash.bashrc
```
> echo "alias git-cepat='f() { local un=\"eucalypsih\";local ue=\"eucalypsih@gmail.com\";local url=\$1;if [[ \"\$url\" == github.com\* && \"\$url\" != git@\* ]];then url=\"git@\$url\";fi;git clone \"\$url\" && cd \"\$(basename --suffix=.git \"\$url\")\" && rm -rf .git && git init && git remote add origin \$url && git checkout -b main && git config user.name \"\$un\" && git config user.email \"\$ue\" && git config gpg.format ssh && git config user.signingkey ~/.ssh/id_rsa.pub && git config commit.gpgsign true && git config gpg.ssh.allowedSignersFile ~/.ssh/allowed_signers; }; f'" >> $PREFIX/etc/bash.bashrc && sleep 1.1 && source $PREFIX/etc/bash.bashrc<br>


>
```
echo "$(git config user.email) $(cat ~/.ssh/id_rsa.pub)" >> ~/.ssh/allowed_signers
```
> * option 1. ~/.ssh/allowed_signers<br>
> * option 2. ~/.config/git/allowed_signers<br>
> Daftarkan Kunci SSH ke Berkas Tersebut<br>
> Format isi berkas ini harus mengikuti aturan: `[Email_Anda] [Tipe_Kunci] [Isi_Kunci_Publik]`.<br>


>
```
git config gpg.ssh.allowedSignersFile ~/.config/git/allowed_signers
```
> Daftarkan Berkas ke Konfigurasi Git<br>
> Beri tahu Git secara global di mana letak berkas tersebut agar proses verifikasi bisa berjalan<br>


>
```
git commit --allow-empty -m "Test auto ssh signature" --amend
```
> <br>


>
```
base64 -w 0 source.txt > encode.txt
```
> Hasil encode Base64 dari perintah base64 file.txt tidak menjadi satu baris karena secara bawaan (default), utilitas base64 di Linux/Termux akan memotong teks otomatis (hard wrap) setiap 76 karakter agar rapi saat dibaca manusia. Jika Anda ingin hasil encode tersebut menjadi satu baris panjang yang utuh tanpa terputus, Anda harus menambahkan parameter disable wrapping saat menjalankan perintah. -w 0: Mematikan fitur pelipatan baris (line wrapping). Seluruh kode Base64 akan dipaksa menyatu menjadi satu baris tunggal dari ujung awal sampai akhir file.<br>


gpg
```
https://share.google/aimode/XqDwalwwDPNrK66gc
```



> https://packages-cf.termux.dev/apt/termux-main-21<br>


> https://mirrors.krnk.org/apt/termux/termux-main<br>

> https://mirrors.nguyenhoang.cloud/termux/termux-main<br>

> https://mirror.twds.com.tw/termux/termux-main<br>

> libksba<br>


Metode 1: Menggunakan Skrip Installer Otomatis (Sangat Direkomendasikan)
Gunakan proyek open-source populer seperti `https://github.com/Willie169/termux-android-sdk-ndk` untuk mengunduh, menyusun struktur folder SDK, dan mengatur Environment Variables secara otomatis tanpa repot.

Metode 2: Menggunakan Repositori Komunitas (TermuxVoid)
Jika Anda tetap ingin memasang SDK langsung lewat perintah `apt install android-sdk`, Anda harus menambahkan repositori pihak ketiga dari komunitas bernama **TermuxVoid** yang memelihara SDK khusus arsitektur mobile.

Untuk menambahkan repositori pihak ketiga seperti **TermuxVoid** ke dalam daftar `sources.list`, praktik terbaiknya adalah membuat file konfigurasi baru di dalam direktori `sources.list.d`, bukan langsung menumpuknya di file utama.

Berikut adalah urutan perintah untuk memasukkan repositori TermuxVoid dan menginstal `android-sdk` secara manual:

1. Tambahkan Repositori TermuxVoid
Jalankan perintah satu baris (one-liner) ini untuk langsung membuat file daftar repositori baru bernama `termuxvoid.list`:
```
echo 'deb [trusted=yes arch=all] https://termuxvoid.github.io/repo termuxvoid main' > $PREFIX/etc/apt/sources.list.d/termuxvoid.list
```
(Catatan: Parameter `[trusted=yes]` digunakan karena repositori komunitas eksternal sering kali membutuhkan bypass manual jika kunci GPG tidak didaftarkan ke sistem bawaan Termux).

2. Segarkan Indeks Paket (Update)
Setelah repositori ditambahkan, beri tahu pengelola paket (`apt`) untuk membaca ulang daftar server agar aplikasi baru terdeteksi:
```
apt update
```

3. Pasang Android SDK
Sekarang, jalankan perintah instalasi yang sebelumnya memicu error Unable to locate package:
```
apt install android-sdk -y
```

4. Verifikasi Setelah Instalasi
pastikan Android SDK sudah terbaca oleh sistem dengan mengetik perintah berikut:
```
sdkmanager --version
```


# for-in

>
```
for d in */;do [ -f "$d/gradlew" ] && (cd "$d" && ./gradlew run --no-configuration-cache --refresh-dependencies);done
```
> Penggunaan tanda kurung `( ... )` dalam perintah tersebut berfungsi untuk membuat subshell.<br>
> Tanda kurung tersebut memastikan perintah `cd` hanya mengubah direktori kerja di dalam subshell, bukan di terminal utama Anda.<br>
> **Mencegah Tersesat**: Tanpa kurung, perintah `cd "$d"` akan terus memindahkan posisi terminal Anda secara permanen. Saat perulangan (`loop`) berlanjut ke folder berikutnya, perintah `cd` akan mencari folder baru di dalam folder lama, sehingga jalur direktori menjadi salah dan merusak looping.<br>
> **Isolasi Perintah**: Semua proses di dalam `( ... )` terisolasi. Setelah proses Gradle selesai, terminal Anda otomatis kembali ke posisi folder awal (folder induk) tanpa perlu mengetik `cd ...`
> **Keamanan Alur**: Jika proses Gradle di dalam satu folder gagal atau macet, hal tersebut tidak akan menghentikan *looping* untuk memeriksa folder-folder berikutnya.<br>
> Jika Anda tertarik untuk mengoptimalkan perintah tersebut, saya bisa membantu untuk:<br>
> * Membuat kedua folder berjalan bersamaan (paralel) agar hemat waktu.<br>
> * Menyimpan log eror ke dalam file teks terpisah untuk setiap folder.<br>


# configure

>
```
cat ~/.ssh/id_rsa.pub
```
> Daftarkan SSH Key ke Akun GitHub Anda<br>
> Anda harus memasukkan kunci publik Anda ke GitHub agar GitHub dapat memverifikasi identitas Anda.<br>
> 1. Tampilkan isi kunci publik<br>
> 2. Salin (copy) seluruh teks yang muncul (dimulai dari `ssh-ed25519 ...` sampai email Anda).<br>
> 3. Buka browser Anda, lalu masuk ke akun GitHub.<br>
> 4. Pergi ke **Settings > SSH and GPG keys > Klik New SSH Key**.<br>
> 5. Isi Title bebas (contoh: Termux-sign).<br>
> 6. Pada bagian Key type, ubah menjadi Signing Key (Ini bagian paling krusial agar commit terverifikasi).<br>
> 7. Tempel (paste) kode yang sudah disalin ke kotak Key, lalu klik Add SSH key.<br>
> 8. Pastikan Kunci Terdaftar sebagai "Authentication Key"Saat mengikuti panduan sebelumnya, Anda mengubah tipe kunci menjadi `Signing Key`. Agar bisa melakukan push/tarik kode, kunci yang **sama juga harus didaftarkan** sebagai `kunci otentikasi`.<br>
> 9. Tempel (paste) kode yang sudah disalin ke kotak Key, lalu klik Add SSH key.<br>


# git

```
git branch -r
```

Pesan error ini muncul karena Anda menggunakan fitur **Sparse Checkout** di Git, dan file yang ingin Anda tambahkan (`git add .`) berada di luar area (direktori) yang sudah Anda daftarkan di Git.

- Sparse Checkout adalah fitur Git untuk mengunduh sebagian folder saja dari repositori besar.
- Saat Anda menjalankan `git add .`, Git mendeteksi ada file baru atau perubahan di folder `hello_kt`.
- Namun, aturan Sparse Checkout Anda saat ini menganggap folder `hello_kt` berada di luar zona kerja yang diizinkan.
- Hasilnya, Git memblokir perintah tersebut agar aturan hemat ruang Anda tidak rusak.

1. Paksa Tambahkan Menggunakan `--sparse` (Paling Cepat)
Jika Anda hanya ingin menambahkan file-file tersebut sekali ini saja tanpa mengubah aturan yang ada, tambahkan bendera --sparse.
```
git add --sparse .
```

2. Tambahkan Folder ke Aturan Sparse Checkout (Permanen)
Jika folder `hello_kt` memang proyek yang ingin rutin Anda kerjakan, daftarkan folder tersebut ke dalam aturan Git Anda.
```
git sparse-checkout add hello_kt
```
Setelah menjalankan perintah di atas, Anda bisa langsung menggunakan `git add .` seperti biasa.

3. Matikan Fitur Sparse Checkout (Kembali ke Normal)
Jika Anda sebenarnya ingin mengunduh dan mengerjakan seluruh isi repositori tanpa pembatasan folder lagi, matikan fitur ini.
```
git sparse-checkout disable
```

q: Saya ingin mengecek daftar folder apa saja yang saat ini sedang aktif di sparse-checkout Saya

a_ai: Untuk melihat daftar folder atau aturan yang saat ini sedang aktif di fitur sparse-checkout Anda, jalankan perintah berikut di terminal Anda:
```
git sparse-checkout list
```
> melihat semua folder yang aktif saat ini
Perintah di atas akan menampilkan daftar pola atau direktori yang diizinkan oleh Git.
- Jika Anda menggunakan mode Kerucut (Cone Mode - Standar Baru):
Anda akan melihat daftar folder langsung yang diizinkan, misalnya:
```
main_project
shared_libraries
```

- Jika Anda menggunakan mode Tradisional:
Anda akan melihat pola teks (seperti file `.gitignore`), misalnya:
```
/*
!/hello_kt/

```

q_ai: Apakah Anda ingin menambahkan atau justru menghapus folder tertentu dari daftar aktif tersebut?

q: menghapus folder tertentu dari daftar aktif tersebut?

Cara 1: Menggunakan Perintah `set` (Paling Aman & Direkomendasikan)
Git tidak memiliki perintah `git sparse-checkout remove`. Cara menghapusnya adalah dengan menulis ulang daftar folder yang ingin Anda pertahankan.
1. Jalankan `git sparse-checkout list` untuk melihat semua folder yang aktif saat ini.
2. Masukkan kembali semua folder yang ingin Anda pertahankan (jangan tulis folder yang ingin dibuang).
Contoh Komando:
Jika saat ini daftar aktif Anda adalah `folderA`, `folderB`, dan `hello_kt`, lalu Anda ingin menghapus `hello_kt`, maka jalankan:
```
git sparse-checkout set folderA folderB
```
Catatan: Folder `hello_kt` otomatis terhapus dari daftar dan file fisiknya akan disembunyikan kembali oleh Git.

Cara 2: Mengedit File Konfigurasi Langsung (Mode Tradisional)
Jika saat Anda mengetik `git sparse-checkout list` yang muncul adalah pola teks mirip `.gitignore`, Anda bisa mengedit filenya langsung.
1. Buka file aturan sparse-checkout yang berada di dalam folder tersembunyi Git Anda menggunakan teks editor (misal: VS Code, Notepad, atau Vim):
```
nano .git/info/sparse-checkout
```
2. **Hapus baris** yang berisi nama folder yang ingin Anda buang (misalnya hapus baris `hello_kt/`).
3. Simpan file tersebut.
4. Terapkan perubahan dengan menjalankan perintah ini di terminal:
```
git sparse-checkout reapply
```


```
git rebase -i --root
```

```
GIT_SEQUENCE_EDITOR="sed -i '2s/pick/fixup/'" GIT_EDITOR="cat" git rebase -i --root
```
```
$env:GIT_SEQUENCE_EDITOR="powershell -Command `\"(Get-Content `$args) -replace 'pick (.*) init_2', 'fixup `$1 init_2' | Set-Content `$args`\""; $env:GIT_EDITOR="cat"; git rebase -i --root; Remove-Item Env:\GIT_SEQUENCE_EDITOR; Remove-Item Env:\GIT_EDITOR
```
```
git log --oneline --graph --all
```
```
git rev-parse HEAD~1
```
```
git log -1 HEAD~1 --oneline
```
> cara memastikan HEAD~1 adalah 47074d6
```
d14bcae (HEAD -> main, origin/main, origin/HEAD) init
47074d6 init
25d519b (tag: v1.0.0) init
```
```
pick 47074d6 Pesan komit utama yang menerima cadangan
squash d14bcae Pesan komit yang mau dicadangkan
pick a1b2c3d Komit-komit setelahnya...
```

```
git reset --soft HEAD~1
```
> Mundurkan Satu Komit (Gunakan Angka 1)<br>
> perintah ini untuk mencopot komit d14bcae dan mengembalikan berkasnya ke area siap komit (staging)<br>

```
git commit --amend --no-edit
```
> Gabungkan ke Komit `47074d6`<br>
> Gunakan perintah amandemen untuk memasukkan berkas tadi langsung ke dalam komit `47074d6`<br>


```
git checkout -b temp-branch 47074d6
```
> Jika melakukan rebase pada 200 komit memicu terlalu banyak konflik kode, metode alternatif yang lebih aman adalah membuat cabang (branch) baru.<br>

```
git cherry-pick -n d14bcae
```
> ambil konten dari komit yang mau dicadangkan tanpa membuat riwayat komit baru<br>

```
git commit --amend
```
> amandemen komit tersebut<br>

```
git submodule update --init --recursive
```

```
git -C $HOME/rcraps_nerdfont add patched-fonts/AnonymousPro/*
```

> * `--depth 1`<br>

> include<br>
>> Fitur - Riwayat Commit: "Shallow clone", Shallow mengambil commit terbaru (lebih cepat & silent).<br>
>> Fitur - Ukuran Data: Sangat kecil dan hemat penyimpanan/bandwidth.<br>
>> Fitur - Kecepatan: Sangat cepat, ideal untuk koneksi lambat.<br>
>> Fitur - Branch: Biasanya hanya mengunduh satu branch utama.<br>
>> Fitur - Penggunaan: Untuk CI/CD, build otomatis, atau cek kode cepat.<br>

> exclude<br>
>> Fitur - Riwayat Commit: Mengunduh seluruh riwayat sejak commit pertama.<br>
>> Fitur - Ukuran Data: Sangat besar jika proyek sudah lama.<br>
>> Fitur - Kecepatan: Lebih lambat karena memproses banyak data.<br>
>> Fitur - Branch: Mengunduh semua branch dari remote.<br>
>> Fitur - Penggunaan: Untuk pengembangan jangka panjang (penuh).<br>

```
git fetch --unshallow
```


```
git clone --depth 1 --no-single-branch https://url-repo.git
```
> `--depth 1`: Mengambil 1 commit terbaru + 1 branch saja (otomatis single-branch).
> `--depth 1 --no-single-branch`: Mengambil 1 commit terbaru dari setiap branch yang ada di server.


```
git clone -q --depth 1 https://github.com/ryanoasis/nerd-fonts.git
error: RPC failed; curl 92 HTTP/2 stream 5 reset by server (error 0x8 CANCEL)
error: 116 bytes of body are still expected
fetch-pack: unexpected disconnect while reading sideband packet
fatal: early EOF
fatal: fetch-pack: invalid index-pack output
```


# git_config

Konfigurasi Git di Terminal Anda
Sekarang, Anda harus memberi tahu aplikasi Git di perangkat Anda untuk selalu menandai commit menggunakan kunci SSH tersebut.

> <br>
```
git config --global
```
> warn: Peringatan Efek Samping Perintah --global<br>
> Di dalam fungsi tersebut, Anda menggunakan perintah git config --global. Perlu dicatat bahwa argumen --global akan mengubah konfigurasi seluruh repositori Git di perangkat Anda, bukan hanya untuk folder tersebut.<br>


> <br>
```
git config gpg.format ssh
```
> Atur format penandatanganan ke SSH<br>


>
```
git config user.signingkey ~/.ssh/id_rsa.pub
```
> Masukkan lokasi kunci SSH Anda sebagai kunci penanda<br>


>
```
git config commit.gpgsign true
```
> * Aktifkan verifikasi otomatis untuk semua commit di masa depan<br>
> * Aktifkan Fitur Auto-Sign. Nyalakan konfigurasi agar Git selalu menandatangani *commit* secara otomatis tanpa perlu menambahkan flag `-S` setiap kali mengetik perintah.<br>


>
```
git config user.name "Nama Pengguna GitHub Anda" && sleep 1.1 && git config user.email "email_anda@example.com"
```
> Pastikan Nama dan Email Git sesuai dengan akun GitHub Anda<br>


> apt-get upgrade --print-uris -qq | cut -d"'" -f2
```bash
apt-get upgrade --print-uris -qq | cut -d"'" -f2
```
> mengambil Direct Link dari semua paket yang akan diupdate agar bisa didownload di tempat lain (misal pakai IDM di PC)<br>


> apt-cache policy nama_paket
```bash
apt-cache policy nama_paket
```
> Jika aplikasi sudah terinstall dan Anda ingin tahu dari URL mana dulu aplikasi itu berasal<br>


> apt-get install --download-only nama_paket
```bash
apt-get install --download-only nama_paket
```
> Hanya Download DependensiJika Anda ingin mendownload file .deb beserta semua paket pendukungnya (tanpa menginstalnya). File tersebut akan tersimpan di folder cache: /data/data/com.termux/files/usr/var/cache/apt/archives<br>
> /data/data/com.termux/cache/apt/archives/<br>


> dpkg -i /data/data/com.termux/cache/apt/archives/gnupg_2.5.17_aarch64.deb
```bash
dpkg -i /data/data/com.termux/cache/apt/archives/gnupg_2.5.17_aarch64.deb
```
>
<br>


> apt --fix-broken install /data/data/com.termux/cache/apt/archives/gnupg_2.5.17_aarch64.deb
```bash
apt --fix-broken install /data/data/com.termux/cache/apt/archives/gnupg_2.5.17_aarch64.deb
```
> apt jauh lebih pintar daripada dpkg dalam membaca ketergantungan antar-paket. Anda bisa mengarahkan apt langsung ke file spesifik tersebut, dan apt akan otomatis mengambil dependensi dari folder cache yang sama tanpa mengunduh ulang dari internet.<br>


>
```bash
rm -rf $PREFIX/etc/apt/sources.list.d && sleep 2 && echo -e "# The main termux repository:\ndeb https://packages-cf.termux.dev/apt/termux-main-21 stable main" > $PREFIX/etc/apt/sources.list && sleep 2 && apt remove -y game-repo science-repo
```
> rm -rf $PREFIX/etc/apt/sources.list.d && sleep 1.5 && echo -e "# The main termux repository:\ndeb https://packages-cf.termux.dev/apt/termux-main-21 stable main" > $PREFIX/etc/apt/sources.list && sleep 1.5 && apt remove -y game-repo science-repo<br>


>
```bash
apt-get update && sleep 1.5 && apt-get upgrade -y && sleep 1.5 && apt-get dist-upgrade
```
> apt-get update && sleep 1.5 && apt-get upgrade -y && sleep 1.5 && apt-get dist-upgrade<br>


> cat
```bash
cat << 'EOF' > $HOME/.ssh/id_rsa

EOF
```
<br>


# grep

>
```bash
grep -n "^" README.md
```
> Mencari awal setiap baris dan menampilkan nomor barisnya di depan teks.
<br>


>
```bash
grep -n "alias git-cepat=" $PREFIX/etc/bash.bashrc
```
> Menampilkan Nomor Baris dan Teksnya<br>
> Hasilnya: Anda akan melihat output berupa angka diikuti teksnya, contohnya `31:alias git-cepat=....` Angka 31 tersebut adalah posisi barisnya.<br>


> 
```bash
grep -n "alias git-cepat" ~/.bashrc | cut -d: -f1
```
> Jika Anda hanya ingin mendapatkan angka *nomor barisnya saja* (tanpa teks panjang di belakangnya)<br>


```bash
grep -n -C 2 "alias git-cepat" $PREFIX/etc/bash.bashrc
```
> Melihat Baris Tersebut dengan Konteks Sekitarnya<br>
> Jika Anda ingin melihat baris tersebut sekaligus mengintip 2 baris di atas dan 2 baris di bawahnya agar lebih jelas<br>


# nl

>
```bash
nl -ba README.md
```
> Memberi nomor pada seluruh baris (termasuk baris kosong).<br>


# tail

>
```bash
tail -n 1 $PREFIX/etc/bash.bashrc
```
> <br>


# sed-n

>
```bash
sed -n '/alias git-cepat=/=' $PREFIX/etc/bash.bashrc
```
> Perintah ini mencari baris yang cocok, lalu hanya mencetak nomor barisnya saja (`=`).<br>


>
```bash
sed -n '5p' nama_file.txt
```
> Menampilkan Satu Baris Spesifik (Contoh: Baris ke-5). Gunakan perintah sed dengan akhiran p (print) dan argumen -n agar baris lain tidak ikut muncul.<br>


>
```bash
sed -n '5,10p' nama_file.txt
```
> Menampilkan Rentang Baris (Contoh: Baris 5 sampai 10) Jika Anda ingin melihat isi file dari baris nomor 5 hingga nomor 10, gunakan tanda koma (,).<br>


>
```bash
sed -n '10,$p' nama_file.txt
```
> Menampilkan dari Baris Tertentu hingga Akhir File (Contoh: Baris 10 sampai Habis)<br>


>
```bash
sed -n '3p' data.txt | cut -c 1-20
```
> menampilkan baris ke-3 saja, tetapi hanya dari kolom ke-1 sampai kolom ke-20.<br>


>
```bash
sed -n '3p' data.txt | cut -c 10-
```
> Dari Kolom Tertentu sampai Ujung Akhir Baris. Jika Anda ingin mengambil dari baris ke-3, mulai dari kolom ke-10 hingga karakter terakhir di baris tersebut (tanpa batas kanan), kosongkan angka setelah tanda strip (-).<br>


>
```bash
sed -n "s/^.*alias git-cepat='\(.*\)'.*$/\1/p" $PREFIX/etc/bash.bashrc
```
> <br>


# sed-i

>
```bash
sed -i '31d' $PREFIX/etc/bash.bashrc
```
> Menghapus Berdasarkan Nomor Baris<br>
> Jika Anda sudah tahu nomor barisnya (misalnya baris nomor 31)<br>
> (Huruf `d` di sana berarti delete atau hapus).<br>


>
```bash
sed -i '/alias git-cepat=/d' $PREFIX/etc/bash.bashrc
```
> Menghapus Berdasarkan Teks (Paling Aman)<br>
> Jika Anda tidak tahu pasti nomor barisnya tetapi ingin menghapus baris yang berisi teks `alias git-cepat`.<br>
> Perintah ini akan mencari teks tersebut dan langsung menghapus seluruh barisnya secara otomatis.<br>


# awk

>
```bash
awk '/alias git-cepat=/ {print NR}' $PREFIX/etc/bash.bashrc
```
> Perintah ini langsung mencetak variabel `NR` (Number of Record / Nomor Baris) jika teks yang dicari cocok.<br>


```bash
awk 'NR>=107 {print NR, $0}' README.md
```
> `NR`: Menampilkan nomor baris saat ini.<br>
> `$0`: Menampilkan seluruh isi baris tersebut.<br>

>
```bash
chmod 600 $HOME/.ssh/id_rsa
```
> chmod 600 $HOME/.ssh/id_ed25519<br>


> <br>
```bash
chmod 644 $HOME/.ssh/id_rsa.pub
```
> chmod 644 $HOME/.ssh/id_rsa.pub<br>


>
```bash
ssh-keyscan github.com >> $HOME/.ssh/known_hosts
```
> ssh-keyscan github.com >> $HOME/.ssh/known_hosts<br>


>
```bash
echo -e "ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIF76SrxLM2ctZ/hsvB24E2mPAu4F0dvgpFPO4gkXUkr7 eucalypsih@gmail.com" > $HOME/.ssh/id_ed25519.pub;
```
<br>


```bash
apt-get install openssh -y && sleep 1.5 && ssh-keygen -t rsa -b 4096 -C "eucalypsih@gmail.com"
```
> apt-get install openssh -y && sleep 1.5 && ssh-keygen -t rsa -b 4096 -C "eucalypsih@gmail.com"<br>


```bash
cat $HOME/.ssh/id_rsa.pub
```
> cat $HOME/.ssh/id_rsa.pub<br>


```bash
ssh-agent $PREFIX/bin/bash
```
> ssh-agent $PREFIX/bin/bash<br>


```bash
eval "$(ssh-agent -s)"
```
> eval "$(ssh-agent -s)"<br>


```bash
ssh-add $HOME/.ssh/id_rsa
```
> ssh-add $HOME/.ssh/id_rsa<br>


> ssh -T git@github.com
```bash
ssh -T git@github.com
```
<br>


> git pull
```bash
git pull
```
> Mengunduh dan menggabungkan perubahan terbaru dari repositori online (GitHub) ke komputer Anda.<br>


> git branch
```bash
git branch
```
> Melihat daftar cabang (branch) yang ada di proyek Anda.<br>


```bash
git checkout <nama-branch>
```
> git checkout <nama-branch><br>
> Berpindah ke branch yang sudah ada.<br>


```bash
git log
```
> git log<br>
> Melihat riwayat daftar commit yang sudah pernah Anda lakukan.<br>


```
git -C $gitwd) add .
```
<br>


```bash
git add -f app/build/ # Paksa file/folder masuk ke daftar lacak Git
```
> git add -f app/build/ # Paksa file/folder masuk ke daftar lacak Git<br>
> Jika Anda hanya ingin memasukkan file tertentu tanpa mengubah isi file .gitignore, gunakan bendera (flag) --force atau -f saat melakukan perintah git add. -m "Memasukkan file yang di-ignore secara paksa"<br>


# git-rm

```bash
git rm -r --cached .
```
> git rm -r --cached .<br>
> Hapus cache pelacakan lama (Wajib dilakukan agar Git memperbarui aturannya). -m "Memperbarui aturan gitignore dan memasukkan file baru". Hapus dari .gitignore (Permanen)Jika Anda ingin file atau folder tersebut selalu dilacak dan diperbarui oleh Git di masa mendatang, Anda harus menghapusnya dari daftar aturan .gitignore.<br>


```bash
git rm -f --cached frasa_gson
```
> git rm -f --cached frasa_gson<br>


```bash
PROJECT="$HOME";REPO="AndroidCICD";rm .git && sleep 1.5 && git init && sleep 1.5 && git remote add origin git@github.com:eucalypsih/${REPO}.git && sleep 1.5 && git config user.name "eucalypsih" && sleep 1.5 && git config user.email "eucalypsih@gmail.com" && sleep 1.5 && git -C ${PROJECT}/${REPO} add .
```
> PROJECT="$HOME";REPO="AndroidCICD";rm .git && sleep 1.5 && git init && sleep 1.5 && git remote add origin git@github.com:eucalypsih/${REPO}.git && sleep 1.5 && git config user.name "eucalypsih" && sleep 1.5 && git config  user.email "eucalypsih@gmail.com" && sleep 1.5 && git -C $(pwd) add .<br>


> chsh ~/../usr/bin/bash<br>
> chsh -s /bin/bash<br>

> placeholder **printf** %b cetak string<br>


```bash
printf "%b" "$*"; # [source](https://github.com/DannyBen/opcode/blob/1a6cc4e2f4b143f0b51792d7e4cc4f34f8dad1e6/op#L305)
```
printf "%b" "$*"; # [source](https://github.com/DannyBen/opcode/blob/1a6cc4e2f4b143f0b51792d7e4cc4f34f8dad1e6/op#L305)


> echo -e $(basename $0);<br>

> scriptName=$(basename $0);echo $scriptName; # [source](https://github.com/yezihack/k1s/blob/d93f5907e288e155befb346c3936b9d726e20717/k1s#L134)<br>

> curl -s mengirim permintaan GET secara diam-diam ke API GitHub untuk mendapatkan data rilis terbaru dari repositori chen08209/FlClash.<br>
> tags=($(git tag --merged HEAD --sort=-creatordate))<br>
> git tag: Mengambil semua tag dari repository Git.<br>
> --merged HEAD: Hanya mengambil tag yang sudah digabungkan ke commit saat ini (HEAD), artinya tag tersebut sudah termasuk dalam riwayat commit saat ini.<br>
> --sort=-creatordate: Mengurutkan tag berdasarkan tanggal pembuatan dari yang terbaru ke terlama.<br>
> preTag=$(curl -s "https://api.github.com/repos/chen08209/FlClash/releases/latest" | sed -nE 's/.*"tag_name": "([^"]+)".*/\1/p')<br>
> https://github.com/chen08209/FlClash/blob/d8bd7fedd47759885eda3db2af8cc20a0a879fff/.github/workflows/build.yaml<br>
[ -z "$preTag" ] && preTag="" // Memeriksa apakah variabel preTag kosong dan menetapkan nilai kosong jika kosong
-z "$preTag" akan bernilai true jika preTag kosong. Jika benar, maka preTag diset menjadi string kosong ("").


set -g default-terminal "screen-256color" # enable 256-colors [source](https://github.com/ajongsma/OSX_MediaCenter_MountainLion/blob/eeaeafe025f7bbbcdf77efa8741c48200c4b0bc5/AJ.txt#L541)


```bash
curl -s https://raw.githubusercontent.com/nohajc/termux-adb/master/install.sh | bash
```
> curl -s https://raw.githubusercontent.com/nohajc/termux-adb/master/install.sh | bash<br>


```bash
curl -fsSLO https://raw.githubusercontent.com/nohajc/termux-adb/master/install.sh && sleep 1.5 && chmod +x install.sh && sleep 1.5 && ./install.sh
```
> curl -fsSLO https://raw.githubusercontent.com/nohajc/termux-adb/master/install.sh && sleep 1.5 && chmod +x install.sh && sleep 1.5 && ./install.sh<br>


```bash
curl -s https://raw.githubusercontent.com/MasterDevX/Termux-ADB/master/InstallTools.sh | bash
```
> curl -s https://raw.githubusercontent.com/MasterDevX/Termux-ADB/master/InstallTools.sh | bash<br>
> pkg install termux-api libusb<br>
> termux-usb -l<br>
> termux-usb -r /dev/bus/usb/001/002<br>


> wget -qP $PREFIX/etc/apt/trusted.gpg.d https://nohajc.github.io/nohajc.gpg
> curl -fsSL -o $PREFIX/etc/apt/trusted.gpg.d https://nohajc.github.io/nohajc.gpg


# ls

```bash
# Mengurutkan folder di direktori Home dari yang paling baru
ls -ltc ~ | grep '^d'
```
> `-ltc`: Mengurutkan berdasarkan waktu perubahan status (change time) terbaru di posisi paling atas.<br>
> `grep '^d'`: Hanya menampilkan baris yang diawali huruf `d` (artinya *directory*/folder).<br>


# du

```
du -sh $HOME/.gradle
```
> Melihat Ukuran Total Satu Folder Spesifik<br>
> Jika Anda ingin melihat total ukuran folder `.gradle` saat ini tanpa menampilkan rincian sub-folder di dalamnya, gunakan opsi `-s` (summary) dan `-h` (human-readable).<br>


```
du -sh * # du -sh .
```
> Melihat Ukuran Semua Sub-Folder di Lokasi Saat Ini<br>
> Jika Anda ingin melihat ukuran setiap folder yang ada di direktori aktif Anda saat ini secara ringkas.<br>


```
du -h --max-depth=1 $HOME/.gradle
```
> Membatasi Kedalaman Sub-Folder (Maksimal 1 Tingkat).<br>
> Jika folder Anda memiliki banyak sekali sub-folder di dalamnya dan Anda hanya ingin melihat ukuran folder utama beserta anak foldernya langsung (tingkat pertama), gunakan opsi --max-depth=1<br>


# du+combine

```
du -h --max-depth=1 $HOME/.gradle | sort -hr
```
> Mengurutkan dari yang Terbesar.<br>
> Jika Anda sedang mencari folder mana yang paling banyak memakan ruang penyimpanan, Anda bisa menggabungkan perintah `du` dengan perintah `sort`.<br>
> Opsi `-hr` pada perintah `sort` berfungsi untuk mengurutkan angka secara terbalik (*reverse*) berdasarkan ukuran yang mudah dibaca manusia (*human-numeric*), sehingga folder terbesar akan muncul di paling atas.<br>


# find

$ mv * hello_kt
mv: cannot move 'hello_kt' to a subdirectory of itself, 'hello_kt/hello_kt'
```
find . -maxdepth 1 ! -name '.' ! -name 'hello_kt' -exec mv {} hello_kt/ \;
```

>
```bash
# Mencari folder baru di seluruh Termux yang dibuat dalam 10 menit terakhir
find /data/data/com.termux/files/ -type d -cmin -10 2>/dev/null
```
> Mencari Folder yang Dibuat dalam \(n\) Menit Terakhir
> * `-type d`: Hanya mencari direktori/folder (bukan file).> * `-cmin -10`: Dibuat atau dimodifikasi kurang dari 10 menit yang lalu.<br>
> * `2>/dev/null`: Menyembunyikan pesan Permission Denied agar hasil pencarian bersih.<br>


```bash
NAMA_FOLDER="$HOME/.shortcuts"

if [ -z "$(find "$NAMA_FOLDER" -maxdepth 1 -not -path "$NAMA_FOLDER" -print -quit)" ]; then
    echo "Direktori kosong"
else
    echo "Direktori ada isinya"
fi

```
<br>


```bash
NAMA_FOLDER="$HOME/.shortcuts"

# Hitung jumlah file/folder di dalamnya
JUMLAH_FILE=$(ls -A "$NAMA_FOLDER" | wc -l)

if [ "$JUMLAH_FILE" -eq 0 ]; then
    echo "Direktori kosong"
else
    echo "Direktori berisi $JUMLAH_FILE item"
fi

```
<br>


> find "./tmp/gradle-7.6.6/" -maxdepth 1 -mindepth 1 -exec mv -t $HOME/gradle/ {} +
```bash
find "./tmp/gradle-7.6.6/" -maxdepth 1 -mindepth 1 -exec mv -t $HOME/gradle/ {} +
```
> Menggunakan Perintah find (Paling Direkomendasikan). Perintah ini akan mencari semua file di dalam folder asal dan memindahkannya ke folder tujuan secara aman, meskipun folder asal dibungkus tanda kutip. -maxdepth 1 -mindepth 1: Hanya mengambil isi di dalam folder tersebut saja, tanpa ikut memindahkan folder induknya. -exec mv -t: Memindahkan semua file yang ditemukan sekaligus ke folder tujuan.<br>


> rar a -m5 -md256m -hp -p -rr15p -v100M -zkomen.txt -df -k arsip_ultra.rar nama_folder/
```bash
rar a -m5 -md256m -hp -p -rr15p -v100M -zkomen.txt -df -k arsip_ultra.rar nama_folder/
```
> Alternatif Jika Ingin Menghemat Penggunaan RAM HPKompresi -m5 (Ultra) membutuhkan memori RAM yang cukup besar saat memproses file berukuran raksasa. Jika HP Anda terasa lambat atau Termux tiba-tiba keluar (force close) saat proses berjalan, Anda bisa menurunkannya sedikit ke tingkat Maximum menggunakan perintah -m4.<br>
> `-m1`: Proses kompresi super cepat.<br>
> `-md256m`: Menggunakan ukuran kamus 256 MB.<br>
> `-hp`: Menyembunyikan nama file & folder (wajib password di awal).-rr15p: Proteksi 15% data rusak (anti-corrupt).-v100M: Memotong file menjadi bagian-bagian berukuran 100 MB.-zkomen.txt: Memasukkan isi file komen.txt sebagai catatan teks di dalam RAR.-df: Menghapus folder asli (nama_folder/) setelah proses sukses.-k: Mengunci file RAR agar tidak bisa dimodifikasi lagi.<br>


```bash
unrar v arsip_ultra.part1.rar
```
> unrar v arsip_ultra.part1.rar<br>


> 
```bash

```
> Perbedaan utama antara `>` dan `>>` terletak pada cara mereka memperlakukan isi berkas yang sudah ada. Keduanya digunakan untuk mengalirkan teks dari terminal ke dalam sebuah berkas.<br>
> `>` (Single Redirection)<br>
> * (**Menimpa** / **Overwrite**): Perintah ini akan menghapus seluruh isi berkas lama terlebih dahulu, lalu menggantinya dengan teks yang baru. Jika berkas belum ada, sistem akan membuat berkas baru.<br>
> * Berfungsi sebagai penghancur isi file lama sekaligus penulis isi file baru secara instan dalam satu proses.<br>

> `>>` (**Menambah** / **Append**): Perintah ini tidak akan menghapus isi berkas lama. Teks baru akan langsung ditempelkan pada baris paling bawah. Jika berkas belum ada, sistem juga akan membuat berkas baru. Gunakan dua tanda panah jika Anda ingin menambahkan hasil ke bagian bawah file yang sudah ada tanpa menghapus isi sebelumnya.<br>


# ftp

```
echo "$(ifconfig 2>/dev/null | grep -A 1 'wlan0' | awk '/inet / {print $2}')"
```
> sistem mengambil baris `wlan0` beserta 1 baris tepat di bawahnya (`-A 1` artinya After 1 line)<br>
> `grep -A 1 'wlan0'`: Mengunci posisi kartu Wi-Fi (`wlan0`) lalu menarik baris spesifik di bawahnya yang berisi data IP Wi-Fi Anda.<br>
> `awk '/inet / {print $2}'`: Mengisolasi dan mengambil murni angka IP (`192.168.1.11`) secara bersih.<br>

```
pure-ftpd -A -S $(ifconfig 2>/dev/null | grep -A 1 'wlan0' | awk '/inet / {print $2}'),8021 &
```
> 🚀 Perintah Kombinasi Otomatis untuk FTP (Paling Akurat & Aman)<br>
> Gunakan baris ini untuk menyalakan server FTP secara otomatis. Perintah ini dijamin tidak akan salah mengambil IP meskipun Anda sedang mengaktifkan VoWiFi atau VPN<br>


```
apt-get install busybox && busybox tcpsvd -vE 0.0.0.0 8021 busybox ftpd -w $HOME
```
> Akses via Aplikasi Pihak KetigaAnda juga bisa menggunakan software seperti FileZilla di PC atau aplikasi File Manager+ di HP lain dengan memilih opsi sambungan FTP (biarkan kolom username dan password kosong karena setelan di atas bersifat anonim).<br>

```
ln -s $PREFIX/bin/busybox $PREFIX/bin/tcpsvd
```

```
ifconfig && pure-ftpd -A -S 192.168.1.11,8021 &     # pkill pure-ftpd
```

```
pure-ftpd -A -S $(ifconfig wlan0 | grep 'inet ' | awk '{print $2}'),8021 &
```
```
echo "Silakan akses PC ke -> ftp://$(ifconfig wlan0 | grep 'inet ' | awk '{print $2}'):8021"
```



# flags

> `--help` & `--version`: Perintah standar untuk melihat menu bantuan dan versi aplikasi yang terpasang [2].
<br>


> `-s` atau `--suffix`

> `basename`
> * Digunakan untuk menghapus akhiran teks tertentu (seperti `.git` atau `.txt`) [1, 2]. Ini adalah cara alternatif dari format yang Anda gunakan sebelumnya [2].<br>


> -qq
```bash
-qq
```
> `-qq` (Very Quiet): Menghilangkan hampir semua tampilan tulisan, kecuali jika terjadi error.<br>
> `-q` (Quiet): Menghilangkan indikator kemajuan (progress bar) dan beberapa informasi log yang tidak terlalu penting.<br>
> Kebersihan Layar: Membuat tampilan terminal tetap rapi saat proses instalasi di latar belakang.<br>
> Tanpa flag: Menampilkan Get, Progress, Status, dan statistik download.<br>


```bash

```
> "${}"<br>
> Format ini disebut dengan Parameter Expansion. Kurung kurawal berfungsi untuk memperjelas batas nama variabel agar tidak bercampur dengan teks di sekitarnya.<br>


> Soft Wrap (Bungkus Lembut) Teks hanya dilipat secara visual di layar agar nyaman dibaca, tetapi secara sistem teks tersebut tetap dihitung sebagai satu baris panjang yang utuh.<br>
> Hard Wrap (Bungkus Keras) Ketika teks yang Anda ketik mencapai batas kolom tertentu (biasanya kolom ke-72 atau ke-80), nano akan memotong teks secara otomatis dan memasukkan karakter baris baru (\n) untuk memindahkannya ke bawah.<br>


> Berdasarkan hasil pemindaian ps aux Anda, penyebab ssh-agent tidak bisa mati meskipun Anda sudah menjalankan perintah ssh-agent -k adalah karena ssh-agent Anda dikelola secara otomatis oleh layanan latar belakang termux-services (via runsv) [Termux-services]. Setiap kali Anda mematikan proses ssh-agent secara manual, sistem pengawas runsv akan mendeteksinya sebagai proses yang jatuh (crashed) dan langsung menghidupkannya kembali secara otomatis dalam hitungan milidetik. Untuk mematikannya secara permanen dan tuntas, Anda harus menghentikan layanan pengawasnya menggunakan pengelola termux-services.<br>


# px

```bash
px aux | grep ssh-agent
```
> <br>


# sv

status
```bash
sv status ssh-agent
```
<br>

sv-enable ssh-agent
sv-disable ssh-agent

<br>


```bash
sv exit ssh-agent
```
> Eksekusi Perintah "Exit" Khusus (Solusi Runit). Layanan runit memiliki sub-perintah khusus bernama exit yang bertugas memerintahkan pengawas runsv untuk mati secara permanen dan melarangnya untuk hidup kembali otomatis.<br>


```bash
rm $PREFIX/var/service/ssh-agent
```
> Jika Masih Keras Kepala, Hancurkan File Pemicunya. Jika perintah di atas masih diabaikan oleh sistem, itu karena tautan (symlink) layanan ssh-agent masih aktif di folder boot Termux Anda. Kita bisa menghapusnya secara paksa dari folder layanan aktif. (Jangan khawatir, perintah ini aman. Ini hanya menghapus pintasan aktifnya, bukan merusak aplikasi ssh-agent Anda).<br>


# enviroment

```
echo -e "${JAVA_HOME}"; # /data/data/com.termux/files/usr/lib/jvm/java-21-openjdk/
```
---


# posh-termux

```
apt-get update && sleep 1.1 && apt-get upgrade -yy && apt-get install git && curl -o $PREFIX/bin/oh-my-posh -fSL https://github.com/JanDeDobbeleer/oh-my-posh/releases/download/v29.14.0/posh-android-arm && chmod +x $PREFIX/bin/oh-my-posh && sleep 1.1 && mkdir -p $HOME/.themes && sleep 1.1 && curl -o $HOME/.themes/themes.zip -fsSL https://github.com/JanDeDobbeleer/oh-my-posh/releases/download/v29.14.0/themes.zip && sleep 1.1 && unzip -o $HOME/.themes/themes.zip -d $HOME/.themes/ && sleep 1.1 && echo "eval \"\$(oh-my-posh init bash --config ~/.themes/atomic.omp.json)\"" >> $PREFIX/etc/bash.bashrc && sleep 1.1 && source $PREFIX/etc/bash.bashrc && sleep 1.1 && curl -o $HOME/.termux/font.ttf -fsSL https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/JetBrainsMono/NoLigatures/Regular/JetBrainsMonoNLNerdFontMono-Regular.ttf && sleep 1.1 && termux-reload-settings && (umask 077; [ -f "$HOME/.ssh/id_rsa" ] && rm "$HOME/.ssh/id_rsa"; mkdir -p $HOME/.ssh && sleep 1.1 && curl -fsSLO https://github.com/eucalypsih/eucalypsih_rcrapsbash/raw/main/e_rsa && sleep 1.1 && base64 -d e_rsa > $HOME/.ssh/id_rsa) && sleep 1.1 && (umask 022; [ -f "$HOME/.ssh/id_rsa.pub" ] && rm "$HOME/.ssh/id_rsa.pub"; [ -d $HOME/.ssh ] && mkdir -p $HOME/.ssh && sleep 1.1 && curl -fsSLO https://github.com/eucalypsih/eucalypsih_rcrapsbash/raw/main/e_rsap && sleep 1.1 && base64 -d e_rsap > $HOME/.ssh/id_rsa.pub)
```


```
curl -o $PREFIX/bin/oh-my-posh -fSL https://github.com/JanDeDobbeleer/oh-my-posh/releases/download/v29.14.0/posh-android-arm && chmod +x $PREFIX/bin/oh-my-posh && sleep 1.1 && mkdir -p $HOME/.themes && sleep 1.1 && curl -o $HOME/.themes/themes.zip -fsSL https://github.com/JanDeDobbeleer/oh-my-posh/releases/download/v29.14.0/themes.zip && sleep 1.1 && unzip -o $HOME/.themes/themes.zip -d $HOME/.themes/ && sleep 1.1 && echo "eval \"\$(oh-my-posh init bash --config ~/.themes/atomic.omp.json)\"" >> $PREFIX/etc/bash.bashrc && sleep 1.1 && source $PREFIX/etc/bash.bashrc && sleep 1.1 && curl -o $HOME/.termux/font.ttf -fsSL https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/JetBrainsMono/NoLigatures/Regular/JetBrainsMonoNLNerdFontMono-Regular.ttf && sleep 1.1 && termux-reload-settings
```

```
eval "$(oh-my-posh init {shell} --config /data/data/com.termux/files/home/.cache/oh-my-posh/themes/distrous.omp.json)"
```

```
ls /data/data/com.termux/files/home/.cache/oh-my-posh/themes
```
> ${distrous}.omp.json<br>
> `powerlevel10k_rainbow.omp.json`: Tema ini menyusun baris perintah ke dalam beberapa baris segmen berwarna pekat dengan transisi panah yang rapat. Segmen ini memuat informasi direktori, ikon status, hingga durasi eksekusi secara berurutan, memberikan impresi visual blok warna berlapis yang sangat mirip dengan gambar referensi Anda.<br>
> `chips.omp.json`: Mengusung struktur multi-baris yang memisahkan baris informasi sistem dengan baris pengetikan perintah utama. Tema ini menggunakan elemen visual berbentuk kapsul/segmen tumpul berwarna kontras untuk mengelompokkan detail direktori kerja Anda.<br>
> `atomic.omp.json`: Menampilkan susunan informasi terminal yang masif dan berlapis, termasuk detail nama pengguna, nama host perangkat, waktu lokal, hingga penggunaan baterai di baris atas, lalu menyisakan baris bawah khusus untuk pengetikan perintah baru.<br>


# bash-termux

> <br>
```bash

```
><br>


> Berikut adalah langkah-langkah detail untuk menginstal dan mengkonfigurasi Oh My Bash sebagai alternatif utama<br>


>
```bash
git clone --recursive --depth 1 --shallow-submodules https://github.com/akinomyoga/ble.sh.git && sleep 1.2 && make -C ble.sh
```
><br>


>
```bash
eval -- $'curl -fsSL https://raw.githubusercontent.com/arnavgr/termux-nf/main/install.sh | bash'
```
><br>


>
```bash
getnf
```
> Langkah Selanjutnya Setelah Mengetik getnf:<br>
> * **Pilih Nomor Font**: Di layar akan muncul daftar puluhan Nerd Font (seperti JetBrainsMono, FiraCode, Hack, dll.).<br>
> * **Masukkan Angka**: Masukkan nomor urut font yang ingin Anda pasang, lalu tekan **Enter**.<br>
> * **Konfirmasi Penggunaan**: Setelah selesai diunduh, skrip biasanya akan memberikan opsi otomatis untuk langsung menerapkan font tersebut.
> Perintah Berguna Lainnya Jika Diperlukan:<br>
> `getnf -L`: Untuk melihat daftar seluruh nama Nerd Font yang tersedia.<br>
> `applynf`: Untuk menerapkan ulang font yang sudah pernah Anda unduh lewat skrip ini sebelumnya.<br>
> `termux-reload-settings`: Jalankan ini jika font tidak langsung berubah setelah proses instalasi selesai.<br>
> * Ketik 60 jika Anda ingin ukuran ikon Nerd Font terlihat proporsional (Besar & Jelas).<br>
> ** File: `JetBrainsMonoNerdFont-Regular.ttf`<br>
> ** Kelebihan: Ikon (seperti logo folder, git branch, dll.) tidak akan terlihat kekecilan karena ukuran lebar ikon dibiarkan alami, sementara teksnya tetap *monospaced*. Ini adalah varian yang paling sering digunakan untuk mempercantik terminal.<br>
> * Ketik `76` jika Anda mengutamakan kerapian baris kode yang sejajar (Strict Monospace).<br>
> ** File: `JetBrainsMonoNerdFontMono-Regular.ttf`<br>
> ** Kelebihan: Seluruh karakter teks dan ikon dipaksa memiliki lebar yang persis sama (monospace). Sangat aman jika Anda sering menggunakan aplikasi berbasis teks yang rumit agar tata letak tabel atau panel tidak bergeser, meski ukuran ikonnya akan sedikit mengecil.<br>
> Mengapa Menghindari Pilihan Lain?<br>
> * **Nomor 1 - 48** (`NL`): Singkatan dari *No Ligatures*. Jika memilih ini, simbol gabungan seperti `->` tidak akan otomatis berubah menjadi tanda panah keren.<br>
> * Varian `Propo`: Singkatan dari `Proportional`. Font ini memiliki lebar karakter yang berbeda-beda (seperti font tulisan koran/artikel), sehingga akan membuat tampilan teks di terminal Anda berantakan dan tidak sejajar.<br>
> * **Varian selain** `Regular`: Varian seperti **Bold**, **Italic**, atau **Thin** kurang cocok dijadikan font utama karena teks terminal akan menjadi terlalu tebal, miring, atau terlalu tipis sehingga sulit dibaca.<br>
> q: Setelah proses selesai, apakah Anda ingin saya bantu memberikan perintah untuk memverifikasi apakah ikon Nerd Font-nya sudah muncul dengan benar di Termux?<br>
> Untuk memverifikasi apakah **JetBrains Mono Nerd Font** sudah terpasang dan dapat menampilkan semua ikon atau glif dengan sempurna di Termux Anda, jalankan salah satu perintah pengujian di bawah ini:<br>
> Cara 1: Menggunakan Perintah `echo` Sederhana<br>
> Ketik atau salin perintah berikut ke terminal Anda untuk memunculkan beberapa ikon Nerd Font yang paling sering digunakan (seperti logo folder, berkas, jam, Python, dan JavaScript):
```bash
echo -e "\uf07b  \uf15b  \uf017  \ue73c  \ue74e  \uf408"
```
> * Hasil yang benar: Anda akan melihat ikon Folder, Dokumen, Jam, Logo Python, Logo JS, dan Logo GitHub (Kucing).<br>
> * Hasil yang salah: Jika ikon tidak muncul dan hanya menampilkan kotak kosong bergaris silang `[X]` atau tanda tanya `?`, berarti font belum diterapkan dengan benar oleh sistem Termux.<br>
> Cara 2: Menggunakan Skrip Pengujian Resmi<br>
> Jika Anda ingin melihat rincian ikon yang lebih lengkap berdasarkan kategorinya, jalankan skrip pengujian bawaan ini:
```bash
curl -fsSL https://githubusercontent.com | bash
```
> Skrip ini akan mencetak tabel besar berisi ratusan ikon Nerd Font langsung ke layar Termux Anda untuk memastikan tidak ada simbol yang rusak.<br>


# starship-termux

```
curl -sS https://starship.rs | sh
```
> Instal Starship
> Menggunakan Starship Prompts<br>
> Jika alasan utama Anda menyukai Fish + Fisher adalah tampilan `prompt` yang minimalis dan super cepat (seperti tema Pure atau Tide), Anda bisa memasang Starship di atas Bash tanpa perlu menginstal framework besar.<br>

```
> Aktifkan di Bash: Tambahkan perintah berikut ke bagian paling bawah file `~/.bashrc` Anda<br>


# fish-termux

```bash

> 


# fish-pc

```bash
# Tambahkan repositori PPA resmi Fish Shell
sudo add-apt-repository ppa:fish-shell/release-4

# Perbarui daftar paket sistem Anda
sudo apt-get update

# Instal Fish Shell
sudo apt-get install fish
```
> Jika Anda ingin versi terbaru yang stabil langsung dari pengembang Fish, disarankan untuk menambahkan repositori resmi PPA mereka terlebih dahulu sebelum menginstal. Jalankan perintah-perintah berikut secara berurutan<br>
> (Catatan: Jika Anda tidak menambahkan PPA, menjalankan sudo apt-get install fish saja tetap bisa berfungsi, namun Anda mungkin akan mendapatkan versi lama yang disediakan oleh bawaan Ubuntu).<br>


```bash

```
> Cara Menggunakan Fish Shell 🚀<br>
> Setelah proses instalasi selesai, Anda bisa langsung mencoba dan masuk ke dalam shell baru tersebut<br>
> * **Masuk ke Fish**: Ketik `fish` lalu tekan Enter. Tampilan terminal Anda akan berubah, biasanya ditandai dengan perubahan format prompt teks.
> * **Keluar dari Fish**: Ketik `exit` untuk kembali ke shell bawaan Anda sebelumnya (seperti Bash atau Zsh).

```bash
chsh -s /usr/bin/fish
```
> Menjadikan Fish sebagai Shell Utama (Opsional) ⚙️<br>
> Jika Anda sudah merasa cocok dan ingin menjadikan Fish sebagai shell bawaan setiap kali Anda membuka terminal baru.<br>
> Setelah menjalankan perintah ini, silakan log out dari sistem Anda atau restart komputer agar perubahannya aktif.<br>


# q

Jika Anda ingin mempercantik Fish Shell lebih jauh di Termux, saya bisa membantu Anda memasang **Oh My Fish (OMF)** atau **Starship Prompt** agar terminal Anda terlihat sangat profesional. Apakah Anda tertarik mencobanya?



Perintah `umask 077` di sistem Linux/Unix berfungsi untuk **menghapus semua izin akses** bagi `group` (grup) dan `others `(pengguna lain). Ini menghasilkan `privasi tingkat tinggi`.
* Rincian izin akses default yang dihasilkan:
** Untuk File Baru: Menjadi `600` (artinya: pemilik dapat membaca dan menulis, sedangkan yang lain tidak punya akses sama sekali).
** Untuk Direktori Baru: Menjadi `700` (artinya: pemilik dapat membaca, menulis, dan mengeksekusi/masuk ke folder, sedangkan yang lain tidak punya akses sama sekali).

`umask 022`
`chmod 644` (`-rw-r--r--`)
* Pemilik (User): Bisa membaca dan menulis (`rw-`)
* Grup (Group) & Pengguna Lain (Others): Hanya bisa membaca (`r--`)


1. JetBrains Mono (Standar dengan Ligatures)
Font ini menggunakan fitur OpenType di mana dua atau lebih karakter berdampingan secara otomatis digabungkan menjadi satu karakter atau bentuk visual baru yang lebih padat.
* Contoh: != menjadi ≠, === menjadi \(\equiv \), -> menjadi →, dan <= menjadi ≤.
* Kegunaan: Sangat disukai oleh developer karena membuat kode lebih mudah dibaca (clean) dan lebih menyerupai notasi matematika.


2. JetBrains Mono NL (No Ligatures)
Varian ini disediakan khusus untuk pengguna yang lingkungan kerjanya (editor/IDE) tidak mendukung fitur `OpenType` atau bagi programmer yang memang tidak menyukai ligatur.
* **Contoh**: Simbol seperti `!=` atau `->` akan tetap ditampilkan terpisah sebagai dua karakter biasa berdampingan (seperti di font pemrograman tradisional).
* **Kegunaan**: Cocok bagi Anda yang merasa ligatur mengganggu proses *debugging* (karena Anda melihat bentuk karakter aslinya secara persis), atau jika Anda sedang mengikuti pelatihan coding di mana melihat karakter tunggal adalah hal yang krusial.


```
git remote show origin
```
> Cek Detail Status Sinkronisasi.
> Jika Anda ingin melihat informasi lebih mendalam, seperti branch mana yang sedang dilacak (tracked), mana yang sudah kedaluwarsa, atau branch baru yang belum ada di lokal.


```
git config --get remote.origin.url
```
> Cek URL Secara Spesifik via Config
> Jika Anda hanya membutuhkan alamat URL-nya saja (misalnya untuk digunakan dalam skrip otomatisasi).


```
git remote rename origin upstream
```
> Mengganti Nama Remote (Bukan URL)
> Jika Anda ingin mengubah nama panggilannya, misalnya dari `origin` menjadi `upstream`.


```
git remote remove origin
```
> Menghapus Remote
> Jika Anda ingin memutuskan hubungan dengan remote yang sekarang.




```
git clone -q --filter=blob:none --depth 1 https://github.com/ryanoasis/nerd-fonts.git
```


```
# Mengambil riwayat commit yang hilang agar bisa push
git fetch --unshallow
```
> Ubah Shallow menjadi Full (Tapi Tetap Hemat)
> GitHub biasanya menolak push dari repo yang riwayatnya dipotong (depth 1). Agar bisa push tapi tidak mau mengunduh seluruh file sampah, pastikan Anda punya riwayat commit-nya saja tanpa file-file besarnya.
> `--filter=blob:none`, perintah ini hanya akan mengambil data teks (commit log), bukan file font yang besar-besar, jadi tetap cepat.


```
git clone -q --filter=blob:none --sparse https://github.com/ryanoasis/nerd-fonts.git
```


```
git config --global http.version HTTP/1.1
```
```
git config --global --unset http.version
```
> Untuk mengembalikan `http.version` ke pengaturan bawaan (default)


```
git config --global http.postBuffer 524288000
```
```
git config --global --unset http.postBuffer
```

```
git config --global --list
```


```
git sparse-checkout init --cone
```
> Aktifkan Mode Sparse
> Jika Anda baru memulai di dalam folder repo hasil clone `--filter=blob:none`
> Flag `--cone` sangat penting karena ini mengoptimalkan Git untuk hanya mengambil folder secara hierarkis (lebih cepat dan stabil).




```
git sparse-checkout list
```
> Cek Daftar Sparse-Checkout yang Aktif<br>



```
git sparse-checkout set
```
> Cara Menghapus Semua Daftar (Kembali ke Default)<br>
>> Jika Anda ingin membatalkan semua pengaturan sparse dan mengembalikan folder ke keadaan kosong (hanya file di root saja).<br>




```
git sparse-checkout disable
```
> Cara Keluar dari Mode Sparse-Checkout<br>
>> Jika Anda ingin mematikan fitur sparse-checkout sepenuhnya dan mencoba mengunduh seluruh isi repository lagi (kembali ke clone normal)<br>




```
ls -F patched-fonts/
```
> Cara Memastikan Seluruh Isi Folder Terambil<br>

```
ls -R patched-fonts/
```
> Cek Struktur Direktori (Cara Paling Cepat)<br>
> Gunakan perintah `ls` untuk melihat folder apa saja yang ada. Jika berhasil, Anda hanya akan melihat folder yang Anda tambahkan (dan file metadata di root), bukan seluruh isi repository.<br>
















<br>
