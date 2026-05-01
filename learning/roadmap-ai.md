<div dir="rtl" align="right">

# 🤖 نقشه راه هوش مصنوعی – چک‌لیست دانش فنی

این مسیر برای اعضایی طراحی شده که می‌خواهند **مدل‌های هوش مصنوعی را در پروژه‌های وب تیم استفاده کنند** – چه از طریق APIهای آماده و چه با اجرای مدل‌های متن‌باز روی سرور.

> ✅ هدف: توانایی **استفاده، شخصی‌سازی سبک و بسته‌بندی مدل‌ها** به عنوان یک سرویس.  
> 📌 قرار نیست پژوهشگر یادگیری عمیق بشویم؛ قرار است از ابزارهای موجود استفاده عملی کنیم.

---

## 🐍 پایه (Fundamentals)

### Python برای علم داده
- [ ] نصب و مدیریت کتابخانه‌ها (pip, virtualenv, conda – آشنایی)
- [ ] کار با آرایه‌ها و ماتریس‌ها با **NumPy** (آرایه‌های n بعدی، برش، ایندکس‌گذاری، عملیات برداری)
- [ ] کار با داده‌های جدولی با **Pandas** (Series, DataFrame, خواندن/نوشتن فایل، فیلتر، گروه‌بندی، ادغام)
- [ ] مصورسازی ساده با **Matplotlib** و **Seaborn** (نمودار خطی، پراکندگی، هیستوگرام)
- [ ] مدیریت داده‌های حجیم (sample, chunking – آشنایی)

### آمار و مبانی ریاضی (اختیاری ولی مفید)
- [ ] آمار توصیفی (میانگین، میانه، انحراف معیار)
- [ ] احتمال شرطی
- [ ] جبر خطی (بردارها، ماتریس‌ها، ضرب ماتریس)
- [ ] مشتق و گرادیان (مفهوم)

### مفاهیم پایه هوش مصنوعی
- [ ] تفاوت AI, Machine Learning, Deep Learning
- [ ] یادگیری نظارت شده (Supervised) و بدون نظارت (Unsupervised)
- [ ] مدل‌های ساده (رگرسیون خطی، رگرسیون لجستیک، درخت تصمیم) – **مفاهیم نه پیاده‌سازی از صفر**
- [ ] معیارهای ارزیابی (accuracy, precision, recall, F1, RMSE)
- [ ] بیش‌برازش (Overfitting) و کم‌برازش (Underfitting)
- [ ] مجموعه‌های آموزش (train)، اعتبارسنجی (validation) و تست (test)
- [ ] یادگیری انتقالی (Transfer Learning) – **مفهوم کلیدی برای استفاده از مدل‌های آماده**

---

## 📚 کتابخانه‌های پردازش داده و یادگیری ماشین

### Scikit-learn (برای مدل‌های کلاسیک)
- [ ] پیش‌پردازش داده (StandardScaler, MinMaxScaler, OneHotEncoder)
- [ ] تقسیم داده به train/test (train_test_split)
- [ ] مدل‌های پایه (LinearRegression, LogisticRegression, RandomForestClassifier)
- [ ] ارزیابی (accuracy_score, classification_report, confusion_matrix)
- [ ] Pipeline (اختیاری)

### HuggingFace Transformers (پرتکرارترین)
- [ ] نصب و آشنایی با Ecosystem (transformers, datasets, tokenizers)
- [ ] بارگذاری یک مدل زبانی از پیش‌آموزش‌دیده (مثلاً `distilbert-base-uncased`)
- [ ] توکن‌سازی (tokenizer)
- [ ] fine-tuning سبک روی داده فارسی (با Trainer API یا PyTorch ساده)
- [ ] استفاده از پایپلاین‌های آماده (text-generation, summarization, sentiment-analysis)
- [ ] ذخیره و بارگذاری مدل fine-tuned

### سایر مدل‌های آماده
- [ ] استفاده از LLMها از طریق API (OpenAI, Claude, Gemini – در صورت دسترسی)
- [ ] استفاده از مدل‌های بینایی (vision) با HuggingFace (تصویر به متن، تشخیص اشیاء – اختیاری)

---

## 🔬 یادگیری عمیق (مقدماتی)

### PyTorch (Basic)
- [ ] تنسورها (tensors) و عملیات روی آن‌ها
- [ ] Autograd (محاسبه خودکار گرادیان)
- [ ] ساخت یک شبکه ساده با `nn.Module`
- [ ] لایه‌های رایج (Linear, Conv2d, RNN, LSTM – آشنایی)
- [ ] حلقه آموزش (loss, optimizer, backward, step)
- [ ] Dataset و DataLoader
- [ ] ذخیره و بارگذاری مدل (`torch.save`, `load_state_dict`)
- [ ] استفاده از مدل‌های پیش‌آموزش‌دیده (torchvision models)
- [ ] انتقال به GPU (`.to(device)`)

### TensorFlow / Keras (Basic)
- [ ] مدل‌های Sequential
- [ ] لایه‌های پایه (Dense, Flatten, Conv2D)
- [ ] کامپایل (compile) و fit
- [ ] ارزیابی و پیش‌بینی
- [ ] استفاده از مدل‌های پیش‌آموزش‌دیده (TensorFlow Hub یا Keras Applications)

> 📌 برای شروع، **PyTorch کافی است**؛ TensorFlow آشنایی سطحی داشته باشی خوب است.

---

## 🧠 مفاهیم کلیدی در استفاده از مدل‌های زبان (NLP)

- [ ] توکن‌سازی (tokenization) و vocab
- [ ] attention mechanism (مفهوم)
- [ ] معماری Transformer (خلاصه)
- [ ] embedding
- [ ] پردازش متن فارسی (نرمال‌سازی، حذف علائم، tokenizerهای فارسی مثل `parsgpt-tokenizer`)

---

## 🌐 بسته‌بندی و ارائه مدل (سرویس)

### FastAPI برای هوش مصنوعی
- [ ] بارگذاری مدل هنگام استارت اپلیکیشن
- [ ] ایجاد endpoint برای پیش‌بینی (POST /predict)
- [ ] تبدیل ورودی به تنسور و برعکس
- [ ] مدیریت حافظه (تمیز کردن کش، بارگذاری lazy)

### ONNX و بهینه‌سازی (اختیاری)
- [ ] تبدیل مدل PyTorch به ONNX
- [ ] اجرا با ONNX Runtime

### Docker برای مدل
- [ ] Dockerfile برای سرویس FastAPI
- [ ] docker-compose شامل مدل + دیتابیس + کش

---

## 🧪 تست و مانیتورینگ

- [ ] تست یکپارچه برای endpoint مدل (pytest + FastAPI TestClient)
- [ ] ثبت لاگ (متن درخواست، زمان پاسخ، خطاها)
- [ ] سنجش latency و بهینه‌سازی (چند نمونه)
- [ ] fallback برای وقتی مدل پاسخ نمی‌دهد (مثلاً پاسخ از پیش تعیین شده)

---

## 📦 کتابخانه‌ها و ابزارهای کمکی

- [ ] کتابخانه‌هایی برای پردازش زبان فارسی (hazm, parsivar – اختیاری)
- [ ] sentence-transformers (embedding متن)
- [ ] chromadb یا faiss (ذخیره و بازیابی بردارها – برای RAG ساده)
- [ ] LangChain (آشنایی – برای زنجیره‌سازی LLM و ابزارها)

---

## 🧭 نحوه استفاده از این چک‌لیست

- **اولویت اول:** پایه (Python, Pandas, NumPy، مفاهیم)
- **اولویت دوم:** HuggingFace Transformers و FastAPI (زیرا سریع‌ترین راه برای استفاده عملی است)
- **اولویت سوم:** PyTorch مقدماتی (برای درک و شخصی‌سازی)
- **اختیاری:** TensorFlow, ONNX, LangChain

> در پروژه اولیه تیم (مثلاً رزومه‌ساز هوشمند) از **یک API آماده (مانند HuggingFace) یا مدل کوچک متن‌باز** استفاده می‌کنیم. نیازی به آموزش مدل عظیم از صفر نیست.

---

## 📚 منابع پیشنهادی

| مبحث | منبع پیشنهادی |
|------|----------------|
| Python برای داده | دوره NumPy/Pandas مکتب‌خونه |
| مفاهیم ML | دوره یادگیری ماشین مکتب‌خونه |
| HuggingFace | مستندات رسمی HuggingFace + دوره فارسی (در صورت وجود) |
| PyTorch | دوره PyTorch (مکتب‌خونه یا fast.ai) |
| FastAPI | دوره FastAPI (برای ساخت API مدل) |

> این سند زنده است. اگر کتابخانه یا مفهوم جدیدی در حین پروژه به آن برخوردی، به ارین بگو تا لیست به‌روز شود.

</div>