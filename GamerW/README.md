
# Gamer W 
## Deskripsi

Can you figure out how to [cheat](https://gamer_w.tjctf.org/) the system? Grab his hat to prove your victory!

## Flag dari GamerW

```
tjctf{c3tus_del3tus_ur_m3ms_g0ne}
```

## Cara kerja / Penyelesaian

Pada game tersebut dihimbau harus menggunakan chrome extension **Cetus**. Cetus dimanfaatkan untuk memanipulasi game tersebut. 
Langkah pertama, masuk ke dalam shop. Yang dapat kita ubah adalah value dari gold itu sendiri. Search menggunakan Cetus dengan comparison operator **EQ** dan value type **f32**. 

![Tampilan Cetus](./cetus.png)

Setelah dicari, akan didapatkan kode untuk gold adalah : `0x02111f3c`. Kemudian bookmark dan ubah value goldnya menjadi banyak untuk membeli semua yang ada di shop. 
Level 1 akan melawan 1 monster hijau yang bisa diselesaikan tanpa menggunakan cheat apapun.



Level 2 akan melawan 3 monster hijau yang sama dengan level 1. Dengan sedikit skill untuk bermain game dapat dimenangkan tanpa harus menggunakan cheat



Level 3 akan muncul boss pemilik monster monster tersebut. Boss pada level ini masih dapat dikalahkan tanpa harus menggunakan cheat



Level 4 boss tersebut akan ter-upgrade dan memiliki machine gun yang dapat menembak banyak peluru hijau sekaligus. Disinilah saatnya menggunakan cheat :thumbsup:



Gunakan Cetus untuk mengubah total hp dari pemain kita. Kode untuk hp pemain adalah : `0x2112f1c`. Bookmark dan ubah valuenya menjadi banyak supaya tidak mati-mati saat terkena tembakan hijau.

Level 5 boss akan minum potion yang membuat lifenya regenerate jika terkena serangan. Disini manfaatkan lagi cheat untuk mengubah hp dari bossnya. Boss tersebut memiliki hp 300, dapat diketahui dengan cara menghitung :smirk: . Kode untuk hp boss adalah : `0x2112e4c`. Bookmark, freeze, dan ubah valuenya menjadi 0. 