# Deploy คอนโซลนี้ไป Hugging Face Space

ไฟล์ใน `friday-space/` คือ Space พร้อมสร้างทันที

## วิธีที่เร็วที่สุด (ไม่ต้องใช้ git)
1. เปิด https://huggingface.co/new-space ด้วยบัญชี **Thitistc**
2. Space name: `friday-console` · Space SDK: **Static**
3. Create Space
4. Add file → Upload → เลือก `friday-space/index.html`
5. แก้ไฟล์ README.md ใน Space ให้มี YAML header เดียวกับใน friday-space/README.md
6. เสร็จ — URL: https://huggingface.co/spaces/Thitistc/friday-console

## วิธี git (ถ้าต้องการ sync อัตโนมัติ)
```bash
git clone https://huggingface.co/spaces/Thitistc/friday-console
cp friday-space/* friday-console/
cd friday-console && git add . && git commit -m "init" && git push
```
