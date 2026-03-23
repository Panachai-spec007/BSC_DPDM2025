# **SC663403	Data Preparation and Data Mining**

**ปณชัย แก้วไธสง 663020285-8**

**รายวิชา** : Data Preparation and Data Mining การเตรียมข้อมูลและการทำเหมืองข้อมูล 

--------
**คำอธิบายรายวิชา** : แนวคิดของการเตรียมข้อมูล ชนิดและประเภทของข้อมูล เครื่องมือที่ใช้ในการเตรียมข้อมูล การจัดการข้อมูลในรูปแบบต่าง ๆ พื้นฐานของการทำเหมืองข้อมูลและแนวคิดเชิงพรรณนา การสกัดความรู้จากข้อมูล อัลกอริทึมการสร้างตัวแบบเพื่อการทำนายการค้นพบความสัมพันธ์ในการทำเหมืองข้อมูล การจัดกลุ่มข้อมูล เทคนิคการประเมินตัวแบบ การเรียนรู้จากตัวแบบที่หลากหลาย และ กรณีศึกษาที่เกี่ยวข้อง


---
**Course Work and Grading**
| รายละเอียด | คะแนน |
| :--- | :--- |
| Midterm (data prepocessing ปฏิบัติ (เดี่ยว))| 25% |
| Final(ทฤษฎี data mining (เดี่ยว)) | 25% |
| Project (data prepocessing + data mining (จัดกลุ่มเอง 5-6 คน)) | 20% |
| Homework (แบ่งกลุ่มใหม่ทุกครั้ง) | 15% |
| Quiz (เดี่ยว ถามในห้อง) | 10% |
| GitHub | 5% |

***Final Score = Score * %attendance***

----
**เอกสารการเรียน**
| บทที่ | Slides |
| :--- | :--- |
| 01 | [Introduction](Chapter%201%20Introduction.pdf) |
| 02 | [Getting to Know Your Data](Chapter%202%20Getting%20to%20Know%20Your%20Data.pdf) |
| 03 | [Preprocessing](03Preprocessing.pdf) |
| 06 | [Frequent Patterns Basic](06FPBasic.pdf) |
| 08 | [Classification Basic](08ClassBasic(1).pdf) |
| 09 | [Classification Advanced](09ClassAdvanced.pdf) |
| 10 | [Clustering Basic](10ClusBasic.pdf) |
| พิเศษ | [AI](ai1.0.2.pdf) |

## สรุปเนื้อหาสำคัญ (Core Modules)

**Data Preprocessing (การเตรียมข้อมูล)** 
"Quality data leads to quality patterns." กระบวนการเปลี่ยนข้อมูลดิบให้พร้อมใช้งาน:
* **Data Cleaning:** จัดการค่าว่าง (Missing values) และกำจัด Noise/Outliers
* **Data Integration:** รวมข้อมูลจากหลายแหล่งและจัดการความซ้ำซ้อน
* **Data Reduction & Transformation:** การลดมิติข้อมูล (Dimensionality Reduction) และการทำ Normalization เพื่อให้โมเดลประมวลผลได้แม่นยำขึ้น

**Frequent Pattern Mining (การหาความสัมพันธ์)** 
การค้นหารูปแบบที่เกิดขึ้นบ่อยในชุดข้อมูลขนาดใหญ่:
* **Market Basket Analysis:** วิเคราะห์ว่าสินค้าอะไรที่มักถูกซื้อพร้อมกัน
* **Algorithms:** ศึกษาเทคนิคอย่าง **Apriori** และ **FP-Growth** เพื่อหา Association Rules ที่มีค่า Support และ Confidence สูง

**Classification (การจำแนกประเภท)** 
การสร้างโมเดลทำนายกลุ่มข้อมูล (Supervised Learning):
* **Basic Methods:** Decision Tree, Naïve Bayes, และ Linear Classifiers
* **Advanced Methods:** Support Vector Machines (SVM), Neural Networks, Deep Learning และ Ensemble Methods (การรวมหลายโมเดลเข้าด้วยกันเพื่อความแม่นยำ)
* **Evaluation:** การวัดผลด้วย Accuracy, Precision, Recall และ F1-Score

**Cluster Analysis (การจัดกลุ่ม)**
การแบ่งกลุ่มข้อมูลที่คล้ายคลึงกันเข้าด้วยกันโดยไม่มีป้ายกำกับ (Unsupervised Learning):
* **Partitioning:** เช่น K-Means
* **Hierarchical:** การจัดกลุ่มแบบลำดับชั้น
* **Density-Based:** เช่น DBSCAN สำหรับค้นหากลุ่มที่มีรูปร่างอิสระและตรวจจับ Outliers

---

**ประโยชน์ที่ได้รับ (Key Benefits)**

1.  **Insight Discovery:** สามารถเปลี่ยนข้อมูลมหาศาลให้กลายเป็นความรู้ที่ใช้ตัดสินใจทางธุรกิจได้
2.  **Predictive Power:** ใช้ทำนายแนวโน้มในอนาคต เช่น พฤติกรรมลูกค้า หรือความเสี่ยงทางการเงิน
3.  **Efficiency:** เข้าใจเทคนิคการจัดการ Big Data ให้มีประสิทธิภาพ ไม่สิ้นเปลืองทรัพยากรเครื่อง
4.  **AI Foundation:** เป็นรากฐานสำคัญในการต่อยอดไปสู่ Machine Learning และ Data Science

---

**References**
* *Data Mining: Concepts and Techniques* by Jiawei Han, Micheline Kamber, and Jian Pei.
* CS 412 Course Material, University of Illinois at Urbana-Champaign.

---

