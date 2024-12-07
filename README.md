### To create authentication and authorization using MongoDB and Node.js

---
# Prerequisites
### Node.js and npm installed.
### MongoDB setup (local or Atlas cloud instance).
---


# Install Dependencies
``` 
npm install express mongoose bcryptjs jsonwebtoken dotenv

```

# Directory Structure
```
auth-app/
│
├── models/
│   └── schema.js
├── routes/
│   └── auth.js
├── app.js
├── .env
└── package.json
```

# Environment Variables
```
MONGO_URI=mongodb://localhost:27017/authdb
JWT_SECRET=your_jwt_secret
```
