# Campus-card-analysis
基于Python对校园一卡通消费信息分析
包含原始数据和源码，首先进行清洗和整理，再进行相关数据分析并利用matplotlib绘图。

### 1.数据清洗

##### 1.1. 为保护隐私，将原始数据中的“学院/专业/学年/班级”使用代号进行替换。
##### 1.2. 检测数据中是否存在“学院/专业/学年/班级”缺失的情况，如有，删除该条数据。< br>
##### 1.3. 检测数据中是否存在消费数据缺失的情况，如有，设计一种填充规则对缺失数据进行填充。

### 2.数据整理
##### 将上述“学院/专业/学年/班级”列转化成四个列，分别描述学院，专业，年级，班级。
##### 将每个同学的消费信息按照消费时间划分成“早餐”，“午餐”，“晚餐”，“其他”四部分。

### 3.数据分析
##### 任选一个班级，分析该班同学的用餐习惯：吃早、中、晚餐的次数；一日三餐消费占全部消费的比例。
##### 任选一个同学，分析该同学在自己班级中的消费排名：一日三餐消费，全部消费，三餐消费在全部消费中的比重。
##### 输出每一个班消费三餐消费最高、全部消费最高的十位同学。

> 源码压缩包中已经运行后的结果，数据文件目录写的是相对路径，需要把原数据放到项目路径下，也可改成绝对路径。
结果文件打开方式为 a 追加，再运行需把结果文件和清洗后文件及图片删除只留代码和元数据避免重复。
