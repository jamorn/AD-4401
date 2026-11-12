⚖️ Stand-alone Scale OCR & Weight Logging Web App
ระบบเว็บแอปพลิเคชันสำหรับอ่านและบันทึกค่าน้ำหนักจากเครื่องชั่งอุตสาหกรรม (รองรับ A&D AD-4401 และรุ่นอื่นๆ) ออกแบบมาสำหรับการทำงานแบบ Stand-alone โดยให้พนักงานหน้างานใช้มือถือหรือแท็บเล็ตเปิดกล้องส่องตัวเลขผ่านกรอบเป้าหมาย (Guide Box) ระบบจะดึงค่าอัตโนมัติเพื่อให้พนักงานตรวจสอบ (Verify) และส่งข้อมูลขึ้นระบบคลาวด์อย่างรวดเร็ว

🚀 Key Features
Camera & ROI Cropping: เปิดกล้องหลังอัตโนมัติพร้อมกรอบไกด์ไลน์ (Guide Box) เพื่อจำกัดพื้นที่และตัดแสงสะท้อนหรือตัวหนังสือรอบข้างออก

Auto-Fill OCR (Mock / Ready for Integration): ดึงค่าน้ำหนักจากหน้าจอเครื่องชั่งมาเติมลงฟอร์มให้อัตโนมัติเมื่ออยู่ในกรอบ

Human Verify: เปิดโอกาสให้พนักงานตรวจสอบหรือแก้ไขตัวเลขได้ทันทีบนหน้าจอก่อนกดยืนยัน (Submit)

Success Confirmation Modal: แสดงหน้าต่างยืนยันค่าน้ำหนักที่บันทึกสำเร็จ (รูปแบบ xxx.xx kg) พร้อมเริ่มงานรอบถัดไปทันที

Cloud & Local Integration Ready: ออกแบบสถาปัตยกรรมให้รองรับการส่งข้อมูลขึ้น Firebase และซิงค์ลง SQL Server ภายในองค์กร

🛠️ Tech Stack
Frontend: HTML5, Tailwind CSS, JavaScript (Vanilla / React Next.js Ready)

Camera API: HTML5 MediaDevices (navigator.mediaDevices.getUserMedia) & Canvas API

Deployment: Vercel / GitHub Pages
