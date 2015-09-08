# Building AngularJS Application course

**Course Information and Course Outline:**  
Please click to http://next.greatfriends.biz/training/course/GF235

Please installed the following software:

1. Microsoft Visual Studio Code (latest as possible)
-  Google Chrome
-  NodeJS
-  Git Source Control 

## 1. Microsoft Visual Studio Code
http://code.visualstudio.com

Free cross-platform modern code editor 
with built-in git and debugging support. 


## 2. Google Chrome

ใช้ Google Chrome หรือ Firefox เพื่อใช้รับ Clipboard จากเครื่องอาจารย์

หลักสูตรที่เกี่ยวกับเว็บ (ASP.NET, ASP.NET MVC, jQuery, Angular, TypeScript) 
ใช้ **Developer Tools** เพื่อตรวจสอบ ดีบั๊กโค้ดใน browser Chrome จะสะดวกที่สุด

อาจจะติดตั้ง Extension ของ Chrome เหล่านี้ไว้ด้วย
- JSON Viewer
- Postman

## 3. Node.js

Node.js is a JavaScript runtime platform.

http://www.nodejs.org

เมื่อติดตั้งเสร็จแล้วให้ทดสอบใน Command Prompt ดังนี้

**> npm -v**  
2.11.2

และทดสอบติดตั้ง Node App ดังนี้

**> npm install -g bower**  
**> npm install -g typescript**  
**> npm install -g tsd**

ซึ่งควรจะติดตั้งได้สำเร็จดี ไม่มี error ใดๆ


## 4. Git Source Control

`git` is the most popular distributed source control.

http://www.git-scm.com

ตัวติดตั้งเป็น Wizard จึงติดตั้งง่าย (ถ้าไม่ได้ระบุด้านล่างนี้ ก็ใช้ค่า default ได้) 
- หัวข้อ **Adjusting PATH environment**
ให้เลือก *Use Git from the Windows Command Prompt*
- หัวข้อ **Configuring the line ending conversion** ให้เลือก
*Checkout Windows-style, commit Unix-style line endings*
- หัวข้อ **Configuring the terminal emulator to use with Git Bash** ให้เลือก 
*Use Windows' default console window*
 
เมื่อติดตั้งเสร็จแล้วให้ทดสอบใน Command Prompt ดังนี้

  ```
  > git --version  
  git version 2.5.1.windows.1
  ```
  
เนื่องจากว่า bower ต้องการใช้ git ดังนั้น
การทดสอบจะใช้ bower ติดตั้ง component ดู เช่น

  ```
  > cd \
  > md test  
  > cd test  
  > bower install bootstrap  
  ```

ถ้าติดตั้งสำเร็จจะได้โฟลเดอร์ชื่อ *bower_components* 
และมีโฟลเดอร์ *bootstrap* อยู่ข้างใน

แต่ถ้าไม่สามารถติดตั้งได้ (เช่นติด proxy ของบริษัท)
ก็ไม่เป็นไร เราสามารถใช้ npm แทน bower ได้
 