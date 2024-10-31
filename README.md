# แนวทางการทำงาน ESP32-Blink
## 1 ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
เลือกโปรเจค blink จาก show examples แล้วกด create
![image](https://github.com/user-attachments/assets/b300c129-bdda-4135-be79-3e265464bf26)

## 2 ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร
โค้ดดีงกล่าวเป็นการทำให้ LED กระพริบ โดยใช้ไดรเวอร์ GPIO ซึ่งไม่ต้องแก้ไขไฟล์ blink_example_main.c และ สามารถไปที่ Example Configuration เพื่อตั้งค่าส่วนต่างๆได้ 
![image](https://github.com/user-attachments/assets/8ea147d1-7d20-4a10-ba9a-e9adf92dcc7b)

## 3 แสดงขั้นตอนการทำ project
ไปที่Example Configuration เพื่อตั้งค่าขาGPIOและระยะเวลาติด-ดับได้ และกด built flash moniter
![image](https://github.com/user-attachments/assets/32ee579d-741c-459a-8982-1eb98b162444)

## 4. แสดงผลการทำ project


https://github.com/user-attachments/assets/c057bebe-3946-4756-b0af-9630b61394fd



## 5 สรุปผลการทำ project
โปรเจคนี้ทำเกี่ยวกับ LED กระพริบซึ่งสามารถตั้งค่า GPIO/ประเภทของ LED ได้ ในเมนู Example Configuration
