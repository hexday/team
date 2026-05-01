<div dir="rtl" align="right">

# ☁️ نقشه راه دوآپس (DevOps) – چک‌لیست دانش فنی

این مسیر برای **مسئولین زیرساخت تیم** (مهدی قورچی و رضا قادری) طراحی شده، اما بقیه اعضا هم می‌توانند از آن برای یادگیری شخصی استفاده کنند.

> ✅ هدف: توانایی **استقرار، مدیریت و مانیتورینگ برنامه‌ها** روی سرورهای واقعی.  
> 📌 تمرکز بر ابزارهای سبک و کاربردی – نه ابزارهای سنگین سازمانی (مگر در آینده).

---

## 🧱 پایه و پیش‌نیازها

### گیت و گیت‌هاب (مرور سریع)
- [ ] دستورات روزانه (clone, pull, push, commit, add, status, log)
- [ ] شاخه‌ها (branch, checkout, merge)
- [ ] رفع تداخل (conflict)
- [ ] Pull Request و کد ریویو
- [ ] آشنایی با GitHub Actions (برای خودکارسازی – در بخش CI/CD)

> برای جزئیات بیشتر به فایل‌های [`work-with-git.md`](work-with-git.md) و [`work-with-repository.md`](work-with-repository.md) مراجعه کنید.

### خط فرمان لینوکس (Linux CLI)
- [ ] ساختار دایرکتوری‌ها (/, home, etc, var, opt, tmp)
- [ ] دستورات پایه: ls, cd, pwd, mkdir, rm, cp, mv, touch, cat, less, tail, head
- [ ] مجوزها (chmod, chown, chgrp)
- [ ] فرآیندها (ps, top, htop, kill, systemctl, journalctl)
- [ ] شبکه (ip, netstat, ss, ping, curl, wget, scp)
- [ ] کاربران و گروه‌ها (useradd, usermod, groupadd, sudo)
- [ ] بایگانی و فشرده‌سازی (tar, gzip, zip)
- [ ] متغیرهای محیطی (export, env, ~/.bashrc)

---

## 🐳 کانتینریزیشن (Containerization)

### Docker
- [ ] نصب Docker روی لینوکس (و ویندوز/Mac برای توسعه)
- [ ] مفاهیم: image, container, registry (Docker Hub)
- [ ] دستورات پایه: docker pull, build, run, ps, stop, rm, logs, exec
- [ ] ساخت Dockerfile (FROM, RUN, COPY, ADD, WORKDIR, EXPOSE, CMD, ENTRYPOINT)
- [ ] مدیریت تصاویر (docker images, rmi, tag, push)
- [ ] حجم‌ها (volumes) و ذخیره‌سازی داده (docker volume)
- [ ] شبکه در Docker (bridge, host, none, user-defined networks)
- [ ] Docker Compose: فایل docker-compose.yml (services, networks, volumes)
- [ ] دستورات compose: up, down, logs, exec, build
- [ ] لاگ و دیباگ کانتینرها (docker logs, docker inspect, docker stats)

---

## 📦 مدیریت سرور (Server Administration)

### انتخاب و راه‌اندازی سرور ابری
- [ ] آشنایی با ارائه‌دهندگان: **Hetzner، DigitalOcean، Vultr** (و در آینده AWS Lightsail)
- [ ] ایجاد سرور (droplet / instance) با اوبونتو ۲۰.۰۴ + LTS
- [ ] اتصال SSH با کلید عمومی (ssh-keygen، authorized_keys)
- [ ] تنظیمات امنیتی اولیه: تغییر پورت SSH، غیرفعال کردن root login، فایروال با ufw
- [ ] به‌روزرسانی سیستم (apt update && apt upgrade)

### وب سرور (Web Server)
- [ ] نصب و تنظیم Nginx (reverse proxy, static files, load balancing – پایه)
- [ ] تنظیم سایت‌ها (sites-available, sites-enabled)
- [ ] پروکسی معکوس به برنامه (مثلاً proxy_pass به localhost:8000)
- [ ] تنظیم SSL با Let's Encrypt (Certbot)
- [ ] بررسی لاگ‌های Nginx (access.log, error.log)

### مدیریت فرآیندها (Process Management)
- [ ] استفاده از Gunicorn یا uWSGI برای برنامه‌های Python (Django)
- [ ] استفاده از Uvicorn برای FastAPI
- [ ] ایجاد systemd service (فایل‌های `.service` در `/etc/systemd/system/`)
- [ ] دستورات: systemctl start/stop/restart/enable/status
- [ ] مانیتورینگ ساده با systemd و journalctl

### دیتابیس روی سرور
- [ ] نصب PostgreSQL (apt یا docker)
- [ ] ایجاد کاربر و دیتابیس
- [ ] تنظیم access (pg_hba.conf)
- [ ] بکاپ‌گیری خودکار با cron (pg_dump)
- [ ] نصب Redis (apt یا docker) و تنظیمات پایه

---

## 🔄 CI/CD (ادغام و استقرار خودکار)

### GitHub Actions
- [ ] ایجاد فایل workflow (`.github/workflows/main.yml`)
- [ ] رویدادهای trigger (push, pull_request, schedule)
- [ ] jobs و steps (checkout, setup-python, install dependencies)
- [ ] اجرای تست‌ها (pytest, jest)
- [ ] ساخت image و ارسال به Docker Hub (یا ghcr.io)
- [ ] استقرار خودکار روی سرور با استفاده از `appleboy/ssh-action` یا `scp` و `ssh`

### استقرار دستی (برای مواقع خاص)
- [ ] rsync برای انتقال فایل‌ها
- [ ] اسکریپت‌های bash برای استقرار سریع (pull, migrate, collectstatic, restart service)

---

## 📊 مانیتورینگ و لاگ (Monitoring & Logging)

- [ ] نمایش وضعیت سرور با `htop`, `df -h`, `free -m`
- [ ] بررسی لاگ‌های برنامه (journalctl -u myservice)
- [ ] آشنایی با Prometheus + Grafana (نصب ساده و مشاهده متریک‌های پایه)
- [ ] جمع‌آوری لاگ متمرکز با ELK سبک (اختیاری)

---

## 🐛 دیباگ و عیب‌یابی (Debugging & Troubleshooting)

- [ ] بررسی اینکه آیا سرویس در حال اجراست (systemctl status, docker ps)
- [ ] مشاهده لاگ‌های برنامه (docker logs, journalctl, tail -f)
- [ ] بررسی پورت‌ها (netstat -tulpn, ss -tulpn)
- [ ] تست اتصال شبکه (curl, ping, telnet)
- [ ] بررسی خطاهای Nginx (browser + error.log)
- [ ] دیباگ کانتینر با `docker exec -it container /bin/bash`
- [ ] استفاده از `strace` و `lsof` در صورت نیاز (اختیاری)

---

## 🔐 امنیت (Security)

- [ ] به‌روزرسانی منظم سیستم (apt update && apt upgrade)
- [ ] فایروال (ufw) و قوانین پیش‌فرض
- [ ] رمزنگاری کلیدها و متغیرهای محیطی (در GitHub Secrets، نه در کد)
- [ ] جلوگیری از اجرای دایرکت scripts آپلودی
- [ ] تنظیم headers امنیتی در Nginx (HSTS, X-Frame-Options, etc.)
- [ ] راه‌اندازی VPN ساده (WireGuard – اختیاری برای دسترسی امن)

---

## 🧪 تحویل و راه‌اندازی (Delivery & Deployment)

- [ ] ایجاد محیط‌های **staging** و **production** (حداقل جدا)
- [ ] بکاپ منظم از دیتابیس (cron + scp به جای امن)
- [ ] مستندسازی فرآیند راه‌اندازی (README برای deploy)
- [ ] بررسی health-check endpoint
- [ ] داشتن rollback plan (برگرداندن به نسخه قبلی)

---

## ✅ نحوه استفاده از این چک‌لیست

- این مسیر توسط **یک یا دو نفر از تیم** به صورت عمیق دنبال می‌شود.  
- بقیه اعضا فقط مفاهیم پایه Docker و گیت را یاد بگیرند.  
- هر کدام از موارد بالا را که توانایی **پیاده‌سازی و توضیح آن را داری**، تیک بزن.  
- در گزارش هفتگی خود پیشرفتت را در هر بخش اعلام کن.

> این سند زنده است. با رشد تیم و پیچیده‌تر شدن پروژه‌ها، مباحث جدید (مانند Kubernetes، Terraform) اضافه خواهد شد.

</div>