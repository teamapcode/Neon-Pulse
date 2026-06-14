```markdown
<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=35&duration=3000&pause=500&color=00FFFF&center=true&vCenter=true&width=500&height=70&lines=⚡+NEON+PULSE+⚡" alt="Neon Pulse" />
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/WebAudio-FF6B6B?style=for-the-badge&logo=webaudio&logoColor=white" />
</p>

<p align="center">
  <b>یک بازی آرکید سینت‌ویو با افکت‌های نئونی، سیستم کومبو، پاورآپ و موسیقی پویا</b>
</p>

---

## 🎮 درباره بازی

**NEON PULSE** یک بازی آرکید سریع و اعصاب‌خردکن با تم سینت‌ویو و افکت‌های نئونی است. شما کنترل یک **هگزagon درخشان** را به دست می‌گیرید و باید از موانع هندسی فرار کنید، پاورآپ‌های طلایی جمع کنید و رکورد خود را بشکنید!

---

## ✨ ویژگی‌های اصلی

| ویژگی | توضیح |
|-------|-------|
| 🎨 **افکت نئونی پویا** | رنگ بازی با هر ۵۰۰ امتیاز تغییر می‌کند |
| 💥 **لرزش دوربین** | برخورد با موانع با تابع `Math.sin` |
| 🧨 **سیستم ذرات انفجاری** | هنگام Game Over و برخوردها |
| 💾 **ذخیره رکورد** | بهترین امتیاز در `localStorage` ذخیره می‌شود |
| 📈 **دیفیكالتی لگاریتمی** | سرعت و دشواری به مرور زمان افزایش می‌یابد |
| ⚡ **سیستم کومبو** | عبور متوالی از موانع = امتیاز تصاعدی |
| 🛡️ **پاورآپ‌ها** | 2X امتیاز، کند کردن زمان، سپر محافظ |
| 🎵 **موسیقی سینت‌ویو پویا** | BPM و فرکانس با افزایش امتیاز بالاتر می‌رود |
| 🔊 **صداهای تعاملی** | صدای سکه، صدای برخورد، صدای Game Over ("اوه اوه اوه") |

---

## 🎯 کنترل‌ها

| ورودی | عملکرد |
|-------|--------|
| 🖱️ **حرکت ماوس** | حرکت هگزagon به چپ و راست |
| 👆 **لمس (موبایل)** | کشیدن انگشت روی صفحه |

---

## 🎮 پاورآپ‌ها

| نماد | نام | توضیح |
|------|-----|-------|
| 🟡 2X | **Double Score** | امتیاز دریافتی را دو برابر می‌کند |
| 🔵 ⏱ | **Slow Motion** | سرعت موانع را کاهش می‌دهد |
| 🟢 🛡 | **Shield** | یک بار برخورد را جذب می‌کند |

---

## 🎵 موسیقی

موسیقی پس‌زمینه با استفاده از **Web Audio API** ساخته شده و به صورت داینامیک با امتیاز بازیکن تغییر می‌کند:

- **BPM پایه**: 95 → با افزایش امتیاز تا 175 افزایش می‌یابد
- **فرکانس باس**: از 75Hz تا 120Hz
- **فرکانس لید**: از 160Hz تا 280Hz

---

## 🖼️ اسکرین‌شات

<p align="center">
  <img src="https://via.placeholder.com/800x400?text=Neon+Pulse+Gameplay" alt="Gameplay Screenshot" width="80%">
</p>

> 💡 *اسکرین‌شات واقعی از بازی را می‌توانید بعد از اجرا مشاهده کنید*

---

## 🚀 نصب و اجرا

### روش اول: اجرای مستقیم

```bash
git clone git@github.com:USERNAME/neon-pulse.git
cd neon-pulse
# فایل index.html را در مرورگر باز کنید
```

### روش دوم: اجرای آنلاین با GitHub Pages

بعد از آپلود، بازی در آدرس زیر در دسترس است:

```
https://USERNAME.github.io/neon-pulse/
```

---

## 📁 ساختار پروژه

```
neon-pulse/
├── index.html      # ساختار اصلی بازی
├── style.css       # استایل‌ها و افکت‌های نئونی
└── game.js         # منطق کامل بازی (800+ خط)
```

---

## 🛠️ تکنولوژی‌های استفاده شده

| تکنولوژی | کاربرد |
|----------|--------|
| **HTML5 Canvas** | رندر گرافیک و انیمیشن‌ها |
| **CSS3** | افکت‌های نئونی، انیمیشن‌ها، ریسپانسیو |
| **JavaScript (Vanilla)** | منطق بازی، فیزیک، برخوردها |
| **Web Audio API** | موسیقی پویا، صداهای برخورد |
| **LocalStorage API** | ذخیره رکورد |

---

## 🎯 سیستم امتیازدهی

| عمل | امتیاز پایه | کومبو |
|-----|-------------|-------|
| عبور از مانع | 10 + (دیفیكالتی × 2) | +10% به ازای هر کومبو |
| پاورآپ Double Score | ×2 | - |

---

## 🤝 مشارکت

کد کاملاً متن‌باز است. هر گونه ایده، باگ‌گزارشی یا Pull Request با افتخار پذیرفته می‌شود.

---

## 📝 لایسنس

**MIT License** - آزاد برای استفاده، کپی، تغییر و توزیع.

---

## 👨‍💻 سازنده

<div align="center">
  
  **AP Code**
  
  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/APCode)
  
</div>

---

<p align="center">
  <i>"عجب چیز باحاله، دم سازنده اش گرم!"</i> 😎
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=2000&pause=1000&color=00FFFF&center=true&width=400&height=30&lines=NEON+PULSE+-+Synthwave+Arcade+Game" />
</p>
```

---