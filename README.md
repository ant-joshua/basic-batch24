# Catatan

### Cara Initialisasi Git

1. Initialisasi Git

```bash
git init
```

2. Memasukan perubahan file yang akan di upload

```bash
git add .
```

3. Mengatur default email & username

#### (optional) jika belum perlu setting email dan username git

Setting Email Git

```bash
git config user.email "antoniusjoshua47@gmail.com"
```

Setting Username Git

```bash
git config user.name "Antonius Joshua"
```

Notes : tambahkan --global jika tidak ingin setting ulang setiap menginitialisasi git

```bash
git config user.email --global "antoniusjoshua47@gmail.com"
```

4. Memberikan komentar tentang perubahan yang terjadi

```bash
git commit -m "ini messagenya"
```

5. Ini digunakan untuk mengganti default branch dari master ke main

```bash
git branch -M main
```

6. Menyambungkan folder local ke remote repository git

```bash
git add remote origin [url]
```

Contoh nya seperti ini

```bash
git add remote origin https://github.com/ant-joshua/basic-batch24.git
```

### Cara Push Codingan ke Github

```bash
git add .
```

```bash
git commit -m "message nya"
```

```bash
git push
```
