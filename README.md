# Velora-Real-Estate-System
نظام فيلورا العقارية - إدارة الأملاك والتحصيل والمصروفات والضريبة

## 📋 نظرة عامة
تطبيق ويب متكامل لإدارة الممتلكات العقارية، يوفر أدوات شاملة لتتبع الأملاك والتحصيل والمصروفات والضرائب.

## 🎯 الميزات الرئيسية
- 🏠 إدارة الأملاك والعقارات
- 💰 نظام التحصيل والدفعات
- 📊 تتبع المصروفات والنفقات
- 🧮 حساب الضرائب تلقائياً
- 📈 تقارير وإحصائيات مفصلة
- 👥 إدارة المستأجرين والملاك
- 📋 نظام الوحدات والشقق

## 🛠️ البيئة التقنية

### Frontend
- **React** 18+ مع TypeScript
- **Tailwind CSS** للتصميم
- **React Router** للملاحة
- **Axios** للطلبات HTTP
- **React Query** لإدارة الحالة

### Backend
- **Node.js** + **Express.js**
- **PostgreSQL** لقاعدة البيانات
- **Sequelize** كـ ORM
- **JWT** للمصادقة
- **Joi** للتحقق من البيانات

## 📁 هيكل المشروع

```
Velora-Real-Estate-System/
├── frontend/                 # تطبيق React
│   ├── src/
│   │   ├── components/       # مكونات React
│   │   ├── pages/            # الصفحات
│   │   ├── services/         # خدمات API
│   │   ├── hooks/            # React Hooks مخصصة
│   │   ├── types/            # أنواع TypeScript
│   │   └── App.tsx
│   ├── package.json
│   └── tsconfig.json
├── backend/                  # تطبيق Express
│   ├── src/
│   │   ├── routes/           # المسارات والـ endpoints
│   │   ├── controllers/      # معالجات الطلبات
│   │   ├── models/           # نماذج قاعدة البيانات
│   │   ├── middleware/       # وسطاء مخصصة
│   │   ├── config/           # إعدادات التطبيق
│   │   └── app.ts
│   ├── package.json
│   └── tsconfig.json
├── docker-compose.yml        # تشغيل قاعدة البيانات
├── .gitignore
└── README.md
```

## 🚀 البدء السريع

### المتطلبات
- Node.js 18+
- PostgreSQL 14+
- npm أو yarn

### التثبيت والتشغيل

1. **استنساخ المستودع**
```bash
git clone https://github.com/acpaali96-ship-it/Velora-Real-Estate-System.git
cd Velora-Real-Estate-System
```

2. **إعداد قاعدة البيانات**
```bash
docker-compose up -d
```

3. **تثبيت حزم Backend**
```bash
cd backend
npm install
cp .env.example .env
```

4. **تشغيل Backend**
```bash
npm run dev
```

5. **تثبيت حزم Frontend (في terminal جديد)**
```bash
cd frontend
npm install
npm start
```

6. **الوصول للتطبيق**
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## 📚 الوثائق

- [دليل Backend](./backend/README.md)
- [دليل Frontend](./frontend/README.md)
- [معايير المساهمة](./CONTRIBUTING.md)

## 👨‍💻 المساهمة
نرحب بالمساهمات! يرجى قراءة [CONTRIBUTING.md](./CONTRIBUTING.md) لمعرفة كيفية المساهمة.

## 📝 الترخيص
هذا المشروع مرخص تحت [MIT License](./LICENSE)

## 📧 التواصل
للأسئلة والاستفسارات، يرجى فتح issue في المستودع.
