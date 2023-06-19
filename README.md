<div dir="rtl">
<p align="center"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://github.com/Sourasky-DHLAB/LLMs/blob/main/Resources/Llamas.png" /></p>
<h1 id="תמלול-אוטומטי-של-וידאו-ואודיו-באמצעות-whisper">מודלי שפה גדולים במדעי הרוח והאמנויות</h1>
<p><a href="https://he.wikipedia.org/wiki/%D7%9E%D7%95%D7%93%D7%9C_%D7%A9%D7%A4%D7%94_%D7%92%D7%93%D7%95%D7%9C" target="_blank" rel="nofollow noopener">מודל שפה גדול</a>&nbsp;(באנגלית: Large Language Model; ראשי תיבות: LLM) הוא אלגוריתם למידה עמוקה שיכול לזהות, לסכם, לתרגם, לחזות ולייצר טקסט וצורות אחרות של תוכן בהתבסס על ידע שנרכש ממערכי נתונים אדירי מימדים.</p>
<p>מודלי שפה גדולים הם טכנולוגיה יוצאת מגדר הרגיל ליצירת טקסט. עם זאת, טכנולוגיה זו עדיין נמצאת בראשיתה ולפיכך סובלת משורה של מגבלות משמעותיות שמקשות על ניצולה לצרכים אקדמיים.</p>
<p>מטרת המחברות במאגר (repository) זה הוא להדגים את הפוטנציאל הגלום בשימוש במודלים מסוג זה לצרכי מחקר, לימוד והוראה במדעי הרוח והאמנויות, וזאת תוך כדי התמודדות עם חלק מן הבעיות הנפוצות במודלי שפה (פרטיות, הוספת ידע חדש, הזיות וכולי).</p>
<h2 id="שימוש-נכון-במחברות">שימוש נכון במחברות</h2>
<p>כדי להשתמש במחברות יש להיעזר ב-Google Colab, כלי שמאפשר לנו לצפות ולהריץ את המחברות שהכנו עבורכם מראש. כדי לפתוח מחברת בסביבת Google Colab יש ללחוץ על הכפתור הבא שנמצא בראשית כל מחברת:</p>
<p align="center"><img src="https://github.com/Sourasky-DHLAB/Whisper/blob/main/Resources/colab.png" /></p>
<h2 id="סוגי-מחברות-במאגר">סוגי מחברות במאגר</h2>
<p>בשלב זה המאגר מכיל שתי מחברות:</p>
<div dir="rtl">1. <a href="https://github.com/Sourasky-DHLAB/LLMs/blob/main/Colab/llama_index_chatgpt.ipynb">llama_index_chatgpt.ipynb</a>: מחברת להוספת ידע חדש אל ChatGPT של חברת OpenAI. באמצעות מחברת זו ניתן לתשאל בשפה טבעית כל קובץ PDF שנמצא ברשותכם. העבודה עם מחברת זו מחייבת <strong>רכישת מפתח API של חברת OpenAI</strong>.<br />2. <a href="https://github.com/Sourasky-DHLAB/LLMs/blob/main/Colab/llama_index_private_llm.ipynb">llama_index_private_llm.ipynb</a>: מחברת להתקנת מודל שפה באופן מקומי בסביבת Colab. מחברת זו תלווה את המשתמשים בהתקנת מודל שפה בעל 5 מיליארד פרמטרים. לאחר ההתקנה המשתמשים יוכלו להוסיף למודל ידע חדש ולתשאל בשפה טבעית קבצים הנמצאים ברשותם.&nbsp;</div>
<div dir="rtl">&nbsp;</div>
<div dir="rtl">שתי המחברות משתמשות במסגרת פיתוח בשם <a href="https://gpt-index.readthedocs.io/en/latest/">llama index</a>, המאפשרת לחבר מקורות מידע שונים למודלי שפה גדולים. בעתיד הקרוב נוסיף מחברות נוספות המשתמשות במסגרת פיתוח דומה בשם <a href="https://python.langchain.com/docs/get_started/introduction.html">langchain</a>, דרכה נדגים תשאול עבודה עם קבצי טקסט ו-CSV.<br /><br />
<h2 id="דוגמה-מתוך-המחברות">דוגמה מתוך המחברות</h2>
<p align="center"><img src="https://github.com/Sourasky-DHLAB/Whisper/blob/main/Resources/screenshot.png" /></p>
</div>
</div>
