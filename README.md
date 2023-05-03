## Notes App
### Praktik Membuat Aplikasi Back-End Menggunakan NodeJS (Hapi Framework)

> Pada branch develop terdapat beberapa modifikasi yang kemungkinan kamu cari. Lets check!

### Run Server 
```bash
npm run start-dev
```

> Untuk menggunakan postman collection and environment, harus menggunakan `newman`.
### Run Postman Collection dengan Newman
```bash
newman run notes-api-test.postman_collection.json --environment notes-api-test.postman_environment.json
```