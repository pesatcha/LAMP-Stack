# satrt_LAMP-Stack
 เมื่อเข้า root ได้แล้ว  
 # ติดตั้ง Apache  
 ใช้คำสั่ง yum install httpd  
 เมื่อติดตั้งเสร็จ ใช้คำสั่ง systemctl start httpd เป็นคำสั่งเริ่มต้นใช้งาน  
 systemctl enable httpd เป็นคำสั่งเปิดใช้งาน  
 systemctl status httpd คำสั่งในการเช็คว่าทำงานรึยัง  
 จากนั้น นำ ip เช็คที่หน้า webbrowser 
 # ติดตั้ง Mysql  
 ใช้คำสั่ง yum install mariadb-server  
  เมื่อติดตั้งเสร็จ ใช้คำสั่ง systemctl start mariadb เป็นคำสั่งเริ่มต้นใช้งาน  
  systemctl enable httpd เป็นคำสั่งเปิดใช้งาน  
  systemctl status httpd คำสั่งในการเช็คว่าทำงานรึยัง  
  mysql -u root -p คำสั่ง login เข้าไปในฐานข้อมูล "ครั้งแรกที่ล็อคอินเข้าจะไม่มี password"  
  คำสั่ง show databases;  เพื่อแสดงฐานข้อมูล หากต้องการออกให้ใช้คำสั่ง \q  
  mysql_sacure_installation คำสั่งติดตั้ง password ให้กับ root
  # ติดตั้ง PHP 
 ใช้คำสั่ง yum install php php-mysql* เพื่อเพิ่มแพคเกจเสริม 

 # เมื่อติดตั้งครบทั้ง 3 อย่างแล้ว ให้ทำให้ apache run php และ php connect databases
 ให้ restart server ใช้คำสั่ง systemctl restart httpd  
 how to test  ให้ค้นหา w3school php connect to mysql นำตัวอย่างโค้ดมาใส่ที่  
 cd /var/www/html/  
 สร้างไฟล์.php ใน vi เช่น vi ชื่อไฟล์.php เมื่อเข้าไปที่ vi แล้ว ให้ใส่โค้ด แล้วทดสอบด้วยการ เข้าไปที่ webbrowser ใส่เลข ip เครื่อง / ชื่อไฟล์.php
 # เว็บแหล่งหาคำสั่งข้อมูลเพิ่มเติม
 คำสั่ง root centos    
 http://www.doanytech.com/add-create-a-sudo-user-for-centos-8/    
 คำสั่ง vi  
 [https://secure.jvh.co.th/index.php/knowledgebase/36/Linux-Server-CentOS](https://secure.jvh.co.th/index.php/knowledgebase/36/Linux-Server-CentOS--%E0%B8%AB%E0%B8%94%E0%B9%83%E0%B8%8A-vi-%E0%B9%81%E0%B8%81%E0%B9%84%E0%B8%82%E0%B9%84%E0%B8%9F%E0%B8%A5%E0%B8%9A%E0%B8%99%E0%B8%A5%E0%B8%99%E0%B8%81%E0%B8%8B.html#:~:text=%E0%B8%9E%E0%B8%B4%E0%B8%A1%E0%B8%9E%E0%B9%8C%20%3Awq%20%E0%B9%80%E0%B8%9E%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87%E0%B8%9A%E0%B8%B1%E0%B8%99%E0%B8%97%E0%B8%B6%E0%B8%81,%E0%B9%80%E0%B8%9E%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%94%E0%B8%B9%E0%B9%84%E0%B8%9F%E0%B8%A5%E0%B9%8C%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B9%81%E0%B8%81%E0%B9%89%E0%B9%84%E0%B8%82)  
สอนติดตั้ง LAMP Stack  
https://www.youtube.com/watch?v=cd4gFDQQMDE  
Linux commands VI  
https://medium.com/@pratya.yeekhaday/linux-vi-command-69bfd522fff
 
  
