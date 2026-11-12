# ครัวคุมงบ (PWA)

แอพวางแผนมื้ออาหารและคุมงบ ใช้ได้ออฟไลน์ ข้อมูลเก็บในเครื่อง ล็อกด้วย PIN

## ขึ้น GitHub Pages
1. สร้าง repo ใหม่บน GitHub (แบบ Public) เช่น `kroo-kumngob`
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (index.html, sw.js, manifest.webmanifest, โฟลเดอร์ icons)
3. Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save
4. รอ 1-2 นาที ลิงก์จะเป็น `https://<ชื่อผู้ใช้>.github.io/kroo-kumngob/`

## ติดตั้งลงมือถือ
- Android (Chrome): เปิดลิงก์ → เมนู ⋮ → ติดตั้งแอป
- iPhone (Safari): เปิดลิงก์ → ปุ่มแชร์ → เพิ่มลงในหน้าจอโฮม

## อัปเดตแอพ
แทนไฟล์ index.html ใน repo แล้วแก้เลขเวอร์ชันในบรรทัดแรกของ sw.js (`const V='kroo-v1'` → `kroo-v2`)

## หมายเหตุ
- ข้อมูลและ PIN เก็บในเบราว์เซอร์ของแต่ละเครื่อง ไม่ซิงก์ข้ามเครื่อง
- ฟอนต์โหลดจาก Google Fonts ถ้าเครือข่ายบล็อก แอพจะใช้ฟอนต์ไทยของเครื่องแทน
