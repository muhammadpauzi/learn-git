# Learning GIT

- `git merge` menggabungkan commit dari branch lain (membuat commit baru)
- `git rebase` mirip seperti `git merge` tapi menyimpan commit dari branch yang di merge ke branch utama (langsung)

![alt](./images/image.png)

## Penting

- Hindari rebase pada cabang yang sudah di-push ke remote. Hal ini dapat menyebabkan konflik dan membuat rekan kerja kesulitan untuk melakukan merge.
- Gunakan rebase dengan hati-hati. Meskipun rebase memiliki keuntungan, namun jika digunakan secara sembarangan dapat menyebabkan masalah.

- `git stash` untuk menyimpan perubahan sementara tanpa commit, jadi biasanya ketika kita mengerjakan sesuatu di branch A, tapi kita sadar ada yang lupa pada branch main, namun ketika kita ingin pindah ke branch main, perubahan yang ada pada branch A akan ikut ke branch main, jadi dari pada buat commit baru, mending pakai `git stash` nanti ketika kembali ke branch A lagi, tinggal pakai `git stash pop`
