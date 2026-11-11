# คู่มือเตรียม Google Workspace สำหรับ Student Database

1. ใช้ Google Account ที่กำหนดเป็นเจ้าของระบบ
2. สร้าง Google Drive folder ชื่อ `STUDENT_DATABASE`
3. ตั้งค่าโฟลเดอร์เป็น Restricted / จำกัดผู้เข้าถึง
4. สร้าง Google Spreadsheet ชื่อ `STUDENT_DATABASE_MASTER`
5. สร้างแท็บตามไฟล์ CSV ในโฟลเดอร์ `schemas/` แล้วนำเฉพาะแถวหัวตารางไปวาง
6. อย่าใส่ข้อมูลนักเรียนจริงในช่วงทดสอบ
7. จด Spreadsheet ID และ Drive Folder ID เก็บไว้ในที่ปลอดภัย ไม่ต้องใส่ใน GitHub หากไม่จำเป็น
8. ก่อนเปิดใช้งานจริง ต้องกำหนด backend identity, สิทธิ์ API, role และ classroom authorization ให้เสร็จ

หมายเหตุ: Google Sheets เป็นฐานข้อมูลเริ่มต้นที่เหมาะกับระบบขนาดเล็ก/ปานกลาง แต่ควรวาง backend interface ให้ย้ายฐานข้อมูลได้ในอนาคต
