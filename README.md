# How to run Project
## ติดตั้ง node_module
ติดตั้งที่ login-api และ react-resize
```
cd login-api
npm install

cd react-resize
npm install
```

---

## Login-api
ต่อไปเป็นการรัน service Node Express
```
cd login-api
nodemon app.js
```

---

## React-resize
ต่อไปเป็นการรัน service React.js
```
cd react-resize
npm start
```

---

## resize-api
ต่อไปเป็นการรัน service resize-api (API การปรับขนาดภาพ)
```
cd resize-api
uvicorn main:app --reload
```

---
