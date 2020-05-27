# Ling Ling 
## Deskripsi

Who made this meme? 

## Flag dai Ling-Ling

```
tjctf{ch0p1n_fl4gs}
```

## Cara pengerjaan / Penyelesaian

Setelah mengunduh gambar, dapat dilihat gambar tersebut adalah meme dengan not balok Chopins Third Ballade. Dari soal dapat diketahui yang dicari adalah pembuat dari meme tersebut. Untuk mendapatkan data tersebut dapat menggunakan `exiftool` dan grep pada `terminal`. 

    $ exiftool meme.png | grep Artist
    
  
Setelah itu akan muncul langsung Artist/pembuat dari meme tersebut.