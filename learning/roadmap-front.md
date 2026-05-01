<div dir="rtl" align="right">

# 🎨 نقشه راه فرانت‌اند – چک‌لیست دانش فنی

این فایل یک نمای کلی از تمام مباحثی است که در مسیر یادگیری فرانت‌اند به آنها نیاز داریم.  
هیچ زمان‌بندی مشخصی ندارد – فقط یک چک‌لیست جامع برای سنجش پیشرفت و شناسایی نقاط قوت و ضعف.

> ✅ هر مورد را وقتی آموختی و تمرین کردی، تیک بزن.  
> 📌 هدف: آشنایی با همهٔ این مفاهیم تا پایان فاز وب (۵ ماه) – نه تسلط صد در صدی، بلکه توانایی استفادهٔ عملی.

---

## 🧱 پایه (Fundamentals)

### HTML
- [ ] ساختار پایهٔ یک صفحه (DOCTYPE, html, head, body)
- [ ] تگ‌های معنایی (header, nav, main, section, article, aside, footer)
- [ ] تگ‌های متنی (h1–h6, p, span, strong, em)
- [ ] لینک‌ها (a)، تصاویر (img)، لیست‌ها (ul, ol, li)
- [ ] جدول‌ها (table, tr, td, th)
- [ ] فرم‌ها (form, input, select, textarea, button, label)
- [ ] اعتبارسنجی سادهٔ سمت کاربر (required, pattern, type)
- [ ] آشنایی با داده‌های سفارشی (data-*)

### CSS
- [ ] نحوهٔ اتصال CSS به HTML (inline, internal, external)
- [ ] انتخابگرها (selector): کلاس، آیدی، عنصر، فرزند، شبه‌کلاس‌ها
- [ ] واحدها (px, rem, em, %, vw, vh)
- [ ] مدل جعبه (box model: margin, border, padding, content)
- [ ] نمایش (display): block, inline, inline-block, none
- [ ] موقعیت‌یابی (position): static, relative, absolute, fixed, sticky
- [ ] float و clear (آشنایی)
- [ ] رنگ‌ها، پس‌زمینه (background)، سایه‌ها (box-shadow, text-shadow)
- [ ] فونت و تایپوگرافی (font-family, font-size, line-height, text-align)
- [ ] Flexbox (container properties + items properties)
- [ ] CSS Grid (grid-template-columns, grid-template-rows, gap, placement)
- [ ] انیمیشن و transition
- [ ] transform (translate, rotate, scale)
- [ ] مدیا کوئری (media query) برای ریسپانسیو
- [ ] معماری CSS: BEM یا CSS Modules (آشنایی)
- [ ] متغیرهای CSS (custom properties)

### JavaScript (ES5+)
- [ ] متغیرها (var, let, const)
- [ ] انواع داده (string, number, boolean, null, undefined, symbol)
- [ ] عملگرها (arithmetic, comparison, logical)
- [ ] ساختارهای شرطی (if, else, switch)
- [ ] حلقه‌ها (for, while, do-while, for...of, for...in)
- [ ] توابع (function declaration, expression, arrow functions)
- [ ] scope و closure
- [ ] آرایه‌ها (map, filter, reduce, forEach, sort, find)
- [ ] اشیاء (object literals, dot/bracket notation, spread/rest)
- [ ] کلاس‌ها (constructor, methods, inheritance)
- [ ] promise و async/await
- [ ] fetch API (درخواست HTTP)
- [ ] DOM manipulation (getElementById, querySelector, createElement, appendChild, remove)
- [ ] رویدادها (addEventListener, event object, bubbling/delegation)
- [ ] localStorage / sessionStorage
- [ ] ماژول‌ها (import, export)
- [ ] خطایابی (try...catch)
- [ ] آشنایی با Web APIs: setTimeout, setInterval, console, navigator

---

## 📚 کتابخانه‌ها (Libraries)

### مدیریت DOM و ابزارها
- [ ] jQuery (آشنایی – نه لزوماً کار عملی سنگین)
- [ ] Lodash / Underscore (اختیاری)

### مدیریت فرم و اعتبارسنجی
- [ ] React Hook Form
- [ ] Formik (آشنایی)

### انیمیشن و تعاملات
- [ ] GSAP (GreenSock)
- [ ] Framer Motion (برای React)
- [ ] Anime.js (اختیاری)

---

## 🧩 فریم‌ورک‌های اصلی (Frameworks)

### React.js
- [ ] JSX
- [ ] کامپوننت تابعی
- [ ] props و prop-types
- [ ] state (useState)
- [ ] اثرات جانبی (useEffect)
- [ ] context API (useContext)
- [ ] reducers (useReducer)
- [ ] refs (useRef)
- [ ] روتینگ (React Router DOM)
- [ ] مدیریت فرم در React
- [ ] استیت مدیریت (Redux Toolkit / Zustand / Recoil) – حداقل یکی
- [ ] render props و higher-order components (آشنایی)
- [ ] lazy loading و code splitting (React.lazy)
- [ ] hooks سفارشی (custom hooks)
- [ ] تست کامپوننت (React Testing Library / Jest)

### Next.js (بنیان)
- [ ] ایجاد پروژه با create-next-app
- [ ] پوشه‌بندی (app router یا pages router)
- [ ] روتینگ و لینک (Link, useRouter)
- [ ] دریافت داده (getServerSideProps, getStaticProps, fetch در سمت کلاینت)
- [ ] استایل (CSS Modules, global CSS, styled-jsx)
- [ ] بهینه‌سازی تصاویر (next/image)
- [ ] SEO ( metadata, Head component)
- [ ] API routes (ساخت endpoint ساده)

### Vue.js (آشنایی)
- [ ] template syntax
- [ ] data, methods, computed, watch
- [ ] directives (v-if, v-for, v-bind, v-model)
- [ ] کامپوننت‌ها (props, emit)
- [ ] Vue Router
- [ ] Pinia یا Vuex (آشنایی)

> 📌 برای شروع، تمرکز اصلی بر روی **React و Next.js** است. Vue.js گزینهٔ ثانویه برای پروژه‌های خاص.

---

## 🎨 تکنولوژی‌های CSS (فریم‌ورک‌ها و پیش‌پردازنده‌ها)

- [ ] Bootstrap 5 (grid, components, utilities)
- [ ] TailwindCSS (ابزارمحور)
- [ ] Material UI (MUI – برای React)
- [ ] Chakra UI (برای React)
- [ ] Sass/SCSS (متغیرها، nest کردن، mixin, extend)
- [ ] CSS-in-JS (styled-components یا Emotion)
- [ ] PostCSS (آشنایی)

---

## 🌐 پیشرفته و تخصصی

### TypeScript (برای فرانت‌اند)
- [ ] نوع‌دهی ایستا (type, interface)
- [ ] جنریک‌ها (generics)
- [ ] utility types (Partial, Pick, Omit, Record)
- [ ] استفاده از TypeScript در React (FC, PropsWithChildren, useState تایپ‌شده)
- [ ] استفاده در Next.js

### گرافیک و 3D (اختیاری – برای پروژه‌های خاص)
- [ ] Canvas API (نقاشی دو بعدی)
- [ ] Three.js (صحنه، دوربین، اجسام، نور، بافت)
- [ ] WebGL (آشنایی کلی)
- [ ] D3.js (برای نمودارهای داده)
- [ ] Chart.js (نمودارهای ساده)

### تست خودکار
- [ ] Jest (unit testing)
- [ ] React Testing Library
- [ ] Cypress یا Playwright (E2E testing – آشنایی)

### Build tools و محیط
- [ ] Vite (create Project)
- [ ] webpack (آشنایی با مفاهیم)
- [ ] ESLint و Prettier (تنظیمات پایه)
- [ ] Environment variables (.env)

### Progressive Web App (PWA)
- [ ] service workers (مفاهیم)
- [ ] manifest.json
- [ ] آفلاین شدن ساده

### مباحث کلیدی دیگر
- [ ] SEO فنی (سئو برای تک‌صفحه‌ای‌ها)
- [ ] Core Web Vitals (LCP, FID, CLS)
- [ ] کار با WebSocket (socket.io-client یا WebSocket API)
- [ ] آشنایی با WebRTC (امکان انتقال صدا/تصویر – اختیاری)
- [ ] امنیت در فرانت‌اند (XSS، CSRF، Content Security Policy)
- [ ] بین‌المللی‌سازی (i18n – react-i18next یا next-i18next)
- [ ] مدیریت خطا و لاگ (Sentry یا ساده)

---

## ✅ نحوه استفاده از این چک‌لیست

- هر موردی را که **آموختی و توانایی استفاده از آن در یک پروژه کوچک را داری**، تیک بزن.  
- هر هفته یک بار مرور کن و ببین کدام بخش هنوز ضعیف است.  
- برای یادگیری، نیازی به ترتیب خاصی نیست؛ ولی بهتر است ابتدا *پایه* را کامل کنی، بعد سراغ فریم‌ورک بروی.  
- در گزارش هفتگی خود می‌توانی به این چک‌لیست ارجاع دهی و بگویی «این هفته روی فلان مبحث کار کردم».  

> این سند زنده است. اگر مبحث جدیدی به ذهنت رسید یا در پروژه به آن برخوردی، به ارین بگو تا لیست به‌روز شود.

</div>