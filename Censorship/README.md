# Censorship 
## Deskripsi

My friend has some top-secret government intel. He left a message, but the government censored him! They didn't want the information to be leaked, but can you find out what he was trying to say? ```nc p1.tjctf.org 8003```

## Flag dari Censorship

```
tjctf{TH3_1llum1n4ti_I5_R3aL}
```

## Cara Pengerjaan /Penyelesaian

1. Buka lah aplikasi wireshark yang ada di pc. setelah itu screemshot(ss) salah satu wired interface yang tersedia
2. Setelah itu Jalankan perintah berikut ```nc p1.tjctf.org 8003``` pada linux terminal, kemudian jawab pertanyaan yang ada. Setelah itu, terdapat pilihan-pilihan baru yang sudah terscreenshot oleh wireshark 

3. Pada wireshark export packet dengan cara pilih ```File - Export Packet Disserctions - As Plain Text...``` ;

4. Buka paket yang tentunya sudah diexport tadi pada text editor, kemudian cari kata kunci dengan cara tekan ```ctrl + f``` lalu ketik ```"tjctf{"```. Maka flag akan ditemukan.