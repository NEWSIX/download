## FILEFLOW (PIR)



* [ดาวน์โหลด Fileflow V1.7.3 (15/ธ.ค./2023)](https://drive.usercontent.google.com/download?id=1r-h7y7KQcz4rHs34KjuFXZrhq_H5SSU4&export=download&authuser=2&confirm=t&uuid=d503d3f6-d0b0-4f6e-b1be-2ffe4f04f7d6&at=APZUnTUinV8FJuoeuEmeFt54AGnn:1702602781249)
  `flash excel `

  + แก้ไขจำนวนของออเดอร์

* [ดาวน์โหลด Fileflow V1.7.2 (6/ธ.ค./2023)](https://drive.usercontent.google.com/download?id=1zhDHMPKqnOCyADp50V7ha-1rHBazMFbv&export=download&authuser=2&confirm=t&uuid=d524663c-19d2-42df-aee4-1c46ec3b7227&at=APZUnTXEa9dDJSDkgTaEvwSB5EYV:1701829591083)
  `รหัสสินค้าอยู่ก่อนไซซ์`

  + ระบุรหัสสินค้า <b>ก่อน</b> ไซซ์เสมอ เช่น
    +  sub-tk01-Bc14W (L) ==>  sub-tk01-`Bc14W` (L)
    +  sub-tk01-FLOWER-Bc14W (L) ==> sub-tk01-FLOWER-`Bc14W` (L)
    +  sub-tk01-FLOWER-ประเทศไทย2024 ==> `Bc14W` (L)

* [ดาวน์โหลด Fileflow V1.7.1 (3/ธ.ค./2023)](https://drive.usercontent.google.com/download?id=1CqRH6CrWtV3Adep58A66Kjc4eXgqojbh&export=download&authuser=2&confirm=t&uuid=f86c5fca-0162-4661-bd78-e7d170831602&at=APZUnTUeVRYdKi48lhkOSZEi9D5N%3A1701599843080)
  `สามารถเลือกคอลัมของ Excel ได้เอง`

  + ตั้งค่า -> ด้านล่าง -> เลือก platform
    + คัดลอกชื่อหัวข้อคอลัม (header) ที่ระบุรหัสสินค้า เช่น `item_name` (shipnity)
    + เลือกอักษรหว่าง ประเภท วัตถุดิบ รหสินค้า ไซซ์ เช่น sub-tk01-1173 (6XL) ==> รหว่างคือ `-`
    + เลือกอักษรก่อน ไซซ์ เช่น sub-tk01-1173 (6XL) ==> ` (` (มีช่องว่างด้วย)
  
<br>

 ![alt text]( https://github.com/NEWSIX/FileFlowPro/blob/main/content/fileflowV1.7.2.gif?raw=true)

 ![alt text]( https://github.com/NEWSIX/FileFlowPro/blob/main/content/excel_column.png?raw=true)

* [ดาวน์โหลด Fileflow V1.6.7 (2/ธ.ค./2023)](https://drive.usercontent.google.com/download?id=1AWv1F_OhyxMi5IUyIH4JyiWEGvaYpCTm&export=download&authuser=2&confirm=t&uuid=4a3b13d7-7c1e-4cf9-95f1-1b101da1f8ff&at=APZUnTW4_b5_q88WotqKlmCjDaDs:1701518760474)
  
* [ลิงค์สำรอง  Fileflow V1.7.2](https://drive.google.com/file/d/1zhDHMPKqnOCyADp50V7ha-1rHBazMFbv/view?usp=drive_link)
* [ลิงค์สำรอง  Fileflow V1.7.1](https://drive.google.com/file/d/1CqRH6CrWtV3Adep58A66Kjc4eXgqojbh/view?usp=drive_link)
* [ลิงค์สำรอง  Fileflow V1.6.7](https://drive.google.com/file/d/1AWv1F_OhyxMi5IUyIH4JyiWEGvaYpCTm/view?usp=drive_link)

<hr>

### ขั้นตอนการทำงานของโปรแกรม FileFlowPro
<br>

โปรแกรม FileFlowPro เป็นโปรแกรมที่ช่วยให้พนักงานสามารถนำเข้าข้อมูลออเดอร์จากไฟล์ Excel ได้อย่างสะดวกและรวดเร็ว โดยโปรแกรมจะทำการทำความสะอาดข้อมูล แยกออเดอร์ตามแพลตฟอร์ม จัดกลุ่มออเดอร์ และดาวน์โหลดไฟล์รูปภาพที่เกี่ยวข้องออกมาในนามสกุลที่ต้องการ
<br>
ขั้นตอนการทำงานของโปรแกรม

1. โปรแกรมจะตรวจสอบว่าไฟล์ Excel ข้อมูลออเดอร์มีอยู่หรือไม่ หากไม่พบไฟล์ Excel โปรแกรมจะแจ้งเตือนให้ผู้ใช้สร้างไฟล์ Excel ขึ้นมาใหม่
2. โปรแกรมจะทำการแยกออเดอร์ตามแพลตฟอร์ม เช่น Shopee, Lazada, TikTok เป็นต้น โดยอัตโนมัติ
3. โปรแกรมจะทำการทำความสะอาดข้อมูลออเดอร์ เช่น ลบออเดอร์ซ้ำ ลบออเดอร์ที่ไม่มีข้อมูลที่จำเป็น หรือ ข้อมูลที่ไม่จำเป็นออก เป็นต้น 
4. ผู้ใช้สามารถค้นหาข้อมูลออเดอร์ได้อย่างสะดวกและรวดเร็วด้วยฟังก์ชัน filter และ search
5. โปรแกรมจะจัดกลุ่มออเดอร์ โดยสามารถเลือกจำนวนออเดอร์ที่ต้องการจัดกลุ่มได้ เช่น 40-60 ออเดอร์ต่อกลุ่ม โดยโปรแกรมจะจัดกลุ่มออเดอร์ตามแพลตฟอร์ม
6. โปรแกรมจะดาวน์โหลดไฟล์รูปภาพที่เกี่ยวข้องออกมาในนามสกุลที่ต้องการ เช่น .tiff, .jpg, .png เป็นต้น โดยโปรแกรมจะดาวน์โหลดไฟล์รูปภาพจากแพลตฟอร์มที่ออเดอร์มาจากที่ผู้ใช้ได้กำหนด
7. โปรแกรมจะ export ข้อมูลออเดอร์ออกมาเป็นไฟล์ Excel โดยผู้ใช้สามารถเลือกรูปแบบของไฟล์ Excel ที่ต้องการได้ เช่น
  <br>- ไฟล์ Excel สำหรับใช้ในการเบิกสินค้า
  <br>- ไฟล์ Excel สำหรับใช้ในการอัพเข้าสู่ระบบของ Flash Express
8. โปรแกรมจะแสดงสถานะการทำงานให้ผู้ใช้ทราบ เช่น กำลังทำงาน ทำงานเสร็จแล้ว ทำงานล้มเหลว เป็นต้น
  
<b>สรุป</b>

โปรแกรม FileFlowPro เป็นโปรแกรมที่มีประสิทธิภาพสูงในการช่วยลดเวลาและแรงงานในการนำเข้าข้อมูลออเดอร์จากไฟล์ Excel โดยโปรแกรมมีจุดเด่นที่ช่วยลดโอกาสในการเกิดข้อผิดพลาดจากการคัดลอกข้อมูล ช่วยให้ข้อมูลออเดอร์มีความถูกต้องและครบถ้วน รองรับการทำงานกับไฟล์ Excel จากแพลตฟอร์มต่างๆ และสามารถเลือกจำนวนออเดอร์ที่ต้องการจัดกลุ่มได้ นอกจากนี้ โปรแกรมยังสามารถ export ข้อมูลออเดอร์ออกมาเป็นไฟล์ Excel ได้อีกด้วย

<hr>

### เทคโนโลยีของโปรแกรม FileFlowPro

<b>Front-end:</b>
<br>
+ React (Typescript) + Vite
+ Redux Toolkit

<b>Back-end:</b>
<br>
+ Node.js
+ GraphQL
+ Tauri (Rust)
  
<b>Database:</b>
<br>
+ MongoDB
+ IndexedDB
+ Localstorage
  
<b>UI:</b>
<br>
+ Lucid
+ Material UI
+ Tailwind
+ Radix

 <hr>

 ![alt text]( https://github.com/NEWSIX/FileFlowPro/blob/main/content/FileFlowPro.gif?raw=true)
 <br> 
- (v1.7) (12/3/2023)
