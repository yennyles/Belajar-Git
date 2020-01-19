# Belajar-Git
Nyobain main Git dari dasar

### 1. Jadikan folder jadi repo git 
git init

### 2. Add file di folder ke repo
git add *.html >> Add semua file dgn extensi html
git add . >> add semua file
git add namafile.ext >> Add file "namafile.ext

### 3. Commit 
git commit -m "Tulis komentar..." >>> Tulis komentar misal : commit pertama, kedua, ketiga, setelah add file

### 4. Upload ke github/gitlab/bitbucket, etc
Set URL
git remote add origin https://ALAMAT/NAMAREPO.git 
push
git push -u origin "namabranch" >> nama branch default master, bisa lain2

### Note:
git remote set-url origin https://new.url.here >>> untuk mengubah alamat repo yg baru


## Referensi :
##### https://www.petanikode.com/tutorial/git/
##### https://medium.com/aisy-rozsidhy/tutorial-penggunaan-github-untuk-pemula-part-1-upload-file-ke-github-e807df4e9ecc
