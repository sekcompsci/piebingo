# piebingo
Bingo Game จะแบ่งส่วนของการทำงานเป็น 2 ส่วน คือ Server และ Client การทำงานของ Server จะทำหน้าที่รอรับผู้เล่น(Client) เชื่อมต่อเข้ามา โดยตั้งชื่อและส่งตัวเลขที่ตัวเองถืออยู่ในมือ เมื่อ Server ได้รับข้อมูลตัวเลขเสร็จจะเริ่มนับถอยหลัง 15 วินาที เพื่อรอผู้เล่นคนอื่นๆ ถ้าไม่มีใครเชื่อมต่อเข้ามาอีก Server จะทำการเริ่มสุ่มตัวเลขขึ้นมาทุกๆ 5 วินาที และฝั่งผู้เล่นจะแสดงตารางตัวเลขสุ่มที่ไม่ซ้ำกันขึ้นมา เมื่อผู้เล่นคนไหน Bingo ตัวเลขไม่ว่าจะเป็นแนวตั้ง แนวนอน หรือทแยงมุม จะเป็นผู้ชนะและทุกคนที่เล่นผู้จะเห็นชื่อของผู้ชนะปรากฏที่หน้าจอ

**วิธีการใช้งาน**

รัน server ทำงานก่อน client <br>
**APPID** คือ Application Name ที่สร้างไว้<br>
**KEY** และ **SECERT** คือ Application Key ที่ถูกสร้างภายใต้ Application Name

Server<br>
http://rawgit.com/anunpanya/piebingo/master/index.html#APPID:KEY:SECRET<br>
ในส่วน QR Code หากต้องการเปลี่ยน url ให้แกไขที่บรรทัด 69

Client<br>
http://rawgit.com/anunpanya/piebingo/master/client.html#APPID:KEY:SECRET
