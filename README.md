<div align="center">

# 🐳 آموزش جامع داکر (Docker) — به زبان فارسی

**از صفر تا استقرار در محیط تولید | کامل‌ترین مرجع فارسی Docker**

[![Stars](https://img.shields.io/github/stars/Fatemebookanian/docker-guide-fa?style=social)](https://github.com/Fatemebookanian/docker-guide-fa/stargazers)
[![Forks](https://img.shields.io/github/forks/Fatemebookanian/docker-guide-fa?style=social)](https://github.com/Fatemebookanian/docker-guide-fa/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red)](https://github.com/Fatemebookanian)
[![Language](https://img.shields.io/badge/زبان-فارسی-blue)]()

<p>اگر این جزوه برایتان مفید بود، با زدن ⭐ از آن حمایت کنید — انگیزه‌ی به‌روزرسانی و افزودن مطالب بیشتر می‌شود!</p>

</div>

---

## 📖 درباره‌ی این جزوه

این مخزن یک **جزوه‌ی کامل و گام‌به‌گام آموزش داکر به زبان فارسی** است که از مفاهیم بنیادین شروع می‌کند و تا موضوعات پیشرفته مثل Swarm، امنیت و استقرار در محیط تولید پیش می‌رود. هر مفهوم با ساختار یکنواخت توضیح داده شده است:

> 🔸 **تعریف کامل** → 🔸 **چرا وجود دارد؟** → 🔸 **مزایا و معایب** → 🔸 **مثال عملی با دستور**

هدف این بوده که خواننده نه‌فقط «چه دستوری» بلکه «چرا» را هم بفهمد. مطالب با زبان ساده و همراه با ده‌ها مثال کد، جدول مقایسه و سناریوی واقعی نوشته شده‌اند.

---

## ✨ ویژگی‌ها

- ✅ بیش از **۱۷۰ مفهوم و دستور** داکر، کاملاً به فارسی
- ✅ ساختار آموزشی منظم (تعریف، دلیل وجود، مزایا/معایب، مثال)
- ✅ ده‌ها **بلوک کد آماده‌ی اجرا** و **جدول مقایسه**
- ✅ نسخه‌ی **HTML تعاملی** با فهرست مطالب کلیک‌پذیر و طراحی تیره‌ی چشم‌نواز
- ✅ نسخه‌ی **Markdown** برای مطالعه‌ی مستقیم روی گیت‌هاب
- ✅ پوشش کامل از مبانی تا Production

---

## 📚 سرفصل‌ها

| # | بخش | موضوعات کلیدی |
|---|------|----------------|
| ۰ | **DevOps و مبانی معماری** | DevOps، CI/CD، Monolithic vs Microservices، مجازی‌سازی |
| — | **مبانی و شروع کار** | داکر چیست، کانتینر vs VM، نصب، چرخه‌ی Build/Ship/Run، تاریخچه |
| ۱ | **معماری داکر** | Engine، runc/containerd/shim، Daemonless، Storage Driver |
| ۲ | **مدیریت ایمیج‌ها** | معماری لایه‌ای، tag، search، multi-arch، inspect، history |
| ۳ | **مدیریت کانتینرها** | چرخه‌ی عمر، محدودیت منابع، exec/attach/cp، restart policy |
| ۴ | **لاگ‌گذاری (Logging)** | Log Drivers، blocking/non-blocking، tagging |
| ۵ | **Volumes** | Volume، Bind Mount، tmpfs، اشتراک‌گذاری |
| ۶ | **شبکه (Networking)** | CNM، Bridge، Macvlan، Port Mapping، Service Discovery |
| ۷ | **Dockerfile** | دستورات، Best Practices، Distroless، Multistage |
| ۸ | **Docker Compose** | شبکه، ولیوم، Healthcheck، مثال‌های WordPress و Nextcloud |
| ۹ | **Docker Swarm & Stack** | Raft، HA، Scaling، Rolling Update، Drain |
| ۱۰ | **امنیت (Security)** | Namespaces، cgroups، Capabilities، seccomp، AppArmor، Trivy |

---

## 🚀 نحوه‌ی استفاده

**۱) مطالعه‌ی آنلاین (Markdown):** فایل [`docker-guide.md`](./docker-guide.md) را همین‌جا روی گیت‌هاب باز کنید.

**۲) نسخه‌ی HTML تعاملی:** فایل [`docker-guide.html`](./docker-guide.html) را دانلود و در مرورگر باز کنید (فهرست کلیک‌پذیر دارد).

```bash
# کلون کردن مخزن
git clone https://github.com/Fatemebookanian/docker-guide-fa.git
cd docker-guide-fa

# باز کردن نسخه‌ی HTML (لینوکس)
xdg-open docker-guide.html
```

---

## 🤝 مشارکت

اگر اشتباهی دیدید یا مطلبی برای افزودن داشتید، خوشحال می‌شوم Issue یا Pull Request بزنید. هر بازخوردی ارزشمند است. 🙌

## ⭐ حمایت

اگر این مجموعه به یادگیری داکر کمکتان کرد، لطفاً با زدن دکمه‌ی **Star** در بالای صفحه از آن حمایت کنید. این کار کاملاً رایگان است و انگیزه‌ی بزرگی برای ادامه‌ی کار می‌دهد. ⭐

## 📄 مجوز

این اثر تحت مجوز [MIT](./LICENSE) منتشر شده است؛ استفاده، اشتراک‌گذاری و ویرایش با ذکر منبع آزاد است.

---

<div align="center">

نوشته و گردآوری: **Fateme** · [GitHub](https://github.com/Fatemebookanian)

</div>
