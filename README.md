# FitChooseIntegrate
Developed multiple AI models integrated into the application, including
 - A virtual try-on system enabling users to preview outfits on virtual avatars.
 - A style-matching AI that recommends clothing items with compatible styles.
 - A clothing detection model for automatic identification and tagging of apparel during data input.
Conducted research on state-of-the-art technologies and academic papers to align the senior project with the defined objectives and ensure technical feasibility.
Technologies Used : Computer Vision, Object Detection, and Deep Learning 
## การติดตั้ง

### ดาวน์โหลดไฟล์โมเดล

ก่อนรันแอปพลิเคชัน ต้องดาวน์โหลดไฟล์โมเดล YOLO:

1. ดาวน์โหลดไฟล์ `best.pt` จาก [Google Drive](แมน)
2. สร้างโฟลเดอร์ `backend/weight.model/` ในโปรเจค
3. วางไฟล์ `best.pt` ในโฟลเดอร์ `backend/weight.model/`

### Backend

1. ติดตั้ง dependencies:
   ```bash
   cd backend
   pip install -r requirements.txt
   ```
