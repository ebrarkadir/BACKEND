# 🧠 BACKEND – MERN Places API (Node.js + Express + MongoDB)

Bu proje, `frontend` tarafıyla bağlantılı olarak çalışan RESTful bir API sunar. Kullanıcı ve konum yönetimi işlevlerini yerine getirir.

---

## ⚙️ Özellikler

- ✅ Kullanıcı kayıt ve login (JWT token)
- ✅ Konum oluşturma, güncelleme, silme
- ✅ MongoDB ile veri kalıcılığı
- ✅ Resim yükleme ve saklama (`/uploads/images`)
- ✅ Hata yönetimi ve özel hata sınıfları
- ✅ Frontend: [FRONTEND](https://github.com/ebrarkadir/FRONTEND)

---

## 🚀 Başlatmak için

```bash
cd backend
npm install
npm start
```

Uygulama `http://localhost:5000` adresinden çalışır.

---

## 🔗 API Endpoint'leri

### /api/users

- `POST /signup`
- `POST /login`

### /api/places

- `GET /:pid`
- `GET /user/:uid`
- `POST /`
- `PATCH /:pid`
- `DELETE /:pid`

---

## 🛠️ Kullanılan Teknolojiler

- Node.js + Express.js
- MongoDB (Mongoose ODM)
- Multer (dosya yükleme için)
- JWT Authentication
- CORS ve body-parser middleware

---
