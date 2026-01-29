# Roadmap นักพัฒนา Microcontroller (จากศูนย์สู่มือโปร)

โปรเจกต์รวบรวมเนื้อหาการสอนและแนวทางการเรียนรู้สำหรับผู้ที่สนใจด้าน Microcontroller ตั้งแต่เริ่มต้นจนถึงระดับมือโปร โดยใช้ **MkDocs Material** ในการจัดการเอกสาร

## 🚀 เข้าชมเว็บไซต์

คุณสามารถเข้าชมเนื้อหาทั้งหมดได้ที่: [GhostMicro - Microcontroller Roadmap](https://GhostMicro.github.io/micro-series-dev-microcontroller/)

## 📖 เนื้อหาในซีรีส์ (10 ตอน)

1. โลกของ Microcontroller เลือกตัวไหนดี?
2. Arduino Uno R4: จุดเริ่มต้นของทุกคน
3. ESP32: มหาอำนาจแห่ง IoT (ตอนที่ 1)
4. ESP32: เชื่อมต่อโลกอินเทอร์เน็ต (ตอนที่ 2)
5. STM32: ก้าวสู่มาตรฐานอุตสาหกรรม
6. Raspberry Pi: คอมพิวเตอร์จิ๋วที่ทำได้ทุกอย่าง
7. Raspberry Pi + Python: ควบคุม Hardware
8. การเลือกใช้แหล่งจ่ายไฟ (Power Supply)
9. Communication Protocols: คุยกันยังไง?
10. Project Final: รวมพลังสร้างระบบ Smart Home

## 🛠 การติดตั้งเพื่อพัฒนา (Local Setup)

หากคุณต้องการแก้ไขเนื้อหาและพรีวิวบนเครื่องของคุณเอง:

1. **ติดตั้ง Python** (แนะนำเวอร์ชัน 3.x)
2. **ติดตั้ง dependencies:**

   ```bash
   pip install mkdocs-material
   ```

3. **รันเซิร์ฟเวอร์เพื่อดูผลลัพธ์:**

   ```bash
   mkdocs serve
   ```

4. เปิด Browser ไปที่ `http://127.0.0.1:8000`

## 📦 การ Deploy (Automated Flow)

โปรเจกต์นี้ใช้ **GitHub Actions** ในการ Deploy อัตโนมัติ:

- เมื่อมีการ `git push` ไปยังสาขา `main` ตัวระบบจะทำการ Build และอัปเดตหน้าเว็บจริงให้ทันทีผ่าน GitHub Pages

---

สร้างสรรค์โดยทีมงาน **GhostMicro**
