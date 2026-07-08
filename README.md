# תרגול — אסטרטגיות פיננסיות

אפליקציית ווב (עברית, RTL, Mobile-First) לתרגול לקראת המבחן:
בחנים בשאלות ברירה עם משוב מיידי, סימולציית מבחן משוקללת ותשעה מחשבונים פיננסיים חיים.

## הפעלה מקומית

פתחו את `index.html` בכל דפדפן. עובד offline.

## Deploy ל-GitHub Pages

התיקייה הזו מוכנה כמו שהיא ל-Pages — כוללת `index.html` יחיד ו-`.nojekyll`.

```bash
# מתוך התיקייה הזו (deploy/):
git init -b main
git add .
git commit -m "Initial deploy"
git remote add origin https://github.com/<שם-משתמש>/<שם-repo>.git
git push -u origin main
```

ואז ב-GitHub → Settings → Pages → Source: `main` / root → Save.
כתובת האפליקציה תהיה `https://<שם-משתמש>.github.io/<שם-repo>/`.

## תוספת למובייל

באייפון/אנדרואיד — לחצו על "שיתוף" בדפדפן → "הוסף למסך הבית" ותקבלו אייקון שנפתח במסך מלא כמו אפליקציה.
