
# สร้างเนื้อหาเอกสาร และรูปภาพด้วย Copilot กับ Microsoft Word

> **หมายเหตุ**: คุณควรมี [บัญชี Microsoft Account](https://signup.live.com) แบบส่วนตัว (เช่น outlook.com) และเข้าสู่ระบบด้วยบัญชีนี้บนคอมพิวเตอร์ของคุณ หากคุณมีทั้งบัญชีที่ใช้งานในที่ทำงานและบัญชีส่วนตัว โปรดเลือกบัญชี *ส่วนตัว* ในการตั้งค่าบัญชีด้านบนซ้ายของ Microsoft Edge


เพื่อเริ่มต้นการฝึกใช้ Generative AI เราจะใช้ **Microsoft Copilot ใน Edge** เพื่อวิเคราะห์เอกสารที่มีอยู่และสรุปข้อมูลเชิงลึกจากเอกสาร

---

## 📝 **ขั้นตอนที่ 1: เปิดเอกสารใน Microsoft Edge**

1. ใน **Microsoft Edge** ไปที่ [OneDrive](https://onedrive.live.com) (`https://onedrive.live.com`) และลงชื่อเข้าใช้ด้วยบัญชี Microsoft ส่วนตัวของคุณ จากนั้นปิดข้อความต้อนรับหรือข้อเสนอที่ปรากฏขึ้น

2. เปิดเอกสาร [Business Idea.docx](https://github.com/MicrosoftLearning/mslearn-copilot/raw/main/Allfiles/Business%20Idea.docx) ในแท็บเบราว์เซอร์ใหม่ (`https://github.com/MicrosoftLearning/mslearn-copilot/raw/main/Allfiles/Business%20Idea.docx`)  

   - เมื่อเอกสารเปิดขึ้นใน Edge ให้เลือกตัวเลือก **Edit a copy** เพื่อคัดลอกเอกสารไปยัง OneDrive  

   - เอกสารจะเปิดใน **Microsoft Word Online** โดยอัตโนมัติ

> 💡 **เคล็ดลับ**: หากไม่พบตัวเลือก **Edit a copy** ให้ดาวน์โหลดเอกสารลงในคอมพิวเตอร์ จากนั้นอัปโหลดไฟล์ **Business Idea.docx** ไปยัง OneDrive โดยใช้ปุ่ม **+ Add new**

---

## 📝 **ขั้นตอนที่ 2: ดูเนื้อหาเอกสาร**

- เปิดดูเนื้อหาในเอกสาร **Business Idea** ซึ่งอธิบายไอเดียธุรกิจเกี่ยวกับบริการทำความสะอาดในนิวยอร์ก

---

## 📝 **ขั้นตอนที่ 3: เปิด Copilot ใน Edge**

1. คลิกไอคอน **Copilot** บนแถบเครื่องมือ Edge เพื่อเปิด **Copilot Pane** ดังภาพ:  

   ![Screenshot of the Copilot pane in Microsoft Edge.](./Media/edge-copilot.png)

2. ในช่องแชทที่ด้านล่างของ **Copilot Pane** ให้ป้อนพรอมต์นี้:

   ```prompt
   Summarize this document into 5 key points, and suggest next steps.
   ```
   ภาษาไทย
   ```prompt
    สรุปเนื้อหาสำคัญในเอกสารนี้เป็น 5 ข้อ และแนะนำขั้นตอนถัดไปว่าควรทำอะไรต่อ
    ```

3.	หากมีการแสดงหน้าต่างแจ้งเตือน ให้กดปุ่มยืนยัน เพื่ออนุญาตให้ Copilot เข้าถึงข้อมูลผ่านหน้าเว็บ
4.	ตรวจสอบคำตอบจาก Copilot ซึ่งจะสรุปประเด็นสำคัญ 5 ข้อจากเอกสารและแนะนำขั้นตอนถัดไป

> ⚠️ หมายเหตุ: คำตอบที่ได้อาจแตกต่างกันไป

5.	หากมีคำถามเพิ่มเติม ให้ลองป้อนพรอมต์ต่อไปนี้:

    ```prompt
    How do I go about setting up a business in New York?
    ```
    ภาษาไทย
    ```prompt
    ฉันควรทำอย่างไรเพื่อเริ่มต้นธุรกิจในนิวยอร์ก
    ```

6. ตรวจสอบคำตอบ ซึ่งควรประกอบไปด้วยคำแนะนำและลิงก์ไปยังแหล่งข้อมูลเพิ่มเติมสำหรับการเริ่มต้นธุรกิจในนิวยอร์ก

> 🚨 คำเตือน: คำตอบจาก AI อ้างอิงจากข้อมูลสาธารณะบนอินเทอร์เน็ต อาจไม่ถูกต้อง 100% และไม่สามารถทดแทนคำแนะนำจากผู้เชี่ยวชาญได้

## 📝 **ขั้นตอนที่ 4: ใช้ Copilot เพื่อสร้างแผนธุรกิจ**

1. ในเอกสาร **Business Idea.docx** ที่เปิดอยู่ใน Microsoft Edge ให้ป้อนพรอมต์นี้:

   ```prompt
   Suggest a name for my cleaning business.
   ```
    ภาษาไทย
    ```prompt
    แนะนำชื่อสำหรับธุรกิจทำความสะอาดของฉัน
    ```

2. ตรวจสอบคำแนะนำเกี่ยวกับชื่อบริษัท และเลือกชื่อที่คุณชอบ  
   - หากต้องการเลือกชื่อที่ได้จากคำแนะนำ ให้ป้อนข้อความเช่น: `Let's go with the first one.`

3. จากนั้น ป้อนพรอมต์ต่อไปนี้:

   ```prompt
   Based on the contents of this document, create a business plan for my cleaning business.
   ```
    ภาษาไทย
    ```prompt
    จากเนื้อหาในเอกสารนี้ สร้างแผนธุรกิจสำหรับธุรกิจทำความสะอาดของฉัน
    ```

4. ตรวจสอบคำตอบที่ได้ จากนั้นไปที่เมนู **File** ใน Microsoft Word และสร้างเอกสารเปล่าใหม่  
   - หากมี **Designer Pane** ปรากฏขึ้น ให้ปิดไป  
   - เปลี่ยนชื่อเอกสารจาก *Document* เป็น `Business Plan`

5. คัดลอกแผนธุรกิจที่สร้างโดย Copilot จาก **Copilot Pane** และวางลงในเอกสารใหม่  
   ![Screenshot of a Word document with a Copilot-generated business plan.](./Media/generated-content.png)

## 📝 **ขั้นตอนที่ 5: สร้างโลโก้บริษัทด้วย Copilot**

1. ใน **Copilot Pane** ป้อนพรอมต์นี้:

   ```prompt
   Create a corporate logo for the cleaning company. The logo should be round and include an iconic New York landmark.
   ```
    ภาษาไทย
    ```prompt
    สร้างโลโก้บริษัทสำหรับบริษัททำความสะอาด โลโก้ควรมีรูปร่างกลมและมีสัญลักษณ์ของสถานที่สำคัญในนิวยอร์ก
    ```

2. ตรวจสอบโลโก้ที่ Copilot สร้างขึ้น

3. ใช้พรอมต์เพิ่มเติมเพื่อปรับแต่งดีไซน์ (เช่น: `Make it green and blue`) จนกว่าจะได้โลโก้ที่ถูกใจ  

> 💡 **เคล็ดลับ**: หากโลโก้ที่สร้างมีคำสะกดผิด ให้ลองเปลี่ยนพรอมต์และสร้างใหม่

4. คลิกขวาที่โลโก้และคัดลอกไปยังคลิปบอร์ด จากนั้นวางโลโก้ที่ด้านบนของเอกสารแผนธุรกิจ  
   ![Screenshot of a Word document with a Copilot-generated image.](./Media/generated-image.png)

5. ปิด browser tabs ของ Microsoft Word และกลับมาที่ OneDrive

## สรุป

ในการฝึกใช้ Generative AI ด้วย **Microsoft Copilot ใน Edge** คุณได้เรียนรู้วิธีใช้ Copilot ในการสร้างข้อมูลสรุปจากเอกสาร และสร้างแผนธุรกิจ โลโก้ และเนื้อหาอื่น ๆ ที่เกี่ยวข้องกับธุรกิจทำความสะอาดของคุณ