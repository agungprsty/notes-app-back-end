## Praktik Membuat Aplikasi Back-End Menggunakan NodeJS (Hapi Framework)

> Untuk menggunakan postman collection and environment, harus menggunakan `newman`.

### Jalankan server 
```bash
npm run start-dev
```

### Jalankan Postman Collection dengan Newman
```bash
newman run notes-api-test.postman_collection.json --environment notes-api-test.postman_environment.json
```