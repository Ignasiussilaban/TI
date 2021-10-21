# 1. Cara Install Git di OS LinUX
Instalasi Git pada Distro keluarga Debian dapat menggunakan perintah **apt** pada terminal.

```sudo apt install git```  **atau** ```sudo apt-get install git```


Untuk Distro Fedora :

```yum install git```

Untuk melihat versi GIT yang terinstal dengan perintah :

```git --version```

# 2. Cara Install Git di OS WindoWS
Instalasi Git di Windows memang tidak seperti di Linux yang ketik perintah langsung terinstal. Kita harus men-download dulu, kemudian melakukan ritual *next>next>finish*.
Tapi dalam proses instalasi, ada pilihan yang harus diperhatikan agar perintah git dapat dikenali di **CMD**.

## Download Git
Silahkan buka website resminya Git di <https://git-scm.com>. Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.

![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/git-scm.com.png?raw=true)

![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/Downloadinggit.png?raw=true)

## Git-2.33.1-64-bit.exe
![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/FileGit.png?raw=true)

## Langkah-langkah Install Git di Windows

Baiklah, mari kita mulai proses instalasinya. Dengan mengklik 2x file instaler Git yang sudah diunduh, atau Klik kanan pada file dan pilih **run as administrator**.

![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/klikkanan.png?raw=true)

# 3. Konfigurasi Awal yang Harus Dilakukan
Ada beberapa konfigurasi yang harus dupersiapakan sebelum mulai menggunakan Git, seperti name dan email.

Silahkan lakukan konfigurasi dengan perintah berikut ini.

Maka akan muncul informasi licensi git, pilih **next** untuk melanjutkan proses selanjutnya.

![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/licensi.png?raw=true)

Selanjutnya menentukan lokasi instalasi. Biarkan saja apa adanya, kemudian terus klik **Next** > sampai pada tahap **install**.

![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/install.png?raw=true)

Tunggu proses instalasi sampai selesai,

![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/installing.png?raw=true)

Setelah selesai, kita bisa langsung klik **Finish**.

![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/finish.png?raw=true)

Selamat, Git sudah terinstal di Windows dan sudah terhubung langsung ke **CMD**. Untuk mencobanya, silahkan buka **CMD** atau **PowerShell**, kemudian ketik perintah ```git --version```.

![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/gitCMD.png?raw=true)

# 3. Konfigurasi Awal yang Harus Dilakukan
Ada beberapa konfigurasi yang harus dupersiapakan sebelum mulai menggunakan Git, seperti **name** dan **email**.

Silahkan lakukan konfigurasi dengan perintah berikut ini.

```git config --global user.name "Tior3turn"```
```git config --global user.email "ignaslabantio@gmail.com"```

Kemudian periksa konfigurasinya dengan perintah:

```git config --list```

Apabila berhasil tampil seperti gambar berikut ini, berarti konfigurasi berhasil.

![https://git-scm.com](https://github.com/Tior3turn/TI/blob/main/Tugas/ProgramVCS/Image/gitconfig.png?raw=true)
