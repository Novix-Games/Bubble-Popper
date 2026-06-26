# Bubble Popper — PWA Deployment Guide

## הוראות העלאה ל-GitHub Pages (חינם)

### שלב 1 — GitHub
1. כנס ל- https://github.com ו-**Sign Up** (חינם)
2. לחץ **New Repository**
3. שם: `bubble-popper`
4. בחר **Public**
5. לחץ **Create Repository**

### שלב 2 — העלאת הקבצים
העלה את כל הקבצים בתיקייה הזו (גרור לדפדפן ב-GitHub):
```
index.html
manifest.json
sw.js
icons/
```

### שלב 3 — הפעלת GitHub Pages
1. Settings → Pages
2. Source: **Deploy from a branch**
3. Branch: **main** / root
4. Save

### שלב 4 — הכתובת שלך
אחרי ~2 דקות האפליקציה תהיה ב:
```
https://YOUR_USERNAME.github.io/bubble-popper/
```

### התקנה על הטלפון (Android)
1. פתח Chrome עם הכתובת
2. תפריט ⋮ → **Add to Home screen**
3. מותקן כאפליקציה מלאה ✓

### התקנה על הטלפון (iPhone)
1. פתח Safari עם הכתובת
2. שתף ↑ → **Add to Home Screen**
3. מותקן ✓

---

## עדכונים עתידיים
כל פעם שתשנה את bubble-popper.html:
1. העלה את הקובץ החדש ל-GitHub (גרור ושמור)
2. שנה `CACHE_NAME` ב-sw.js (v1→v2) כדי לאלץ רענון
3. המשתמשים יקבלו את הגרסה החדשה אוטומטית

---

## שלב הבא — Google Play (אופציונלי)
לאחר שיש URL פעיל של GitHub Pages:
1. כנס ל- https://pwabuilder.com
2. הכנס את ה-URL שלך
3. לחץ **Package for stores** → Android
4. מוריד APK מוכן להעלאה ל-Play Store
