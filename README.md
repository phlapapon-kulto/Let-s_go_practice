# Let-s_go_practice
----------------------
โจทย์โปรเจกต์: E-Commerce Sales & Customer Insights

1. สถานการณ์และโจทย์ธุรกิจ (Business Problem)
เจ้าของร้านค้าออนไลน์แห่งหนึ่งต้องการนำข้อมูลประวัติการสั่งซื้อย้อนหลังมาใช้ปรับแผนการตลาด แต่ปัญหาคือข้อมูลกระจัดกระจาย มีรายการคืนสินค้า และข้อมูลบางส่วนหายไป โจทย์ของคุณคือการทำความสะอาดข้อมูล วิเคราะห์พฤติกรรมการซื้อ และสรุปเป็นรายงาน/Dashboard พร้อมคำแนะนำทางธุรกิจ

2. ชุดข้อมูลที่ใช้ (Recommended Datasets)

Sample Superstore Dataset (ค้นหาได้บน Kaggle): เหมาะสำหรับเริ่มต้น มีครบทั้ง Date, Sales, Category, Region, Customer ID

Online Retail Dataset (UCI Machine Learning Repository): ข้อมูลธุรกรรมจริง มีรายการคืนสินค้าและข้อมูลที่ต้อง Clean ค่อนข้างเยอะ เหมาะสำหรับฝึกแก้ปัญหาข้อมูล "รก"

3. สิ่งที่คุณต้องลงมือทำ (Key Tasks)

Data Cleaning & Wrangling:

จัดการข้อมูลที่ขาดหาย (Missing values) และรายการซ้ำ (Duplicates)

แปลงฟอร์แมตวันที่ (Date format) และกรองรายการคืนสินค้า (ยอดขายติดลบ) ออก

สร้าง Column ใหม่ที่จำเป็น เช่น Total Spend = Quantity * Unit Price, Purchase Month, Day of Week

Exploratory Data Analysis (EDA):

ตอบคำถาม: สินค้าหมวดหมู่ไหนสร้างรายได้สูงสุด 3 อันดับแรก?

ตอบคำถาม: ช่วงเวลา/วันไหนในสัปดาห์ที่ลูกค้านิยมสั่งซื้อมากที่สุด?

ตอบคำถาม: ลูกค้าประจำ (Repeat Customers) มีสัดส่วนเท่าไรเมื่อเทียบกับลูกค้าใหม่?

Data Visualization:

กราฟแท่ง (Bar Chart) แสดงยอดขายแยกตาม Category

กราฟเส้น (Line Chart) แสดงแนวโน้ม (Trend) ยอดขายรายเดือน

Heatmap แสดงความถี่การสั่งซื้อแบ่งตาม "วันในสัปดาห์ vs ช่วงเวลาของวัน"

4. เครื่องมือที่ใช้ (Tech Stack)

วิเคราะห์ข้อมูล: Python (Pandas, NumPy) หรือ SQL (SQLite / DuckDB)

ทำ Visualization: Matplotlib / Seaborn (ทำใน Jupyter Notebook) หรือใช้ Streamlit / Power BI

5. ผลลัพธ์สุดท้าย (Final Deliverables)

GitHub Repository: มีโค้ด Jupyter Notebook ที่เขียนอธิบายขั้นตอนอย่างเป็นระเบียบ และไฟล์ README.md

Executive Summary: สรุป 3 อินไซต์สำคัญพร้อมข้อเสนอแนะเชิงธุรกิจ เช่น "ควรจัดโปรโมชัน Flash Sale ในวันพุธช่วง 19.00 - 21.00 น. เพราะเป็นช่วงที่ยอดสั่งซื้อสูงที่สุด"
