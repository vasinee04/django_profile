

<div align="center">
</div>

<div align="center">
	<h1>🌸 <span style="color:#e75480">VASINEE Django Profile Webapp</span> 🌸</h1>
	<p>
		<img src="https://img.shields.io/badge/Django-5.x-success?logo=django" alt="django"/>
		<img src="https://img.shields.io/badge/Bootstrap-5.x-blueviolet?logo=bootstrap" alt="bootstrap"/>
		<img src="https://img.shields.io/badge/License-Educational-lightgrey" alt="license"/>
	</p>
	<p><b>เว็บโปรไฟล์ส่วนตัว</b> สร้างด้วย <b>Django</b> และ <b>Bootstrap 5</b> พร้อม UI สีชมพูสวยงาม รองรับภาษาไทย 🇹🇭</p>
</div>

---

## ✨ คุณสมบัติเด่น

<h2>✨ คุณสมบัติเด่น</h2>

<ul>
	<li>👩‍🎓 <b>หน้าโปรไฟล์ส่วนตัว (About)</b></li>
	<li>🧮 <b>ตารางสูตรคูณ (Multiplication Table)</b></li>
	<li>🔁 <b>ฟอร์มวนซ้ำ (For Loop Demo)</b></li>
	<li>🖼️ <b>แกลเลอรี่ภาพบรรยากาศชีวิตการเรียน (Index)</b></li>
	<li>📬 <b>ช่องทางติดต่อ (Contact)</b> พร้อมลิงก์ Facebook, IG, Line, Email, โทรศัพท์</li>
	<li>🎨 ใช้ <b>Bootstrap 5</b>, Bootstrap Icons, CSS ธีมชมพู</li>
	<li>📱 <b>Responsive</b> รองรับมือถือ</li>
</ul>

---

## 🗂️ โครงสร้างโปรเจกต์ (อัปเดตล่าสุด Sep 2025)

```text
My_profile/
├── manage.py
├── manage_dev.py
├── requirements.txt
├── data.json
├── db.sqlite3
├── vercel.json
├── README.md
├── build_files.sh
├── My_profile/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── settings_dev.py
│   ├── urls.py
│   ├── wsgi.py
│   └── __pycache__/
├── webpage/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   ├── views.py
│   ├── migrations/
│   │   ├── __init__.py
│   │   └── __pycache__/
│   └── __pycache__/
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── for.html
│   └── table.html
├── static/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   ├── datatables-simple-demo.js
│   │   └── scripts.js
│   └── assets/
│       ├── demo/
│       │   ├── chart-area-demo.js
│       │   ├── chart-bar-demo.js
│       │   ├── chart-pie-demo.js
│       │   └── datatables-demo.js
│       └── img/
│           ├── B1.jpg
│           ├── B2.jpg
│           ├── B3.jpg
│           ├── B4.jpg
│           ├── error-404-monochrome.svg
│           ├── ui10.png
│           └── ui11.png
└── env/  # Python virtual environment (ไม่ต้อง commit ลง git)
	├── pyvenv.cfg
	├── Include/
	├── Lib/
	└── Scripts/
```

---

## 🚀 วิธีติดตั้งและใช้งาน

1. **Clone repo และติดตั้ง dependencies**
	 ```bash
	 git clone <repo-url>
	 cd My_profile
	 python -m venv env
	 env\Scripts\activate  # (Windows)
	 pip install -r requirements.txt
	 ```

2. **รันเซิร์ฟเวอร์**
	 ```bash
	 python manage.py runserver
	 ```
	 เปิดเว็บที่ [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 📝 อธิบายโค้ดและการทำงาน

| ไฟล์/โฟลเดอร์ | คำอธิบาย |
|---|---|
| `webpage/views.py` | ฟังก์ชัน view สำหรับแต่ละหน้า (index, about, contact, for_view, table_view) |
| `webpage/urls.py` | กำหนด path สำหรับแต่ละหน้า |
| `templates/base.html` | โครงสร้างหลักของเว็บ ใช้ Bootstrap และธีมสีชมพู |
| `templates/index.html` | หน้าแรก มี Hero Section, Carousel, และ Gallery |
| `templates/about.html` | ข้อมูลส่วนตัว, ความเชื่อ, เป้าหมาย, ตารางเป้าหมาย |
| `templates/contact.html` | ช่องทางติดต่อ พร้อมไอคอนและปุ่มลิงก์ |
| `templates/for.html` | ฟอร์มรับตัวเลข แสดงผลลัพธ์การวนซ้ำ |
| `templates/table.html` | ฟอร์มรับตัวเลข แสดงตารางสูตรคูณ |
| `static/` | เก็บไฟล์ CSS, JS, รูปภาพ, และ assets อื่นๆ |

---

## ⚙️ การตั้งค่า Production

- แก้ไข `ALLOWED_HOSTS` ใน `settings.py` ให้ตรงกับโดเมนที่ใช้งานจริง
- ตั้งค่า `DEBUG = False` สำหรับ production

---

## 📄 License

This project is for educational purposes only.