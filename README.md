Member Branch
 - Valerie = member1
 - Alice = member2
 - Jovito = member3



Valerie = adat, kuliner, sejarah, seni

Jovito = beranda, about, map

Alice = css, menyesuaikan seluruh halamannya.


1. Sebelum berkerja; "git pull origin main" 
2. Kerjain websitenya.
3. Setelah selesai kerja:
    git add . (jangan lupa titik)

    git commit -m "Describe what you changed"

    contoh: git commit -m "Menambahkan berita
4. git push origin member*

    Example:
    git push origin member3


Simplenya:

Pull main

Kerja

git add .   

git commit -m "..."

git push origin member*

(member* diganti dngn nomor masing2, contoh: git push origin member3)


Info:

- **setiap kerja harus ngikutin proses yang diatas... soalnya kita ngga bisa ngerjain 1 file dalam waktu yang sama**

- branch main, member1, member2, member3 semuanya beda. makanya setiap sebelum kerja harus "git pull origin main"(gunanya biar in sync filenya sama yang lain). setiap ada update di masing-masing branch member nanti perlahan diupdate ke main. Gunanya updatenya perlahan biar nanti pada saat ada 2 orang yang kerja bersamaan ga ada error/aneh aneh yang terjadi.

- Kalo kamu git pull origin main, tapi kamu udah ada ngerjain sesuatu di branch mu kerjaan mu bisa ngilang. jadi nanti git push dulu ke branch mu sendiri, nanti kalo sudah gabung sama main baru bisa git pull lagi.
