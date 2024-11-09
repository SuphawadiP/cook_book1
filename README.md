# Hello World Example

## การเลือก Example IDF

![image](https://github.com/user-attachments/assets/3f5883ec-8854-4d1a-a48d-7875819e77c7)

ขั้นตอนการเลือก Example IDF
1. เลือก ESP-IDF
2. เปิดโปรแกรมตัวอย่าง hello_world
3. เลือก hello_world
4. เลือก Create project using example hello_world
5. build, flash และ monitor โปรแกรม

### ผลลัพธ์
โดยการทำงานของ Example นี้คือให้แสดงผลข้อความ "Hello World" และ restart ทุกๆ 10 วินาที

![Screenshot 2024-11-09 212605](https://github.com/user-attachments/assets/276b9ef2-74f2-4478-a269-ba617f6fef75)

https://drive.google.com/file/d/155X24JyQ-q-5kneNnJix3GNYwuw3f8W3/view?usp=sharing

## การแก้ไข

6. แก้ไขไฟล์ main.c เพื่อแก้ไขการแสดงผล
   
* สามารถแก้ไขข้อความที่ต้องการให้แสดงผลได้

![Screenshot 2024-11-09 215523](https://github.com/user-attachments/assets/561aaa84-0c89-4cbc-a517-2c30ce7a3ea9)
     
ตัวอย่าง
```
    printf("Hello!!!\n");
    printf("私の名前は [Phai] です。\n");
```
* สามารถแก้ไขความเร็วที่ต้องการให้แสดงผลได้ จากการเปลี่ยนการนับเวลาถอยและระยะเวลาในการ delay
  
![Screenshot 2024-11-09 220159](https://github.com/user-attachments/assets/d6c75d88-c1e7-40d3-b460-df0f19533540)

## ผลลัพธ์หลักการแก้ไข

* แสดงผลข้อความบน Serial Moniter "Hello world! 私の名前は [Phai] です。" และ restart ทุกๆ 1 นาที

![Screenshot 2024-11-09 221322](https://github.com/user-attachments/assets/1f9ae45d-3f02-46f7-aac1-7c04d16cc5ea)

https://drive.google.com/file/d/1Qzm-6j0ZK3HCQDrA8jlBN_0Vf5AB3aPU/view?usp=sharing

## สรุปผลการทดลอง
* การทดลอง Hello World Example บน ESP32 เป็นขั้นพื้นฐานที่ช่วยให้เราเข้าใจการเชื่อมต่อและการเขียนโค้ดเบื้องต้นบนบอร์ด ESP32 ได้ดี เมื่ออัปโหลดโค้ดสำเร็จ และเปิด Serial Monitor จะเห็นข้อความที่กำหนดไว้ ซึ่งแสดงว่าการเชื่อมต่อและการอัปโหลดโค้ดทำงานได้อย่างถูกต้อง

