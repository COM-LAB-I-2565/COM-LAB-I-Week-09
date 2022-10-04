# Week-09
#  การทดลองที่ 1 การใช้งาน Repository เบื้องต้น #

## วัตถุประสงค์
1.	เพื่อให้ผู้เรียนรู้และเข้าใจแนวคิดในการใช้ Repository 
2.	เพื่อให้ผู้เรียนสามารถใช้ Repository (Github) เบื้องต้นได้

## ทฤษฎีก่อนการทดลอง

__Git__
Git  เป็นระบบควบคุมเวอร์ชั่น (Version control systems) เป็นเครื่องมือที่ใช้บริหารจัดการการเปลี่ยนแปลงของไฟล์ต่าง ๆ ใน project การบันทึกการแก้ไขไฟล์แต่ละครั้งจะเรียกว่ารุ่น (revision) ซึ่งแต่ละรุ่นของการเปลี่ยนแปลงจะถูกกำกับด้วยการประทับเวลา (timestamp) และบุคคลที่ทำการเปลี่ยนแปลง ดังนั้น หากเกิดความผิดพลาดหรือเสียหายจากการแก้ไข เราก็จะสามารถย้อนเวลากลับไปยังการแก้ไขครั้งก่อนๆ ที่สมบูรณ์ได้ตามต้องการ ถือได้ว่าระบบควบคุมเวอร์ชั่นเป็นระบบพื้นฐานที่นิยมใช้ในการบริการจัดการ source code ของโปรแกรม ซึ่งจริง ๆ แล้ว เราสามารถใช้ระบบควบคุมเวอร์ชั่นกับไฟล์ชนิดใดๆ หรืองานชนิดใดๆ ก็ได้ ไม่เฉพาะ source code ของโปรแกรมเท่านั้น  ในปัจจุบัน มีระบบควบคุมเวอร์ชั่นให้เลือกใช้หลากหลาย ทั้งเป็นแบบฟรีและมีค่าใช้จ่าย (เช่น  Git, Mercurial, Subversion) โดย Git จะได้รับความนิยมมากกว่าชนิดอื่น ๆ  การทำงานของ Git นั้นจะมีพื้นที่เก็บไฟล์ ซึ่งเรียกว่า  ‘repositories’ ซึ่งเราสามารถติดตั้งบริการ git บน server ใดๆ ก็ได้ แต่ server บริการ git ที่ได้รับความนิยมในปัจจุบันได้แก่ Github, Gitlab, Bitbucket เป็นต้น ข้อดีของการใช้ server รวมก็คือ สามารถแบ่งปันและร่วมมือ ช่วยเหลือกันในแก้ไขโปรแกรมได้จากทุกคนทั่วโลก ลักษณะเฉพาะอย่างหนึ่งของ Git ก็คือ ใน folder ที่ชื่อ .git บนคอมพิวเตอร์ของเราจะเก็บทุกสิ่งที่เก็บบน server จึงมั่นใจได้ว่า เราสามารถทำงานกับระบบควบคุมเวอร์ชันได้ทั้งแบบออนไลน์และออฟไลน์ และหากเกิดกรณีที่ repository บน server เสียหาย เราก็สามารถนำทุกอย่างที่เก็บบนเครื่องกลับขึ้นไปเก็บบน server ได้

__Github__
เดิมที Github เป็นบริษัทหนึ่ง ที่ให้บริการ Git repository บนพื้นฐานของเว็บ (web-based Git repository hosting)  แต่ปัจจุบันถูกซื้อกิจการโดยบริษัทไมโครซอฟท์ โดย Github จะให้พื้นที่เราสร้าง repository สำหรับโปรเจค ให้บริการฟังก์ชันการทำงานพื้นฐานของระบบ git เช่น การ branches, merges, และ commits อีกทั้งยังให้พื้นที่สำหรับแจ้งข้อผิดพลาด บัก หรือความต้องการเพิ่มเติม features ต่างๆ ตลอดจนมีความสามารถในการเขียนคำอธิบายแบบ wiki ใน repository นั้น ๆ ด้วย  Github เป็นบริษัทที่มีมูลค่าประมาณ 2 พันล้าน USD, มีผู้ใช้ประมาณ 20 ล้านคน  มี repositories ประมาณ 40 ล้าน  และในจำนวนเหล่านั้น มีโปรเจคที่สำคัญมากรวมอยู่ด้วย เช่น kernel ของ Linux , source code ของ dotnet framework จากไมโครซอฟท์  และอื่นๆ   ทำให้มีความมั่นใจในระดับหนึ่งว่าถ้า Github เกิดล่มขึ้นมา ก็จะมีเพื่อนร่วมชะตากรรมอีกไม่น้อย

## ขั้นตอนการทดลอง
### 1. เริ่มใช้งาน Github (คลิก)
