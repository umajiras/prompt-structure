# prompt-structure (องค์ประกอบพื้นฐานของ Prompt)
การใช้งานและการออกแบบ prompt ให้ได้ผลลัพธ์ที่แม่นยำและตรงความต้องการ 

# 🌟 การเขียน Prompt อย่างมีประสิทธิภาพ  

## 📚 สารบัญ
- [โครงสร้างของ Prompt](#โครงสร้างของ-prompt)
  - [👤 Persona](#-persona)
  - [🌍 Context](#-context)
  - [🎯 Task](#-task)
  - [🧩 Constraints](#-constraints)
  - [📄 Format](#-format)
  - [🎭 Tone](#-tone)
- [🧠 ตัวอย่าง Prompt ที่ครบทุกองค์ประกอบ](#-ตัวอย่าง-prompt-ที่ครบทุกองค์ประกอบ)

---

## โครงสร้างของ Prompt

Prompt ที่ดีควรประกอบด้วย 6 องค์ประกอบหลักดังนี้:

| องค์ประกอบ | คำอธิบาย |
|------------|----------|
| 👤 **Persona** | ให้ AI สวมบทบาท เช่น "เจ้าหน้าที่ฝึกอบรม", "นักโภชนาการ" |
| 🌍 **Context** | บริบทของงาน เช่น “เตรียมการประชุมประจำเดือน” |
| 🎯 **Task** | สิ่งที่ต้องการให้ AI ทำ เช่น “เขียนสรุปประชุม”, “วางแผนกิจกรรม” |
| 🧩 **Constraints** | เงื่อนไข เช่น "ไม่เกิน 3 ย่อหน้า", "ใช้คำไม่ซ้ำ" |
| 📄 **Format** | รูปแบบผลลัพธ์ เช่น "ตาราง", "ลิสต์หัวข้อ", "บทความ" |
| 🎭 **Tone** | โทนภาษา เช่น “เป็นกันเอง”, “ทางการ”, “มืออาชีพ” |

---

## ตัวอย่าง Prompt

### 👤 Persona
```markdown
คุณคือ AI ผู้ช่วยส่วนตัวของผู้บริหารระดับสูง คุณต้องสรุปข้อมูลให้กระชับ เข้าใจง่าย และสามารถใช้ประกอบการตัดสินใจได้ทันที
```

```markdown
คุณคือเจ้าหน้าที่ฝ่ายบุคคล (HR) คุณต้องแนะนำเนื้อหาการอบรมให้พนักงานใหม่เข้าใจง่ายและนำไปใช้ได้จริง
```

```markdown
คุณคือผู้เชี่ยวชาญด้านการออกแบบเนื้อหาภายในองค์กร คุณต้องสร้างข้อความประชาสัมพันธ์ที่ดึงดูดใจและเหมาะกับพนักงานทุกระดับ
```

```markdown
คุณเป็นนักจิตวิทยาที่สามารถให้คำปรึกษาด้านสุขภาพจิต โปรดให้คำปรึกษาและคำตอบที่เหมาะสมที่สุด
```

```markdown
คุณคือที่ปรึกษาด้านการพัฒนาทักษะบุคลากร คุณต้องแนะนำกิจกรรมหรือแนวทางฝึกฝน Soft Skills ที่นำไปใช้ในที่ทำงานได้จริง
```

```markdown
คุณคือครูสอนพิเศษภาษาอังกฤษที่อธิบายเข้าใจง่ายพร้อมตัวอย่างให้นักเรียนเข้าใจ
```
___

### 🌍 Context

```markdown
ข้อมูลนี้จะถูกใช้ประกอบการประชุมระดับผู้บริหาร ซึ่งต้องการสรุปที่กระชับ ชัดเจน และเน้นประเด็นสำคัญเพื่อการตัดสินใจภายในเวลาอันจำกัด
```

```markdown
คำอธิบายนี้จัดทำขึ้นสำหรับพนักงานใหม่ที่เพิ่งเข้าร่วมงาน โดยยังไม่มีพื้นฐานในเรื่องที่เกี่ยวข้อง จึงต้องใช้ภาษาที่เข้าใจง่ายและมีตัวอย่างประกอบ
```

```markdown
ข้อความนี้จะถูกส่งเป็นประกาศภายในองค์กรผ่านช่องทางไลน์กลุ่ม เพื่อแจ้งแนวทางปฏิบัติในช่วงสถานการณ์ฉุกเฉิน โดยต้องสื่อสารให้เข้าใจได้ในครั้งเดียว
```

```markdown
เนื้อหานี้ใช้สำหรับจัดทำเอกสารประชาสัมพันธ์กิจกรรมเพื่อสังคม (CSR) ของบริษัท ซึ่งจะเผยแพร่ต่อสาธารณะผ่านเว็บไซต์และช่องทางโซเชียลมีเดีย
```

```markdown
คำตอบนี้จะถูกใช้ในการฝึกอบรมหัวหน้างาน เพื่อให้สามารถนำไปถ่ายทอดต่อกับทีมงานได้ จึงต้องมีโครงสร้างที่ชัดเจน เข้าใจง่าย และมีตัวอย่างที่ใช้ได้จริงในบริบทการทำงาน
```


---

### 🎯 Task

```markdown
ช่วยสรุปสาระสำคัญจากรายงานประชุมความยาว 3 หน้ากระดาษ ให้อยู่ในรูปแบบที่กระชับ ชัดเจน และเหมาะสำหรับผู้บริหารที่มีเวลาน้อย
```

```markdown
ช่วยเขียนข้อความประชาสัมพันธ์กิจกรรมปลูกต้นไม้ประจำปีของบริษัท ให้น่าสนใจ ดึงดูดใจพนักงาน และกระตุ้นให้เกิดการมีส่วนร่วม
```

```markdown
ช่วยจัดตารางการฝึกอบรมพนักงานใหม่ในช่วงทดลองงาน ให้ครอบคลุมทั้งเรื่องระเบียบการทำงาน วัฒนธรรมองค์กร และการใช้งานระบบภายใน
```

```markdown
ช่วยอธิบายแนวคิดของการใช้ AI ในโรงงานผลิตแบบที่คนไม่มีพื้นฐานด้านเทคโนโลยีก็สามารถเข้าใจได้ พร้อมยกตัวอย่างประกอบ
```

```markdown
ช่วยเปรียบเทียบข้อดีและข้อจำกัดของการ Work from Home เทียบกับการทำงานในออฟฟิศ โดยเน้นมุมมองของทั้งพนักงานและผู้บริหาร
```

---

### 🧩 Constraints

```markdown
คำตอบต้องไม่เกิน 150 คำ และใช้ภาษาที่เข้าใจง่ายสำหรับคนทั่วไป
```

```markdown
ห้ามใช้ศัพท์เทคนิคหรือคำย่อ โดยให้ใช้ภาษาที่คนไม่มีพื้นฐานเฉพาะทางก็สามารถเข้าใจได้
```

```markdown
ให้สรุปเป็นข้อ ๆ ไม่เกิน 5 ข้อ และแต่ละข้อไม่เกิน 2 บรรทัด
```

```markdown
เนื้อหาต้องเหมาะสำหรับอ่านบนโทรศัพท์มือถือ โดยไม่ใช้ตารางหรือข้อความยาวต่อเนื่อง
```

```markdown
ห้ามใช้คำซ้ำ และควรหลีกเลี่ยงการขึ้นต้นประโยคด้วยคำว่า "โดย"
```

---

### 📄 Format

```markdown
จัดให้อยู่ในรูปแบบหัวข้อย่อย พร้อมคำอธิบายสั้น ๆ ใต้แต่ละหัวข้อ
```

```markdown
แสดงผลลัพธ์ในรูปแบบตารางเปรียบเทียบข้อดี-ข้อเสียอย่างชัดเจน
```

```markdown
เขียนเป็นอีเมลฉบับสมบูรณ์ พร้อมหัวเรื่อง คำขึ้นต้น เนื้อหา และคำลงท้าย
```

```markdown
จัดเนื้อหาเป็นลิสต์รายการ (Bullet points) ที่อ่านง่ายและไม่เกิน 5 รายการ
```

```markdown
เขียนเป็นบทความสั้น ๆ ที่มีโครงสร้างนำเรื่อง เนื้อหา และสรุปตอนท้าย
```

```markdown
จัดเนื้อหาให้อยู่ในรูปแบบ PowerPoint โดยแบ่งออกเป็น 5 สไลด์ พร้อมใส่หัวข้อและคำอธิบายในแต่ละสไลด์ เพื่อใช้ในการนำเสนอในที่ประชุม
```

```markdown
เขียนเนื้อหานี้ในรูปแบบไฟล์ Word (.docx) พร้อมจัดโครงสร้างให้มีหัวเรื่อง บทนำ เนื้อหา และสรุป เพื่อสามารถนำไปแก้ไขหรือพิมพ์แจกได้ทันที
```

---

### 🎭 Tone

```markdown
ใช้โทนภาษาสุภาพและเป็นทางการ เหมาะสำหรับสื่อสารกับผู้บริหารหรือใช้ในเอกสารราชการ
```

```markdown
ใช้โทนภาษากึ่งทางการ เน้นให้ดูเป็นมิตรแต่ยังคงความน่าเชื่อถือ เหมาะสำหรับอีเมลถึงเพื่อนร่วมงานหรือคู่ค้า
```

```markdown
ใช้โทนภาษาสบาย ๆ เป็นกันเอง เหมาะสำหรับโพสต์ภายในองค์กร หรือการสื่อสารภายในทีม
```

```markdown
ใช้โทนภาษาที่สร้างแรงบันดาลใจและให้กำลังใจ เหมาะกับการพูดกับพนักงานใหม่หรือคนที่กำลังหมดไฟ
```

```markdown
ใช้โทนภาษากระชับ ชัดเจน ตรงประเด็น โดยไม่ใส่รายละเอียดเกินความจำเป็น เหมาะสำหรับการรายงานหรือสรุปผลให้ผู้บริหารที่มีเวลาจำกัด
```

---

## 🧠 ตัวอย่าง Prompt ที่ครบทุกองค์ประกอบ

```markdown
คุณคือผู้ช่วยวางแผนไลฟ์สไตล์ส่วนตัว  
บริบท: ฉันมีวันหยุดสุดสัปดาห์นี้ และอยากใช้เวลาให้คุ้มค่าที่สุด  
คำสั่ง: ช่วยแนะนำกิจกรรมที่ทำได้ในบ้านแบบไม่ต้องออกไปข้างนอก  
ข้อจำกัด: ต้องไม่ใช้เงินเกิน 200 บาท  
รูปแบบ: รายการลิสต์ 3 กิจกรรม  
โทนภาษา: เป็นกันเองและให้แรงบันดาลใจ
```

```markdown
คุณคือนักโภชนาการที่เข้าใจชีวิตวัยทำงาน  
บริบท: ฉันไม่มีเวลากินข้าวเที่ยงเป็นเรื่องเป็นราว แต่ก็ไม่อยากสุขภาพพัง  
คำสั่ง: ช่วยแนะนำเมนูที่ทำง่ายใน 10 นาทีและพกไปกินที่ทำงานได้  
ข้อจำกัด: ใช้วัตถุดิบไม่เกิน 5 อย่าง  
รูปแบบ: รายการเมนูพร้อมคำอธิบายสั้น ๆ  
โทนภาษา: เป็นกันเองและใส่ใจสุขภาพ
```

```markdown
คุณคือที่ปรึกษาด้านการเงินที่เน้นการวางแผนให้คนวัยเริ่มต้นทำงาน  
ช่วยวางแผนจัดการเงินเดือน 18,000 บาท โดยตั้งเป้าเก็บเงิน 20% ทุกเดือน  
บริบทคือมีค่าใช้จ่ายจำเป็น เช่น หอพัก ค่าเดินทาง  
แนะนำการแบ่งเงินออกเป็น 4 หมวดหลัก  
จัดในรูปแบบตาราง หรือรายการ  
ใช้ภาษาชัดเจน เรียบง่าย เข้าใจง่ายสำหรับคนทั่วไป
```

```markdown
คุณคือนักเขียนบทความออนไลน์ที่มีความเชี่ยวชาญเรื่องสุขภาพจิต  
ช่วยเขียนบทความสั้นเกี่ยวกับการรับมือกับความเครียดในช่วงวันทำงานที่หนักหน่วง  
บริบทคือผู้อ่านเป็นวัยทำงานออฟฟิศที่มีเวลาจำกัด  
ความยาวไม่เกิน 150 คำ  
จัดเป็นบทความสั้น ๆ ที่มีโครงสร้างชัดเจน  
ใช้โทนภาษาที่เข้าใจง่ายและให้ความรู้สึกอบอุ่น
```

```markdown
คุณคือนักวิเคราะห์ข้อมูลที่มีหน้าที่สรุปรายงานให้ผู้บริหาร  
ช่วยสรุปข้อมูลยอดขายรายไตรมาสของบริษัทให้อยู่ในรูปแบบที่อ่านเข้าใจง่าย  
บริบทคือข้อมูลจะนำเสนอในที่ประชุมผู้บริหารระดับสูง  
ข้อมูลควรสั้น กระชับ ไม่เกิน 120 คำ  
แสดงผลในรูปแบบย่อหน้าเดียว  
ใช้ภาษาทางการ ชัดเจน ตรงประเด็น
```

