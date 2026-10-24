# ⚡ Dev-Pipeline Master Skill (v2.1)

> **Structured AI Software Development, Embedded Systems Pipeline & Anthropic Prompt/System Repair Playbook**

---

## 📌 เหมาะกับการทำงานด้านใด? (Use Cases)

สกิลนี้ออกแบบมาสำหรับสายพัฒนาซอฟต์แวร์และระบบฮาร์ดแวร์ฝังตัว (Embedded Systems) ที่ต้องการควบคุมความเสถียรของระบบด้วยวิศวกรรมการตรวจสอบข้อผิดพลาดระดับสูง เหมาะอย่างยิ่งสำหรับ:

1. **Software & Embedded Systems Development**  
   *(การพัฒนาและควบคุมวงจรการสร้างโค้ดสำหรับไมโครคอนโทรลเลอร์, แพลตฟอร์มฮาร์ดแวร์ และซอฟต์แวร์ระบบ)*
2. **System Failure Analysis & Triage**  
   *(การคัดกรอง จัดกลุ่มข้อผิดพลาด และสร้างชุดประเมินผลระบบก่อนลงมือแก้ไขหรือปรับปรุง)*
3. **Scope Trimming & YAGNI Enforcement**  
   *(การควบคุมสโคปงานไม่ให้บานปลาย ตัดฟีเจอร์ส่วนเกินเพื่อให้ระบบส่งมอบได้รวดเร็วและมีประสิทธิภาพ)*
4. **Rigorous Code Review & Architecture Audit**  
   *(การตรวจสอบความปลอดภัย ช่องโหว่ และโครงสร้างสเปกก่อนนำไปคอมไพล์หรือใช้งานจริง)*

---

## ⚙️ Workflow Overview (6 Stages)

```mermaid
graph TD
    A[💡 Raw Idea & Requirements] --> S1[/1. Idea & Feasibility Analysis/]
    S1 --> S2[/2. Eval & Failure Buckets Triage/]
    S2 --> S3[/3. Scope Trimming YAGNI/]
    S3 --> S4[/4. Technical Specification/]
    S4 --> S5[/5. Task Breakdown & Code Implementation/]
    S5 --> S6[/6. Code Review & Caveman Summary/]
    S6 --> B[🚀 Production Ready & Verified System]