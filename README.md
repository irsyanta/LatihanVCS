##TUTORIAL VCS

1. Login/buat akun github, lalu buat repository baru
![Login Github](Screenshot/buat_repository.PNG)
2. Login Git di cmd, dengan perintah:
`$ git config --global user.name "UsernameAnda"`
`$ git config --global user.email "EmailAnda"`
![Login CMD](Screenshot/login_cmd.PNG)
3. Buat folder **"Latihan VCS"**
![Buat File](Screenshot/buat_file.PNG)
4. Klik **"Git Bash Here"** pada folder **"LatihanVCS"**
![Git Bash](Screenshot/git_bash.PNG)
5. Ubah folder menjadi repository dengan mengetik `$ git init`
![Init](Screenshot/init.PNG)
6. Tambahkan file ke repository dengan membuat **README.md** lalu ketik `$ git add README.md`
![Input](Screenshot/input.PNG)
7.Buat commit dengan mengetik `$ git commit -m "Commit Pertama"`
![Commit](Screenshot/commit.PNG)
8. Remote repository Github dengan cara mengetik `$ git remote add origin git@github.com:UserNameGit/NamaRepository.git`
![Remote](Screenshot/remote.PNG)
9. Push ke Github dengan mengetik `$ git push -u origin master`
![login2](Screenshot/login.PNG)
10. Jika terjadi error seperti gambar dibawah, kita bisa mengakalinya dengan command `$ git remote set-url "linkgithubkalian.git"
![Error](Screenshot/eror.PNG)
11. Jika berhasil maka akan muncul tulisan seperti berikut: 
![sukses](Screenshot/sukses.PNG)
