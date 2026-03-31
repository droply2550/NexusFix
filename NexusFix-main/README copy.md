# 🃏 NexusFix

**NexusFix** เป็นเว็บไซต์ที่พัฒนาด้วย **Django Framework** โดยมีวัตถุประสงค์เพื่อเป็นระบบจัดการข้อมูลและแสดงสินค้าประเภทร้านการ์ด (Card Shop)

---

## ✨ ฟีเจอร์ของระบบ (Features)
- [x] **CRUD System:** จัดการข้อมูลสินค้า (เพิ่ม / แก้ไข / ลบ)
- [x] **Data Display:** แสดงข้อมูลและรายการสินค้าบนหน้าเว็บ
- [x] **Media Support:** รองรับการอัปโหลดและแสดงรูปภาพสินค้า

## 🛠 เทคโนโลยีที่ใช้
- **Backend:** Python / Django Framework
- **Database:** SQLite
- **Frontend:** HTML / CSS / Bootstrap

## 📥 วิธีติดตั้งและเริ่มใช้งาน

### 1. เตรียมโปรเจกต์
```bash
git clone https://github.com/replaysleep/NexusFix.git

# เข้าโฟลเดอร์โปรเจกต์
cd NexusFix/Nexus

# สร้าง virtual environment
python -m venv venv

# เปิดใช้งาน (Windows)
venv\Scripts\activate

pip freeze > requirements.txt
pip install -r requirements.txt

# ตรวจสอบความเรียบร้อยและสร้างฐานข้อมูล
python manage.py migrate

# สร้างบัญชี Admin สำหรับหลังบ้าน ( )
python manage.py createsuperuser

# รันเซิร์ฟเวอร์
python manage.py runserver

เข้าใช้งานได้ที่: http://127.0.0.1:8000/