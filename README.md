# panda-lesson-5
panda lesson 5

מחיקת שורות עם לפחות NaN אחד → dropna(how='any')
מחיקת שורות עם NaN בכל העמודות → dropna(how='all')
מחיקת שורות עם NaN רק בעמודות A ו-C → dropna(subset=['A', 'C'])
החלפת כל NaN בערך מוגדר (למשל 0) → fillna(0)
החלפת NaN בעמודה B בממוצע העמודה → fillna(mean_B)
