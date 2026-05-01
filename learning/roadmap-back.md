<div dir="rtl" align="right">

# 🧩 نقشه راه بک‌اند – چک‌لیست دانش فنی

این فایل یک نمای کلی از تمام مباحث ضروری برای بک‌اند است.  
هدف: آشنایی و توانایی استفادهٔ عملی از هر مفهوم در پروژه‌های واقعی.

> ✅ هر مورد را وقتی یاد گرفتی و تمرین کردی، تیک بزن.  
> 📌 ترتیب پیشنهادی: از بخش پایه شروع کن، سپس سراغ جنگو و دیتابیس برو، بعد FastAPI و مباحث پیشرفته.

---

## 🐍 پایه (Fundamentals)

### Python (Core)
- [ ] نصب و راه‌اندازی (python, pip, virtualenv/venv)
- [ ] متغیرها و انواع داده (int, float, str, bool, list, tuple, dict, set)
- [ ] عملگرها و اولویت آن‌ها
- [ ] ساختارهای شرطی (if, elif, else)
- [ ] حلقه‌ها (for, while, break, continue)
- [ ] توابع (تعریف، پارامترها، return، توابع لامبدا)
- [ ] ماژول‌ها و پکیج‌ها (import, from, __name__)
- [ ] مدیریت فایل (open, read, write, with)
- [ ] کار با تاریخ و زمان (datetime)
- [ ] برخورد با خطا (try, except, finally, raise)
- [ ] لیست درک‌ها (list comprehensions)
- [ ] ژنراتورها (generator, yield)
- [ ] دکوراتورها (decorators)
- [ ] کلاس‌ها و شی‌گرایی (__init__, self, inheritance, polymorphism, magic methods)
- [ ] context managers (with, __enter__, __exit__)
- [ ] نوع‌دهی پویا و نوع‌دهی با type hints

### Git & GitHub
- [ ] مخازن محلی (init, clone, add, commit, status, log)
- [ ] شاخه‌ها (branch, checkout, merge, rebase – پایه)
- [ ] کار با ریموت (pull, push, fetch)
- [ ] conflict و حل آن
- [ ] Pull Request (در گیت‌هاب)
- [ ] آشنایی با GitFlow ساده (main, develop, feature branches)

### شبکه (پایه برای بک‌اند)
- [ ] مدل OSI و TCP/IP (خلاصه)
- [ ] آدرس IP، پورت، DNS
- [ ] پروتکل HTTP/HTTPS (methods: GET, POST, PUT, DELETE, status codes)
- [ ] تفاوت HTTP/1.1 و HTTP/2 (آشنایی)
- [ ] کوکی (cookie) و جلسه (session)
- [ ] وب‌سوکت (WebSocket) – آشنایی

### دیتابیس (مفاهیم اولیه)
- [ ] دیتابیس رابطه‌ای: جداول، رکوردها، کلید اولیه (PK)، کلید خارجی (FK)
- [ ] زبان SQL (SELECT, INSERT, UPDATE, DELETE, JOIN, GROUP BY, ORDER BY)
- [ ] نرمال‌سازی (1NF, 2NF, 3NF)
- [ ] ایندکس (مفهوم و کاربرد)
- [ ] تراکنش (ACID)

---

## 🧱 فریم‌ورک‌های اصلی

### Django
- [ ] ایجاد پروژه و اپلیکیشن
- [ ] مدل‌ها (models) و ORM (query, filter, exclude, annotate)
- [ ] قالب‌ها (templates) و context
- [ ] ویوها (views – تابعی و کلاس‌محور)
- [ ] یوآرال (URL dispatcher)
- [ ] فرم‌ها (forms) و اعتبارسنجی
- [ ] احراز هویت (django.contrib.auth)
- [ ] ادمین پنل (customization)
- [ ] signals (مفاهیم)
- [ ] middleware
- [ ] static & media files (تنظیمات در development)
- [ ] مدیریت خطا (debug, logging)

### Django REST Framework (DRF)
- [ ] نصب و راه‌اندازی
- [ ] سریالایزر (serializers)
- [ ] ویوهایی (APIView, ViewSet, ModelViewSet)
- [ ] روتینگ (routers)
- [ ] احراز هویت (TokenAuthentication, JWT)
- [ ] مجوزها (permissions)
- [ ] پاژینیشن (pagination)
- [ ] فیلتر (filtering, search)
- [ ] مستندسازی (drf-yasg, spectacular)

### FastAPI
- [ ] نصب و اپلیکیشن اولیه
- [ ] مسیریابی و متدها (GET, POST, ...)
- [ ] مدل‌های Pydantic برای validation و serialization
- [ ] dependency injection
- [ ] مدیریت خطا (HTTPException)
- [ ] فایل‌های استاتیک
- [ ] احراز هویت (OAuth2, JWT)
- [ ] WebSocket (پایه)
- [ ] middleware
- [ ] مستندسازی خودکار (Swagger UI, ReDoc)
- [ ] تست با TestClient (pytest)

### Flask (آشنایی)
- [ ] ایجاد اپلیکیشن ساده
- [ ] مسیریابی و Request/Response
- [ ] Jinja2 templates
- [ ] فرم‌ها (Flask-WTF)
- [ ] SQLAlchemy (آشنایی)
- [ ] احراز هویت (Flask-Login)

---

## 🗄️ دیتابیس‌ها

### PostgreSQL
- [ ] نصب و اتصال (psycopg2, asyncpg)
- [ ] انواع داده (integer, varchar, text, date, json, array)
- [ ] ایندکس‌ها (B-tree, hash, GIN)
- [ ] تراکنش و lock
- [ ] view و materialized view
- [ ] stored procedure (پایه)
- [ ] بهینه‌سازی کوئری (EXPLAIN, ANALYZE)

### Redis
- [ ] نصب و اجرا (docker یا مستقیم)
- [ ] انواع داده (string, list, set, sorted set, hash)
- [ ] دستورات پایه (SET, GET, LPUSH, RPUSH, SADD, HSET)
- [ ] کار به عنوان کش (cache)
- [ ] ذخیره جلسه (session storage)
- [ ] pub/sub (انتشار/اشتراک)
- [ ] persistence (RDB, AOF – آشنایی)

### MongoDB (NoSQL)
- [ ] نصب و اتصال (pymongo, motor)
- [ ] اسناد (documents) و مجموعه‌ها (collections)
- [ ] دستورات CRUD (insert, find, update, delete)
- [ ] aggregation pipeline (مراحل پایه)
- [ ] ایندکس در MongoDB
- [ ] تفاوت با دیتابیس رابطه‌ای

---

## ⚙️ سرویس‌ها و ابزارها

### Message Queue & Task Queue
- [ ] Celery (نصب، تنظیم با Redis/RabbitMQ)
- [ ] تعریف تسک (task)
- [ ] اجرای آسنکرون (apply_async, delay)
- [ ] برنامه‌ریزی (periodic tasks – celery beat)
- [ ] Flower (مانیتورینگ – اختیاری)

### Web Server و لینوکس سرور
- [ ] دستورات پایه لینوکس (ls, cd, ps, kill, chmod, systemctl, journalctl)
- [ ] نصب و تنظیم Nginx (reverse proxy, static files)
- [ ] Gunicorn / uWSGI (برای Django)
- [ ] Uvicorn (برای FastAPI)
- [ ] Supervisor (مدیریت پروسه)
- [ ] لاگ‌گیری و دوران لاگ (logrotate)

### سرویس‌های ابری (پایه)
- [ ] معرفی DigitalOcean / Hetzner / Vultr (خرید سرور)
- [ ] اتصال SSH و تنظیمات اولیه (فایروال با ufw, کاربر غیر root)
- [ ] تنظیم دامنه و SSL با Let's Encrypt (Certbot)
- [ ] راه‌اندازی دیتابیس روی سرور (PostgreSQL)
- [ ] بکاپ‌گیری (pg_dump, cron)

---

## 🔒 امنیت (Security)

- [ ] هش کردن رمز عبور (bcrypt, passlib، یا Django built-in)
- [ ] ذخیره امن متغیرهای محیط (python-dotenv, محیط سرور)
- [ ] CORS (تنظیم صحیح در DRF/FastAPI)
- [ ] نرخ محدودیت (rate limiting – django-ratelimit, slowapi)
- [ ] Headers امنیتی (X-Content-Type-Options, X-Frame-Options, CSP – آشنایی)
- [ ] تزریق SQL (SQL Injection – پیشگیری با ORM/parameterized queries)
- [ ] XSS و CSRF (مفاهیم و راهکارها در Django/FastAPI)
- [ ] اعتبارسنجی ورودی (validation با Pydantic/DRF serializers)
- [ ] آشنایی با OWASP Top 10

---

## 🧪 تست و کیفیت (Testing & QA)

- [ ] تست واحد (unit test) با pytest
- [ ] تست یکپارچه‌سازی (integration testing) برای API
- [ ] پوشش تست (coverage.py)
- [ ] mock و patch (برای شبیه‌سازی سرویس‌های خارجی)
- [ ] تست در Django (TestCase, Client)

---

## 🐳 دوآپس پایه (برای بک‌اند)

- [ ] Docker: Dockerfile برای اپلیکیشن
- [ ] docker-compose (برای برنامه + دیتابیس + Redis)
- [ ] GitHub Actions (ساخت و تست خودکار روی push)
- [ ] استقرار ساده روی سرور با docker-compose

---

## 📚 منابع پیشنهادی

| مبحث | منبع پیشنهادی (مکتب‌خونه یا معادل) |
|------|--------------------------------------|
| Python پیشرفته | دوره پیشرفته پایتون مکتب‌خونه |
| Django | دوره جنگو مکتب‌خونه |
| Django REST | دوره DRF |
| FastAPI | دوره FastAPI |
| PostgreSQL | دوره جامع PostgreSQL |
| Redis | دوره Redis (مکتب‌خونه) |
| Docker | دوره Docker |
| Git/GitHub | دوره کنترل نسخه با گیت |

---

## ✅ نحوه استفاده از این چک‌لیست

- هر هفته مرور کن و تیک مواردی را که توانایی استفاده از آن‌ها را در یک پروژه کوچک داری، بزن.  
- اولویت با بخش **پایه**، سپس **Django**، بعد **دیتابیس رابطه‌ای** و در نهایت **FastAPI و بقیه**.  
- در گزارش هفتگی خود می‌توانی به این چک‌لیست ارجاع دهی و پیشرفت‌ات را اعلام کنی.  
- اگر مبحثی نیاز به به‌روزرسانی دارد، به ارین بگو.

> این سند زنده است و با نیازهای پروژه تیم به‌روز می‌شود.

</div>