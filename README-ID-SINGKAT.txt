Pakai repo/folder ini untuk deploy ke Worker yang SUDAH kamu buat di Cloudflare: floral-frost-f5c1

Penting:
- Nama worker di wrangler.toml sudah disamakan ke floral-frost-f5c1
- Binding di dashboard harus: DB dan MAIL_KV
- Variable di dashboard harus: MAIL_DOMAINS, EXPIRE_MINUTES, MESSAGE_RETENTION_DAYS
- ACCESS_KEY tetap pakai Secret di dashboard
- Setelah deploy code, jalankan isi schema.sql ke D1 Console
