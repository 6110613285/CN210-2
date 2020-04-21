# รายงานวิชา CN210
* --CCCCCC--------NN----N-----  2222222--------1111----------00000000
* CC-------CC------N-N---N-----22-----22------11---11---------0--------0
* C------------------N--N--N-----------2--------------11---------0--------0
* CC-------CC------N---N-N--------22----------------11---------0--------0
* --CCCCCC--------N----NN------22222222-----111111111-----00000000
## สรุปเนื้อหารายวิชา
วิชานี้จะเป็นการสอนเกี่ยวกับการทำงานของคำสั่งต่างๆภายใน mips โดยใน mips จะมีชุดคำสั่งอยู่ทั้งหมด 3 รูปแบบ คือ 
* 1.R-format

![image](http://4.bp.blogspot.com/-Ui0mt4h44s8/Up2nvk3iU3I/AAAAAAAAAPY/sF4haVYx6BE/s1600/1.png)

* 2.I-format

![image](http://4.bp.blogspot.com/-SrDyDKDbxJ8/Up2oHmwtNEI/AAAAAAAAAPg/9i686ypFdCg/s1600/3.png)

* 3.J-format

![image](http://1.bp.blogspot.com/-MqcOl_V2rSw/Up2okUK7aNI/AAAAAAAAAPo/R5iPs60F8Y0/s1600/2.png)

## Vonneuman กับ Harvard
* Vonneuman ข้อมูล(Data)และชุดคำสั่ง(Instruction)จะถูกเก็บบนหน่วยความจำเดียวกัน
* Harvard ข้อมูล(Data)และชุดคำสั่ง(Instruction)จะถูกเก็บคนละหน่วยความจำ

## ความแตกต่างระหว่าง RISC กับ CISC
* RISC ย่อมาจาก Reduced Instruction Set Computer โดย RISC เป็นคอมพิวเตอร์ที่มีชุดคำสั่งน้อยๆ และไม่ซับซ้อน
* CISC ย่อมาจาก Complex Instruction Set Computer โดย CISC เป็นคอมพิวเตอร์ที่มีความซับซ้อน
* ในการทำงานคอมพิวเตอร์แบบ RISC จะมีความเร็วมากกว่า CISC เนื่องจากแบบ RISC มีความซับซ้อนที่น้อยมากกว่า

![image](https://2.bp.blogspot.com/-PAHTUSBJA8s/Wzck5pNEhbI/AAAAAAAAAN4/NvbTkpo17dwrH6LM6XmKZEJtkYUINBxLQCLcBGAs/s1600/Capture.PNG)

การทำงานของคำสั่งต่างๆ แบบ single , multi cycle และ pipe lining

single cycle
* เป็นการทำวานแบบ 1 คำสั่งต่อ 1 cycle โดยที่ทุกคำสั่งจะใช้เวลาเท่ากันทั้งหมด

![image](https://camo.githubusercontent.com/647f042b60fb2e9bb9484b6bdb40f8d65f35e6ad/68747470733a2f2f7777772e636973652e75666c2e6564752f7e6d73737a2f436f6d704f72672f466967757265342e31312d4d4950536461746170617468522d6c6f642d6265712e676966)
multi cycle
* เป็นการทำงานที่ใช้เวลาไม่เท่ากัน โดยเวลาที่ใช้ขึ้นอยู่กับคำสั่ง

![image](https://camo.githubusercontent.com/3a759f503101d7359e3b9e88a79a64b022814d5a/68747470733a2f2f692e696d6775722e636f6d2f6d5758485770542e706e67)
pipe lining
* เป็นการลดระยะเวลาที่้ในการทำงานลงโดยเมื่อมีอุปกรณ์ที่ว่างก้จะนำคำสั่งต่อไปมาทำงานทันที

![image](http://2.bp.blogspot.com/-4YXOlZ30iCQ/UKTYR4Y4FLI/AAAAAAAAAGk/pCdSkaaazVA/s1600/02-What-is-pipelining-02.png)

## Homework
|CLIP|เนื้อหาในคลิป|
|-----|------|
|[CLIP1](https://youtu.be/VZFLH8Wq3IA)|ตัวอย่างในการทำงานของคำสั่ง add ใน mips โดยภายในคลิปจะพูดถึงคำสั่ง R-type ที่เก็บข้อมูล 32 bitว่าในคำสั่ง add มีการเก็บในรูปแบบของคำสั่ง R-type ยังไงบ้าง และแสดงการคำนวณคำสั่ง add
|[CLIP2](https://youtu.be/CYYIpdiYHF8)|ตัวอย่างการทำงานของระบบคอมพิวเตอร์ในภาษาขั้นสูง
|[CLIP3](https://youtu.be/N3aXtqCpFQU)|ความแตกต่างะหว่างการทำงานแบบ single cycle และ multi cycle|
|[CLIP4](https://youtu.be/8Pwj3uYp1AM)|ตัวอย่างการทำงานของคำสั่ง lw ในการทำงานแบบ multi cycle|
|[CLIP5](https://youtu.be/Ckm_JZbouUE)|การทำงานของคำสั่ง beq ในการทำงานแบบ multi cycle|
|[CLIP6](https://youtu.be/f7Kut2O65Ig)|วิธีในการทำงานของคำสั่ง r-type ใน multi cycle|
|[CLIP7](https://youtu.be/vvQ5upcfwJA)|การทำงานแบบ pipelining|
