# satrt_LAMP-Stack
http://www.doanytech.com/add-create-a-sudo-user-for-centos-8/ คำสั่งเข้า root centos  
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

