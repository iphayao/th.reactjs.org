---
id: hello-world
title: Hello World
permalink: docs/hello-world.html
prev: cdn-links.html
next: introducing-jsx.html
---

ตัวอย่าง React แบบน้อยที่สุด จะเป็นแบบนี้:

```js
ReactDOM.render(
  <h1>Hello, World!</h1>,
  document.getElementById('root')
);
```

มันแสดงหัวข้อว่า "Hello, World!" บนหน้านั้น

[ทดลองบน Codepen](codepen://hello-world)

คลิกลิ้งค์ข้างบนเพื่อเปิดตัวแก้ไขออนไลน์ อย่าลังลังที่จะทำการเปลี่ยนแปลงบางอย่าง และดูว่ามันมีผลอย่างไร หน้าส่วนใหญ่ในคู่มือนี้จะมีตัวอย่างที่สามารถแก้ไขได้เหมือนแบบนี้


## วิธีอ่านคู่มือนี้ {#how-to-read-this-guide}

ในคู่มือนี้ เราจะตรวจสอบส่วนต่าง ๆ ของแอป React กัน เช่น ส่วนประกอบ (Element) และ คอมโพเนนท์ (Component) เมื่อคุณเชี่ยวชาญขึ้นแล้ว คุณสามารถสร้างแอปที่ซับซ้อนจากชิ้นส่วนเล็ก ๆ ที่นำมาใช้ซ้ำได้

>เกร็ดความรู้
>
>คู่มือนี้ออกแบบมาสำหรับผู้ที่ต้องการ **แนวคิดการเรียนรู้ทีละขั้นตอน** ถ้าคุณชอบเรียนรู้ด้วยการลงมือทำ ลองดู [แบบฝึกหัดภาคปฏิบัติ](/tutorial/tutorial.html) คุณอาจพบว่าคู่มือนี้และแบบฝึกหัดนั้นสามารถเติมเต็มซึ่งกันและกันได้

นี่คือบทแรกในการแนะนำเกี่ยวกับแนวคิดหลักของ React แบบทีละขั้นตอน คุณสามารถค้นหารายการของบททั้งหมดได้ในแถบนำทางด้านข้าง หากคุณกำลังอ่านสิ่งนี้จากอุปกรณ์มือถือ คุณสามารถเข้าถึงแถบนำทางโดยการกดปุ่มที่มุมล่างขวาของหน้าจอ

ทุกบทในคู่มือนี้จะเสริมสร้างความรู้ที่ได้จากบทอื่น ๆ ก่อนหน้านี้ **คุณสามารถเรียนรู้ React ส่วนใหญ่ได้ โดยอ่านบทแนะนำ "แนวคิดหลัก" ตามลำดับที่ปรากฏในแถบด้านข้าง** ตัวอย่างเช่น [“แนะนำ JSX”](/docs/introducing-jsx.html) เป็นบทต่อไปหลังจากบทนี้

## สมมติฐานระดับความรู้ {#knowledge-level-assumptions}

React เป็น JavaScript ไลบราลี่, ดังนั้นเราจะสมมติว่าคุณมีความเข้าใจพื้นฐานเกี่ยวกับภาษา JavaScript **ถ้าคุณรู้สึกว่าไม่มั่นใจมากเท่าไหร่, เราแนะนำให้ไปอ่าน [แบบฝึกหัด JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript) ตัวนี้ก่อน เพื่อวัดระดับความรู้ของคุณ** และให้คุณทำตามคู่มือนี้ได้โดยไม่หลงทาง คุณอาจใช้เวลาราว ๆ 30 นาทีถึงหนึ่งชั่วโมง แต่จะช่วยให้คุณไม่ต้องรู้สึกว่าเหมือนกำลังเรียนรู้ทั้ง React และ JavaScript ในเวลาเดียวกัน

>หมายเหตุ
>
>ในคู่มือนี้จะใช้ไวยากรณ์ JavaScript ที่ใหม่กว่าบางครั้ง หากคุณไม่ได้ทำงานกับ JavaScript เลยในช่วงไม่กี่ปีที่ผ่านมานี้ [เกร็ดความรู้ 3 หัวข้อนี้](https://gist.github.com/gaearon/683e676101005de0add59e8bb345340c) ก็พอจะช่วยคุณได้มากอยู่


## มาเริ่มกันเลย! {#lets-get-started}

เลื่อนลงไปเรื่อย ๆ และคุณจะพบลิงค์ไปยัง [บทต่อไปของคู่มือนี้](/docs/introducing-jsx.html) อยู่ก่อนส่วนท้ายของเว็บไซต์


