# DWDM21
Data Warehouse &amp;  Data Mining 2021

Sasikarn Boonmee  6230205399

Group Name:ลูกหมี

1 **นางสาวศศิกานต์ บุญมี
รหัส 623020539-9**

2 **นางสาวมินตรา ทิพยรัตน์สุนทร
รหัส 623020041-2**

3 **นางสาวกัลยารัตน์ แสนสมบัติ
รหัส 623020513-7**

4 **นางสาวฐิติชญา ไกรวงค์
รหัส 623020520-0**

5 **นางสาวนันทิชา วิชิต
รหัส 623020526-8**

# สารบัญเนื้อหา

วิชานี้เรียน Data Warehouse & Data Mining คือจะเรียนเกี่ยวกับข้อมูลว่า Data มีกระบวนการอะไรบ้างหลังจากถูกเก็บไว้ใน Database คือเอามันมาจัดการเพื่อสกัดความรู้และนำมันไปใช้ประโยชน์
Warehoure = โรงงาน คือ เก็บ Data มาแล้วก็คัดแยกจัดเก็บต่อจากDatabase เป็นตัวบรรจุข้อมูล หลังจากนั้นตัวที่ถูกเก็บมาเราก็จะทำ Mining ต่อ คือ การทำเหมืองข้อมูล จะคล้ายเราสกัดหาของมีค่าที่อยู่ใน Data 
ซึ่ง Data warehouse จะเป็นประโยชน์สำหรับการ mining

* บทที่ 1 [Introduction]
  * (https://github.com/sskboonmee/DWDM21/blob/main/Chapter1_ID6230205399.pdf)
  * (https://github.com/sskboonmee/DWDM21/blob/main/01Introlecturebysasikarn.pdf)
  * Why Data Mining = เราจะเอา Data ที่เรามีอยู่ไปสกัลองค์ความรู้ได้ยังไง 
  * What Is Data Mining = Data Mining คืออะไร
  * A Multi=Dimensional View of Data Mining = Data ต่างๆที่ใช้ใน Data Mining 
  * What Kinds of Patterns Can Be Mined? = ชนิดของ Data 
  * What Kinds of Technologoes Are Used? = Data Mining แบ่งเป็นเทคนิคหลักๆได้กี่แบบ
    หลักๆ มี 3 แบบ คือ 
    1.Pattern Discovery การสกัดหารูปแบบ  เช่น Association Rules 
    2.Classification การจำแนกกลุ่ม เช่น Decision tree,neural networks 
    3.Cluster Analysis แบ่งกลุ่ม 

* บทที่ 2 [Know your Data] 
  * lecture
    * (https://github.com/sskboonmee/DWDM21/blob/main/HW-2.1-ID6230205399.pdf)
    * (https://github.com/sskboonmee/DWDM21/blob/main/Measuring-Data-similarity-and-Dissmilarity-lecturebysasikarn.pdf)
  * Basic python
    * (https://github.com/sskboonmee/DWDM21/blob/main/Data101(Chapter2).ipynb)
     * Variables
     * Data structure
     * Loop
     * Condition
     * Function
  * Data Exploration
    * (https://github.com/sskboonmee/DWDM21/blob/main/Data102(Chapter2).ipynb) 
     * Boxplot
     * Times Series Plot 
  * Data Visualization 
    * (https://github.com/sskboonmee/DWDM21/blob/main/Data_Visualization.ipynb)
     * Scatter plot
     * Plot
     * Bar chart
       * Grouped Barchart
       * Stacked Barchart
     * Histogram 
  * Distance Numpy
    * (https://github.com/sskboonmee/DWDM21/blob/main/Distance_Numpy.ipynb)
     * Numpy Array
       * สร้าง numpy array (matrix) จาก list
       * สร้าง matrix เริ่มต้น (zeros, ones)
       * สร้าง matrix random 
       * matrix properties
       * Indexing & Slicing
       * Useful functions
     * Distance Matrix
       * Euclidean Distance (L2-norm)
       * Distance function
       * Manhattan Distance (L1-norm)
       * Distance of Binary Value
* บทที่ 3 [Data Preprocessing]
  * lecture  
     * (https://github.com/sskboonmee/DWDM21/blob/main/HW6CH3-sasikarn.pdf)
  * Github
     * (https://github.com/sskboonmee/DWDM21/blob/main/Data_processing_(Chapter3).ipynb)
     * ชี้ข้อมูลในตาราง
       * ชี้แบบธรรมดาใช้ [ชื่อ column] [index]
       * ชี้แบบ .iloc (มองข้อมูลเป็น matrix)
     * Missing Values NAN NULL NA
       * Handling Missing Value 1 (ลบ missing)
       * Handling Missing Value 1.5 (ลบค่า Missing เฉพาะใน Column ที่เราสนใจ)
       * Handing Missing Value 2 (แทนด้วย class ใหม่ (unknown))
       * Handing Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
       * Handing Missing Value 4 (แทนด้วย ค่ากลาง)
       * Handing Missing Value 5 (แทนด้วย ค่ากลางของ Samples ใน Class เดียวกัน)
     * Select date by values [PD]
       * ต่อตารางแนวแกน Y [PD]
       * การเรียงข้อมูล [PD]
       * Outlier
     * การรวมตาราง Data Integration (ต่อตารางในแนวแกน x)
       * รวม 2 ตาราง (.merge())
       * เลือกเฉพาะ column ที่ต้องการมาแปะ (.map())
       * Group by (pandas)
       * [PD] save ตารางเอาไปใช้ที่อื่น
       * [PD] การสร้างตาราง
* บทที่ 4 [Data Warehousing and On-line Analytical Processing]
  * lecture 
    * (https://github.com/sskboonmee/DWDM21/blob/main/04OLAPlecturebysasikarn.pdf) 
      * Data Warehouse : Basic Concepts 
      * Data Warehouse Modeling : Data Cube and OLAP  โมเดลของData Warehouse
       *(https://github.com/sskboonmee/DWDM21/blob/main/%E0%B8%9A%E0%B8%974.pdf)
      * Data Warehouse Design and Usage การออกแบบและการใช้งานคลังข้อมูล
      * Data Warehouse Implementation การใช้งานคลังข้อมูล
      * Summary 
* บทที่ 5 Association Rules
  * lecture
    * (https://github.com/sskboonmee/DWDM21/blob/main/Chapter623_09.pdf)  
  * Github 
    * (https://github.com/sskboonmee/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)  
    * เตรียม Data สำหรับ (Fequence Pattern) Association Rule
    * Apriori
 * บทที่ 6 [Classification]
  * Lecture
    * (https://github.com/sskboonmee/DWDM21/blob/main/08Clasificationlecturebysasikarn%20.pdf)
    * (https://github.com/sskboonmee/DWDM21/blob/main/Artificial-Neuron-Network-19_10.pdf)
  * Github
    * Decision Tree
      * (https://github.com/sskboonmee/DWDM21/blob/main/Chapter7_Classification(Decision_Tree).ipynb)
      * Load data
      * Train Model
      * Evaluation
      * Advanced Tree
      * Test
    * KNN
      * (https://github.com/sskboonmee/DWDM21/blob/main/Chap7Classification(KNN_NN).ipynb)
      * Load data
      * Split data
      * Train Model 
      * Retrain & Evaluate
      * Neural Network
    * Evaluation
      * (https://github.com/sskboonmee/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
      * Load data
      * Split data     
      * สร้าง Model ทำนาย
        * import
        * define
        * train
      * evaluation
 * บทที่ 7 [Clustering]  
           
