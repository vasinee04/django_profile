<div align="center">
</div>

<div align="center">
	<h1>🌸 <span style="color:#e75480">VASINEE Django Profile Webapp</span> 🌸</h1>
	<p>
		<img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python" alt="python"/>
		<img src="https://img.shields.io/badge/Django-5.x-success?logo=django" alt="django"/>
		<img src="https://img.shields.io/badge/Bootstrap-5.x-blueviolet?logo=bootstrap" alt="bootstrap"/>
		<img src="https://img.shields.io/badge/License-MIT-green" alt="license"/>
	</p>
	<p><b>เว็บโปรไฟล์ส่วนตัว</b> สร้างด้วย <b>Django</b> และ <b>Bootstrap 5</b> พร้อม UI สีชมพูสวยงาม รองรับภาษาไทย 🇹🇭</p>
</div>

---

## 📄 พัฒนาโดย
**นางสาววาสินี มาฤทธิ์** `6712732126`  
สาขาวิทยาการคอมพิวเตอร์ ปี 2 | มหาวิทยาลัยราชภัฏศรีสะเกษ

---

## ✨ คุณสมบัติเด่น

- 🖼️ **แกลเลอรี่ภาพบรรยากาศชีวิตการเรียน (Index)** - Hero Section พร้อม Carousel และ Gallery
- 🔁 **ฟอร์มวนซ้ำ (For Loop Demo)** - สาธิตการใช้งาน Python For Loop
- 🧮 **ตารางสูตรคูณ (Multiplication Table)** - ฟอร์มสร้างตารางสูตรคูณแบบ Interactive
- 📅 **ฟอร์มรายชื่อนักศึกษา (Student List Demo)** - จัดการรายชื่อนักศึกษา
- 👥 **ฟอร์มรายวิชา (Subject List Demo)** - จัดการรายวิชาที่เรียน
- 👩‍🎓 **หน้าโปรไฟล์ส่วนตัว (About)** - ข้อมูลส่วนตัว ความเชื่อ และเป้าหมาย
- 📬 **ช่องทางติดต่อ (Contact)** - พร้อมลิงก์ Facebook, IG, Line, Email, โทรศัพท์
- 🎨 **UI/UX สีชมพู** - ใช้ Bootstrap 5, Bootstrap Icons, CSS ธีมชมพูสวยงาม
- 📱 **Responsive Design** - รองรับทุกขนาดหน้าจอ มือถือ แท็บเล็ต เดสก์ท็อป

---

## 🛠️ เทคโนโลยีที่ใช้

- **Backend**: Django 5.x, Python 3.8+
- **Frontend**: Bootstrap 5, HTML5, CSS3, JavaScript
- **Database**: SQLite3 (Development), PostgreSQL (Production Ready)
- **Icons**: Bootstrap Icons
- **Deployment**: Vercel Ready

---

# 📁 โครงสร้างไฟล์โปรเจ็กต์

```
MY_PROFILE/
├── 📁 env/                     # Virtual Environment
├── 📁 My_profile/              # Django Project Settings
│   ├── 📄 __init__.py
│   ├── 📄 asgi.py
│   ├── 📄 settings.py          # การตั้งค่าโปรเจ็กต์
│   ├── 📄 urls.py              # URL Configuration หลัก
│   ├── 📄 wsgi.py
│   └── 📄 vercel.json          # Vercel Deployment Config
├── 📁 static/                  # Static Files
│   ├── 📁 assets/
│   │   ├── 📁 css/             # Custom CSS Files
│   │   ├── 📁 js/              # Custom JavaScript Files
│   │   └── 📁 img/             # Images และ Screenshots
│   └── 📁 bootstrap/           # Bootstrap Assets
├── 📁 templates/               # Django Templates
│   ├── 📄 base.html            # Base Template/Layout
│   ├── 📄 index.html           # หน้าแรก/Gallery
│   ├── 📄 about.html           # หน้าโปรไฟล์ส่วนตัว
│   ├── 📄 contact.html         # หน้าติดต่อ
│   ├── 📄 for.html             # หน้าสาธิต For Loop
│   ├── 📄 table.html           # หน้าตารางสูตรคูณ
│   ├── 📄 student.html         # หน้ารายชื่อนักศึกษา
│   └── 📄 subject.html         # หน้ารายวิชา
├── 📁 webpage/                 # Django Application
│   ├── 📁 migrations/          # Database Migrations
│   ├── 📄 __init__.py
│   ├── 📄 admin.py             # Django Admin Configuration
│   ├── 📄 apps.py              # App Configuration
│   ├── 📄 models.py            # Database Models
│   ├── 📄 tests.py             # Unit Tests
│   ├── 📄 urls.py              # App URL Routing
│   └── 📄 views.py             # View Functions
├── 📄 .gitignore               # Git Ignore Rules
├── 📄 build_files.sh           # Production Build Script
├── 📄 data.json                # Sample Data File
├── 📄 db.sqlite3               # SQLite Database
├── 📄 manage.py                # Django Management Script
├── 📄 manage_dev.py            # Development Management Script
├── 📄 requirements.txt         # Python Dependencies
├── 📄 vercel.json              # Vercel Configuration
└── 📄 README.md                # This Documentation
```

---

## ⚙️ การติดตั้งและรันโปรเจ็กต์

### 📋 ความต้องการของระบบ
- Python 3.8 หรือสูงกว่า
- pip (Python Package Manager)
- Git

### 🚀 Development Setup

```bash
# 1. Clone repository
git clone https://github.com/username/vasinee-django-profile.git
cd MY_PROFILE

# 2. สร้าง Virtual Environment
python -m venv env

# 3. เปิดใช้งาน Virtual Environment
# Windows:
env\Scripts\activate
# macOS/Linux:
source env/bin/activate

# 4. ติดตั้ง Dependencies
pip install -r requirements.txt

# 5. สร้าง Database และ Migrations
python manage.py makemigrations
python manage.py migrate

# 6. สร้าง Superuser (Optional)
python manage.py createsuperuser

# 7. รัน Development Server
python manage.py runserver
# หรือใช้
python manage_dev.py runserver
```

เปิดเว็บบราว์เซอร์ที่: **http://127.0.0.1:8000/**

### 🌐 Production Deployment

#### Vercel Deployment
```bash
# 1. ติดตั้ง Vercel CLI
npm install -g vercel

# 2. Build สำหรับ Production
bash build_files.sh

# 3. Deploy ไปยัง Vercel
vercel --prod

# 4. ตั้งค่า Environment Variables ใน Vercel Dashboard:
# - DJANGO_SECRET_KEY=your-secret-key
# - DJANGO_DEBUG=False
# - ALLOWED_HOSTS=your-domain.vercel.app
```

#### การตั้งค่า Production
ใน `settings.py` ให้แก้ไข:
```python
# Production Settings
DEBUG = False
ALLOWED_HOSTS = ['your-domain.vercel.app', 'localhost']

# Security Settings
SECURE_SSL_REDIRECT = True
SECURE_BROWSER_XSS_FILTER = True
SECURE_CONTENT_TYPE_NOSNIFF = True
```

---

## 📦 Dependencies (requirements.txt)

```
Django>=5.0.0
Pillow>=10.0.0
whitenoise>=6.0.0
gunicorn>=20.0.0
python-decouple>=3.8
```

---

## 📝 อธิบายโค้ดและการทำงาน

| ไฟล์/โฟลเดอร์ | คำอธิบาย | ฟีเจอร์หลัก |
|---|---|---|
| `webpage/views.py` | ฟังก์ชัน view สำหรับแต่ละหน้า | index, about, contact, for_view, table_view, student_view, subject_view |
| `webpage/urls.py` | กำหนด URL path สำหรับแต่ละหน้า | URL routing และ pattern matching |
| `templates/base.html` | โครงสร้างหลักของเว็บไซต์ | Navigation, Footer, Bootstrap integration |
| `templates/index.html` | หน้าแรก | Hero Section, Image Carousel, Photo Gallery |
| `templates/about.html` | ข้อมูลส่วนตัว | Personal info, Goals, Beliefs, Achievement table |
| `templates/contact.html` | ช่องทางติดต่อ | Social media links, Contact information |
| `templates/for.html` | ฟอร์มวนซ้ำ | Interactive form, Python loop demonstration |
| `templates/table.html` | ตารางสูตรคูณ | Dynamic multiplication table generator |
| `templates/student.html` | รายชื่อนักศึกษา | Student management form and display |
| `templates/subject.html` | รายวิชา | Subject management system |
| `static/assets/` | Static files | CSS themes, JavaScript, Images, Icons |

---

## 🎨 Features Overview

### 🏠 หน้าแรก (Index)
- **Hero Section** พร้อมข้อความต้อนรับ
- **Image Carousel** แสดงภาพสไลด์
- **Photo Gallery** รูปภาพบรรยากาศการเรียน
- **Responsive Cards** แสดงข้อมูลสำคัญ

### 👩‍🎓 หน้าโปรไฟล์ (About)
- ข้อมูลส่วนตัวและประวัติการศึกษา
- ความเชื่อและปรัชญาชีวิต  
- เป้าหมายระยะสั้นและระยะยาว
- ตารางแสดงเป้าหมายแบบ Interactive

### 📬 หน้าติดต่อ (Contact)
- ช่องทางติดต่อครบถ้วน (Facebook, IG, Line, Email, Tel)
- ไอคอนและปุ่มลิงก์สวยงาม
- การแสดงผลแบบ Responsive

### 🧮 ฟีเจอร์ Interactive
- **ตารางสูตรคูณ**: รับค่าจากผู้ใช้และสร้างตารางแบบไดนามิก
- **For Loop Demo**: สาธิตการใช้งานลูปใน Python
- **Student & Subject Management**: ระบบจัดการข้อมูลแบบง่าย

---

## 📸 ตัวอย่าง Screenshots

### 🏠 Screenshots หน้าแรก (Index)
![Index Page](static/assets/img/screenshots/screenshots_index.png)
*หน้าแรกพร้อม Hero Section, Carousel และ Gallery รูปภาพชีวิตนักศึกษา*

---
