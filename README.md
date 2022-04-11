# ชื่อโครงงาน : ที่ใส่รหัสผ่านเพื่อปลดล็อกประตูนิรภัย
โครงงานนี้เป็นส่วนหนึ่งของรายวิชา 01204223 Practicum for Computer Engineering ภาคปลาย ปีการศึกษา 2564 หมู่ 11,12

## สมาชิกผู้จัดทำ:  
> :shipit:นิสิตภาควิชาวิศวกรรมคอมพิวเตอร์ คณะวิศวกรรมศาสตร์ มหาวิทยาลัยเกษตรศาสตร์ วิทยาเขตบางเขน:shipit:  

6310500261 นายชยพล สาสนรักกิจ<br>
6310500295 นายทิวัตถ์ ทรัพย์รัตนกุล<br>
6310503308 นายณัฐดนัย เติมบุญผาติ<br>
6310503499 นายภราดร วัชรเสมากุล<br>

## Table of contents    
  - [รายละเอียดไฟล์ Source Code](#รายละเอียดไฟล์-source-code)
  - [รายการไลบรารีและเฟรมเวิร์คที่ใช้](#รายการไลบรารีและเฟรมเวิร์คที่ใช้)
  - [รายการอุปกรณ์ฮาร์ดแวร์ที่ใช้](#รายการอุปกรณ์ฮาร์ดแวร์ที่ใช้)

## รายละเอียดโฟลเดอร์
### audio   
```

### only_keyboard 
```
โฟลเดอร์สำหรับเก็บข้อมูลในการเล่นเกมส์โดยรับinputจากแป้นพิมพ์
│   Tetris.py             : โปรแกรมสำหรับการเก็บข้อมูลและอัลกรอลิทึมในเกมส์   
│   menu.py               : โปรแกรม GUI สำหรับการแสดงผล หน้าตัวเลือกในการเล่นเกมส์
|   multi.py              : โปรแกรม GUI สำหรับการแสดงผล การเล่นเกมแบบ 2 คน
|   single.py             : โปรแกรม GUI สำหรับการแสดงผล การเล่นเกมแบบ 1 คน
|   How_to_play.py        : โปรแกรม GUI สำหรับการแสดงผล วิธีการเล่นเกมส์
```

### pic
```
|  556546.jpg             : รูปพื้นหลังในturtorail
|  menu button.png        : รูปพื้นหล้งปุ่ม
|  menu_button (1).png    : รูปพื้นหล้งปุ่ม
|  menu_button (2).png    : รูปพื้นหล้งปุ่ม
|  menu_button.png        : รูปพื้นหล้งปุ่ม
|  tetris-2.jpg           : รูปภาพพื้นหลังหน้าmenu
```

### tetris_upgrade 
```
โฟลเดอร์สำหรับเก็บข้อมูลในการเล่นเกมส์โดยรับinputจากบอร์ด
│   Tetris.py             : โปรแกรมสำหรับการเก็บข้อมูลและอัลกรอลิทึมในเกมส์   
│   menu.py               : โปรแกรม GUI สำหรับการแสดงผล หน้าตัวเลือกในการเล่นเกมส์
|   multi.py              : โปรแกรม GUI สำหรับการแสดงผล การเล่นเกมแบบ 2 คน
|   single.py             : โปรแกรม GUI สำหรับการแสดงผล การเล่นเกมแบบ 1 คน
|   tetris-2.jpg          : รูปภาพพื้นหลังหน้าmenu
|   How_to_play.py        : โปรแกรม GUI สำหรับการแสดงผล วิธีการเล่นเกมส์
```

### firmware
```
โฟลเดอร์สำหรับเก็บข้อมูลเฟิร์มแวร์
|   Makefile              : makefile
|   main.c                : ส่ง request ไปยัง Mcu
|   peri.c                : ไว้initial port และ analog read
|   peri.h                : เป็น header ของ peri.c
```

### Others  
```
README.md : ไฟล์ระบุชื่อกลุ่ม ชื่อโครงงาน รายชื่อผู้จัดทำ รายละเอียดไฟล์ รายการไลบรารี/
```

## รายการไลบรารีและเฟรมเวิร์คที่ใช้
### Hardware 
`usbconfig.h`

### Frontend 
`-`

### Backend 
`pygame` `random` `State` 

## รายการอุปกรณ์ฮาร์ดแวร์ที่ใช้
<ul>
  <li>Raspberry PI 1 ตัว</li>
  <li>Board NodeMCU - ATmega328p (Practicum Board v3.2 CPE. KU 2020-11) 2 ตัว</li>
  <li>Peripheral board (PRACTICUM PROTOBOARD CPE. KU) 2 บอร์ด</li>
  <li>สายแพร์ 2 เส้น</li>
  <li>Tag Switch(สวิตซ์กดติดปล่อยดับ) ขนาด 6 x 6 mm 8 ตัว</li>
  <li>เซนเซอร์แสง(LDR) 2 ตัว</li>
  <li>ตัวต้านทาน 10K 2 ตัว</li>
  </ul>
