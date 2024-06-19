# ecoland-backend-api

## Getting Started

Hai! Untuk memulai menjalakan program ini secara lokal yang perlu dilakukan adalah:
Pertama, clone repository ini ke local

```bash
git clone https://github.com/Ecoland-C624-PS008/ecoland-backend-api.git
```

Kemudian langkah selanjutnya adalah install package dan module yang diperlukan dengan *NPM*

```bash
cd ecoland-backend-api
npm install
```
Terakhir bisa jalankan script berikut untuk menjalankan program node.js

```bash
npm run dev
```

---

## Endpoints

**Base Url** :  `https://ecoland-backend-api.onrender.com/`

| Endpoint | Usage | Example | Method |
|----------|-------|---------|----------|
| `/login` | Login user | - |  POST  |
| `/register` | Register user | - |  POST   |
| `/me` | Get user data  | - |  GET   |
| `logout` | End session | `api/articles/?cat=Fermentasi` |  DELETE   |
| `/api/articles/:id` | Get Article by Id | `/api/articles/65616bd5f02afdb3f4f95a01` |   GET  |
| `/api/articles/:id` | Update Article | `/api/articles/65616bd5f02afdb3f4f95a01` |  PUT  |
| `/api/articles/:id` | Delete Article | `/api/articles/65616bd5f02afdb3f4f95a01` |  DELETE  |

| Endpoint | Usage | Example | Method |
|----------|-------|---------|----------|
| `/lands` | Get lands data | - |  GET  |
| `/lands/:id` | Get land by id | `/lands/824da653-8ae0-421a-a6da-8a098cd0e9a8` |  GET   |
| `/lands/:id` | Update land data  | `/lands/824da653-8ae0-421a-a6da-8a098cd0e9a8` |  PATCH   |
| `/lands-admin` | Post lands data by Admin | - |  POST   |
| `/lands-admin/:id` | Update land data by Admin | `/lands-admin/824da653-8ae0-421a-a6da-8a098cd0e9a8` |   PATCH  |
| `/lands-admin/:id` | Delete land data by Admin | `/lands-admin/824da653-8ae0-421a-a6da-8a098cd0e9a8` |  DELETE  |

| Endpoint | Usage | Example | Method |
|----------|-------|---------|----------|
| `/users` | Get users by Admin | - |  GET  |
| `/users/:id` | Get user by id | `/users/4bfbd5b4-89d5-418c-a7d7-6df7add35abc` |  GET   |
| `/users` | Post users  | `/users` |  POST   |
| `/users/:id` | Update user data by id | `/users/4bfbd5b4-89d5-418c-a7d7-6df7add35abc` |  PATCH   |
| `/users/:id` | Delete user data by id | `/users/4bfbd5b4-89d5-418c-a7d7-6df7add35abc` |   DELETE  |
