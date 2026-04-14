# BudgetChef Webalkalmazás

## 1. Célunk: 
- A **BudgetChef** egy elegáns és intuitív receptkezelő webalkalmazás, amely leegyszerűsíti a főzés folyamatát, és segít a receptek rendszerezésében.  
Célunk, hogy modern, fiatalos felhasználói élményt nyújtsunk: egy olyan felületet, amely vizuálisan vonzó, könnyen kezelhető, és lehetővé teszi a gyors, hatékony főzést a mindennapokban. A platform elsősorban fiatal felnőttek számára készült, akik értékelik a praktikus és stílusos megoldásokat a konyhában.

---

## 2. Telepítés és indítás

A projekt futtatásához kövesd az alábbi lépéseket:

### 3. Csomagok telepítése

Nyisd meg a terminált a projekt könyvtárában, majd futtasd:

```bash
npm install
```
### 4. Fejlesztői környezet indítása

#### a) Frontend indítása:
```bash
npm run dev
```

#### b) Backend indítása:
```bash
npm run start:dev
```

### 5. Backend produkciós indítása (éles környezetben):
```bash
npm run build
npm start:prod
npm run start
```
### 6. Frontend jest tesztelés indítása:
```bash
npm test --LoginComp
npm test --RegisterComp
npm test --ProfileComp
npm test --AdminComp
