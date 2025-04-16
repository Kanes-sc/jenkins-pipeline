ตัวอย่างขั้นตอน CI/CD
1. Developer เขียนโค้ดใหม่
2. Jenkins เริ่ม Pipeline
3. SonarQube ตรวจคุณภาพโค้ด
4. Docker สร้าง Image แอป
5. ส่งขึ้น Registry
6. Deploy ขึ้น ROSA อัตโนมัติ


✅ Build → ✅ Scan Code (SonarQube) → ✅ Test → ✅ Build Docker Image → ✅ Push to Registry → ✅ Deploy to ROSA
