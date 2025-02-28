# Daftar Perintah Git

1. Buat branch baru untuk nama branch 
git checkout -b (nama branch)

2. Buat file baru dan tambahkan konten(nama file)
touch (nama file).txt
echo "Isi (nama file)" > (nama file).txt

3. Tambahkan file ke staging area
git add (nama file).txt

4. Commit perubahan
git commit -m "Menambahkan file (nama file).txt"

5. Pindah kembali ke branch utama (main)
git checkout main

6. Merge branch (nama branch) ke branch utama
git merge (nama branch)

7. Push perubahan ke repositori remote
git push origin main
