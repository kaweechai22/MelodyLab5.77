# PhySound Acoustics Data+Cal+Visualizer GitHub v5

เวอร์ชันนี้เพิ่ม **Sound Wave Visualizer** แบบ Observation Mode ตามแนวคิดของครู: แอปแสดงภาพจำลองและให้ปรับค่าพารามิเตอร์เท่านั้น แต่ไม่ใส่ข้อความชี้นำ และไม่สรุปความสัมพันธ์ให้นักเรียน

## สิ่งที่เพิ่มใน v5

- Sound Wave Visualizer
- Longitudinal Wave
- Pressure Variation
- Displacement + Pressure
- Longitudinal / Transverse Compare
- Superposition
- Beats Visualizer
- Standing Wave in Air Column
- Resonance Visualizer
- Harmonics / Timbre
- Doppler Visualizer
- Play / Pause / Reset
- Export Visualizer Image เป็น PNG

## หลักคิด

แอปทำหน้าที่:
- แสดงภาพจำลองให้สังเกต
- ให้ปรับค่าพารามิเตอร์พื้นฐาน
- เก็บข้อมูลเสียงจริง
- ตรวจสอบความคลาดเคลื่อนของอุปกรณ์
- ส่งออกข้อมูลดิบและภาพกราฟ

แอปไม่ทำ:
- ชี้นำประเด็นแทนครู
- สรุปผลให้นักเรียน
- ทำ Dashboard วิเคราะห์กลุ่ม
- ทำ Report Pack อัตโนมัติ

## วิธีอัป GitHub Pages

อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้น repository แล้วเปิด Settings → Pages → Deploy from branch → main / root


## v5.1 Clean Home

- ลบข้อความส่วน Hero หน้าแรกออก
- หน้าแรกเน้นการ์ดเมนูเป็นหลัก


## v5.2 Bilingual Menu

- ปรับชื่อเมนูเป็น 2 ภาษา
- ใช้รูปแบบ English (ภาษาไทย)


## v5.3 Axes and Units

- เพิ่มชื่อแกนและหน่วยในหน้า Sound Wave Visualizer ทุกโหมด
- ใช้หน่วยเชิงแนวคิด เช่น position x (m), amplitude (arb. unit), frequency f (Hz), time t (s)


## v5.4 Relative Units

- เปลี่ยนข้อความหน่วยจาก arb. unit เป็น relative / relative amplitude / relative response เพื่อให้นักเรียนเข้าใจง่ายขึ้น


## v5.5 Observation Point

- เพิ่มจุดสังเกตสีเด่นในหน้า Wave Visualizer หลายโหมด
- ใช้สีชมพู/แดงเป็น highlighted observation point
- เพิ่ม label ชี้ตำแหน่งเพื่อให้นักเรียนติดตามการเคลื่อนที่หรือเปรียบเทียบตำแหน่งได้ง่ายขึ้น


## v5.6 Clean Visualizer Text

- ลบข้อความอธิบายใต้หัวข้อ Sound Wave Visualizer
- ลบข้อความ note ในกล่อง Parameters


## v5.7 Clean Measure

- ซ่อนข้อความสถานะไมโครโฟนในหน้า Measure ให้แสดงเฉพาะเมื่อเกิด error
- ลบตัวเลือก Student/Teacher Mode ออกจากหน้า Measure เพื่อลดความรก


## v5.8 Clean Home Header

- ลบคำว่า Data+Cal+Visualizer ออกจากแถบหัวเว็บ
- ลบเมนูตัวอักษรด้านบนทั้งหมด
- ปรับหน้าแรกให้เน้นแสดงการ์ดเมนูหลักใน 1 หน้าจอมากขึ้น


## v5.9 Phyphox Pages

- หน้าแรกแสดงเฉพาะการ์ดหัวข้อใหญ่
- กดหัวข้อแล้วเปิดหน้า HTML แยกของหัวข้อนั้น
- หน้ารายละเอียดซ่อนหัวข้ออื่นทั้งหมด
- มีปุ่มย้อนกลับ และใช้ปุ่มย้อนกลับของโทรศัพท์/เบราว์เซอร์ได้


## v5.10 Embedded Export

- เอา Session ออกจากหน้าแรกและลบ session.html
- เพิ่ม Data Export ในหน้าทดลองย่อย
- ข้อมูลที่บันทึกและส่งออกเป็นข้อมูลเฉพาะของหน้านั้น ๆ


## v5.11 Topic-by-Topic Workflow

- เน้นการใช้งานทีละหัวข้อ
- หน้าแรกไม่มี Session แยกกลาง
- แต่ละหน้าทดลองมี Data Export ของตัวเอง
- ไฟล์ CSV ที่ส่งออกใช้ข้อมูลเฉพาะหัวข้อนั้น
- Measure และ Calibration ยังคงใช้ระบบส่งออกเฉพาะหน้าของตนเอง


## v5.12 Mobile-fit Home

- ปรับหน้าแรกบนมือถือเป็น 2 คอลัมน์แบบ compact card
- ให้ 7 หัวข้อหลักแสดงครบในหน้าจอมือถือมากขึ้นโดยไม่ต้องเลื่อน
- ลดความสูงการ์ด ไอคอน และคำอธิบายเฉพาะหน้าแรก
- จอเตี้ยมากจะซ่อน note หรือ description อัตโนมัติเพื่อให้หัวข้อครบ
