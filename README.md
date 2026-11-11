# Tank Jang 3D

4 kishigacha onlayn 3D tank o'yini. Frontend: Three.js. Backend/ma'lumotlar bazasi: Firebase Realtime Database.

## Ishga tushirish
1. Firebase Console → Build → **Realtime Database** → Create database (test mode).
2. Rules bo'limiga `database.rules.json` ichidagini joylang (Publish).
3. Agar bazangiz URL'i `https://bahadir-b268a-default-rtdb.firebaseio.com` dan farq qilsa, `index.html` ichidagi `databaseURL` ni to'g'rilang.
4. Lokal server: `npx serve .` yoki `python -m http.server 8000` → http://localhost:8000
5. Do'stlaringiz bilan bir xil **xona kodi**ni kiriting.

## GitHub'ga yuklash
```bash
cd tank-jang
git init
git add .
git commit -m "Tank Jang 3D"
git branch -M main
git remote add origin https://github.com/<foydalanuvchi>/tank-jang.git
git push -u origin main
```
Keyin Settings → Pages → Branch: main orqali bepul onlayn o'ynash mumkin
(Firebase Console → Authentication → Settings → Authorized domains ga `<foydalanuvchi>.github.io` ni qo'shing).

## Boshqaruv
W/S yurish, A/D burilish, sichqoncha nishon, chap tugma yoki Space – otish.
