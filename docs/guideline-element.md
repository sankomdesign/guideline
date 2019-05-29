Element
==========

Element. คือส่วนที่ประกอบขึ้นเป็น User interface ผู้ใช้งานมีความคุ้นเคยกับ User interface จากประสบการณ์ที่ผ่านมาของพวกเขา โปรดเลือกใช้งานด้วยความระมัดระวัง โดยคำนึงถึงความสม่ำเสมอและสามารถคาดเดาได้ เพื่อช่วยให้เป้าหมายของผู้ใช้งานนั้นเสร็จแบบมีประสิทธิภาพและได้รับความพึงพอใจ

##### 1. Input controls
- Button, Data field, List-Box

##### 2. Selection controls
- Toggles, Radio-button, Checkbox, Dropdown list
  
##### 3. Navigational components
- Breadcrumb, Slider, Search, Pagination, Tag, Navigation Bar

##### 4. Informational components
- Tool-tip, icon, Progress bar, Notification, Message Box, Modal

##### 5. Container
- Accordion

## Input Box
ใช้สำหรับรับข้อมูลจากผู้ใช้งาน เพื่อนำข้อมูลไปเก็บหรือประมวลผลต่อ ใช้สำหรับรับข้อมูลเป็น Text หรือ ตัวเลข

#### Anatomy
![Test](images/text-box/Text-Box-Anatomy.jpg)
1. Label
2. Leading Icon (optional)
3. Helper Text (optional)
4. Tailing Icon (optional)
5. Container 

#### State
![Test](images/text-box/Text-Box-State.jpg)

#### Speces
![Test](images/text-box/Text-Box-Spec.jpg)

#### Required text indicator
ถ้าส่วนใหญ่จำเป็นต้องกรอก ให้ระบุช่องกรอกเป็น (Optional) แทน แล้วเอา * ออกทั้งหมด
![Test](images/text-box/Text-Box-Indicator.jpg)


## Button

### ใช้ปุ่มอย่างไร ให้ผู้ใช้งานทำงานได้อย่างถูกต้อง
ก่อนอื่นให้แบ่งปุ่มออกเป็น 3 ประเภท คือ

1. Positive Button - มีการเปลี่ยนแปลง,ส่ง,เพิ่มข้อมูล เป็นต้น
2. Netural Button - ไม่มีการเปลี่ยนแปลง,กลับสู่หน้าที่ผู้ใช้งานเข้ามา เป็นต้น
3. Negative Button - ลบข้อมูล,รีเซ็ต เป็นต้น

เมื่อเราเข้าใจปุ่มแต่ละประเภทแล้ว ให้เราดูตามรูปแบบ Flow ของโปรแกรมดังนี้

### Positive Flow
การทำงานของ Flow นี้จะเน้นไปในทางแก้ไขข้อมูล เพิ่มเติมข้อมูล ทำให้เราต้องเพิ่ม Contrast ให้กับปุ่ม นอกจากนั้นให้เลือกใช้สีที่ดูแล้วเห็นว่าปุ่มนี้เป็น Positive

![Positive-Flow](images/button/Positive-Flow.jpg)

### Negative Flow
การทำงานของ Flow นี้จะเน้นไปในทางลบ,ทำลายข้อมูล ล้างข้อมูล ทำให้เราต้องเพิ่ม Contrast ให้กับปุ่ม นอกจากนั้นให้เลือกใช้สีที่ดูแล้วเห็นว่าปุ่มนี้เป็น Negative

![Negative-Flow](images/button/Negative-Flow.jpg)

### Why Cancel Button should have lowest contrast
เนื่องจากปุ่ม Cancel ไม่ใช่ปุ่มที่ไว้สำหรับทำ Action เป็นเพียงปุ่มที่นำผู้ใช้งานกลับไปยังหน้าจอที่เขาเข้ามา การลด Contrast ให้ได้มากที่สุด จะทำให้ผู้ใช้งานรู้สึกปลอดภัยในการกดมากขึ้น แต่ไม่ควรใช้ Contrast ต่ำมากจนเหมือนปุ่มนั้นถูก Disable อยู่

![Cancel-Button](images/button/Cancel-Button.jpg)

### Too many action
ในกรณีที่มีทางเลือกให้กับผู้ใช้ทำงานกับระบบมากกว่า 2 อย่างขึ้นไปทำให้เราต้องตัดสินใจว่าจุดประสงค์ของโปรแกรมนั้นต้องการให้ผู้ใช้ทำอะไรเป็นหลัก ปุ่มนั้นจะเป็นปุ่มที่มี Contrast หนักที่สุด ปุ่มที่เหลือจะต้องลด Contrast ลงมา
และจะมีปุ่ม "กากบาท" เกิดขึ้นมาแทนปุ่ม Cancel 

![Cancel-Button](images/button/3-Button.jpg)

## Selection Control

#### Checkbox

- เมื่อต้องการเลือกหนึ่งหรือหลายๆสิ่งจากหลายการ
- เมื่อมีตัวเลือกย่อยในหัวเรื่อง
- เมื่อต้องการเปิด-ปิดตัวเลือก (Desktop)

![Test](images/input-control/Checkbox-Case.jpg)
![Test](images/input-control/Select-all-Case.jpg)


#### Radio

- เลือกเพียงหนึ่งอย่างจากสิ่งที่มีทั้งหมด
- เห็นตัวเลือกทั้งหมดพร้อมๆกัน

![Test](images/input-control/Radio-Case.jpg)


#### Switch
- เมื่อต้องการเปิด-ปิดสิ่งใดๆ (Tablet, Mobile)
- เมื่อต้องการเปิด-ปิดสิ่งใดๆ ซึ่งมีผลทันที

![Test](images/input-control/Switch-Case.jpg)

#### State

![Test](images/input-control/State.jpg)


#### Speces

![Test](images/input-control/Specs.jpg)

## Modal
ใช้เพื่อเป็นตัวคั่นจังหวะ เพื่อให้ผู้ใช้งานได้ทำการทบทวนอีกรอบก่อนจะยืนยัน หรือเพื่อให้ข้อมูลกับผู้ใช้งาน

1. Confirmation Modal - ใช้เพื่อยืนยันการกระทำบางอย่างของผู้ใช้งาน เช่นต้องการเพิ่มข้อมูล ต้องการยืนยันที่จะลบข้อมูล เป็นต้น
2. Information Modal - ใช้เพื่อเพียงให้ข้อมูล หรือ Response จากระบบ เช่น Response บอกผู้ใช้ว่าทำการบันทึกเรียบร้อย เป็นต้น

### Anatomy
![Modal](images/modal/Modal-Anatomy.jpg)
1. Container
2. Title
3. Supporting Text
4. Buttons

### Priority of Modal
การใช้งาน Dialogs แบ่งการใช้งานตามความ Priority คือ
| Priority    | Component            | User Action         |
| ----------- | -------------------- | ------------------- |
| High        | Confirmation Modal   | กดปุ่มตัดสินใจที่จะเลือกทำ หรือ กระทำบางอย่างกับระบบเพื่อให้งานเสร็จสมบูรณ์|
| Low         | Information Modal    | กดปุ่มเพื่อรับทราบ หรือ หายไปอัตโนมัติเมื่อหมดเวลา |

![Modal](images/modal/Modal-Case.jpg)

### Make sense your Modal

![Modal](images/modal/Make-Sense-Your-Modal.jpg)
ระวังการใช้งานปุ่มดังตัวอย่างในรูป เนื่องจากทั้งปุ่ม OK และ ปุ่ม Cancel ให้ Response เหมือนกันคือกล่อง Dialog หายไป ถึงแม้จะลดเหลือปุ่มเดียวก็พอจะดู Make sense แต่ก็ไม่ใช่ปุ่มที่ไว้ทำ Action อยู่ดี แก้ปัญหาโดยการใช้ปุ่ม "กากบาท" แทน

## List of items
การแสดงรายการต่างๆเช่น รายการเอกสาร, รายการของผู้ใช้งาน นอกจากการแสดงผลแบบตารางแล้ว ยังสามารถแสดงรายการด้วยการ์ดได้ โดยปรับหัวตารางให้ไปอยู่คู่กับชุดข้อมูล และกลุ่มของข้อมูลที่มีความสัมพันธ์กันก็สามารถอยู่ด้วยกันโดยอาศัยหัวตาราง (label) เดียวกัน

![Test](images/element-list/list01.png)