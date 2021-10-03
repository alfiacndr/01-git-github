# 01-git-github
Langkah Langkah Github

Pada pertemuan kali ini kita akan mempelajari tata cara penggunaan Github
1. Melakukan Instalasi Git

2. Melakukan konfigurasi

    Konfigurasi ini diperlukan agar Git mengetahui pengaksesnya melalui user name dan user email


        ALFIA@DESKTOP-K23RKUL MINGW64 ~
        $ git config --global user.name "alfiacndr"

        ALFIA@DESKTOP-K23RKUL MINGW64 ~
        $ git config --global user.email alfiacndr28@gmail.com

    Cara mengecek apakah konfigurasinya berjalan


        ALFIA@DESKTOP-K23RKUL MINGW64 ~
        $ git config --list
        diff.astextplain.textconv=astextplain
        filter.lfs.clean=git-lfs clean -- %f
        filter.lfs.smudge=git-lfs smudge -- %f
        filter.lfs.process=git-lfs filter-process
        filter.lfs.required=true
        http.sslbackend=openssl
        http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
        core.autocrlf=true
        core.fscache=true
        core.symlinks=false
        pull.rebase=false
        credential.helper=manager-core
        credential.https://dev.azure.com.usehttppath=true
        init.defaultbranch=master
        core.editor="C:\Users\ALFIA\AppData\Local\Programs\Microsoft VS Code\Code.exe" --wait
        user.name=alfiacndr
        user.email=alfiacndr28@gmail.com

3. Membuat akun github dengan melengkapi data

4. membuat repository kosong di github baik secara private maupun publik

5. Melakukan clone repository kosong tersebut ke komputer lokal dengan menggunakan gitbash


        ALFIA@DESKTOP-K23RKUL MINGW64 ~/mdplprak/01-git-github
        $ git clone https://github.com/alfiacndr/01-git-github.git
        Cloning into '01-git-github'...
        remote: Enumerating objects: 3, done.
        remote: Counting objects: 100% (3/3), done.
        remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
        Receiving objects: 100% (3/3), done.

6. Mengubah repo master menjadi main


        ALFIA@DESKTOP-K23RKUL MINGW64 ~/mdplprak/01-git-github
        $ cd 01-git-github

        ALFIA@DESKTOP-K23RKUL MINGW64 ~/mdplprak/01-git-github/01-git-github (main)
        $ git branch -m main

7. Mengelola repo sendiri

    Semua manipulasi konten dilakukan di komputer lokal dan hasilnya akan di-push ke remote repo di GitHub. Selanjutnya tinggal push ke repo github
