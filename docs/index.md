# ยินดีต้อนรับสู่ Roadmap นักพัฒนา Microcontroller (จากศูนย์สู่มือโปร)

ซีรีส์นี้ถูกออกแบบมาเพื่อช่วยให้นักพัฒนาเริ่มต้นกับโลกของระบบสมังฝังตัว (Embedded Systems) และ Microcontroller ได้อย่างมั่นใจ ตั้งแต่การเลือกบอร์ดไปจนถึงการสร้างโปรเจกต์ Smart Home ของตัวเอง

## โครงสร้างเนื้อหา

| ตอนที่   | หัวข้อ                                         | รายละเอียดเนื้อหา                           |
| ------ | -------------------------------------------- | ---------------------------------------- |
| **1**  | **โลกของ Microcontroller เลือกตัวไหนดี?**       | พื้นฐาน Arduino, ESP32, STM32 และ Pi       |
| **2**  | **Arduino Uno R4: จุดเริ่มต้นของทุกคน**           | บอร์ดมาตรฐาน การติดตั้ง IDE และไฟกระพริบ      |
| **3**  | **ESP32: มหาอำนาจแห่ง IoT (ตอนที่ 1)**           | Wi-Fi/Bluetooth และการต่อเซนเซอร์          |
| **4**  | **ESP32: เชื่อมต่อโลกอินเทอร์เน็ต (ตอนที่ 2)**       | Cloud (Blynk/LINE Notify) และ Web Server |
| **5**  | **STM32: ก้าวสู่มาตรฐานอุตสาหกรรม**              | Blue Pill และ STM32CubeIDE               |
| **6**  | **Raspberry Pi: คอมพิวเตอร์จิ๋วที่ทำได้ทุกอย่าง**      | MCU vs SBC และการลง OS                   |
| **7**  | **Raspberry Pi + Python: ควบคุม Hardware**    | GPIO และ Python                          |
| **8**  | **การเลือกใช้แหล่งจ่ายไฟ (Power Supply)**        | การจ่ายไฟให้อย่างปลอดภัย                     |
| **9**  | **Communication Protocols: คุยกันยังไง?**       | UART, I2C, SPI                           |
| **10** | **Project Final: รวมพลังสร้างระบบ Smart Home** | สรุปผลและแนวทางการต่อยอด                   |

---

## ตัวอย่างการแสดงวิดีโอจาก YouTube

คุณสามารถจำลองการนำวิดีโอมาใส่ใน MkDocs ได้ง่ายๆ โดยใช้ `<iframe>` ซึ่งเป็นมาตรฐานที่ YouTube ให้มาครับ:

<div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
    <iframe src="https://www.youtube.com/embed/nL3464KGXJI" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
</div>

> [!TIP]
> การใช้ `div` ครอบ `iframe` พร้อมทำ CSS นิดหน่อย (ตามตัวอย่างด้านบน) จะช่วยให้วิดีโอแสดงผลได้พอดีหน้าจอ (Responsive) ทั้งในคอมพิวเตอร์และมือถือครับ!
