# 💻 การติดตั้ง: IDE และ Compiler สำหรับ C/C++

บทนี้จะสอนวิธีติดตั้งโปรแกรมเขียนโค้ดและคอมไพเลอร์สำหรับภาษา C/C++  
แนะนำ 3 โปรแกรมยอดนิยมที่ใช้กันทั่วไปสำหรับนักเรียนและผู้เริ่มต้น

---

## 1. Visual Studio Code (VS Code)

### เหมาะสำหรับ
- ผู้ที่อยากได้เครื่องมือทันสมัย  
- ใช้งานได้ทั้ง Windows, Mac, Linux  
- พร้อมตั้งค่าเองเพื่อเพิ่มความยืดหยุ่น

### วิธีติดตั้ง

1. ดาวน์โหลด VS Code:  
   [https://code.visualstudio.com](https://code.visualstudio.com)

2. ติดตั้งโปรแกรมตามขั้นตอน

3. ติดตั้ง Extension C/C++ และ Code Runner:  
   - เปิด Visual Studio Code  
   - กด `Ctrl+Shift+X` (เปิด Extensions)  
   - ค้นหา `C/C++` และ `Code Runner` แล้วติดตั้ง

4. (Windows) ติดตั้ง MinGW Compiler:  
   - ดาวน์โหลด MinGW-w64: [https://www.mingw-w64.org](https://www.mingw-w64.org)  
   - ตั้งค่า PATH ให้คอมไพเลอร์รู้จัก  
   - ทดสอบคำสั่ง:  
     ```bash
     gcc --version
     ```

5. ทดสอบเขียนโปรแกรมง่าย ๆ เช่น Hello World

---

## 2. Dev C++ (โปรแกรมที่ครูบอยสอนในห้องเรียนนี่เอง)

### เหมาะสำหรับ
- ผู้เริ่มต้นที่ใช้ Windows  
- อยากได้ IDE พร้อมคอมไพเลอร์ในตัว ใช้งานง่าย

### วิธีติดตั้ง

1. ดาวน์โหลด Dev C++ ล่าสุด:  
   [https://sourceforge.net/projects/orwelldevcpp/](https://sourceforge.net/projects/orwelldevcpp/)

2. ติดตั้งโปรแกรมตามขั้นตอน

3. เปิดโปรแกรม สร้างโปรเจกต์ใหม่ ทดสอบเขียนโค้ดและรัน

---

## 3. Code::Blocks

### เหมาะสำหรับ
- ผู้ใช้ Windows ที่อยากได้ IDE ครบเครื่อง พร้อมคอมไพเลอร์ในตัว  
- เน้นเรียนรู้และพัฒนาโปรแกรม C/C++

### วิธีติดตั้ง

1. ดาวน์โหลด Code::Blocks แบบรวม MinGW:  
   [https://www.codeblocks.org/downloads/binaries/](https://www.codeblocks.org/downloads/binaries/)

2. เลือกไฟล์ติดตั้งที่ชื่อประมาณ `codeblocks-XX.XXmingw-setup.exe`

3. ติดตั้งโปรแกรมตามขั้นตอน

4. เปิดโปรแกรม สร้างโปรเจกต์ใหม่ ทดสอบเขียนโค้ดและรัน

## 🎥 วิดีโอแนะนำ (ถ้ามี)

- [วิธีติดตั้ง MinGW](https://www.youtube.com/watch?v=oC69vlWofJQ)  

---