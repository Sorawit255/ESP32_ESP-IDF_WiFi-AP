# แนวทางการทำงาน ESP32 ESP32_ESP-IDF_WiFi-AP cook book
## 1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
- ### เลือกโปรเจค Wi-Fi SoftAP Example จาก show examples แล้วกด create
![image](https://github.com/user-attachments/assets/2d723c0f-a0c4-46e5-82f6-3081d7d7896d)

## 2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร 
- ### สามารถไปที่ idf.py menuconfig ที่ example config ตั้งค่า WiFi SSID/password รวมถึงค่าที่เกี่ยวข้องอื่นๆ
![image](https://github.com/user-attachments/assets/146636f7-37f9-4098-a539-ead6b973e25a)

## 3. แสดงขั้นตอนการทำ project
- ### หลังจากแก้ไขแล้วให้กด build จะได้รหัสไวไฟและรหัสผ่านตามที่เขียน
![image](https://github.com/user-attachments/assets/5e60df2b-ca27-47f2-9b10-4a160fad7d65)
### ให้ลองเชื่อม wifi ในมือถือดู
![S__1220614](https://github.com/user-attachments/assets/8cf3da41-6896-473c-8062-9f03075b2392)

## 4. แสดงผลการทำ project
- ### เมื่อกดเชื่อมผ่านมือถือแล้วจะแสดงค่า
![image](https://github.com/user-attachments/assets/3103f16d-5161-40ef-823d-1964c59d7b2a)
### เมื่อ ออกจากเครือข่าย
![image](https://github.com/user-attachments/assets/4cd88256-bfde-4d04-a454-5d3296b17290)
## 5. สรุปผลการทำ project 
### โปรเจคนี้ทำงานเป็น SoftAP ซึ่งช่วยให้ อุปกรณ์อื่นๆ สามารถเชื่อมต่อมาที่ ESP32 ได้เหมือนกับการเชื่อมต่อกับเครือข่าย Wi-Fi
