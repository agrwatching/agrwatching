- 👋 Hi, I’m watchingX
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
agrwatching/agrwatching is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

tutorial github
jangan lupa download git terlebih dahulu.

git init
Artinya: Menginisialisasi repository Git di folder lokal kamu.
Fungsi: Membuat folder .git tersembunyi di direktori kamu untuk mulai melacak perubahan file dengan Git.

git config --global user.name "Nama Kamu"
git config --global user.email "emailkamu@example.com"

git add README.md
Artinya: Menambahkan file README.md ke staging area.
Fungsi: Memberi tahu Git bahwa kamu ingin menyertakan file ini dalam commit selanjutnya.

3. git commit -m "first commit"
Artinya: Membuat commit pertama dengan pesan "first commit".
Fungsi: Menyimpan snapshot dari file yang sudah di-add tadi ke dalam riwayat versi Git.

4. git branch -M main
Artinya: Mengubah nama branch saat ini menjadi main.
Fungsi: Branch default Git dulu bernama master, sekarang banyak orang menggunakan main sebagai standar.

5. git remote add origin https://github.com/watchingx/Kampus-mengajar-angkatan8.git
Artinya: Menambahkan remote bernama origin yang menunjuk ke URL GitHub tersebut.
Fungsi: Memberitahu Git ke mana kamu ingin mengirim (push) repositorimu secara online.

6. git push -u origin main
Artinya: Mengirim branch main dari repositori lokal ke origin (GitHub).
Fungsi: Upload proyek kamu ke GitHub dan menetapkan origin/main sebagai default upstream branch, jadi ke depannya cukup pakai git push saja.

kemudian jika ingin mengedit projek yang sudah ada tinggal clone.
git clone {copy-paste link}.git
edit ....
git add .
git commit -m "Deskripsi perubahan yang kamu lakukan"
git push
