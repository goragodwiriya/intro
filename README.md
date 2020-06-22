# Intro Page

ดาวน์โหลดสคริปต์ไปวางไว้ที่ root ของเว็บไซต์ เช่น public_html ใช้งานได้ทันที (เว็บต้องไม่มี index.html อยู่ก่อน)

ในกรณีที่ใช้ GCMS จะต้องเพิ่มบรรทัดนี้ลงในไฟล์ .htaccess ด้วย
```
<IfModule mod_rewrite.c>
	...

  DirectoryIndex index.html index.php

  ...
</IfModule>
```
หมายเหตุ สคริปต์นี้รองรับบราวเซอร์รุ่นใหม่ๆเท่านั้น เนื่องจากมีการใช้ความสามารถของ CSS3 ล้วนๆโดยไม่ใช้ Javascript

ตัวอย่าง https://goragod.github.io/intro/index.html

เครดิตรูปภาพจากเพจ Goya Pannarai
