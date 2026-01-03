# 🛒 MarketPy
> فعلا توسعه این ریپازیتوری متوقف شده،بعد از اتمام رساندن ریپازیتوری های دیگر توسعه ادامه می یابد:)
MarketPy is an e-commerce platform built with **Django**, designed with a strong focus on:

- Clean architecture
- Scalability
- Security
- Long-term maintainability

This project is suitable for both small startups and scalable production environments.

---

## 🚀 Features

- User authentication and authorization
- Product and category management
- Shopping cart system
- Order processing
- Payment integration (extensible)
- Django Admin panel
- Ready for REST API and decoupled frontend

---

## 🧱 Tech Stack

- Python 3.10+
- Django 4+
- Django REST Framework (optional)

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/MarketPy.git
cd MarketPy
```

### 2️⃣ Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # Linux / macOS
venv\Scripts\activate     # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Environment variables

Create a `.env` file in the project root:

```env
SECRET_KEY=your-secret-key
DEBUG=True
ALLOWED_HOSTS="localhost,128.0.0.1"
```

### 5️⃣ Apply migrations

```bash
python manage.py migrate
```

### 6️⃣ Create superuser

```bash
python manage.py createsuperuser
```

### 7️⃣ Run the development server

```bash
python manage.py runserver
```

---

## 📁 Project Structure

```text
MarketPy/
│
├── config/
├── apps/
│   ├── accounts/
│   ├── products/
│   ├── orders/
│   └── payments/
│
├── templates/
├── static/
├── media/
├── manage.py
└── requirements.txt
```

---

## 🔐 Security Notes

- Sensitive data must be stored in `.env`
- Set `DEBUG=False` in production
- Always use HTTPS in production environments

---


---

## 🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first.

---

## 📄 License

MIT License © MarketPy

---

# 🛒 MarketPy (فارسی)

MarketPy یک فروشگاه اینترنتی مبتنی بر **Django** است که با تمرکز ویژه بر موارد زیر توسعه داده شده است:

- معماری تمیز و اصولی
- مقیاس‌پذیری بالا
- امنیت
- نگهداری و توسعه آسان در بلندمدت

این پروژه برای استارتاپ‌ها و همچنین محیط‌های production مناسب است.

---

## 🚀 امکانات

- سیستم احراز هویت و مدیریت کاربران
- مدیریت محصولات و دسته‌بندی‌ها
- سیستم سبد خرید
- ثبت و مدیریت سفارش‌ها
- اتصال به درگاه پرداخت (قابل توسعه)
- پنل مدیریت Django
- آماده برای REST API و فرانت‌اند جدا

---

## 🧱 تکنولوژی‌ها

- Python 3.10+
- Django 4+
- PostgreSQL (پیشنهادی)
- Django REST Framework (اختیاری)
- Redis (کش / تسک‌های پس‌زمینه)
- Docker (اختیاری)

---

## ⚙️ نصب و راه‌اندازی

### 1️⃣ دریافت سورس پروژه

```bash
git clone https://github.com/aboalfazlH/MarketPy.git
cd MarketPy
```

### 2️⃣ ساخت محیط مجازی

```bash
python -m venv venv
source venv/bin/activate   # لینوکس / مک
venv\Scripts\activate      # ویندوز
```

### 3️⃣ نصب وابستگی‌ها

```bash
pip install -r requirements.txt
```

### 4️⃣ تنظیم متغیرهای محیطی

یک فایل `.env` بسازید:

```env
DEBUG=True
SECRET_KEY=your-secret-key
```

### 5️⃣ اجرای مایگریشن‌ها

```bash
python manage.py migrate
```

### 6️⃣ ساخت ادمین

```bash
python manage.py createsuperuser
```

### 7️⃣ اجرای سرور توسعه

```bash
python manage.py runserver
```

---

## 📁 ساختار پروژه

```text
MarketPy/
│
├── config/
├── apps/
│   ├── accounts/
│   ├── products/
│   ├── orders/
│   └── payments/
│
├── templates/
├── static/
├── media/
├── manage.py
└── requirements.txt
```

---

## 🔐 نکات امنیتی

- اطلاعات حساس در فایل `.env` نگهداری شوند
- در محیط production مقدار `DEBUG=False` باشد
- استفاده از HTTPS الزامی است

---

## 🤝 مشارکت

Pull Request آزاد است.
برای تغییرات بزرگ ابتدا Issue ثبت کنید.

---

## 📄 لایسنس

[MIT](LISCNSE)
