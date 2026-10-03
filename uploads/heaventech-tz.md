# TEXNIK TOPSHIRIQ (TT) / TECHNICAL SPECIFICATION
## "HeavenTech" Korporativ Veb-Platformasini Ishlab Chiqish va Transformatsiya Qilish

---

### **1. HUJJAT HAQIDA VA UMUMIY MA'LUMOTLAR**

* **Loyiha nomi:** HeavenTech Official Corporate Platform
* **Buyurtmachi:** "HeavenTech" IT Company
* **Loyiha maqsadi:** `usad.uz` (USAD Studio) kichik yakkaxon/jamoaviy landing page-saytini to'liq siklli, Enterprise darajasidagi **HeavenTech** korporativ veb-platformasiga transformatsiya qilish.
* **Tillar:** O'zbek tili (UZ), Rus tili (RU), Ingliz tili (EN).
* **Target Audience (Maqsadli auditoriya):** B2B mijozlar, Enterprise kompaniyalar, Davlat va xususiy sektor vakillari, Xalqaro hamkorlar, Potensial xodimlar (Talent Pool).

---

### **2. LOYIHA MAQSADLARI VA STRATEGIK VAZIFALAR**

1. **Brend Imidjini Oshirish:** Studio/Freelance uslubidan professional va ishonchli B2B IT-kompaniya darajasiga o'tish.
2. **Xizmatlar Ekotizimini Tizimlashtirish:** Telegram Mini Apps, Enterprise CRM/ERP, Custom Software, Mobile Apps, Cloud & DevOps hamda IT-Konsalting xizmatlarini aniq va chuqur namoyish etish.
3. **Lid Generatsiyasi va B2B Savdo:** Interaktiv RFP (Request for Proposal) hamda loyiha kalkulyatori orqali sifatli B2B arizalarni qabul qilish.
4. **Ishonch Omili (Trust Factors):** ISO sertifikatlari, IT-Park a'zoligi, B2B case-study'lar hamda professional jamoani yoritish.

---

### **3. SAYT ARXITEKTURASI VA SITEMAP**

```
HeavenTech Platform
├── 1. Bosh sahifa (Home)
├── 2. Kompaniya haqida (About Us)
├── 3. Xizmatlar (Services & Solutions)
│   ├── 3.1. Enterprise CRM & ERP Tizimlari
│   ├── 3.2. Telegram Mini Apps & Ekotizimlar
│   ├── 3.3. Custom Software & SaaS Platformalar
│   ├── 3.4. Mobil Dasturlash (iOS & Android)
│   └── 3.5. Cloud, DevOps & IT-Konsalting
├── 4. Portfoliolar & Case Studies (Projects)
│   └── Individual Case Study Page (Problem-Solution-ROI format)
├── 5. Texnologik Stak & Infratuzilma (Tech Stack)
├── 6. Karera va Madaniyat (Careers)
├── 7. Blog & Analitika (Insights & Articles)
└── 8. Aloqa va Korporativ Rekvizitlar (Contacts)
```

---

### **4. SAHIFALAR BO'YICHA DETALIZATSIYA VA KONTENT TALABLARI**

#### **4.1. Bosh Sahifa (Home Page)**
* **Hero Section:**
  * Sarlavha: *"HeavenTech — Raqamli transformatsiya va kompleks dasturiy yechimlar"*
  * Sub-sarlavha: B2B va Enterprise bizneslar uchun yuqori unumdorlikka ega tizimlar.
  * CTA tugmalari: *"Loyiha muhokamasi"* (RFP Modal) va *"Case Study'larni ko'rish"*.
* **Ko'rsatkichlar blok (Key Metrics):**
  * Loyihalar soni, Xalqaro va mahalliy B2B mijozlar, Tizimlarning barqarorlik darajasi (99.9% Uptime).
* **Xizmatlar Ekotizimi (Interactive Services Grid):**
  * Har bir xizmat yo'nalishi bo'yicha qisqa interaktiv kartochkalar.
* **Mijozlar va Hamkorlar (Trust Banner):**
  * Hamkor kompaniyalar va mijozlar logotiplari slayderi.
* **Interaktiv RFP / Loyiha Kalkulyatori:**
  * Mijoz loyiha turini, funksionallarini tanlaydi va dastlabki bahoni ko'radi.

#### **4.2. Kompaniya Haqida (About Us)**
* **Transformatsiya va Tarix:** Jamoaviy tajribadan IT-kompaniyangacha bo'lgan rivojlanish bosqichi.
* **Missiya va Qadriyatlar:** Sifat, xavfsizlik, shaffoflik va mijoz biznesi samaradorligini oshirish.
* **Rahbariyat va Jamoa (Leadership & Team):** Kalit mutaxassislar (CEO, CTO, Lead Architects) va ularning kompetensiyalari.
* **Sertifikatlar va IT-Park:** Rasmiy maqom va muvofiqlik sertifikatlari.

#### **4.3. Xizmatlar Bo'limi (Services Detail Pages)**
Har bir xizmat sahifasi quyidagi standart bo'yicha tuziladi:
1. **Xizmat tavsifi va biznes qiymati:** Ushbu xizmat mijoz biznesidagi qaysi muammoni hal qilishi.
2. **Imkoniyatlar va Funksional:** Modullar va texnik xususiyatlar.
3. **Qo'llaniladigan Texnologiyalar:** Backend, Frontend va DB stack.
4. **Biznes uchun ROI:** Samaradorlik oshishi ko'rsatkichlari.
5. **Bog'liq Case Study'lar.**

#### **4.4. Portfoliolar va Case Study'lar (Projects)**
* Standard ro'yxat emas, balki chuqur **B2B Case Study** formati:
  * **Muammo (Challenge):** Mijoz duch kelgan texnik va biznes to'siq.
  * **Yechim (Solution):** HeavenTech tomonidan ishlab chiqilgan arxitektura.
  * **Texnologiyalar (Stack):** Ishlatilgan freymvorklar va infratuzilma.
  * **Natija (Business ROI):** Ishlov berish tezligi, avtomatlashtirish foizi va xarajatlar qisqarishi.

#### **4.5. Karera va HR (Careers)**
* Kompaniya madaniyati va afzalliklari.
* Ochiq vakansiyalar (Job Cards) va rezyume yuborish shakli (Resume Upload System).

#### **4.6. Aloqa (Contacts)**
* Rasmiy e-mail: `info@heaventech.uz` (vaziyatga ko'ra).
* Telefon liniyasi va korporativ manzili.
* Yandex / Google Maps interaktiv xaritasi.
* Rasmiy yuridik rekvizitlar va bank ma'lumotlari.

---

### **5. FUNKSIONAL VA TEXNIK TALABLAR**

1. **Multilingvallik (i18n):**
   * kontent UZ, RU va EN tillarida dinamik boshqarilishi shart.
   * SEO uchun `hreflang` teglaridan foydalanish.
2. **Interaktiv Loyiha Kalkulyatori:**
   * Step-by-step shaklda loyiha sohasini va talablarini tanlash.
   * Tayyor bo'lgach, avtomatik ravishda PDF-smeta shakllantirish va Telegram/CRM'ga yuborish.
3. **CRM va Telegram Integratsiyasi:**
   * Barcha shakllar va arizalar real-vaqt rejimida HeavenTech ichki CRM tizimiga (masalan, Bitrix24/HubSpot) hamda mas'ul xodimlar Telegram botiga tushadi.
4. **Admin Panel (CMS):**
   * Rolga asoslangan kirish huquqlari (RBAC - Admin, Editor, HR).
   * Blog, vakansiyalar, case study va xizmatlarni qulay tahrirlash paneli.

---

### **6. NOFUNKSIONAL VA XAVFSIZLIK TALABLARI**

1. **Unumdorlik va Tezlik:**
   * PageSpeed Performance balli Desktop uchun **90+**, Mobile uchun **85+**.
   * Lazy loading, WebP/AVIF tasvir optimizatsiyasi va CDN ulash.
2. **Xavfsizlik:**
   * HTTPS / SSL shifrlash.
   * OWASP Top-10 zaifliklaridan hisoblangan SQL Injection, XSS, CSRF va Rate-Limiting himoyasi.
   * Ma'lumotlar maxfiyligi (GDPR hamda O'zR Qonunchiligiga muvofiqlik).
3. **SEO Optimallashtirish:**
   * Semantic HTML5 strukturasi.
   * Schema.org (Organization, Service, Article) strukturasi.
   * OpenGraph va Twitter Card meta-teglar.

---

### **7. DASTURLASH STAKI (TAVSIYA ETILADI)**

* **Frontend:** Next.js (React), TypeScript, TailwindCSS, Framer Motion (Server-Side Rendering va SEO uchun).
* **Backend:** Node.js (NestJS) yoki Python (FastAPI / Django) / Go.
* **Database:** PostgreSQL (relyatsion ma'lumotlar uchun), Redis (keshlash va seanslar uchun).
* **Infratuzilma & DevOps:** Docker, Nginx, CI/CD Pipelines (GitHub Actions), Cloudflare CDN.

---

### **8. AMALGA OSHIRISH BOSQICHLARI VA TIMELINE**

| Bosqich | Tavsif | Taxminiy Muddat |
| :--- | :--- | :--- |
| **01. Discovery & Design System** | Prototiplash, UX/UI dizayn, UI-Kit va Figma loyihasi | 2 hafta |
| **02. Frontend & SSR Development** | Sahifalarni adaptive va SSR rejimida dasturlash | 3 hafta |
| **03. Backend & CMS Integration** | API, CMS admin panel, integratsiyalar va kalkulyator | 3 hafta |
| **04. QA & Security Testing** | Funksional, tezlik va xavfsizlik testlari | 1 hafta |
| **05. Production Launch** | Serverga joylash, DNS sozlamalari va SEO indeksatsiya | 1 hafta |
