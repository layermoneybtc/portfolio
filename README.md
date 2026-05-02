# 📊 Portfolio Live v0.01

ระบบติดตามพอร์ตการลงทุน · ราคา Live อัตโนมัติ · ข้อมูลเก็บใน browser คุณเท่านั้น

---

## 🚀 วิธี Deploy ขึ้น GitHub Pages (ฟรี 100%)

### ขั้นตอนที่ 1 — สมัคร GitHub

1. ไปที่ **[github.com](https://github.com)**
2. กด **Sign up** → ใส่ Email, Password, Username
3. ยืนยัน Email → เสร็จ!

---

### ขั้นตอนที่ 2 — สร้าง Repository

1. หลัง Login แล้ว กดปุ่ม **+** มุมขวาบน → **New repository**
2. กรอกข้อมูล:
   - **Repository name**: `portfolio` (หรือชื่ออะไรก็ได้)
   - **Description**: `ระบบติดตามพอร์ตการลงทุน`
   - เลือก **Public** (ต้องเป็น Public ถึงจะใช้ GitHub Pages ฟรี)
   - ✅ ติ๊ก **Add a README file**
3. กด **Create repository**

---

### ขั้นตอนที่ 3 — อัปโหลดไฟล์

1. ในหน้า repository กด **Add file** → **Upload files**
2. ลากไฟล์ **`index.html`** วางลงไป
3. ด้านล่างกรอก "Add portfolio" แล้วกด **Commit changes**

---

### ขั้นตอนที่ 4 — เปิด GitHub Pages

1. ไปที่ **Settings** (tab ด้านบน)
2. เลื่อนลงไปที่เมนูซ้าย → กด **Pages**
3. ตรง **Source** เลือก **Deploy from a branch**
4. ตรง **Branch** เลือก **main** → กด **Save**
5. รอ 1-2 นาที → refresh หน้า
6. จะเห็นลิงก์เว็บ:

```
https://ชื่อคุณ.github.io/portfolio/
```

🎉 **เสร็จแล้ว!** แชร์ลิงก์นี้ให้ใครก็ได้

---

## 🔄 วิธีอัปเดตเวอร์ชันใหม่

1. เข้า repository ของคุณ
2. กดที่ไฟล์ **`index.html`**
3. กดไอคอน **ดินสอ ✏️** (Edit this file)
4. ลบเนื้อหาเดิมทั้งหมด → วางโค้ดใหม่
5. กด **Commit changes**
6. รอ 1-2 นาที → เว็บอัปเดตอัตโนมัติ
7. ข้อมูลผู้ใช้ยังอยู่ครบ (เก็บใน localStorage)

**หรือ** อัปโหลดไฟล์ใหม่ทับ:
1. กด **Add file** → **Upload files**
2. ลากไฟล์ `index.html` ใหม่วาง
3. กด **Commit changes**

---

## 🔒 ความปลอดภัย

| ข้อมูล | เก็บที่ไหน | ใครเข้าถึงได้ |
|---|---|---|
| พอร์ตสินทรัพย์ | localStorage ใน browser | เจ้าของเครื่องเท่านั้น |
| API Keys | localStorage ใน browser | เจ้าของเครื่องเท่านั้น |
| ประวัติซื้อ/ขาย | localStorage ใน browser | เจ้าของเครื่องเท่านั้น |
| โค้ด HTML | GitHub Pages (public) | ทุกคนเห็นโค้ดได้ |

**ไม่มี server เก็บข้อมูล** · ไม่มี database · ไม่มีการส่งข้อมูลส่วนตัวออกไปที่ใดทั้งสิ้น

---

## ⚠️ สิ่งสำคัญ

- **Backup เป็นประจำ** — กด 📤 Export เพื่อ backup เป็นไฟล์ JSON
- **ถ้าล้าง browser data ข้อมูลจะหาย** → Import จาก backup ได้
- **ไม่ใช่คำแนะนำการลงทุน** — ใช้เพื่อติดตามพอร์ตส่วนตัวเท่านั้น

---

## 📋 API Keys ที่ต้องสมัคร (ฟรีทั้งหมด)

| API | สมัครที่ | ใช้กับ | Limit |
|---|---|---|---|
| Finnhub | [finnhub.io/register](https://finnhub.io/register) | หุ้น US, ทองคำ | 60 req/นาที |
| Alpha Vantage | [alphavantage.co](https://www.alphavantage.co/support/#api-key) | หุ้นไทย SET | 25 req/วัน |
| Bitkub | ไม่ต้องสมัคร | Crypto | ไม่จำกัด |
| ExchangeRate API | ไม่ต้องสมัคร | USD/THB | ไม่จำกัด |
