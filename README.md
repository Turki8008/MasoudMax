# MiniMax Telegram Bot 🤖

بوت تليجرام للتواصل مع مساعد الذكاء الاصطناعي MiniMax

## 🚀 سريع البدء

### 1. المتطلبات
- Python 3.8 أو أعلى
- حساب تليجرام

### 2. التثبيت

```bash
# استنساخ المشروع
git clone <repository-url>
cd telegram-bot

# إنشاء بيئة افتراضية
python -m venv venv

# تفعيل البيئة (Linux/Mac)
source venv/bin/activate

# تفعيل البيئة (Windows)
venv\Scripts\activate

# تثبيت المكتبات
pip install -r requirements.txt
```

### 3. التشغيل

```bash
# الطريقة 1: تعيين المتغير البيئي وتشغيل
export TELEGRAM_BOT_TOKEN="YOUR_TOKEN_HERE"
python bot.py

# الطريقة 2: إنشاء ملف .env
echo "TELEGRAM_BOT_TOKEN=YOUR_TOKEN_HERE" > .env
python bot.py
```

### 4. استخدام البوت

1. افتح تليجرام
2. ابحث عن بوتك
3. اضغط `/start`
4. أرسل أي رسالة!

## 📁 هيكل المشروع

```
telegram-bot/
├── bot.py              # الكود الرئيسي
├── requirements.txt    # المكتبات
├── .env               # المتغيرات البيئية (لا تشاركه!)
└── README.md         # هذا الملف
```

## ⚠️ معلومات مهمة

### خصوصية الـ Token
- **لا تشارك ملف `.env` مع أي شخص!**
- **لا ترفعه على GitHub!**
- أضفه دائماً إلى `.gitignore`

### تشغيل البوت باستمرار
لبوت يعمل 24/7، فكر في:
- **Railway** (مجاني)
- **Render** (مجاني)
- **Heroku** (مجاني مع قيود)
- ** VPS خاص**

## 🔧 التخصيص

يمكنك تعديل البوت لإضافة ميزات أكثر:
- ربط مع OpenAI API
- ربط مع Claude API
- إضافة قاعدة بيانات
- إضافة أوامر مخصصة

## 📝 الأوامر المتاحة

| الأمر | الوصف |
|-------|-------|
| `/start` | بدء المحادثة |
| `/help` | عرض المساعدة |
| `/about` | معلومات عن البوت |

## 🛠️ حل المشاكل

### خطأ: "Bot token rejected"
- تأكد من صحة الـ Token
- تأكد من عدم وجود مسافات إضافية

### خطأ: "python-telegram-bot not found"
```bash
pip install python-telegram-bot==20.7
```

### خطأ: "No module named 'dotenv'"
```bash
pip install python-dotenv
```

## 📧 التواصل

للمساعدة أو الاستفسارات، تواصل مع المطور.
