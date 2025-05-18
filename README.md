## How to run and what happens?

![image](https://github.com/user-attachments/assets/61ef0f54-85b5-4ebf-90d4-637455344ce9)

Untuk menjalankan task satu server dan tiga client, cukup buka empat terminal masing-masing untuk satu task. Cara runnya,
- Server : `cargo run --bin server`
- Client : `cargo run --bin client`

Terlihat bahwa tiap message yang kita kirim melalui salah satu client, akan diproses oleh server dan akan direturn ke semua client. Perilaku ini sama seperti *broadcast mechanism*.  
