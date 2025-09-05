# 🚀 Next 15 App – API with Backend

A modern **Next.js 15 application** with a fully featured backend using **MongoDB**.  
Includes RESTful APIs for managing **companies**, with CRUD operations, search, pagination, bulk inserts, and more.  

---

## 📖 Documentation

- **Postman API Documentation** → [View Here](https://documenter.getpostman.com/view/39216913/2sB3Hkq13L)  
- **Live Deployment** → [Open App](https://next-with-backend-kalpankaneriya.vercel.app/)  

---

## 🛠️ Tech Stack

- [Next.js 15](https://nextjs.org/) – App Router & API Routes  
- [MongoDB](https://www.mongodb.com/) – NoSQL database  
- [Node.js](https://nodejs.org/) – Server runtime  
- [Postman](https://www.postman.com/) – API documentation & testing  

---
```
NEXT_APP
├── .env.local
├── lib/
│   └── mongodb.js
├── src/
│   └── app/
│       └── api/
│           └── companies/
│               ├── route.js                    # GET (all) & POST (create)
│               ├── search/
│               │   └── route.js                # GET search by city/minBase/skill
│               ├── paginate/
│               │   └── route.js                # GET paginated results
│               ├── count/
│               │   └── route.js                # GET total count
│               ├── bulk/
│               │   └── route.js                # POST bulk insert
│               ├── text-search/
│               │   └── route.js                # GET text search
│               └── [id]/
│                   ├── route.js                # GET/PUT/DELETE by ID
│                   ├── add-benefit/
│                   │   └── route.js            # PATCH add benefit
│                   └── push-round/
│                       └── route.js            # PATCH add interview round
└── package.json
```
---
