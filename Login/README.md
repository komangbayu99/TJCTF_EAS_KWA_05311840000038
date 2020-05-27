# Login 
## Deskripsi

Could you login into this [very secure site](https://login.tjctf.org/)? Best of luck!

## Flag dari Login

```
tjctf{inevitable890898}
```

## Penyelesaian 

Website tersebut berisi tulisan **Can you log in?** dengan 2 space untuk mengisi username dan password beserta tombol **Login** dibawahnya. 
Untuk mengetahui cara login, inspect element web tersebut. Pada Sources dapat kita ketahui bahwa yang digunakan adalah md5 (ada file bernama md5.js). Pada file index, line ke 70 berisi seperti berikut :

    var _0xb31c=['value','c2a094f7d35f2299b414b6a1b3bd595a','Sorry.\x20Wrong\x20username\x20or\x20password.','admin','tjctf{','getElementsByName','toString'];
    
  
Masukkan username : Admin dan password : inevitable.