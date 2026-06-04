# הוראות פרויקט — אתר מדריך Claude Skills

## על הפרויקט
אתר אינטראקטיבי שמלמד מתחילים איך להשתמש ב-Skills של Claude Code.
קובץ ה-PRD המלא נמצא בתיקייה זו: `claude-skills-tutorial-prd.md` — קרא אותו לפני שמתחיל.

## טכנולוגיה
קובץ HTML יחיד עם CSS ו-JS מוטמעים. ללא ספריות חיצוניות.

## מבנה תיקיות הפרויקט
```
ClaudeCodeTut/
├── CLAUDE.md                        ← הוראות לקלוד (הקובץ הזה)
├── claude-skills-tutorial-prd.md   ← PRD מלא
├── index.html                       ← קובץ הפלט הסופי
└── assets/
    ├── images/                      ← צילומי מסך והדרכה
    └── videos/                      ← kling_intro.mp4 וסרטונים נוספים
```

## Assets קיימים
- `kling_intro.mp4` — סרטון פתיחה ל-Hero section

## עיצוב
- צבעי ברירת מחדל: `#ECBFBB`, `#C9A4A0`, `#C19200`, שחור, לבן
- פונטים: Frank Ruhl Libre לכותרות, Heebo לגוף
- סגנון: Glassmorphism, RTL מלא, רספונסיבי
- אנימציות: כניסת Hero בשלבים, מעברים בין שלבים fade+slide

## הוראות בנייה
1. קרא את ה-PRD המלא לפני שמתחיל
2. בנה לפי המבנה: Hero → 5 שלבים עם Sidebar + כפתורי הבא/קודם
3. צור תיקיית `assets/images/` ו-`assets/videos/` בתחילת הבנייה
4. הכנס את `kling_intro.mp4` כסרטון רקע ל-Hero

## Skills רלוונטיים לפרויקט זה
- `frontend-design` — בנייה עם אסתטיקה גבוהה
- `interaction-design` — אנימציות ומעברים
- `emil-design-eng` — פילוסופיית תנועה נכונה
- `ui-ux-pro-max` — מערכת עיצוב
