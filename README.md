[![Discord](https://img.shields.io/discord/459760634024820736.svg)](https://discord.gg/gx5xc5j)
[![Build Status](https://travis-ci.org/JakeMakesStuff/DCustomRPC.svg?branch=master)](https://travis-ci.org/JakeMakesStuff/DCustomRPC)

# DCustomRPC: The Rewrite!

**האייקון ששומש בפרויקט יוכל להמצא [כאן](https://www.shareicon.net/logo-website-discord-887435).**


הוא ריצ' פריסנס משתמש (כן אתה צודק שם, כן אתה יכול) לשנות אותו DCustomRPC


![intro_img](https://i.imgur.com/8Pf5HjT.png)

## מגדירים את ההגדרות:
ההגדרות די קלות להתקנה:
1.  ותיכנס למשתמש שלך (https://discordapp.com/developers/applications/) לראשונה לך ל

2. מפה, תלחץ על "אפליקציה חדשה" ותן לאפליקציה שם. זה משזה יציג בשורה הראשונה!. "אייקון אפליקציה" ו-"תיאור אפליקציה לא דרושים! אז תתעלמו מהם

3. אחרי זה, אתה אמור להיות בדף האפליקציה. גלגל למטה ותלחץ "הפעל ריצ' פריסנס" ואז "שמור שינויים" זה חשוב

4. אחרי שעשיתה זאת, אתה יכול להעתיק את "מספר הקליינט" (מתחת ל "אודות אפליקציה) ותשנה את ה"מספר קליינט" בקובץ הגדרות

5. כדי להכין את רשימת המשחקים, את/ה תתצתרך להפריד כל סקטציה של משחק על ידי "-" עם המרווח בין מקפים לבין המפתחות הנותרים. כל משחק יכול להכיל את הדברים הבאים

    - `details` - זה התיאור הקצר למשחק

        ![details](https://i.imgur.com/9Z7OdfI.png)
    - `state` - זה התיאור הארוך למשחק

        ![state](https://i.imgur.com/i1YbCfd.png)

    - `large_image` - מקש התמונה עבור התמונה הגדולה על המשחק. כדי לצרף את התמונה שלך למפתח, פתח את דף מפתחי Discord עבור האפליקציה וגלול מטה ל "Rich Presence Assets". מכאן, מכיוון שאנחנו רוצים תמונה גדולה, אנחנו להעלות את התמונה, להזין את המפתח (אשר נכתוב בתצורה) ובחר "גדול". לאחר מכן הקפד ללחוץ על 'העלה נכס' ו'שמור שינויים '. לאחר שנוסיף את התצורה, זה ייראה כך

        ![lg_image](https://i.imgur.com/KbQdc61.png)
    - `large_text` - זהו הטקסט שיופיעה כאשר העכבר ירחף מעל התמונה

        ![lg_text](https://i.imgur.com/nNRHtxo.png)
    - `small_image` - מקש התמונה עבור התמונה הקטנה על המשחק. כדי לצרף את התמונה שלך למפתח, פתח את דף מפתחי Discord עבור האפליקציה וגלול מטה ל "Rich Presence Assets". מכאן, מכיוון שאנחנו רוצים תמונה קטנה, אנחנו להעלות את התמונה, להזין את המפתח (אשר נכתוב בתצורה) ובחר "קטן". לאחר מכן הקפד ללחוץ על 'העלה נכס' ו'שמור שינויים '. לאחר שנוסיף את התצורה, זה ייראה כך

        ![sm_image](https://i.imgur.com/wjo0Nkx.png)
    - `small_text` - זהו הטקסט שיופעיה כאשר העכבר מרחף מעל התמונה הקטנה

        ![sm_text](https://i.imgur.com/EApOnTl.png)

## קישורים שימושיים
[Python 3.6.6](https://www.python.org/downloads/release/python-366/) 

[הורדה: יציב](https://github.com/JakeMakesStuff/DCustomRPC/archive/master.zip) 

##  תנאים מוקדמים של דיסקורד:
בבקשה ודע שסטטוסים משחקיים מופעלים:

![Game Toggle](https://i.imgur.com/V4FWevH.png)

## DCustomRPC התקנה של 
דורש פיית'ון 3.6+. אם יש לך גרסה ישנה יותר אתה תתצתרך להתקין פיית'ון 3.6+ ותוודע שהיא נוספת לפאת', מכאן תוכל להריץ את הקובץ שמתקין את מה שנצתרך לאפליקציה DCustomRPC
1. תפתח/י שורת פקודות והריצו את הקוד הבא
2. `py -m pip install -r requirements.txt`
נסו את האפשרויות האלו עם הראשונה לא פועלת `python3.5 OR python3.6`-יכול להשתנות ל `py`-נ.ב. ה 


## בשורת פקודות DCustomRPC איך מפעילים 
כדי להריץ ולבדוק שהכול פועל בשורת הפקודות.
1. תפתחו את השורת פקודות
2. `py dcustomrpc.pyw` תריצו

## Starting DCustomRPC on Windows Boot: 
## על הדלקת המחשב DCustomRPC הפעלת 
בוינדואס כדי להריץ את התוכנה על הדלקת המחשב. זה פשוט
1. `dcustomrpc.pyw` כחו את הקובץ 
2. לחצו על הקובץ עם הכפתור הימני של העכבר שלכם ותלחצו על "שלח ל" ועז תלחצו על "שולחן עבודה" וזה יצור קיצור דרך לתוכנה 
3. אז תכתכו את הקובץ מהשולחן עבודה
4. `shell:startup` לכו ל  
5. בוינדואז אקספלורר תעתיקו את הקובץ לשם

תודה לג'ייק שנתן לי רשות לתרגם את הפרויקט



All credit goes to its responsible owners and creators,
Thanks to Jake for letting me translate this project!
