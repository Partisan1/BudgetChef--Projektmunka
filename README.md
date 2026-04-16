# BudgetChef Webalkalmazás

## 1. Célunk:

- A **BudgetChef** egy elegáns és intuitív receptkezelő webalkalmazás, amely leegyszerűsíti a főzés folyamatát, és segít a receptek rendszerezésében.  
  Célunk, hogy modern, fiatalos felhasználói élményt nyújtsunk: egy olyan felületet, amely vizuálisan vonzó, könnyen kezelhető, és lehetővé teszi a gyors, hatékony főzést a mindennapokban. A platform elsősorban fiatal felnőttek számára készült, akik értékelik a praktikus és stílusos megoldásokat a konyhában.

---

## 3. Telepítés és indítás

A projekt futtatásához kövesd az alábbi lépéseket:

### 4. Docker indítása

```bash
cd ./mysql
docker run -d --name budgetchef -p 3307:3306 -e MYSQL_ROOT_PASSWORD=budgetchef -e MYSQL_DATABASE=budgetchef_db mysql:8.4
```

### 5. Csomagok telepítése

Nyisd meg a terminált a projekt könyvtárában, majd futtasd:

```bash
cd ./backend
npm install
```

Egy új terminálba írd bele a következőt:

```bash
cd ./frontend
npm install
```

### 6. Fejlesztői környezet indítása

#### a) Frontend indítása:

```bash
cd ./frontend
npm run dev
```

#### b) Backend indítása:

```bash
cd ./backend
npx prisma generate
npx prisma migrate dev
npx prisma db seed
npm run start:dev
```

### 7. Backend produkciós indítása (éles környezetben):

```bash
npm run build
npm start:prod
npm run start
```

### 8. Frontend jest tesztelés indítása:

```bash
npm test --LoginComp
npm test --RegisterComp
npm test --ProfileComp
npm test --AdminComp
```

### 9. GitHub elérési útja:

```bash
https://github.com/Partisan1/BudgetChef--Projektmunka.git
```
