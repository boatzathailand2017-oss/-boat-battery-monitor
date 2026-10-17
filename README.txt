BOAT ELECTRIC Battery Monitor — ตัวอย่างเว็บแอป

ไฟล์ใน ZIP:
- index.html: หน้าจอแอปและปุ่มทดลอง
- manifest.json: ข้อมูลสำหรับเว็บแอปที่เพิ่มลงหน้าจอโฮมได้
- sw.js: แคชไฟล์เพื่อช่วยให้เปิดซ้ำได้
- icon-192.png และ icon-512.png: ไอคอนแอป

สำคัญ: ค่าต่าง ๆ เป็นค่าจำลอง ยังไม่ได้เชื่อมต่อ BMS จริง

วิธีเผยแพร่ผ่าน iPhone:
1. แตกไฟล์ ZIP ในแอป Files
2. เปิด github.com ใน Safari แล้วสมัคร/เข้าสู่ระบบ
3. สร้าง repository แบบ Public ชื่อ boat-battery-monitor
4. เข้า repository > Add file > Upload files แล้วอัปโหลดไฟล์ทั้ง 5 ไฟล์จาก ZIP (อย่าอัปโหลด ZIP ทั้งก้อน)
5. กด Commit changes
6. เปิด Settings ของ repository > Pages
7. ใน Build and deployment เลือก Deploy from a branch
8. เลือก Branch: main และ Folder: /(root) แล้วกด Save
9. รอ GitHub สร้างเว็บ จากนั้น URL มักเป็น https://ชื่อผู้ใช้.github.io/boat-battery-monitor/
10. เปิด URL ใน Safari บน iPhone > ปุ่ม Share > Add to Home Screen > Add

หากหาเมนูอัปโหลดไฟล์ไม่เจอ ให้เปิดเมนู aA ใน Safari แล้วเลือก Request Desktop Website
