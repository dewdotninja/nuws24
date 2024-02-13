## สัมมนาเชิงปฏิบัติการเรื่อง "ไอโอทีสำหรับระบบควบคุมและการเรียนรู้ของเครื่อง"
## "IoT for Control Systems and Machine Learning" Seminar & Workshop

<hr>
<p />  
  
![nuws24_header](https://github.com/dewdotninja/nuws24/assets/37393409/b0b329c4-789a-466b-9406-483445eeb6e3)

<img align=left src="https://i.imgur.com/CzEUVpd.jpg" width=250 /> 
<ul>
  <li /><b>ชื่อเรื่อง :</b> ไอโอทีสำหรับระบบควบคุมและการเรียนรู้ของเครื่อง 
  <li /><b>Topic :</b> IoT for Control Systems and Machine Learning   
  <li /><b>วิทยากร :</b> ดร.วโรดม ตู้จินดา <img align=right src="https://drive.google.com/uc?id=1PnXkwtC1bGNlplGY8DqbwMH6gCkhRp8Q" width=80 />
  <li /><b>สถานที่ :</b> ภาควิชาฟิสิกส์ คณะวิทยาศาสตร์ มหาวิทยาลัยนเรศวร
  <li /><b>วัน-เวลา :</b> เสาร์ 17 กุมภาพันธ์ 2567
</ul>
<hr>

ในปัจจุบันไอโอที (IoT: Internet of Things) เป็นนวัตกรรมที่ได้รับความนิยมเป็นอย่างมาก แม้ว่าไอโอทีจะมีอัตราการรับส่งข้อมูลต่ำ แต่มีข้อดีคือสามารถใช้ประโยชน์จากการแพร่กระจายของอินเทอร์เน็ตที่ครอบคลุมแทบทุกพื้นที่บนโลก ในประเทศไทยที่ประชากรจำนวนมากประกอบอาชีพด้านเกษตรกรรม ผู้พัฒนาไอโอทีส่วนใหญ่จึงมุ่งเน้นไปทางด้านอุปกรณ์ที่ช่วยอำนวยความสะดวกหรือเพิ่มผลผลิตทางการเกษตร ส่วนการประยุกต์ใช้งานอื่นก็เช่นการประหยัดพลังงานในอาคาร ระบบรักษาความปลอดภัยในบ้านเรือน สำหรับการใช้งานด้านอุตสาหรรมก็พบเห็นได้บ้างแต่ยังมีน้อยอยู่ ในขณะที่งานไอโอทีในต่างประเทศเกี่ยวข้องกับหุ่นยนต์ ยานยนต์ขับเคลื่อนอัตโนมัติ ซึ่งจะเห็นว่าเป็นโจทย์ที่ยากและท้าทาย

โดยหลักการแล้วไอโอทีเป็นเพียงการสื่อสารข้อมูลที่ช่วยให้สามารถควบคุมและแสดงผลผ่านอินเทอร์เน็ตได้เท่านั้น การใช้ประโยชน์ในงานที่มีความซับซ้อนมากขึ้นคือต้องอาศัยการพัฒนาโปรแกรมเพื่อให้อุปกรณ์มีความชาญฉลาด สามารถในการทำงานนั้นได้อย่างมีประสิทธิภาพ และเป็นมิตรกับผู้ใช้งาน ดังนั้นในรายวิชาที่ผู้สอนรับผิดชอบที่เกี่ยวข้องกับไอโอที จะเน้นการออกแบบระบบฝังตัวตั้งแต่ฮาร์ดแวร์คือตัวประมวลผล เซนเซอร์ วงจรเชื่อมต่อ การปรับแต่งสัญญาณ การกรองสัญญาณรบกวน จนถึงด้านซอฟต์แวร์ การอิมพลิเมนต์อัลกอริทึมที่ทำให้อุปกรณ์นั้นเป็นได้มากกว่าการแสดงผลและสั่งงานอย่างง่าย ตัวอย่างเช่น ตัวควบคุมป้อนกลับประเภทต่างๆ ตัวควบคุมแขนกล/หุ่นยนต์ วิเคราะห์สัญญาณโดย FFT 

ในกรณีที่ซอฟต์แวร์ที่สร้างความชาญฉลาดมีความซับซ้อนและต้องการทรัพยากรมากกว่าที่มีในระบบฝังตัว การใช้ไอโอทีร่วมกับการออกแบบชั้นของซอฟต์แวร์ที่เหมาะสมช่วยให้สามารถอิมพลิเมนต์ส่วนชั้นบนของซอฟต์แวร์ภายนอกระบบฝังตัวได้ ดังตัวอย่างการจำลองระบบแขนกลและหุ่นยนต์ในภาคบ่ายของสัมมนานี้

ในการสัมมนาเชิงปฏิบัติการครั้งนี้จะคัดเลือกบางส่วนที่สำคัญเพื่อความเหมาะสมกับช่วงเวลา 1 วัน โดยมุ่งเน้นที่ตัวควบคุมไอโอทีสำหรับงานควบคุมกระบวนการ และการควบคุมการเคลื่อนที่ ในช่วงท้ายจะเข้าสู่พื้นฐานของการเรียนรู้เสริมกำลัง (reinforcement learning) คือการอิมพลิเมนต์สมการเบลแมน (Bellman equattion) ช่วยแก้ปัญหาการวนซ้ำมูลค่า (value iteration) สำหรับวางแผนเส้นทางเดินหุ่นยนต์เคลื่อนที่ ซึ่งเป็นเนื้อหาใหม่ที่จะนำเสนอในสัมมนานี้เป็นครั้งแรก

<hr>

#### กำหนดการ

9 AM - 12 PM

<ul>
<li />ติดตั้งซอฟต์แวร์ สาธิตการใช้ Jupyter notebook และ Thonny
<li />วงจรเชื่อมต่อกับ MCU และการปรับแต่งสัญญาณ 
<li />พื้นฐานของระบบควบคุม (เน้นตัวควบคุม PID)
<li />การอิมพลิเมนต์ระบบควบคุมเชิงเส้น
<li />การจำลองระบบฝังตัวบน Wokwi
<li />การพัฒนาไอโอทีบน NETPIE 2020
<li />การแสดงผลและควบคุมบน NETPIE 2020 dashboard
<li />เขียนโปรแกรมไมโครไพทอนเพื่อควบคุมอัตราการไหลของถังน้ำ 3 ระดับ 
</ul>

1 - 4 PM

<ul>
<li />การใช้งาน paho-mqtt บน Jupyter notebook เพื่อนำข้อมูลจากระบบฝังตัวมาแสดงผลในรูปแบบที่ต้องการ
<li />การอิมพลิเมนต์ตัวควบคุมไม่เป็นเชิงเส้นสำหรับแขนกล 2 ก้านต่อ (2-link manipulator)
<li />การจำลองจลนศาสตร์หุ่นยนต์ (robot kinematics)
<li />ตัวควบคุมสำหรับหุ่นยนต์เคลื่อนที่ (mobile robot)
<li />การวางแผนเส้นทางเดินโดยอัลกอริทึมวนซ้ำมุูลค่า (value iteration)
<li />สรุปการสัมมนา
</ul>

<hr>

### อุปกรณ์ที่ใช้ในการอบรม

<ul>
  <li />เครื่องคอมพิวเตอร์ระบบปฏิบัติการ Windows, Mac-OSX หรือ Linux (ซอฟต์แวร์ที่ใช้สามารถใช้งานฟรีทั้งหมด)
  <li />สัญญาณ WiFi เพื่อเชื่อมต่ออินเทอร์เน็ต (อาจใช้การสร้าง hotspot จากมือถือของผู้เรียนได้)
</ul>

### เอกสารประกอบ

สไลด์และไฟล์โปรแกรมทั้งหมดรวบรวมไว้ใน Github repository นี้

การสัมมนานี้สอดคล้องกับเนื้อหาในหนังสือ "การโปรแกรมไพทอนสำหรับงานควบคุมและฝังตัว" ที่สามารถดาวน์โหลดได้ฟรีทั้งเล่มจากลิงก์ด้านล่างนี้

https://github.com/dewdotninja/py4conemb 
