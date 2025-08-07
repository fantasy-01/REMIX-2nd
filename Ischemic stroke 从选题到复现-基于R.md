
##                                                        0.1 课程背景

聚焦GBD数据分析常见问题

- 大批量的数据如何读取
- 各变量如何筛选和整理
- 95%区间数据如何呈现
- 年度趋势应该选取数据库提供的数据还是二次分析
- 全球地图如何绘制（尤其是小地图怎么绘制）
- R语言纵轴双轴图如何绘制
- 风险因素数据如何呈现
- 如何进行趋势预测，基于什么模型



##                                                         0.2 课程目标

对标一篇柳叶刀子刊文章，基于分析方法进行模拟选题，依据研究思路复现主要研究方法，基于R语言



**对标论文：**Global, regional, and national burden of ischemic stroke, 1990–2021: an analysis of data from the global burden of disease study 2021 (**IF: 9.6, JCR Q1**)

1990-2021 年缺血性中风的全球、地区和国家负担：对 2021 年全球疾病负担研究数据的分析

[Global, regional, and national burden of ischemic stroke, 1990-2021: an analysis of data from the global burden of disease study 2021 - PubMed (nih.gov)](https://pubmed.ncbi.nlm.nih.gov/39157811/)

<img src="https://s2.loli.net/2024/09/07/wKbrlyNWvjU2XV5.jpg" alt="image-20240907175109" style="zoom:80%;" />



**模拟选题：**1990-2021 年食管癌的全球、地区和国家负担：对 2021 年全球疾病负担研究数据的分析

| 模拟选题分析步骤：                                           |
| ------------------------------------------------------------ |
| 1. 数据提取，读入与整合                                      |
| 2. 绝对例数与年龄标化率的年度数据以及趋势                    |
| 2.1. 数据表格                                                |
| 2.2. 趋势图                                                  |
| 3.  全球年龄标化率分布                                       |
| 3.1. 2021年全球Incidence，Deaths，DALYs年龄标化率分布        |
| 3.2. 1990-2021年全球Incidence，Deaths，DALYs年龄标化率变化程度分布 |
| 4.  年龄分布趋势                                             |
| 5.  依据SDI水平不同性别疾病负担变化大小差异                  |
| 6.  风险因素                                                 |
| 6.1. 1990-2021年风险因素变化趋势                             |
| 6.2. 2021年风险因素占比                                      |
| 7.  未来15年疾病负担的变化趋势                               |





##                                                         0.3 课程设计

​                                                                                  **GBD数据库SCI文章从选题到复现-基于R语言**                                               

0 课程介绍

​    0.1 课程背景 

​    0.2 课程目标

​    0.3 课程设计

​    0.4 数据库介绍和简单数据整理

​           0.4.1 GBD数据库的介绍，以及选择的理由

​           0.4.2 GBD在线数据库资源呈现以及账号和协作者的申请

​           0.4.3 GBD数据介绍，包含变量类型，如何选择以及下载

​           0.4.4 GBD原始数据的导入，整合和简单结果呈现，基于R语言，代码实现

1 数据提取整理

​    1.1 GBD数据下载

​    1.2 GBD数据导入

​    1.3 GBD数据整理

2 基于全球和SDI水平的逐年趋势变化

3 基于全球，SDI水平以及regional水平，1990年和2021年值分布以及总体趋势变化

4 基于national水平分布

5 年龄变化趋势

6 基于national水平总体变化趋势分布

7 基于SDI水平，不同年龄、性别总体变化趋势

8 风险因素分布

9 未来趋势预测

10 小结



总课时约3小时，具体安排如下：

| **课程章节**                                               | **内容简介**                                                                                                                | **时间** |
| :----------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------- | :----: |
| **0 课程介绍**                                             | （1）对标一篇GBD文章，模拟选题<br/>（2）结合现有文献，调整研究对象，确定具体研究方向<br/>（3）梳理论文数据分析要点，明确下一步复现的数据分析内容<br/>（4）GBD数据库协作者申请<br/>（5）GBD数据库账号账号注册 | 20 min |
| **1 数据提取整理**                                           | （1）GBD数据下载 <br/>（2）GBD数据导入<br/>（3）GBD数据整理                                                                               | 15 min |
| **2 基于全球和SDI水平的逐年趋势变化**                                | （1）趋势图的知识讲解。<br/>（2）代码实操。<br/>（3）结果解读与论文撰写。                                                                             | 15 min |
| **3 基于全球，SDI以及regional水平，<br/>1990年和2021年值分布以及总体趋势变化** | （1）趋势表的知识讲解。<br/>（2）代码实操。<br/>（3）结果解读与论文撰写。                                                                             | 15 min |
| **4 基于national水平分布**                                   | （1）地图的知识讲解。<br/>（2）代码实操。<br/>（3）结果解读与论文撰写。                                                                              | 15 min |
| **5 年龄变化趋势**                                           | （1）年龄趋势图的知识讲解。<br/>（2）代码实操。<br/>（3）结果解读与论文撰写。                                                                           | 15 min |
| **6 基于national水平总体变化趋势分布**                             | （1）趋势分布地图的知识讲解。<br/>（2）代码实操。<br/>（3）结果解读与论文撰写。                                                                          | 15 min |
| **7 基于SDI水平，不同年龄、性别总体变化趋势**                            | （1）趋势变化棒棒图的知识讲解。<br/>（2）代码实操。<br/>（3）结果解读与论文撰写。                                                                         | 15 min |
| **8 风险因素分布**                                           | （1）分布排序的知识讲解。<br/>（2）代码实操。<br/>（3）结果解读与论文撰写。                                                                            | 15 min |
| **9 未来趋势预测**                                           | （1）预测趋势图的知识讲解。<br/>（2）代码实操。<br/>（3）结果解读与论文撰写。                                                                           | 15 min |
| **10 课程小结**                                            | （1）课程小结。<br/>（2）学习扩展资料分享。                                                                                               |  5min  |



##                                                         0.4 数据库介绍和简单数据整理

> - 1 GBD数据库的介绍，以及选择的理由
>
> - 2 GBD在线数据库，资源呈现，以及账号和协作者的申请
>
> - 3 GBD数据介绍，包含变量类型，如何选择以及下载
>
> - 4 GBD原始数据的导入，整合和简单结果呈现，基于R语言，代码实现

本次直播课程的特色：**全面直观感受数据库内容和魅力，手把手教会数据整理以及适配代码运行，随时交流互动，零距离感受科研过程和结果呈现，建立科研亲切感。**



### （1）GBD数据库的介绍，以及选择的理由

<img src="https://s2.loli.net/2024/09/06/ib3cNIdrjBgGokS.jpg" alt="image-20240905111326" style="zoom:80%;" />

全球疾病负担数据库（Global Burden of Disease，GBD）是为量化数百种疾病、伤害和风险因素造成的健康损失提供了一个世界迄今为止最大最全面的工具。是由华盛顿大学健康指标与评估研究所(Institute for Health Metrics and Evaluation, IHME)所主导的，通过162 个国家和地区的 9000 多名研究人员联合收集和分析的。这些数据记录了从 1990 年至今，204 个国家和地区的 370 种疾病和伤害造成的过早死亡和残疾，并按年龄和性别进行了分类。GBD 设计灵活，可用于全球、国家和地方各级，以了解不同时期的健康趋势。

截至目前为止，自GBD 2021数据库2024年数据公开以来在《The Lancet》等医学顶刊中已有数篇文章报道!

<img src="https://s2.loli.net/2024/09/06/khmCVH7RSDtQPLs.jpg" alt="image-20240905111305" style="zoom:80%;" />



选择GBD数据的理由：

- **公开访问和高效免费：**面向全球用户，无需缴费，免费注册；

- **数据覆盖广泛：**包括主要常见疾病和伤害及危险因素，371 diseases and 88 risk factors；涵盖 21地区，204个国家，811个国家以下各级地点；

- **指标丰富：**患病率、发生率、死亡率，YLLs ，YLDs， DALYs，健康预期寿命以及风险因素归因等；

- **数据的高质量和可靠性：**GBD数据包括了医院记录、健康调査、死亡证书和研究文献。通过复杂的统计模型和数据验证，确保了数据的准确性和可靠性。

- **包含不同性别、年龄、年份等**。

  

<img src="https://s2.loli.net/2024/09/06/CWdsT9YU7hGOPju.jpg" alt="image-20240905141858" style="zoom:80%;" />

据不完全统计，历年来发文总计约2300篇，呈逐年上升趋势，2023年达发文量顶峰约有480篇，而截至2024年9月已有发文418篇左右。基于最新GBD 2021的更新，发表论文只是时间问题，更有待在顶刊上发表！！！



### （2）GBD在线数据库资源呈现，以及账号和协作者的申请

- **数据库网址：[Global Health Data Exchange | GHDx](https://ghdx.healthdata.org/)**

<img src="https://s2.loli.net/2024/09/06/aTC5fL8rb3UM2y6.jpg" alt="image-20240905142950" style="zoom:80%;" />

这里包含了各期汇总的数据，可见最新的GBD 2021数据。



- **数据可视化网址：[VizHub - GBD Compare (healthdata.org)](https://vizhub.healthdata.org/gbd-compare/)**

<img src="https://s2.loli.net/2024/09/06/cKZ6Ez4gV7h5tJQ.jpg" alt="image-20240905143750" style="zoom:80%;" />

该网址提供了部分数据分析可视化图片，图片可自行下载。



- **数据筛选和下载网址：[VizHub - GBD Results (healthdata.org)](https://vizhub.healthdata.org/gbd-results/)  *********

<img src="https://s2.loli.net/2024/09/06/vi6uPF1W4UORwTN.jpg" alt="image-20240905143412" style="zoom: 67%;" />

数据的筛选和下载均在该页面进行，也是最常用界面。



- **在注册帐号之前，可先进行协作者的申请**（可以不申请）

1）什么是协作者？

华盛顿大学健康计量与评估研究所（IHME）拥有一个庞大的个人合作者网络，这些合作者在不同的专业领域具有专长，共同开展全球疾病、伤害和危险因素负担研究（GBD）及其附属研究项目。 全球疾病、伤害和风险因素负担研究是一项系统性的科学研究，旨在量化特定时间点不同年龄、性别和地域的疾病、伤害和风险因素造成的健康损失的比较大小。 这是迄今为止衡量全球流行病学水平和趋势的最大规模、最全面的工作。 这项研究使决策者能够比较不同健康状况的影响。 GBD 研究在许多不同国家引起了科学、政策甚至公众的极大兴趣。

合作者在GBD研究中发挥着至关重要的作用。 从数据分析到政策应用，GBD合作者可以通过多种方式为GBD及其附属研究项目做出贡献。 IHME作为协调中心，根据合作者的专业领域，让他们参与到课题中来。 这些成员都是与人口健康相关的许多领域的专家，他们的专长属于以下一个或多个类别： 人口学（全因死亡率、人口、生育率或迁移） 特定疾病、伤害、损伤或风险因素 特定国家和/或地区的流行病学 卫生政策和实践 为实现GBD事业的目标所需的其他技能和专业知识 迄今为止，该网络已有11000多名合作者，分布在163个国家和地区。 GBD合作者来自不同的工作部门和机构，包括研究和科研机构、医疗保健服务和政策以及多边组织。 GBD合作者包括研究人员、科学家、大学教授、政策制定者、政府卫生官员、非政府组织和非营利组织的工作人员、研究生以及实施公共卫生项目或干预措施的专业人员。

2）如何申请？

申请网址：[GBD Collaborator Network | Institute for Health Metrics and Evaluation (healthdata.org)](https://www.healthdata.org/research-analysis/gbd/collaborator-network)

<img src="https://s2.loli.net/2024/09/06/jhDlGBy6bFntmfM.jpg" alt="image-20240905151323" style="zoom:80%;" />

此处点击APPLY NOW之后选择NO，

<img src="https://s2.loli.net/2024/09/06/Z4pOQx9dtcb5GmW.jpg" alt="image-20240905151437" style="zoom:80%;" />

再填写申请的邮箱，

<img src="https://s2.loli.net/2024/09/06/CiGHpu1D5e7ndFZ.jpg" alt="image-20240905151534" style="zoom:80%;" />

进入后，完成7个步骤的必填项（其中需要上传简历）后点击save即可，

<img src="https://s2.loli.net/2024/09/06/ezyL6kvaRrNjI7O.jpg" alt="image-20240905152609" style="zoom:80%;" />



- **账号注册申请**

从[VizHub - GBD Results (healthdata.org)](https://vizhub.healthdata.org/gbd-results/)  进入后，界面呈现如下：

<img src="https://s2.loli.net/2024/09/06/sz7SdUAXh8Bwbuo.png" alt="image-20240905144652" style="zoom:80%;" />

点击Register即可注册，支持常用邮箱（如果申请了协作者，最好是同一邮箱进行注册），可自行注册，所有步骤均是免费。



### （3）GBD数据介绍，包含变量类型，如何选择以及下载

数据包含了21个地区，204个国家，371个疾病及伤害，88个风险因素。最新数据GBD 2021于2024年5月18日公开，面向全球用户。

数据主要包含：

- **GBD Estimates**: <u>Causes of death or injury</u>, <u>Risk factor</u>, Etiology, Impairment, Summary exposure value (SEV), Healthy life expectancy (HALE), Injuries by nature, All-cause mortality, Fertility, <u>Population</u>
- **Measures**: <u>Deaths</u>, <u>Years of life lost (YLLs), Years lived with disability (YLDs), Disability-adjusted life years (DALYs), Prevalence, Incidence</u>, Maternal mortality ratio (MMR), Summary exposure value (SEV), Healthy life expectancy (HALE), Life expectancy (LE), Life table (LT), 5q0, 45q15, Age specific fertility rate (ASFR), Total fertility rate (TFR), Total fertility under 25 years (TFU25), Net reproductive rate (NRR), Live births, Crude birth rate, Population, Migration
- **Metrics**: <u>Number, Rate, Percent</u>, Years, Probability of death
- **Locations**: <u>GBD super regions, regions, countries</u>, select subnational units, custom regions (WHO regions, World Bank Income Levels, and more)
- **Ages**: <u>All GBD age groups</u>
- **Sexes**: <u>Male, Female, Both</u>
- **Years**: <u>1990–2021 (annual results for all measures)</u>

下划线部分！！！较为常用



例子：

**现在想研究：1990-2021年204个国家和地区女性食管癌年龄标化死亡率的疾病负担**

1）GBD Estimate: Cause of death or injury （疾病）；

<img src="https://s2.loli.net/2024/09/06/hvjqJYB1Gros84m.png" alt="image-20240905160705" style="zoom:80%;" />

2）Measure: Deaths（死亡数据）；

<img src="https://s2.loli.net/2024/09/06/3JBrpXQmSL9Zo5D.jpg" alt="image-20240905161224" style="zoom:80%;" />

3）Metric: Rate（率）；

<img src="https://s2.loli.net/2024/09/06/SLBC4zAybPms5F9.jpg" alt="image-20240905162104" style="zoom:80%;" />

4）Cause: Esophageal cancer (食管癌)；

<img src="https://s2.loli.net/2024/09/06/fj7w9RYAJ6dmqTa.jpg" alt="image-20240905161356" style="zoom:80%;" />

这里种类太多，可以在搜索框里输入要搜索疾病的英文名称，勾选即可；

5）Location: 点击Select all countries and territories即可选择204个国家；

<img src="https://s2.loli.net/2024/09/06/x32JCldwjXDZh8i.jpg" alt="image-20240905162352" style="zoom:80%;" />

6）Age: Age-standardized即可得到年龄标化率数据；

<img src="https://s2.loli.net/2024/09/06/UqTS3ny1e9WRf7z.jpg" alt="image-20240905162514" style="zoom:80%;" />

7）Sex: Female；

<img src="https://s2.loli.net/2024/09/06/LAnZUeGlyBioHgP.jpg" alt="image-20240905162626" style="zoom:80%;" />

8）Year：1990-2021；

<img src="https://s2.loli.net/2024/09/06/IVtEHlqorUcemRz.jpg" alt="image-20240905162725" style="zoom:80%;" />

9）点击Download，勾选Both（IDs，数据编号；Names，数据名称），再点击Submit；

<img src="https://s2.loli.net/2024/09/06/McZXTdAfUJKaLIp.png" alt="image-20240905162847" style="zoom:80%;" />

10）点击“here”或者邮箱链接转到数据下载页面；

<img src="https://s2.loli.net/2024/09/06/lxkFbm8JX9CKDpM.jpg" alt="image-20240905163505" style="zoom:80%;" />

<img src="https://s2.loli.net/2024/09/06/GyAP36utbxB7aQw.jpg" alt="image-20240905163251" style="zoom:80%;" />

点击Download即可下载数据，得到的数据类型通常是CSV格式，TXT文件通常是数据说明文件一般不用管；

![image-20240905163714](https://s2.loli.net/2024/09/06/YtSzX8CZD271Bg9.jpg)

<img src="https://s2.loli.net/2024/09/06/eFvIa8dRcUltnKN.jpg" alt="image-20240905163823" style="zoom:80%;" />

通过以上步骤即可得到CSV格式的原始数据，建议数据放在一个文件夹下，方便之后数据的读取。以下是得到的数据展示，

<img src="https://s2.loli.net/2024/09/06/6dzFwynxOtPKAqe.jpg" alt="image-20240905164052" style="zoom:80%;" />



### （4） GBD原始数据的导入，整合和简单结果呈现，基于R语言，代码实现

- 数据导入（**推荐代码写入**）


1）菜单栏式操作：Environment -> Import Dataset -> From Text (base)... 

<img src="https://s2.loli.net/2024/09/06/ezrICpUOAgEmtLQ.jpg" alt="image-20240905172002" style="zoom:80%;" />

找到数据存储路径双击，再点击Import即可，

<img src="https://s2.loli.net/2024/09/06/wpFU3m47ATi9WOq.jpg" alt="image-20240905172355" style="zoom:80%;" />

导入之后数据命名为Esophageal.cancer，之后对数据的引用即可用此名称，也可以后续自己更改名称

<img src="https://s2.loli.net/2024/09/06/BYcrHp6aPZulRNC.png" alt="image-20240905172445" style="zoom:80%;" />



2）代码运行 ***********：

```R
###数据读取
dat <- read.csv("XXX/Esophageal cancer.csv")  ###这里XXX表示文件路径，导入数据后并命名为“dat”
```

<img src="https://s2.loli.net/2024/09/06/PzsBMvuwkCLOqo1.png" alt="image-20240905172749" style="zoom:80%;" />

可以看到两种方式导入数据最终的结果是一致的，这里推荐代码写入，代码更加简单明了，同时也可以自命名数据名称。以下数据整理和分析均是采用代码写入的数据“dat”进行展示。



- 数据整理

```R
###查看导入数据变量
colnames(dat) ###呈现所有变量名称
```

<img src="https://s2.loli.net/2024/09/06/4UM7e8aKydFEPHq.png" alt="image-20240906113340" style="zoom:80%;" />

```R
###变量筛选及名称更改
dat <- dat[,c(2,4,6,8,10,12,13,14,16,15)] ###去除id列，一般只用name列,同时更改“upper”列和“lower”列的位置
colnames(dat) <- c('measure','location','sex',
                  'age','cause','metric',
                  'year','val','lower','upper') ###每列一一对应即可
head(dat) ###查看dat的前六行数据
```

<img src="https://s2.loli.net/2024/09/06/i2MUqx6FDrSLhA7.jpg" alt="image-20240906120804" style="zoom:80%;" />



- 结果呈现

```R
###1990年和2021年特定区域年龄标化率呈现（Table格式）
if (!require("tidyverse")) install.packages("tidyverse") ###装载必要的R包，如果已装载自动忽略
library(tidyverse) ###加载R包
###1990年数据整合
dat_1990 <- dat %>% #从dat数据集中提取，并赋予新数据集名称“dat_1990”
  filter(year == 1990 & #提取数据年份为1990
           measure == 'Deaths' & #提取关于死亡数据
           sex == 'Female' & #提取女性数据
           cause == 'Esophageal cancer' & #提取食管癌数据
           age =='Age-standardized' & #提取标化死亡率数据
           metric == 'Rate' #提取率的数据
  ) %>% 
  dplyr::select(,c(2,8,9,10)) #提取数据集中特定的列，数据表示第几列，这里提取了location，val，lower，upper

colnames(dat_1990) ###查看数据集dat_1990列名称

dat_1990$val <- round(dat_1990$val,2) ###val列值保留两位小数
dat_1990$lower <- round(dat_1990$lower,2) ###lower列值保留两位小数
dat_1990$upper <- round(dat_1990$upper,2) ###upper列值保留两位小数
dat_1990$'Deaths 1990 per 100,000 (95% UI)' <- paste(dat_1990$lower,dat_1990$upper,
                                                     sep = ' to ') ###创建新列，以 to 间隔连接
dat_1990$'Deaths 1990 per 100,000 (95% UI)' <- paste(dat_1990$'Deaths 1990 per 100,000 (95% UI)',
                                                     ')', sep = '') ###在新列上增加括号            
dat_1990$'Deaths 1990 per 100,000 (95% UI)' <- paste('(',dat_1990$'Deaths 1990 per 100,000 (95% UI)',
                                                     sep = '') ###在新列上增加括号 
dat_1990$'Deaths 1990 per 100,000 (95% UI)' <- paste(dat_1990$val,
                                                     dat_1990$'Deaths 1990 per 100,000 (95% UI)',
                                                     sep = ' ') ###在新列上增加数值，以空格连接

###提取数据集中特定的列创建新数据集ASR_1990，这里提取了location，Deaths 1990 per 100,000 (95% UI)
ASR_1990 <- dat_1990[,c(1,5)] 

###2021年数据整合
dat_2021 <- dat %>% #从dat数据集中提取，并赋予新数据集名称“dat_2021”
  filter(year == 2021 & #提取数据年份为2021
           measure == 'Deaths' & #提取关于死亡数据
           sex == 'Female' & #提取女性数据
           cause == 'Esophageal cancer' & #提取食管癌数据
           age =='Age-standardized' & #提取标化死亡率数据
           metric == 'Rate' #提取率的数据
  ) %>% 
  dplyr::select(,c(2,8,9,10)) #提取数据集中特定的列，这里提取了location，val，lower，upper

colnames(dat_2021) ###查看数据集dat_2021列名称

dat_2021$val <- round(dat_2021$val,2) ###val列值保留两位小数 
dat_2021$lower <- round(dat_2021$lower,2) ###lower列值保留两位小数
dat_2021$upper <- round(dat_2021$upper,2) ###lower列值保留两位小数
dat_2021$'Deaths 2021 per 100,000 (95% UI)' <- paste(dat_2021$lower,dat_2021$upper,
                                                     sep = ' to ') ###创建新列，以 to 间隔连接
dat_2021$'Deaths 2021 per 100,000 (95% UI)' <- paste(dat_2021$'Deaths 2021 per 100,000 (95% UI)',
                                                     ')', sep = '') ###在新列上增加括号            
dat_2021$'Deaths 2021 per 100,000 (95% UI)' <- paste('(',dat_2021$'Deaths 2021 per 100,000 (95% UI)',
                                                     sep = '') ###在新列上增加括号 
dat_2021$'Deaths 2021 per 100,000 (95% UI)' <- paste(dat_2021$val,
                                                     dat_2021$'Deaths 2021 per 100,000 (95% UI)',
                                                     sep = ' ') ###在新列上增加数值，以空格连接

###提取数据集中特定的列创建新数据集ASR_2021，这里提取了location，Deaths 2021 per 100,000 (95% UI)
ASR_2021 <- dat_2021[,c(1,5)] 

###数据合并
ASR <- ASR_1990 %>% 
  left_join(ASR_2021,by = "location") #合并数据集ASR_1990,ASR_2021，以location列为合并依据
head(ASR) ###查看数据前六行
```

|          location           | Deaths 1990 per 100,000 (95% UI) | Deaths 2021 per 100,000 (95% UI) |
| :-------------------------: | :------------------------------: | :------------------------------: |
|           Hungary           |       1.05 (0.95 to 1.16)        |        0.93 (0.79 to 1.1)        |
| Federal Republic of Germany |       1.23 (1.12 to 1.33)        |       1.42 (1.23 to 1.57)        |
|   Republic of Azerbaijan    |       6.17 (5.15 to 7.09)        |        3.7 (2.66 to 5.3)         |
|  Republic of South Africa   |       7.57 (5.35 to 11.04)       |       7.02 (5.96 to 8.58)        |
| Republic of the Philippines |        0.98 (0.8 to 1.36)        |        0.76 (0.6 to 1.09)        |
|     Argentine Republic      |       3.82 (3.48 to 4.12)        |       2.33 (2.05 to 2.57)        |

展现前六行结果，UI：Uncertainty Interval



```R
###1990-2021年特定区域年龄标化率趋势图（Figure格式）
p <- dat %>% 
  #选取六个国家数据，|表示或者
  filter(location == 'Hungary' |
           location == 'Federal Republic of Germany' |
           location == 'Republic of Azerbaijan' |
           location == 'Republic of South Africa' |
           location == 'Republic of the Philippines' |
           location == 'Argentine Republic'
         ) %>% 
  ggplot(aes(x=year,y=val)) + #ggplot绘图，指定x轴为年份，y轴为年龄标化率
  geom_line(color = '#4784b3') + #绘折线图，指定颜色
  geom_ribbon(aes(ymin=lower,ymax=upper), 
              fill = '#4784b3', alpha = .7) + #绘制条带图，指定上下区间和颜色，alpha是透明度
  facet_wrap(~location, scales = "free") + #依据location分组图，且轴不限制范围
  theme_minimal() + #指定主题类型
  labs(title = "Trends in age-standardized mortality rates 
among female esophageal cancer, 1990-2021", #Figure标题
       x = "Time (year)", #x轴标题
       y = "Age-standardized mortality rates #y轴标题
(per 100 000 people)") 

p #呈现Figure
```

<img src="https://s2.loli.net/2024/09/06/Q9bqvDps7zLHrk6.png" alt="ASR" style="zoom:80%;" />

Figure结果呈现



# 1 数据提取整理

##                                                         1.1 数据筛选和下载

**推荐：**纵览全文，边看边标记，主要标记研究的疾病种类，measure名称，metric种类，地区，年龄，性别以及年份跨度。

- 疾病数据

|     数据组别     | 数据筛选选项                                                                                                                     |
| :----------: | :------------------------------------------------------------------------------------------------------------------------- |
| GBD Estimate | Cause of death or injury                                                                                                   |
|   Measure    | 1) Prevalence <br/>2) Incidence <br/>3) Deaths <br/>4) DALYs (Disability-Adjusted Life years)                              |
|    Metric    | 1) Number <br/>2) Rate                                                                                                     |
|    Cause     | Ischemic stroke                                                                                                            |
|   Location   | 1) Global <br/>2) 5 SDI-level regions <br/>3) 21 GBD regions <br/>4) 204 countries and territories                         |
|     Age      | 1) <5 years, 5-9 years, 10-14 years,..., 90-94 years, 95+ years (every 5 years)  <br/>2) All ages <br/>3) Age-standardized |
|     Sex      | 1) Both <br/>2) Male <br/>3) Female                                                                                        |
|     Year     | 1990-2021 (single year; Not total percentage change)                                                                       |

- 风险因素数据

|     数据组别     | 数据筛选选项                                                                                         |
| :----------: | ---------------------------------------------------------------------------------------------- |
| GBD Estimate | Risk factor                                                                                    |
|   Measure    | 1) Deaths <br/>2) DALYs (Disability-Adjusted Life years)                                       |
|    Metric    | Percent                                                                                        |
|     Risk     | 1) High body-mass index <br/>2) High alcohol use <br/>3) Low physical activity <br/>4) Tobacco |
|    Cause     | Ischemic stroke                                                                                |
|   Location   | 1) Global <br/>2) 5 SDI-level regions <br/>3) 21 GBD regions                                   |
|     Age      | All ages                                                                                       |
|     Sex      | Both                                                                                           |
|     Year     | 2021                                                                                           |

- 注意：只保留CSV文件即可，TXT文件是说明文本

- 因疾病和风险因素数据略有差异，建议将两者数据分别置于两个文件夹下，便于数据的读取

  <img src="https://s2.loli.net/2024/09/09/qMEA6giSblBXUPd.jpg" alt="[image-20240909132234](https://s2.loli.net/2024/09/09/qMEA6giSblBXUPd.jpg)" style="zoom:80%;" />

  1）疾病数据

  <img src="https://s2.loli.net/2024/09/09/rjCXQyxLMVg9iOI.jpg" alt="[image-20240909132614](https://s2.loli.net/2024/09/09/rjCXQyxLMVg9iOI.jpg)" style="zoom:80%;" />

  2）风险因素数据

  ![[image-20240909132633](https://s2.loli.net/2024/09/09/omYqlErpcP6vhUJ.jpg)](https://s2.loli.net/2024/09/09/omYqlErpcP6vhUJ.jpg)

- 人口数据

  |   数据组别   | 数据筛选选项                                                 |
  | :----------: | ------------------------------------------------------------ |
  | GBD Estimate | Population                                                   |
  |   Measure    | Pop                                                          |
  |    Metric    | Number                                                       |
  |   Location   | Global                                                       |
  |     Age      | <5 years, 5-9 years, 10-14 years,..., 90-94 years, 95+ years (every 5 years) |
  |     Sex      | Both，Male，Female                                           |
  |     Year     | 1990-2021（single year）                                     |

  ![image-renkou](https://s2.loli.net/2024/09/18/UAOY3724hZbidjP.jpg)

- 标准化人口数据

  ![age-standard](https://s2.loli.net/2024/09/18/3tycf2TupwhMPEd.jpg)

  <img src="https://s2.loli.net/2024/09/18/UkJuYC2fvjS8DHA.jpg" alt="age" style="zoom:80%;" />

- 预测人口数据

  ![forest](https://s2.loli.net/2024/09/18/KS4Yoqrx69QPJeR.jpg)

  

##                                                         1.2 数据读入

**代码实操：**

这里提供两种代码方式：

```R
setwd("XXX") ###设置路径，XXX文件路径

if (!require('dplyr')) install.packages('dplyr') ###判定R包是否存在，不存在则自动下载，存在则自动忽略
if (!require('purrr')) install.packages('purrr') 
library(dplyr) ###加载R包
library(purrr) ###加载R包，应用map_dfr函数

###方法一：逐个读取写入
###利用read.csv函数逐个读取csv文件
dat1 <- read.csv("Disease\\IHME-GBD_2021_DATA-0462492e-1.csv")
dat2 <- read.csv("Disease\\IHME-GBD_2021_DATA-0462492e-2.csv")
dat3 <- read.csv("Disease\\IHME-GBD_2021_DATA-0462492e-3.csv")
dat4 <- read.csv("Disease\\IHME-GBD_2021_DATA-0462492e-4.csv")
dat5 <- read.csv("Disease\\IHME-GBD_2021_DATA-0462492e-5.csv")
dat6 <- read.csv("Disease\\IHME-GBD_2021_DATA-0462492e-6.csv")
dat7 <- read.csv("Disease\\IHME-GBD_2021_DATA-0462492e-7.csv")
dat8 <- read.csv("Disease\\IHME-GBD_2021_DATA-0462492e-8.csv")

dat <- dat1 %>% 
  rbind(dat2) %>% 
  rbind(dat3) %>% 
  rbind(dat4) %>% 
  rbind(dat5) %>% 
  rbind(dat6) %>% 
  rbind(dat7) %>% 
  rbind(dat8)  ###将逐个读取的文件纵向合并成一个数据集dat

risk <- read.csv("Risk factor\\IHME-GBD_2021_DATA-f9ceaf1b-1.csv") ###读取风险因素数据


###方法二：借助map函数批量读取
dir <- "XXX"  ###创建文件所在路径
files <- list.files(dir,
                    pattern = ".csv",
                    full.names = T)  ###设置读取文件格式
data <- map_dfr(files,read.csv)  ###批量读取文件，自动合并

risk <- read.csv("Risk factor\\IHME-GBD_2021_DATA-f9ceaf1b-1.csv") ###读取风险因素数据





### 读取标准化人口数据
age_stand <- read.xlsx('Age standard.xlsx') 
###计算各年龄层标准人口占比
agestand <- c(age_stand$Percent_Population %>% as.numeric())/sum(age_stand$Percent_Population)





#### 读取预测人口数据
GBD_population_prediction <- fread('IHME_POP_2017_2100_POP_REFERENCE_Y2020M05D01.csv')
```



数据读取结果：

<img src="https://s2.loli.net/2024/09/09/ucweOAsgrzU9VJS.jpg" alt="image-20240909141536" style="zoom:80%;" />

可见dat和data数据结果是一致的，所以这里推荐方法二；在少数数据文件时两种方法均可

```R
###R中查看具体数据
View(data) ###或者View(dat)
View(risk)
```

1）疾病数据

<img src="https://s2.loli.net/2024/09/09/JuKQi7BgvfX2jc4.jpg" alt="image-20240909142158" style="zoom:80%;" />

2）风险因素数据

<img src="https://s2.loli.net/2024/09/09/nUvzdE5seH7TpIq.jpg" alt="image-20240909142249" style="zoom:80%;" />



##                                                         1.3 数据整理

**代码实操：**

```R
###疾病数据
###简单查看数据格式类型
head(data) ###查看数据前六行
colnames(data) ###查看数据列名称
IS <- data %>% ###赋予新数据集
  dplyr::select(measure_name,location_name,metric_name,
                sex_name,age_name,year,val,lower,upper) %>% ###提取需要的变量
  rename(measure=measure_name,
         location=location_name,
         metric=metric_name,
         sex=sex_name,
         age=age_name) ###复杂列名进行更改简化
View(IS) ###查看数据
```

1）整理后疾病数据

<img src="https://s2.loli.net/2024/09/09/8KRQqIJxYdF6yel.jpg" alt="image-20240909150231" style="zoom:80%;" />



```R
###风险因素数据
###简单查看数据格式类型
head(risk) ###查看数据前六行
colnames(risk) ###查看数据列名称
RF <- risk %>% ###赋予新数据集
  dplyr::select(measure_name,location_name,metric_name,
                sex_name,age_name,rei_name,year,
                val,lower,upper) %>% ###提取需要的变量
  rename(measure=measure_name,
         location=location_name,
         metric=metric_name,
         sex=sex_name,
         age=age_name,
         rei=rei_name) %>% ###复杂列名进行更改简化
  mutate(across('rei', str_replace, 'Alcohol use', 'High alcohol use')) ###rei列用“High alcohol use”替换“Alcohol use”
View(RF) ###查看数据
```

2）整理后风险因素数据

<img src="https://s2.loli.net/2024/09/09/iWn4xbr8ztOF2LM.jpg" alt="image-20240909153057" style="zoom:80%;" />



# 2 趋势图 已完成.

**文献原Figure 1：**

<img src="https://s2.loli.net/2024/09/09/PI9BzckTe82MRwn.jpg" alt="gr1" style="zoom:80%;" />



**代码实操：**

```R
###装载和加载R包
if (!require('dplyr')) install.packages('dplyr')
if (!require('ggplot2')) install.packages('ggplot2')
if (!require('ggsci')) install.packages('ggsci')
if (!require('scales')) install.packages('scales')
library(dplyr)
library(ggplot2)
library(ggsci)
library(scales)

IS_1 <- IS %>% #重新创建IS_1数据集
  #提取年龄标化率
  filter(age=="Age-standardized" & 
           metric=="Rate") %>% 
  #提取特定地区
  filter(location=="Global" |
           location=="High SDI" |
           location=="High-middle SDI" |
           location=="Middle SDI" |
           location=="Low-middle SDI" |
           location=="Low SDI")

###在数据集IS_1里建立新列“group”，方便后续绘图分组
IS_1$group <- ifelse(
  IS_1$sex=="Both"&IS_1$measure=="Prevalence",'a',ifelse(
    IS_1$sex=="Both"&IS_1$measure=="Incidence",'b',ifelse(
      IS_1$sex=="Both"&IS_1$measure=="Deaths",'c',ifelse(
        IS_1$sex=="Both"&IS_1$measure=="DALYs (Disability-Adjusted Life Years)",'d',ifelse(
          IS_1$sex=="Male"&IS_1$measure=="Prevalence",'e',ifelse(
            IS_1$sex=="Male"&IS_1$measure=="Incidence",'f',ifelse(
              IS_1$sex=="Male"&IS_1$measure=="Deaths",'g',ifelse(
                IS_1$sex=="Male"&IS_1$measure=="DALYs (Disability-Adjusted Life Years)",'h',ifelse(
                  IS_1$sex=="Female"&IS_1$measure=="Prevalence",'i',ifelse(
                    IS_1$sex=="Female"&IS_1$measure=="Incidence",'j',ifelse(
                      IS_1$sex=="Female"&IS_1$measure=="Deaths",'k','l')))))))))))

###利用ggplot进行绘图
p <- ggplot(data=IS_1,aes(x=year,y=val)) + #绘图数据集是IS_1,确定x轴是年份，y轴是年龄标化率
  geom_line(aes(color=location)) + #增加图层，绘制折线图，以location分组分配颜色
  geom_point(aes(color=location)) + #增加图层，绘制散点图，以location分组分配颜色
  scale_color_manual(values=pal_lancet(palette = c("lanonc"), alpha = 1)(6)[c(1,3,2,5,6,4)]) + #选取lancet期刊配色
  #分组绘图
  facet_wrap(~group,scales="free_y", #以之前建立的group为依据分组，且y轴范围不固定
             ncol = 4, #限定分组绘图为4列
             #更改每个图的标题
             labeller = labeller(group=c(
               a="Both-ASPR per 100,000",
               b="Both-ASIR per 100,000",
               c="Both-ASDR per 100,000",
               d="Both-DALYs per 100,000",
               e="Male-ASPR per 100,000",
               f="Male-ASIR per 100,000",
               g="Male-ASDR per 100,000",
               h="Male-DALYs per 100,000",
               i="Female-ASPR per 100,000",
               j="Female-ASIR per 100,000",
               k="Female-ASDR per 100,000",
               l="Female-DALYs per 100,000"
             )))+
  theme_bw() + #主题类型
  theme(
  #设置组图标题的字体
  strip.text.x = element_text(size = 10, #大小
                              color = "#ada072", #颜色
                              face = "bold"), #加粗
  #设置组图标题框
  strip.background = element_rect(colour = "black", #标题框边框框颜色
                                   fill = "#eeecdf"), #标题框填充色
  axis.title = element_blank(), #取消横纵轴标题
  legend.title = element_blank(), #取消图例标题
  legend.position = "top") + #将图例设置在顶部
  #设置图例内容的排列方式
  guides(
    color = guide_legend(
      nrow= 1, #设置为一行
      byrow= T #按行排列
    )
  )
p ###查看图片

###保存为png格式
png("XXX\\p.png",width = 800, height = 800, units = "px") ###设置图片格式，XXX是保存的路径
p ###保存的图片
dev.off() ###结束运行

###保存为jpg格式
jpeg("XXX\\p.jpg",width = 800, height = 800, units = "px") ###设置图片格式，XXX是保存的路径
p ###保存的图片
dev.off() ###结束运行

###保存为tiff格式
tiff("XXX\\p.tiff",width = 800, height = 800, units = "px") ###设置图片格式，XXX是保存的路径
p ###保存的图片
dev.off() ###结束运行
```



**绘图结果：**

<img src="https://s2.loli.net/2024/09/11/rogmjzG9QqF6v3k.png" alt="p.png" style="zoom:80%;" />



# 3 趋势表

**文献原Table 1（部分结果）：**

<img src="https://s2.loli.net/2024/09/11/vIizgKwrLFT2pNm.jpg" alt="Table 1" style="zoom:80%;" />

注：这里原文献中的EAPC 95%CI结果呈现有误。



**代码实操：**

```R
###Prevalence
###Number
###1990 Prevalence
IS_1990 <- IS %>%  #创建新数据集
  #筛选变量
  filter(year==1990 &  #年份
           age =='All ages' & #年龄
           metric == 'Number' & #绝对例数
           measure =='Prevalence' & #患病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_1990$val <- round(IS_1990$val,1)  
IS_1990$lower <- round(IS_1990$lower,1)
IS_1990$upper <- round(IS_1990$upper,1) 
###IS_1990数据创建新列
IS_1990$'Number  1990' <- paste(IS_1990$lower,IS_1990$upper,sep = '-') 
IS_1990$'Number  1990' <- paste(IS_1990$'Number  1990',')',sep = '')             
IS_1990$'Number  1990' <- paste('(',IS_1990$'Number  1990',sep = '')  
IS_1990$'Number  1990' <- paste(IS_1990$val,IS_1990$'Number  1990',sep = ' ') 
Prevalence_Num_1990 <- IS_1990[,c(1,5)] ###筛选location和Number 1990两列
head(Prevalence_Num_1990) ###查看数据前六列

## 2021 Prevalence
IS_2021 <- IS %>% #创建新数据集
  #筛选变量
  filter(year ==2021 & #年份
           age =='All ages' & #年龄
           metric == 'Number' & #绝对例数
           measure  =='Prevalence' & #患病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_2021$val <- round(IS_2021$val,1)  
IS_2021$lower <- round(IS_2021$lower,1)
IS_2021$upper <- round(IS_2021$upper,1) 
###IS_2021数据创建新列
IS_2021$'Number  2021' <- paste(IS_2021$lower,IS_2021$upper,sep = '-') 
IS_2021$'Number  2021' <- paste(IS_2021$'Number  2021',')',sep = '')             
IS_2021$'Number  2021' <- paste('(',IS_2021$'Number  2021',sep = '')  
IS_2021$'Number  2021' <- paste(IS_2021$val,IS_2021$'Number  2021',sep = ' ') 
Prevalence_Num_2021 <- IS_2021[,c(1,5)] ###筛选location和Number 2021两列
head(Prevalence_Num_2021) ###查看数据前六列



##### Age-standardized rates
## 1990 Prevalence
IS_1990 <- IS %>% #创建新数据集
  #筛选变量
  filter(year==1990 & #年份
           age =='Age-standardized' & #年龄
           metric == 'Rate' & #率
           measure =='Prevalence' & #患病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_1990$val <- round(IS_1990$val,1)  
IS_1990$lower <- round(IS_1990$lower,1)
IS_1990$upper <- round(IS_1990$upper,1) 
###IS_2021数据创建新列
IS_1990$'ASR  1990' <- paste(IS_1990$lower,IS_1990$upper,sep = '-') 
IS_1990$'ASR  1990' <- paste(IS_1990$'ASR  1990',')',sep = '')             
IS_1990$'ASR  1990' <- paste('(',IS_1990$'ASR  1990',sep = '')  
IS_1990$'ASR  1990' <- paste(IS_1990$val,IS_1990$'ASR  1990',sep = ' ') 
Prevalence_ASR_1990 <- IS_1990[,c(1,5)] ###筛选location和ASR 2021两列
head(Prevalence_ASR_1990) ###查看数据前六列

## 2021 Prevalence
IS_2021 <- IS %>% #创建新数据集
  filter(year ==2021 & #年份
           age =='Age-standardized' & #年龄
           metric == 'Rate' & #率
           measure  =='Prevalence' & #患病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_2021$val <- round(IS_2021$val,1)  
IS_2021$lower <- round(IS_2021$lower,1)
IS_2021$upper <- round(IS_2021$upper,1) 
###IS_2021数据创建新列
IS_2021$'ASR  2021' <- paste(IS_2021$lower,IS_2021$upper,sep = '-') 
IS_2021$'ASR  2021' <- paste(IS_2021$'ASR  2021',')',sep = '')             
IS_2021$'ASR  2021' <- paste('(',IS_2021$'ASR  2021',sep = '')  
IS_2021$'ASR  2021' <- paste(IS_2021$val,IS_2021$'ASR  2021',sep = ' ') 
Prevalence_ASR_2021 <- IS_2021[,c(1,5)] ###筛选location和ASR 2021两列
head(Prevalence_ASR_2021) ###查看数据前六列


##### EAPC
Prevalence_EAPC <- IS %>% #创建新数据集
  #筛选变量
  filter(age =='Age-standardized' &  #年龄
           metric == 'Rate' & #率
           measure =='Prevalence'& #患病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,6,7)) #筛选location，year，val列

nations <- IS_1990$location ###将IS_1990地区赋予nations
###创建数据框EAPC_Prevalence，四列location，EAPC，UCI，LCI
EAPC_Prevalence <- data.frame(location=nations,EAPC=rep(0,times=27),UCI=rep(0,times=27),LCI=rep(0,times=27))

###利用for循环，计算EAPC，并将最终产生的数据整合到EAPC_Prevalence数据集中
for (i in 1:nrow(EAPC_Prevalence)){
  nation <- as.character(EAPC_Prevalence[i,1])
  a <- subset(Prevalence_EAPC, Prevalence_EAPC$location==nation)
  a$y <- log(a$val)
  mod_simp_reg<-lm(y~year,data=a)
  estimate <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1])-1)*100
  low <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1]-1.96*summary(mod_simp_reg)[["coefficients"]][2,2])-1)*100
  high <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1]+1.96*summary(mod_simp_reg)[["coefficients"]][2,2])-1)*100
  EAPC_Prevalence[i,2] <- estimate
  EAPC_Prevalence[i,4] <- low
  EAPC_Prevalence[i,3] <- high
}

#保留两位小数
EAPC_Prevalence$EAPC <- round(EAPC_Prevalence$EAPC,2)
EAPC_Prevalence$UCI <- round(EAPC_Prevalence$UCI,2)
EAPC_Prevalence$LCI <- round(EAPC_Prevalence$LCI,2)
###EAPC_Prevalence数据创建新列
EAPC_Prevalence$'EAPC_95%CI' <- paste(EAPC_Prevalence$LCI,EAPC_Prevalence$UCI,sep = ' to ')
EAPC_Prevalence$'EAPC_95%CI' <- paste(EAPC_Prevalence$'EAPC_95%CI',')',sep = '')
EAPC_Prevalence$'EAPC_95%CI' <- paste('(',EAPC_Prevalence$'EAPC_95%CI',sep = '')
EAPC_Prevalence$'EAPC_95%CI' <- paste(EAPC_Prevalence$EAPC,EAPC_Prevalence$'EAPC_95%CI',sep = ' ')
EAPC_Prevalence <- EAPC_Prevalence[,c(1,5)] ###筛选location和EAPC_95%CI两列

Prevalence <- Prevalence_Num_1990 %>% 
  left_join(Prevalence_ASR_1990,by='location') %>%
  left_join(Prevalence_Num_2021,by='location') %>% 
  left_join(Prevalence_ASR_2021,by='location') %>%
  left_join(EAPC_Prevalence,by='location') %>% 
  arrange(location) ###将上述四个数据集横向合并，并按照location排序，创建新数据集Prevalence
View(Prevalence) ###查看Prevalence数据集




###Incidence
###Number
###1990 Incidence
IS_1990 <- IS %>%  #创建新数据集
  #筛选变量
  filter(year==1990 &  #年份
           age =='All ages' & #年龄
           metric == 'Number' & #绝对例数
           measure =='Incidence' & #发病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_1990$val <- round(IS_1990$val,1)  
IS_1990$lower <- round(IS_1990$lower,1)
IS_1990$upper <- round(IS_1990$upper,1) 
###IS_1990数据创建新列
IS_1990$'Number  1990' <- paste(IS_1990$lower,IS_1990$upper,sep = '-') 
IS_1990$'Number  1990' <- paste(IS_1990$'Number  1990',')',sep = '')             
IS_1990$'Number  1990' <- paste('(',IS_1990$'Number  1990',sep = '')  
IS_1990$'Number  1990' <- paste(IS_1990$val,IS_1990$'Number  1990',sep = ' ') 
Incidence_Num_1990 <- IS_1990[,c(1,5)] ###筛选location和Number 1990两列
head(Incidence_Num_1990) ###查看数据前六列

## 2021 Incidence
IS_2021 <- IS %>% #创建新数据集
  #筛选变量
  filter(year ==2021 & #年份
           age =='All ages' & #年龄
           metric == 'Number' & #绝对例数
           measure  =='Incidence' & #发病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_2021$val <- round(IS_2021$val,1)  
IS_2021$lower <- round(IS_2021$lower,1)
IS_2021$upper <- round(IS_2021$upper,1) 
###IS_2021数据创建新列
IS_2021$'Number  2021' <- paste(IS_2021$lower,IS_2021$upper,sep = '-') 
IS_2021$'Number  2021' <- paste(IS_2021$'Number  2021',')',sep = '')             
IS_2021$'Number  2021' <- paste('(',IS_2021$'Number  2021',sep = '')  
IS_2021$'Number  2021' <- paste(IS_2021$val,IS_2021$'Number  2021',sep = ' ') 
Incidence_Num_2021 <- IS_2021[,c(1,5)] ###筛选location和Number 2021两列
head(Incidence_Num_2021) ###查看数据前六列



##### Age-standardized rates
## 1990 Incidence
IS_1990 <- IS %>% #创建新数据集
  #筛选变量
  filter(year==1990 & #年份
           age =='Age-standardized' & #年龄
           metric == 'Rate' & #率
           measure =='Incidence' & #发病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_1990$val <- round(IS_1990$val,1)  
IS_1990$lower <- round(IS_1990$lower,1)
IS_1990$upper <- round(IS_1990$upper,1) 
###IS_2021数据创建新列
IS_1990$'ASR  1990' <- paste(IS_1990$lower,IS_1990$upper,sep = '-') 
IS_1990$'ASR  1990' <- paste(IS_1990$'ASR  1990',')',sep = '')             
IS_1990$'ASR  1990' <- paste('(',IS_1990$'ASR  1990',sep = '')  
IS_1990$'ASR  1990' <- paste(IS_1990$val,IS_1990$'ASR  1990',sep = ' ') 
Incidence_ASR_1990 <- IS_1990[,c(1,5)] ###筛选location和ASR 2021两列
head(Incidence_ASR_1990) ###查看数据前六列

## 2021 Incidence
IS_2021 <- IS %>% #创建新数据集
  filter(year ==2021 & #年份
           age =='Age-standardized' & #年龄
           metric == 'Rate' & #率
           measure  =='Incidence' & #发病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_2021$val <- round(IS_2021$val,1)  
IS_2021$lower <- round(IS_2021$lower,1)
IS_2021$upper <- round(IS_2021$upper,1) 
###IS_2021数据创建新列
IS_2021$'ASR  2021' <- paste(IS_2021$lower,IS_2021$upper,sep = '-') 
IS_2021$'ASR  2021' <- paste(IS_2021$'ASR  2021',')',sep = '')             
IS_2021$'ASR  2021' <- paste('(',IS_2021$'ASR  2021',sep = '')  
IS_2021$'ASR  2021' <- paste(IS_2021$val,IS_2021$'ASR  2021',sep = ' ') 
Incidence_ASR_2021 <- IS_2021[,c(1,5)] ###筛选location和ASR 2021两列
head(Incidence_ASR_2021) ###查看数据前六列


##### EAPC
Incidence_EAPC <- IS %>% #创建新数据集
  #筛选变量
  filter(age =='Age-standardized' &  #年龄
           metric == 'Rate' & #率
           measure =='Incidence'& #发病率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,6,7)) #筛选location，year，val列

nations <- IS_1990$location ###将IS_1990地区赋予nations
###创建数据框EAPC_Incidence，四列location，EAPC，UCI，LCI
EAPC_Incidence <- data.frame(location=nations,EAPC=rep(0,times=27),UCI=rep(0,times=27),LCI=rep(0,times=27))

###利用for循环，计算EAPC，并将最终产生的数据整合到EAPC_Incidence数据集中
for (i in 1:nrow(EAPC_Incidence)){
  nation <- as.character(EAPC_Incidence[i,1])
  a <- subset(Incidence_EAPC, Incidence_EAPC$location==nation)
  a$y <- log(a$val)
  mod_simp_reg<-lm(y~year,data=a)
  estimate <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1])-1)*100
  low <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1]-1.96*summary(mod_simp_reg)[["coefficients"]][2,2])-1)*100
  high <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1]+1.96*summary(mod_simp_reg)[["coefficients"]][2,2])-1)*100
  EAPC_Incidence[i,2] <- estimate
  EAPC_Incidence[i,4] <- low
  EAPC_Incidence[i,3] <- high
}

#保留两位小数
EAPC_Incidence$EAPC <- round(EAPC_Incidence$EAPC,2)
EAPC_Incidence$UCI <- round(EAPC_Incidence$UCI,2)
EAPC_Incidence$LCI <- round(EAPC_Incidence$LCI,2)
###EAPC_Incidence数据创建新列
EAPC_Incidence$'EAPC_95%CI' <- paste(EAPC_Incidence$LCI,EAPC_Incidence$UCI,sep = ' to ')
EAPC_Incidence$'EAPC_95%CI' <- paste(EAPC_Incidence$'EAPC_95%CI',')',sep = '')
EAPC_Incidence$'EAPC_95%CI' <- paste('(',EAPC_Incidence$'EAPC_95%CI',sep = '')
EAPC_Incidence$'EAPC_95%CI' <- paste(EAPC_Incidence$EAPC,EAPC_Incidence$'EAPC_95%CI',sep = ' ')
EAPC_Incidence <- EAPC_Incidence[,c(1,5)] ###筛选location和EAPC_95%CI两列

Incidence <- Incidence_Num_1990 %>% 
  left_join(Incidence_ASR_1990,by='location') %>%
  left_join(Incidence_Num_2021,by='location') %>% 
  left_join(Incidence_ASR_2021,by='location') %>%
  left_join(EAPC_Incidence,by='location') %>% 
  arrange(location) ###将上述四个数据集横向合并，并按照location排序，创建新数据集Incidence
View(Incidence) ###查看Incidence数据集



###Deaths
###Number
###1990 Deaths
IS_1990 <- IS %>%  #创建新数据集
  #筛选变量
  filter(year==1990 &  #年份
           age =='All ages' & #年龄
           metric == 'Number' & #绝对例数
           measure =='Deaths' & #死亡率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_1990$val <- round(IS_1990$val,1)  
IS_1990$lower <- round(IS_1990$lower,1)
IS_1990$upper <- round(IS_1990$upper,1) 
###IS_1990数据创建新列
IS_1990$'Number  1990' <- paste(IS_1990$lower,IS_1990$upper,sep = '-') 
IS_1990$'Number  1990' <- paste(IS_1990$'Number  1990',')',sep = '')             
IS_1990$'Number  1990' <- paste('(',IS_1990$'Number  1990',sep = '')  
IS_1990$'Number  1990' <- paste(IS_1990$val,IS_1990$'Number  1990',sep = ' ') 
Deaths_Num_1990 <- IS_1990[,c(1,5)] ###筛选location和Number 1990两列
head(Deaths_Num_1990) ###查看数据前六列

## 2021 Deaths
IS_2021 <- IS %>% #创建新数据集
  #筛选变量
  filter(year ==2021 & #年份
           age =='All ages' & #年龄
           metric == 'Number' & #绝对例数
           measure  =='Deaths' & #死亡率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_2021$val <- round(IS_2021$val,1)  
IS_2021$lower <- round(IS_2021$lower,1)
IS_2021$upper <- round(IS_2021$upper,1) 
###IS_2021数据创建新列
IS_2021$'Number  2021' <- paste(IS_2021$lower,IS_2021$upper,sep = '-') 
IS_2021$'Number  2021' <- paste(IS_2021$'Number  2021',')',sep = '')             
IS_2021$'Number  2021' <- paste('(',IS_2021$'Number  2021',sep = '')  
IS_2021$'Number  2021' <- paste(IS_2021$val,IS_2021$'Number  2021',sep = ' ') 
Deaths_Num_2021 <- IS_2021[,c(1,5)] ###筛选location和Number 2021两列
head(Deaths_Num_2021) ###查看数据前六列



##### Age-standardized rates
## 1990 Deaths
IS_1990 <- IS %>% #创建新数据集
  #筛选变量
  filter(year==1990 & #年份
           age =='Age-standardized' & #年龄
           metric == 'Rate' & #率
           measure =='Deaths' & #死亡率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_1990$val <- round(IS_1990$val,1)  
IS_1990$lower <- round(IS_1990$lower,1)
IS_1990$upper <- round(IS_1990$upper,1) 
###IS_2021数据创建新列
IS_1990$'ASR  1990' <- paste(IS_1990$lower,IS_1990$upper,sep = '-') 
IS_1990$'ASR  1990' <- paste(IS_1990$'ASR  1990',')',sep = '')             
IS_1990$'ASR  1990' <- paste('(',IS_1990$'ASR  1990',sep = '')  
IS_1990$'ASR  1990' <- paste(IS_1990$val,IS_1990$'ASR  1990',sep = ' ') 
Deaths_ASR_1990 <- IS_1990[,c(1,5)] ###筛选location和ASR 2021两列
head(Deaths_ASR_1990) ###查看数据前六列

## 2021 Deaths
IS_2021 <- IS %>% #创建新数据集
  filter(year ==2021 & #年份
           age =='Age-standardized' & #年龄
           metric == 'Rate' & #率
           measure  =='Deaths' & #死亡率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_2021$val <- round(IS_2021$val,1)  
IS_2021$lower <- round(IS_2021$lower,1)
IS_2021$upper <- round(IS_2021$upper,1) 
###IS_2021数据创建新列
IS_2021$'ASR  2021' <- paste(IS_2021$lower,IS_2021$upper,sep = '-') 
IS_2021$'ASR  2021' <- paste(IS_2021$'ASR  2021',')',sep = '')             
IS_2021$'ASR  2021' <- paste('(',IS_2021$'ASR  2021',sep = '')  
IS_2021$'ASR  2021' <- paste(IS_2021$val,IS_2021$'ASR  2021',sep = ' ') 
Deaths_ASR_2021 <- IS_2021[,c(1,5)] ###筛选location和ASR 2021两列
head(Deaths_ASR_2021) ###查看数据前六列


##### EAPC
Deaths_EAPC <- IS %>% #创建新数据集
  #筛选变量
  filter(age =='Age-standardized' &  #年龄
           metric == 'Rate' & #率
           measure =='Deaths'& #死亡率数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,6,7)) #筛选location，year，val列

nations <- IS_1990$location ###将IS_1990地区赋予nations
###创建数据框EAPC_Deaths，四列location，EAPC，UCI，LCI
EAPC_Deaths <- data.frame(location=nations,EAPC=rep(0,times=27),UCI=rep(0,times=27),LCI=rep(0,times=27))

###利用for循环，计算EAPC，并将最终产生的数据整合到EAPC_Deaths数据集中
for (i in 1:nrow(EAPC_Deaths)){
  nation <- as.character(EAPC_Deaths[i,1])
  a <- subset(Deaths_EAPC, Deaths_EAPC$location==nation)
  a$y <- log(a$val)
  mod_simp_reg<-lm(y~year,data=a)
  estimate <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1])-1)*100
  low <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1]-1.96*summary(mod_simp_reg)[["coefficients"]][2,2])-1)*100
  high <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1]+1.96*summary(mod_simp_reg)[["coefficients"]][2,2])-1)*100
  EAPC_Deaths[i,2] <- estimate
  EAPC_Deaths[i,4] <- low
  EAPC_Deaths[i,3] <- high
}

#保留两位小数
EAPC_Deaths$EAPC <- round(EAPC_Deaths$EAPC,2)
EAPC_Deaths$UCI <- round(EAPC_Deaths$UCI,2)
EAPC_Deaths$LCI <- round(EAPC_Deaths$LCI,2)
###EAPC_Deaths数据创建新列
EAPC_Deaths$'EAPC_95%CI' <- paste(EAPC_Deaths$LCI,EAPC_Deaths$UCI,sep = ' to ')
EAPC_Deaths$'EAPC_95%CI' <- paste(EAPC_Deaths$'EAPC_95%CI',')',sep = '')
EAPC_Deaths$'EAPC_95%CI' <- paste('(',EAPC_Deaths$'EAPC_95%CI',sep = '')
EAPC_Deaths$'EAPC_95%CI' <- paste(EAPC_Deaths$EAPC,EAPC_Deaths$'EAPC_95%CI',sep = ' ')
EAPC_Deaths <- EAPC_Deaths[,c(1,5)] ###筛选location和EAPC_95%CI两列

Deaths <- Deaths_Num_1990 %>% 
  left_join(Deaths_ASR_1990,by='location') %>%
  left_join(Deaths_Num_2021,by='location') %>% 
  left_join(Deaths_ASR_2021,by='location') %>%
  left_join(EAPC_Deaths,by='location') %>% 
  arrange(location) ###将上述四个数据集横向合并，并按照location排序，创建新数据集Deaths
View(Deaths) ###查看Deaths数据集



###DALYs
###Number
###1990 DALYs
IS_1990 <- IS %>%  #创建新数据集
  #筛选变量
  filter(year==1990 &  #年份
           age =='All ages' & #年龄
           metric == 'Number' & #绝对例数
           measure =='DALYs (Disability-Adjusted Life Years)' & #DALYs数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_1990$val <- round(IS_1990$val,1)  
IS_1990$lower <- round(IS_1990$lower,1)
IS_1990$upper <- round(IS_1990$upper,1) 
###IS_1990数据创建新列
IS_1990$'Number  1990' <- paste(IS_1990$lower,IS_1990$upper,sep = '-') 
IS_1990$'Number  1990' <- paste(IS_1990$'Number  1990',')',sep = '')             
IS_1990$'Number  1990' <- paste('(',IS_1990$'Number  1990',sep = '')  
IS_1990$'Number  1990' <- paste(IS_1990$val,IS_1990$'Number  1990',sep = ' ') 
DALYs_Num_1990 <- IS_1990[,c(1,5)] ###筛选location和Number 1990两列
head(DALYs_Num_1990) ###查看数据前六列

## 2021 DALYs
IS_2021 <- IS %>% #创建新数据集
  #筛选变量
  filter(year ==2021 & #年份
           age =='All ages' & #年龄
           metric == 'Number' & #绝对例数
           measure  =='DALYs (Disability-Adjusted Life Years)' & #DALYs数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_2021$val <- round(IS_2021$val,1)  
IS_2021$lower <- round(IS_2021$lower,1)
IS_2021$upper <- round(IS_2021$upper,1) 
###IS_2021数据创建新列
IS_2021$'Number  2021' <- paste(IS_2021$lower,IS_2021$upper,sep = '-') 
IS_2021$'Number  2021' <- paste(IS_2021$'Number  2021',')',sep = '')             
IS_2021$'Number  2021' <- paste('(',IS_2021$'Number  2021',sep = '')  
IS_2021$'Number  2021' <- paste(IS_2021$val,IS_2021$'Number  2021',sep = ' ') 
DALYs_Num_2021 <- IS_2021[,c(1,5)] ###筛选location和Number 2021两列
head(DALYs_Num_2021) ###查看数据前六列



##### Age-standardized rates
## 1990 DALYs
IS_1990 <- IS %>% #创建新数据集
  #筛选变量
  filter(year==1990 & #年份
           age =='Age-standardized' & #年龄
           metric == 'Rate' & #率
           measure =='DALYs (Disability-Adjusted Life Years)' & #DALYs数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_1990$val <- round(IS_1990$val,1)  
IS_1990$lower <- round(IS_1990$lower,1)
IS_1990$upper <- round(IS_1990$upper,1) 
###IS_2021数据创建新列
IS_1990$'ASR  1990' <- paste(IS_1990$lower,IS_1990$upper,sep = '-') 
IS_1990$'ASR  1990' <- paste(IS_1990$'ASR  1990',')',sep = '')             
IS_1990$'ASR  1990' <- paste('(',IS_1990$'ASR  1990',sep = '')  
IS_1990$'ASR  1990' <- paste(IS_1990$val,IS_1990$'ASR  1990',sep = ' ') 
DALYs_ASR_1990 <- IS_1990[,c(1,5)] ###筛选location和ASR 2021两列
head(DALYs_ASR_1990) ###查看数据前六列

## 2021 DALYs
IS_2021 <- IS %>% #创建新数据集
  filter(year ==2021 & #年份
           age =='Age-standardized' & #年龄
           metric == 'Rate' & #率
           measure  =='DALYs (Disability-Adjusted Life Years)' & #DALYs数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,7:9)) #筛选location，val，lower和upper列

###数据保留一位小数
IS_2021$val <- round(IS_2021$val,1)  
IS_2021$lower <- round(IS_2021$lower,1)
IS_2021$upper <- round(IS_2021$upper,1) 
###IS_2021数据创建新列
IS_2021$'ASR  2021' <- paste(IS_2021$lower,IS_2021$upper,sep = '-') 
IS_2021$'ASR  2021' <- paste(IS_2021$'ASR  2021',')',sep = '')             
IS_2021$'ASR  2021' <- paste('(',IS_2021$'ASR  2021',sep = '')  
IS_2021$'ASR  2021' <- paste(IS_2021$val,IS_2021$'ASR  2021',sep = ' ') 
DALYs_ASR_2021 <- IS_2021[,c(1,5)] ###筛选location和ASR 2021两列
head(DALYs_ASR_2021) ###查看数据前六列


##### EAPC
DALYs_EAPC <- IS %>% #创建新数据集
  #筛选变量
  filter(age =='Age-standardized' &  #年龄
           metric == 'Rate' & #率
           measure =='DALYs (Disability-Adjusted Life Years)'& #DALYs数据
           sex =="Both" #性别
  ) %>% 
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location == 'Global' |
           location == 'Low SDI' |
           location == 'Low-middle SDI' |
           location == 'Middle SDI' |
           location == 'High-middle SDI' |
           location == 'High SDI' |
           location == 'Andean Latin America' |
           location == 'Australasia' |
           location == 'Caribbean' |
           location == 'Central Asia' |
           location == 'Central Europe' |
           location == 'Central Latin America' |
           location == 'Central Sub-Saharan Africa' |
           location == 'East Asia' |
           location == 'Eastern Europe' |
           location == 'Eastern Sub-Saharan Africa' |
           location == 'High-income Asia Pacific' |
           location == 'High-income North America' |
           location == 'North Africa and Middle East' |
           location == 'Oceania' |
           location == 'South Asia' |
           location == 'Southeast Asia' |
           location == 'Southern Latin America' |
           location == 'Southern Sub-Saharan Africa' |
           location == 'Tropical Latin America' |
           location == 'Western Europe' |
           location == 'Western Sub-Saharan Africa') %>% 
  dplyr::select(,c(2,6,7)) #筛选location，year，val列

nations <- IS_1990$location ###将IS_1990地区赋予nations
###创建数据框EAPC_DALYs，四列location，EAPC，UCI，LCI
EAPC_DALYs <- data.frame(location=nations,EAPC=rep(0,times=27),UCI=rep(0,times=27),LCI=rep(0,times=27))

###利用for循环，计算EAPC，并将最终产生的数据整合到EAPC_DALYs数据集中
for (i in 1:nrow(EAPC_DALYs)){
  nation <- as.character(EAPC_DALYs[i,1])
  a <- subset(DALYs_EAPC, DALYs_EAPC$location==nation)
  a$y <- log(a$val)
  mod_simp_reg<-lm(y~year,data=a)
  estimate <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1])-1)*100
  low <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1]-1.96*summary(mod_simp_reg)[["coefficients"]][2,2])-1)*100
  high <- (exp(summary(mod_simp_reg)[["coefficients"]][2,1]+1.96*summary(mod_simp_reg)[["coefficients"]][2,2])-1)*100
  EAPC_DALYs[i,2] <- estimate
  EAPC_DALYs[i,4] <- low
  EAPC_DALYs[i,3] <- high
}

#保留两位小数
EAPC_DALYs$EAPC <- round(EAPC_DALYs$EAPC,2)
EAPC_DALYs$UCI <- round(EAPC_DALYs$UCI,2)
EAPC_DALYs$LCI <- round(EAPC_DALYs$LCI,2)
###EAPC_DALYs数据创建新列
EAPC_DALYs$'EAPC_95%CI' <- paste(EAPC_DALYs$LCI,EAPC_DALYs$UCI,sep = ' to ')
EAPC_DALYs$'EAPC_95%CI' <- paste(EAPC_DALYs$'EAPC_95%CI',')',sep = '')
EAPC_DALYs$'EAPC_95%CI' <- paste('(',EAPC_DALYs$'EAPC_95%CI',sep = '')
EAPC_DALYs$'EAPC_95%CI' <- paste(EAPC_DALYs$EAPC,EAPC_DALYs$'EAPC_95%CI',sep = ' ')
EAPC_DALYs <- EAPC_DALYs[,c(1,5)] ###筛选location和EAPC_95%CI两列

DALYs <- DALYs_Num_1990 %>% 
  left_join(DALYs_ASR_1990,by='location') %>%
  left_join(DALYs_Num_2021,by='location') %>% 
  left_join(DALYs_ASR_2021,by='location') %>%
  left_join(EAPC_DALYs,by='location') %>% 
  arrange(location) ###将上述四个数据集横向合并，并按照location排序，创建新数据集DALYs
View(DALYs) ###查看DALYs数据集


Table1 <- Prevalence %>% 
  rbind(Incidence) %>% 
  rbind(Deaths) %>% 
  rbind(DALYs) ###纵向合并数据集，创建新数据集Table1

print(Table1) |> write.csv(file="Table1.csv") ###呈现Table1结果，并以CSV格式保存下来
```



**绘表结果（部分结果，Prevalence）：**

| location                     | Number   1990                      | ASR   1990             | Number   2021                      | ASR   2021            | EAPC_95%CI              |
| ---------------------------- | ---------------------------------- | ---------------------- | ---------------------------------- | --------------------- | ----------------------- |
| Andean Latin America         | 138242.8 (131026.6-145937.1)       | 604.9 (573.4-638.1)    | 312484.9 (297506.2-327199.8)       | 515.1 (490.6-539)     | -0.6 (-0.64 to -0.57)   |
| Australasia                  | 176175.4 (169750.4-183601.5)       | 751.3 (724.3-783.4)    | 296950.7 (286363-308252.3)         | 581.9 (560.2-603.2)   | -0.93 (-0.98 to -0.89)  |
| Caribbean                    | 178810 (169859.7-188128.7)         | 649.1 (616.1-684.1)    | 327164.5 (312540.5-341547.6)       | 616.9 (589.7-643.6)   | -0.18 (-0.2 to -0.16)   |
| Central Asia                 | 550460.5 (523473.4-577216.8)       | 1107.9 (1052.3-1164.9) | 866712.4 (829519.2-902763)         | 1014.9 (969.9-1063.6) | -0.31 (-0.33 to -0.29)  |
| Central Europe               | 1418231.7 (1324818.4-1513619.6)    | 959.6 (897.8-1022.4)   | 1631106.1 (1537835-1733826.7)      | 776.1 (733.5-820.8)   | -0.77 (-0.82 to -0.72)  |
| Central Latin America        | 678691.9 (630061.6-725121)         | 725.2 (673.9-777.8)    | 1387551.7 (1296756.3-1484316)      | 552.6 (516.9-591.3)   | -1.03 (-1.09 to -0.96)  |
| Central Sub-Saharan Africa   | 266923.7 (253028.2-281576.5)       | 1113.6 (1052.2-1178.4) | 596223.3 (568897.8-624228.7)       | 995.7 (947.7-1046.3)  | -0.41 (-0.43 to -0.38)  |
| East Asia                    | 6921707.7 (6208387-7617523.8)      | 774.2 (691.5-863.7)    | 21503822.8 (19292836.5-23714701.3) | 1018 (920-1120.1)     | 0.95 (0.89 to 1)        |
| Eastern Europe               | 2869099.4 (2565924.6-3174157)      | 1028 (921.9-1132.8)    | 3049360.5 (2763322.4-3340261.4)    | 920.4 (835.8-1005.3)  | -0.38 (-0.41 to -0.35)  |
| Eastern Sub-Saharan Africa   | 867800.8 (811693.6-925063.4)       | 1066.6 (996.2-1139.8)  | 1869299.3 (1761941.3-1973402.3)    | 992.1 (934.2-1049.9)  | -0.27 (-0.29 to -0.25)  |
| Global                       | 34668041.4 (32153636.8-37171587.5) | 849.5 (785.9-913.2)    | 69944884.8 (64788695.1-75009602.8) | 819.5 (760.3-878.7)   | -0.18 (-0.21 to -0.16)  |
| High SDI                     | 10141955.7 (9487690-10833007.6)    | 933.8 (874.5-998)      | 15864865.5 (14925797.9-16872854.7) | 813.9 (768.6-864.1)   | -0.57 (-0.64 to -0.5)   |
| High-income Asia Pacific     | 2058456.1 (1893145.5-2220222.2)    | 1030.5 (947.1-1109.2)  | 3295961.7 (3048492.7-3555085.8)    | 775.6 (723-832.2)     | -1.04 (-1.09 to -0.98)  |
| High-income North America    | 3403854.6 (3107281.7-3724886.2)    | 991.5 (904.5-1081.9)   | 5699097.6 (5260863.2-6152298.3)    | 950 (880.6-1024.5)    | -0.39 (-0.57 to -0.21)  |
| High-middle SDI              | 9174385 (8429846.2-9882568)        | 906.2 (834.7-975)      | 17110640.3 (15738888.3-18478803.4) | 893.3 (824-960)       | -0.09 (-0.14 to -0.04)  |
| Low SDI                      | 2124875.9 (1976569.5-2270871.1)    | 838.1 (776.3-901.2)    | 4447699.2 (4174214.7-4699709.5)    | 755.7 (707.7-800.1)   | -0.39 (-0.43 to -0.36)  |
| Low-middle SDI               | 4631395.2 (4229093.5-5023596.6)    | 680.8 (620.6-741.7)    | 10234283.1 (9418964.3-11004022.1)  | 669.3 (616.3-720.6)   | -0.09 (-0.11 to -0.06)  |
| Middle SDI                   | 8555789.7 (7763206.5-9309792.2)    | 765.9 (693-837.5)      | 22230670.7 (20239639.4-24119856)   | 838.4 (764.8-911)     | 0.27 (0.24 to 0.3)      |
| North Africa and Middle East | 1847829.4 (1741882.4-1963338.4)    | 909.3 (852.4-967.6)    | 4366507.3 (4157817.8-4571157.7)    | 866.3 (823.7-909.4)   | -0.18 (-0.2 to -0.17)   |
| Oceania                      | 26485.1 (25138.3-27927.3)          | 809.7 (767.7-855)      | 59506.3 (57089.1-62156.1)          | 741.4 (711.4-772)     | -0.31 (-0.31 to -0.3)   |
| South Asia                   | 3441863 (3041705-3832962.8)        | 526 (462.2-586.9)      | 7828397.3 (6997064.5-8621267.5)    | 497.7 (445.7-549)     | -0.21 (-0.25 to -0.18)  |
| Southeast Asia               | 2557635.5 (2350464.3-2762167)      | 921.2 (846.8-999.6)    | 6104966 (5651318.6-6562857)        | 919 (851.9-986.3)     | -0.03 (-0.04 to -0.02)  |
| Southern Latin America       | 399118 (380518.4-419432.1)         | 859.4 (819.6-903.1)    | 546568.7 (524188.8-570536.2)       | 640.6 (614.8-668.1)   | -1.05 (-1.1 to -1)      |
| Southern Sub-Saharan Africa  | 364210.1 (330935.5-399540.5)       | 1274.6 (1149.8-1404.1) | 640169.7 (583548.5-694855.4)       | 1122 (1019.9-1224.9)  | -0.49 (-0.54 to -0.44)  |
| Tropical Latin America       | 827663.7 (739294.2-917728.8)       | 850 (757.8-943.6)      | 1543559.5 (1392394.6-1692607.6)    | 605.7 (546.6-663.9)   | -1.24 (-1.3 to -1.18)   |
| Western Europe               | 4563751.4 (4343952.8-4819225.2)    | 806.9 (768.4-850.6)    | 5540066.3 (5333481.7-5752361.9)    | 625.7 (600.1-649.9)   | -0.86 (-0.89 to -0.83)  |
| Western Sub-Saharan  Africa  | 1111030.5 (1034246.3-1188453)      | 1109.4 (1026.9-1194.5) | 2479408.3 (2331911-2621732.8)      | 1046 (977.7-1112.6)   | -0.23 (-0.24  to -0.21) |

注：Table 1里包含了Prevalence，Incidence，Deaths，以及DALYs的结果，因为数据太大，这里只呈现Prevalence相关结果，其他指标与其类似。



# 4 世界地图

**文献原Figure 2：**

<img src="https://s2.loli.net/2024/09/12/EdxefVpwF65GlMk.jpg" alt="gr2_Irg" style="zoom: 80%;" />



**代码实操：**

```R
###装载和加载分析R包
if (!require('sf')) install.packages('sf')
if (!require('maps')) install.packages('maps')
if (!require('patchwork')) install.packages('patchwork')
library(sf)
library(maps)
library(patchwork)
library(dplyr)
library(ggplot2)

###读取绘制世界地图的经纬度等数据
world <- map_data('world')

###创建新数据集,Prevalence分析
map <- IS %>%
  filter(measure == "Prevalence") %>% #患病率数据
  filter(year == 2021) %>% #年份
  filter(sex == "Both") %>% #性别
  filter(age == "Age-standardized") %>% #年龄 
  mutate(val2 = cut(val, breaks = c(0,574.72,699.96,824.84,955.54,1080.98,1603.89,100000000),
                    labels = c("<574.72","574.72-699.96","699.96-824.84","824.84-955.54","955.54-1080.98",
                               "1080.98-1603.89",">1603.89"),  
                    include.lowest = T,right = T)) #建立新列，连续变量转换成分类变量，包含最小值所在区间且包括左端点而不包括右端点

###地区名称转换，方便之后数据集合并
map$location[map$location == 'United States of America'] = 'USA'
map$location[map$location == 'Russian Federation'] = 'Russia'
map$location[map$location == 'United Kingdom'] = 'UK'
map$location[map$location == 'Congo'] = 'Republic of Congo'
map$location[map$location == "Iran (Islamic Republic of)"] = 'Iran'
map$location[map$location == "Democratic People's Republic of Korea"] = 'North Korea'
map$location[map$location == "Taiwan (Province of China)"] = 'Taiwan'
map$location[map$location == "Republic of Korea"] = 'South Korea'
map$location[map$location == "United Republic of Tanzania"] = 'Tanzania'
map$location[map$location == "Bolivia (Plurinational State of)"] = 'Bolivia'
map$location[map$location == "Venezuela (Bolivarian Republic of)"] = 'Venezuela'
map$location[map$location == "Czechia"] = 'Czech Republic'
map$location[map$location == "Republic of Moldova"] = 'Moldova'
map$location[map$location == "Viet Nam"] = 'Vietnam'
map$location[map$location == "Lao People's Democratic Republic"] = 'Laos'
map$location[map$location == "Syrian Arab Republic"] = 'Syria'
map$location[map$location == "North Macedonia"] = 'Macedonia'
map$location[map$location == "Micronesia (Federated States of)"] = 'Micronesia'
map$location[map$location == "Macedonia"] = 'North Macedonia'
map$location[map$location == "Trinidad and Tobago"] = 'Trinidad'
a <- map[map$location == "Trinidad",]
a$location <- 'Tobago'
map <- rbind(map,a)
map$location[map$location == "Cabo Verde"] = 'Cape Verde'
map$location[map$location == "United States Virgin Islands"] = 'Virgin Islands'
map$location[map$location == "Antigua and Barbuda"] = 'Antigu'
a <- map[map$location == "Antigu",]
a$location <- 'Barbuda'
map <- rbind(map,a)
map$location[map$location == "Saint Kitts and Nevis"] = 'Saint Kitts'
a <- map[map$location == "Saint Kitts",]
a$location <- 'Nevis'
map <- rbind(map,a)
map$location[map$location == "Côte d'Ivoire"] = 'Ivory Coast'
map$location[map$location == "Saint Vincent and the Grenadines"] = 'Saint Vincent'
a <- map[map$location == "Saint Vincent",]
a$location <- 'Grenadines'
map <- rbind(map,a)
map$location[map$location == "Eswatini"] = 'Swaziland'
map$location[map$location == "Brunei Darussalam"] = 'Brunei'

#合并数据集
map <- full_join(world,map,by = c('region'='location')) %>%
  filter(val != "NA")

###绘图
fig <- map %>%
  ggplot()+
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_void()+ #主题设置
  scale_fill_manual(values=c("#019e73","#56b4e8","#f0e53e",
                             "#e79e01","#d65e00","#fe0000","#00468BFF")) + #手动添加颜色
  theme(legend.position = c(0.1,0.2), #设置图例位置
        legend.title = element_blank(), #取消图例标题
        legend.text = element_text(color="black",
                                   size = 12,
        ), #设置图例文字
        plot.title =  element_blank(), #取消图标题
        panel.grid=element_blank(), #取消图网格线
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  ) 

fig ###呈现图片

###再绘图，方便后续绘制区域小图
fig2 <- map %>%
  ggplot()+  #主题设置
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_bw()+ 
  scale_fill_manual(values=c("#019e73","#56b4e8","#f0e53e",
                             "#e79e01","#d65e00","#fe0000","#00468BFF")) + #手动添加颜色
  theme(legend.position = 'none', #取消图例
        legend.title = element_blank(), #取消图例标题
        plot.title = element_text(color="black",
                                  size = 10
        ), #设置图标题文字
        panel.grid=element_blank(), #取消图网格线
        panel.border = element_rect(color='black',
                                    fill=NA,
                                    size = 0.5), #设置图边框
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  )

#绘制Caribbean and central America 地区
p2 <- fig2+ labs(x=" ",y="",title="Caribbean and central America")+
  coord_cartesian(xlim = c(-92,-60),ylim = c(5,27))

#绘制Persian Gulf 地区
p3 <- fig2+ labs(x=" ",y="",title="Persian Gulf")+
  coord_cartesian(xlim = c(45,55),ylim = c(19,31))

#绘制Balkan Peninsula 地区
p4 <- fig2+ labs(x=" ",y="",title="Balkan \nPeninsula")+
  coord_cartesian(xlim = c(12,32),ylim = c(35,53))

#绘制Sotheast Asia 地区
p5 <- fig2+ labs(x=" ",y="",title="Sotheast Asia")+
  coord_cartesian(xlim = c(98,123),ylim = c(-10,8))

#绘制West Africa 地区
p6 <- fig2+ labs(x=" ",y="",title="West Africa") +
  coord_cartesian(xlim = c(-17,-7),ylim = c(7,20))

#绘制Eastern Mediterranean 地区
p7 <- fig2+ labs(x=" ",y="",title="Eastern
Mediterranean")+
  coord_cartesian(xlim = c(32,37),ylim = c(29,35))

#绘制Northern Europe 地区
p8 <- fig2+ labs(x=" ",y="",title="Northern Europe") +
  coord_cartesian(xlim = c(5,25),ylim = c(48,60))

###组合绘图
A= (p6|p7)/p8 
plot1 <- fig +
  (p2+p3+p4+p5+A+plot_layout(ncol = 5,widths=c(1.5,1,1.1,1.2,1)))+
  plot_layout(ncol = 1,heights = c(9, 3))

###呈现图片
plot1




###创建新数据集，Incidence分析
map <- IS %>%
  filter(measure == "Incidence") %>% #发病率数据
  filter(year == 2021) %>% #年份
  filter(sex == "Both") %>% #性别
  filter(age == "Age-standardized") %>% #年龄 
  mutate(val2 = cut(val, breaks = c(0,56.74,72.83,88.64,101.68,123.95,214.36,100000000),
                    labels = c("<56.74","56.74-72.83","72.83-88.64","88.64-101.68","101.68-123.95",
                               "123.95-214.36",">214.36"),  
                    include.lowest = T,right = T)) #建立新列，连续变量转换成分类变量，包含最小值所在区间且包括左端点而不包括右端点

###地区名称转换，方便之后数据集合并
map$location[map$location == 'United States of America'] = 'USA'
map$location[map$location == 'Russian Federation'] = 'Russia'
map$location[map$location == 'United Kingdom'] = 'UK'
map$location[map$location == 'Congo'] = 'Republic of Congo'
map$location[map$location == "Iran (Islamic Republic of)"] = 'Iran'
map$location[map$location == "Democratic People's Republic of Korea"] = 'North Korea'
map$location[map$location == "Taiwan (Province of China)"] = 'Taiwan'
map$location[map$location == "Republic of Korea"] = 'South Korea'
map$location[map$location == "United Republic of Tanzania"] = 'Tanzania'
map$location[map$location == "Bolivia (Plurinational State of)"] = 'Bolivia'
map$location[map$location == "Venezuela (Bolivarian Republic of)"] = 'Venezuela'
map$location[map$location == "Czechia"] = 'Czech Republic'
map$location[map$location == "Republic of Moldova"] = 'Moldova'
map$location[map$location == "Viet Nam"] = 'Vietnam'
map$location[map$location == "Lao People's Democratic Republic"] = 'Laos'
map$location[map$location == "Syrian Arab Republic"] = 'Syria'
map$location[map$location == "North Macedonia"] = 'Macedonia'
map$location[map$location == "Micronesia (Federated States of)"] = 'Micronesia'
map$location[map$location == "Macedonia"] = 'North Macedonia'
map$location[map$location == "Trinidad and Tobago"] = 'Trinidad'
a <- map[map$location == "Trinidad",]
a$location <- 'Tobago'
map <- rbind(map,a)
map$location[map$location == "Cabo Verde"] = 'Cape Verde'
map$location[map$location == "United States Virgin Islands"] = 'Virgin Islands'
map$location[map$location == "Antigua and Barbuda"] = 'Antigu'
a <- map[map$location == "Antigu",]
a$location <- 'Barbuda'
map <- rbind(map,a)
map$location[map$location == "Saint Kitts and Nevis"] = 'Saint Kitts'
a <- map[map$location == "Saint Kitts",]
a$location <- 'Nevis'
map <- rbind(map,a)
map$location[map$location == "Côte d'Ivoire"] = 'Ivory Coast'
map$location[map$location == "Saint Vincent and the Grenadines"] = 'Saint Vincent'
a <- map[map$location == "Saint Vincent",]
a$location <- 'Grenadines'
map <- rbind(map,a)
map$location[map$location == "Eswatini"] = 'Swaziland'
map$location[map$location == "Brunei Darussalam"] = 'Brunei'

#合并数据集
map <- full_join(world,map,by = c('region'='location')) %>%
  filter(val != "NA")

###绘图
fig <- map %>%
  ggplot()+
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_void()+ #主题设置
  scale_fill_manual(values=c("#019e73","#56b4e8","#f0e53e",
                             "#e79e01","#d65e00","#fe0000","#00468BFF")) + #手动添加颜色
  theme(legend.position = c(0.1,0.2), #设置图例位置
        legend.title = element_blank(), #取消图例标题
        legend.text = element_text(color="black",
                                   size = 12,
        ), #设置图例文字
        plot.title =  element_blank(), #取消图标题
        panel.grid=element_blank(), #取消图网格线
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  ) 

fig ###呈现图片

###再绘图，方便后续绘制区域小图
fig2 <- map %>%
  ggplot()+  #主题设置
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_bw()+ 
  scale_fill_manual(values=c("#019e73","#56b4e8","#f0e53e",
                             "#e79e01","#d65e00","#fe0000","#00468BFF")) + #手动添加颜色
  theme(legend.position = 'none', #取消图例
        legend.title = element_blank(), #取消图例标题
        plot.title = element_text(color="black",
                                  size = 10
        ), #设置图标题文字
        panel.grid=element_blank(), #取消图网格线
        panel.border = element_rect(color='black',
                                    fill=NA,
                                    size = 0.5), #设置图边框
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  )

#绘制Caribbean and central America 地区
p2 <- fig2+ labs(x=" ",y="",title="Caribbean and central America")+
  coord_cartesian(xlim = c(-92,-60),ylim = c(5,27))

#绘制Persian Gulf 地区
p3 <- fig2+ labs(x=" ",y="",title="Persian Gulf")+
  coord_cartesian(xlim = c(45,55),ylim = c(19,31))

#绘制Balkan Peninsula 地区
p4 <- fig2+ labs(x=" ",y="",title="Balkan \nPeninsula")+
  coord_cartesian(xlim = c(12,32),ylim = c(35,53))

#绘制Sotheast Asia 地区
p5 <- fig2+ labs(x=" ",y="",title="Sotheast Asia")+
  coord_cartesian(xlim = c(98,123),ylim = c(-10,8))

#绘制West Africa 地区
p6 <- fig2+ labs(x=" ",y="",title="West Africa") +
  coord_cartesian(xlim = c(-17,-7),ylim = c(7,20))

#绘制Eastern Mediterranean 地区
p7 <- fig2+ labs(x=" ",y="",title="Eastern
Mediterranean")+
  coord_cartesian(xlim = c(32,37),ylim = c(29,35))

#绘制Northern Europe 地区
p8 <- fig2+ labs(x=" ",y="",title="Northern Europe") +
  coord_cartesian(xlim = c(5,25),ylim = c(48,60))

###组合绘图
A= (p6|p7)/p8 
plot2 <- fig +
  (p2+p3+p4+p5+A+plot_layout(ncol = 5,widths=c(1.5,1,1.1,1.2,1)))+
  plot_layout(ncol = 1,heights = c(9, 3))

###呈现图片
plot2




###创建新数据集,Deaths分析
map <- IS %>%
  filter(measure == "Deaths") %>% #死亡率数据
  filter(year == 2021) %>% #年份
  filter(sex == "Both") %>% #性别
  filter(age == "Age-standardized") %>% #年龄 
  mutate(val2 = cut(val, breaks = c(0,19.15,35.46,48.43,59.53,78.26,216.89,100000000),
                    labels = c("<19.15","19.15-35.46","35.46-48.43","48.43-59.53","59.53-78.26",
                               "78.26-216.89",">216.89"),  
                    include.lowest = T,right = T)) #建立新列，连续变量转换成分类变量，包含最小值所在区间且包括左端点而不包括右端点

###地区名称转换，方便之后数据集合并
map$location[map$location == 'United States of America'] = 'USA'
map$location[map$location == 'Russian Federation'] = 'Russia'
map$location[map$location == 'United Kingdom'] = 'UK'
map$location[map$location == 'Congo'] = 'Republic of Congo'
map$location[map$location == "Iran (Islamic Republic of)"] = 'Iran'
map$location[map$location == "Democratic People's Republic of Korea"] = 'North Korea'
map$location[map$location == "Taiwan (Province of China)"] = 'Taiwan'
map$location[map$location == "Republic of Korea"] = 'South Korea'
map$location[map$location == "United Republic of Tanzania"] = 'Tanzania'
map$location[map$location == "Bolivia (Plurinational State of)"] = 'Bolivia'
map$location[map$location == "Venezuela (Bolivarian Republic of)"] = 'Venezuela'
map$location[map$location == "Czechia"] = 'Czech Republic'
map$location[map$location == "Republic of Moldova"] = 'Moldova'
map$location[map$location == "Viet Nam"] = 'Vietnam'
map$location[map$location == "Lao People's Democratic Republic"] = 'Laos'
map$location[map$location == "Syrian Arab Republic"] = 'Syria'
map$location[map$location == "North Macedonia"] = 'Macedonia'
map$location[map$location == "Micronesia (Federated States of)"] = 'Micronesia'
map$location[map$location == "Macedonia"] = 'North Macedonia'
map$location[map$location == "Trinidad and Tobago"] = 'Trinidad'
a <- map[map$location == "Trinidad",]
a$location <- 'Tobago'
map <- rbind(map,a)
map$location[map$location == "Cabo Verde"] = 'Cape Verde'
map$location[map$location == "United States Virgin Islands"] = 'Virgin Islands'
map$location[map$location == "Antigua and Barbuda"] = 'Antigu'
a <- map[map$location == "Antigu",]
a$location <- 'Barbuda'
map <- rbind(map,a)
map$location[map$location == "Saint Kitts and Nevis"] = 'Saint Kitts'
a <- map[map$location == "Saint Kitts",]
a$location <- 'Nevis'
map <- rbind(map,a)
map$location[map$location == "Côte d'Ivoire"] = 'Ivory Coast'
map$location[map$location == "Saint Vincent and the Grenadines"] = 'Saint Vincent'
a <- map[map$location == "Saint Vincent",]
a$location <- 'Grenadines'
map <- rbind(map,a)
map$location[map$location == "Eswatini"] = 'Swaziland'
map$location[map$location == "Brunei Darussalam"] = 'Brunei'

#合并数据集
map <- full_join(world,map,by = c('region'='location')) %>%
  filter(val != "NA")

###绘图
fig <- map %>%
  ggplot()+
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_void()+ #主题设置
  scale_fill_manual(values=c("#019e73","#56b4e8","#f0e53e",
                             "#e79e01","#d65e00","#fe0000","#00468BFF")) + #手动添加颜色
  theme(legend.position = c(0.1,0.2), #设置图例位置
        legend.title = element_blank(), #取消图例标题
        legend.text = element_text(color="black",
                                   size = 12,
        ), #设置图例文字
        plot.title =  element_blank(), #取消图标题
        panel.grid=element_blank(), #取消图网格线
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  ) 

fig ###呈现图片

###再绘图，方便后续绘制区域小图
fig2 <- map %>%
  ggplot()+  #主题设置
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_bw()+ 
  scale_fill_manual(values=c("#019e73","#56b4e8","#f0e53e",
                             "#e79e01","#d65e00","#fe0000","#00468BFF")) + #手动添加颜色
  theme(legend.position = 'none', #取消图例
        legend.title = element_blank(), #取消图例标题
        plot.title = element_text(color="black",
                                  size = 10
        ), #设置图标题文字
        panel.grid=element_blank(), #取消图网格线
        panel.border = element_rect(color='black',
                                    fill=NA,
                                    size = 0.5), #设置图边框
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  )

#绘制Caribbean and central America 地区
p2 <- fig2+ labs(x=" ",y="",title="Caribbean and central America")+
  coord_cartesian(xlim = c(-92,-60),ylim = c(5,27))

#绘制Persian Gulf 地区
p3 <- fig2+ labs(x=" ",y="",title="Persian Gulf")+
  coord_cartesian(xlim = c(45,55),ylim = c(19,31))

#绘制Balkan Peninsula 地区
p4 <- fig2+ labs(x=" ",y="",title="Balkan \nPeninsula")+
  coord_cartesian(xlim = c(12,32),ylim = c(35,53))

#绘制Sotheast Asia 地区
p5 <- fig2+ labs(x=" ",y="",title="Sotheast Asia")+
  coord_cartesian(xlim = c(98,123),ylim = c(-10,8))

#绘制West Africa 地区
p6 <- fig2+ labs(x=" ",y="",title="West Africa") +
  coord_cartesian(xlim = c(-17,-7),ylim = c(7,20))

#绘制Eastern Mediterranean 地区
p7 <- fig2+ labs(x=" ",y="",title="Eastern
Mediterranean")+
  coord_cartesian(xlim = c(32,37),ylim = c(29,35))

#绘制Northern Europe 地区
p8 <- fig2+ labs(x=" ",y="",title="Northern Europe") +
  coord_cartesian(xlim = c(5,25),ylim = c(48,60))

###组合绘图
A= (p6|p7)/p8 
plot3 <- fig +
  (p2+p3+p4+p5+A+plot_layout(ncol = 5,widths=c(1.5,1,1.1,1.2,1)))+
  plot_layout(ncol = 1,heights = c(9, 3))

###呈现图片
plot3





###创建新数据集，DALYs分析
map <- IS %>%
  filter(measure == "DALYs (Disability-Adjusted Life Years)") %>% #DALYs数据
  filter(year == 2021) %>% #年份
  filter(sex == "Both") %>% #性别
  filter(age == "Age-standardized") %>% #年龄 
  mutate(val2 = cut(val, breaks = c(0,354.47,626.55,865.78,1115.01,1420.64,3037.44,100000000),
                    labels = c("<354.47","354.47-626.55","626.55-865.78","865.78-1115.01","1115.01-1420.64",
                               "1420.64-3037.44",">3037.44"),  
                    include.lowest = T,right = T)) #建立新列，连续变量转换成分类变量，包含最小值所在区间且包括左端点而不包括右端点

###地区名称转换，方便之后数据集合并
map$location[map$location == 'United States of America'] = 'USA'
map$location[map$location == 'Russian Federation'] = 'Russia'
map$location[map$location == 'United Kingdom'] = 'UK'
map$location[map$location == 'Congo'] = 'Republic of Congo'
map$location[map$location == "Iran (Islamic Republic of)"] = 'Iran'
map$location[map$location == "Democratic People's Republic of Korea"] = 'North Korea'
map$location[map$location == "Taiwan (Province of China)"] = 'Taiwan'
map$location[map$location == "Republic of Korea"] = 'South Korea'
map$location[map$location == "United Republic of Tanzania"] = 'Tanzania'
map$location[map$location == "Bolivia (Plurinational State of)"] = 'Bolivia'
map$location[map$location == "Venezuela (Bolivarian Republic of)"] = 'Venezuela'
map$location[map$location == "Czechia"] = 'Czech Republic'
map$location[map$location == "Republic of Moldova"] = 'Moldova'
map$location[map$location == "Viet Nam"] = 'Vietnam'
map$location[map$location == "Lao People's Democratic Republic"] = 'Laos'
map$location[map$location == "Syrian Arab Republic"] = 'Syria'
map$location[map$location == "North Macedonia"] = 'Macedonia'
map$location[map$location == "Micronesia (Federated States of)"] = 'Micronesia'
map$location[map$location == "Macedonia"] = 'North Macedonia'
map$location[map$location == "Trinidad and Tobago"] = 'Trinidad'
a <- map[map$location == "Trinidad",]
a$location <- 'Tobago'
map <- rbind(map,a)
map$location[map$location == "Cabo Verde"] = 'Cape Verde'
map$location[map$location == "United States Virgin Islands"] = 'Virgin Islands'
map$location[map$location == "Antigua and Barbuda"] = 'Antigu'
a <- map[map$location == "Antigu",]
a$location <- 'Barbuda'
map <- rbind(map,a)
map$location[map$location == "Saint Kitts and Nevis"] = 'Saint Kitts'
a <- map[map$location == "Saint Kitts",]
a$location <- 'Nevis'
map <- rbind(map,a)
map$location[map$location == "Côte d'Ivoire"] = 'Ivory Coast'
map$location[map$location == "Saint Vincent and the Grenadines"] = 'Saint Vincent'
a <- map[map$location == "Saint Vincent",]
a$location <- 'Grenadines'
map <- rbind(map,a)
map$location[map$location == "Eswatini"] = 'Swaziland'
map$location[map$location == "Brunei Darussalam"] = 'Brunei'

#合并数据集
map <- full_join(world,map,by = c('region'='location')) %>%
  filter(val != "NA")

###绘图
fig <- map %>%
  ggplot()+
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_void()+ #主题设置
  scale_fill_manual(values=c("#019e73","#56b4e8","#f0e53e",
                             "#e79e01","#d65e00","#fe0000","#00468BFF")) + #手动添加颜色
  theme(legend.position = c(0.1,0.2), #设置图例位置
        legend.title = element_blank(), #取消图例标题
        legend.text = element_text(color="black",
                                   size = 12,
        ), #设置图例文字
        plot.title =  element_blank(), #取消图标题
        panel.grid=element_blank(), #取消图网格线
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  ) 

fig ###呈现图片

###再绘图，方便后续绘制区域小图
fig2 <- map %>%
  ggplot()+  #主题设置
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_bw()+ 
  scale_fill_manual(values=c("#019e73","#56b4e8","#f0e53e",
                             "#e79e01","#d65e00","#fe0000","#00468BFF")) + #手动添加颜色
  theme(legend.position = 'none', #取消图例
        legend.title = element_blank(), #取消图例标题
        plot.title = element_text(color="black",
                                  size = 10
        ), #设置图标题文字
        panel.grid=element_blank(), #取消图网格线
        panel.border = element_rect(color='black',
                                    fill=NA,
                                    size = 0.5), #设置图边框
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  )

#绘制Caribbean and central America 地区
p2 <- fig2+ labs(x=" ",y="",title="Caribbean and central America")+
  coord_cartesian(xlim = c(-92,-60),ylim = c(5,27))

#绘制Persian Gulf 地区
p3 <- fig2+ labs(x=" ",y="",title="Persian Gulf")+
  coord_cartesian(xlim = c(45,55),ylim = c(19,31))

#绘制Balkan Peninsula 地区
p4 <- fig2+ labs(x=" ",y="",title="Balkan \nPeninsula")+
  coord_cartesian(xlim = c(12,32),ylim = c(35,53))

#绘制Sotheast Asia 地区
p5 <- fig2+ labs(x=" ",y="",title="Sotheast Asia")+
  coord_cartesian(xlim = c(98,123),ylim = c(-10,8))

#绘制West Africa 地区
p6 <- fig2+ labs(x=" ",y="",title="West Africa") +
  coord_cartesian(xlim = c(-17,-7),ylim = c(7,20))

#绘制Eastern Mediterranean 地区
p7 <- fig2+ labs(x=" ",y="",title="Eastern
Mediterranean")+
  coord_cartesian(xlim = c(32,37),ylim = c(29,35))

#绘制Northern Europe 地区
p8 <- fig2+ labs(x=" ",y="",title="Northern Europe") +
  coord_cartesian(xlim = c(5,25),ylim = c(48,60))

###组合绘图
A= (p6|p7)/p8 
plot4 <- fig +
  (p2+p3+p4+p5+A+plot_layout(ncol = 5,widths=c(1.5,1,1.1,1.2,1)))+
  plot_layout(ncol = 1,heights = c(9, 3))

###呈现图片
plot4


###以png格式保存图片
png("P\\plot1.png",width = 1200, height = 700, units = "px")
plot1
dev.off()

png("P\\plot2.png",width = 1200, height = 700, units = "px")
plot2
dev.off()

png("P\\plot3.png",width = 1200, height = 700, units = "px")
plot3
dev.off()

png("P\\plot4.png",width = 1200, height = 700, units = "px")
plot4
dev.off()



###以jpg格式保存图片
jpeg("P\\plot1.jpg",width = 1200, height = 700, units = "px")
plot1
dev.off()

jpeg("P\\plot2.jpg",width = 1200, height = 700, units = "px")
plot2
dev.off()

jpeg("P\\plot3.jpg",width = 1200, height = 700, units = "px")
plot3
dev.off()

jpeg("P\\plot4.jpg",width = 1200, height = 700, units = "px")
plot4
dev.off()



###以tiff格式保存图片
tiff("P\\plot1.tiff",width = 1200, height = 700, units = "px")
plot1
dev.off()

tiff("P\\plot2.tiff",width = 1200, height = 700, units = "px")
plot2
dev.off()

tiff("P\\plot3.tiff",width = 1200, height = 700, units = "px")
plot3
dev.off()

tiff("P\\plot4.tiff",width = 1200, height = 700, units = "px")
plot4
dev.off()
```



**绘图结果：**

1）Prevalence

<img src="https://s2.loli.net/2024/09/12/4XApHOJi7jQZEKs.png" alt="Prevalence,plot1" style="zoom:80%;" />



2）Incidence

<img src="https://s2.loli.net/2024/09/12/oensjDYW31ZXt5O.png" alt="Incidence,plot2" style="zoom:80%;" />



3）Deaths

<img src="https://s2.loli.net/2024/09/12/e2gaKyvV7wtlmMQ.png" alt="Deaths,plot3" style="zoom:80%;" />



4）DALYs

<img src="https://s2.loli.net/2024/09/12/LaZXwth8ArIyjcd.png" alt="DALYs,plot4" style="zoom:80%;" />



# 5 年龄变化趋势

**文献原Figure 3：**

<img src="https://s2.loli.net/2024/09/14/jn7sW1KazifLSom.jpg" alt="gr3_lrg" style="zoom:80%;" />

**注：**原文献图中，70-74 years有缺失，后续绘图有增加；





**代码实操：**

```R
###加载R包
library(dplyr)
library(ggplot2)

###Incidence
###创建新数据集Incidence_age
Incidence_age <- IS %>% 
  filter(measure == "Incidence" & #患病率数据
           sex != "Both" & #性别，选取非Both
           age != "All ages" & #年龄，选取非All ages
           age != "Age-standardized" & #年龄，选取非Age-standardized
           year == 2021) %>%  #年份，2021
  #选取特定地区
  filter(location=="Global" |
           location=="High SDI" |
           location=="High-middle SDI" |
           location=="Middle SDI" |
           location=="Low-middle SDI" |
           location=="Low SDI") %>% 
  #设置绝对例数和率及其95%UI值，用于后续绘制双向图
  mutate(val=ifelse(sex=="Male",val,-val),
         lower=ifelse(sex=="Male",lower,-lower),
         upper=ifelse(sex=="Male",upper,-upper)) %>% 
  #设置group新列，用于后续图例按照顺序呈现
  mutate(group=ifelse(location=="High SDI"&sex=="Male","a",ifelse(
    location=="High-middle SDI"&sex=="Male","b",ifelse(
      location=="Middle SDI"&sex=="Male","c",ifelse(
        location=="Low-middle SDI"&sex=="Male","d",ifelse(
          location=="Low SDI"&sex=="Male","e",ifelse(
            location=="High SDI"&sex=="Female","f",ifelse(
              location=="High-middle SDI"&sex=="Female","g",ifelse(
                location=="Middle SDI"&sex=="Female","h",ifelse(
                  location=="Low-middle SDI"&sex=="Female","i","j")))))))))) %>% 
  #设置age_new新列，用于后续按年龄大小绘制年龄趋势图
  mutate(age_new=ifelse(age=="<5 years",1,ifelse(
    age=="5-9 years",2,ifelse(
      age=="10-14 years",3,ifelse(
        age=="15-19 years",4,ifelse(
          age=="20-24 years",5,ifelse(
            age=="25-29 years",6,ifelse(
              age=="30-34 years",7,ifelse(
                age=="35-39 years",8,ifelse(
                  age=="40-44 years",9,ifelse(
                    age=="45-49 years",10,ifelse(
                      age=="50-54 years",11,ifelse(
                        age=="55-59 years",12,ifelse(
                          age=="60-64 years",13,ifelse(
                            age=="65-69 years",14,ifelse(
                              age=="70-74 years",15,ifelse(
                                age=="75-79 years",16,ifelse(
                                  age=="80-84 years",17,ifelse(
                                    age=="85-89 years",18,ifelse(
                                      age=="90-94 years",19,20)))))))))))))))))))) %>% 
  dplyr::select(,c(2,3,4,5,7:11)) #提取特定列

#设定特定的转化比例，用于后续绘制双纵坐标图
ad_factor <- max(Incidence_age$val[Incidence_age$metric=="Rate"&Incidence_age$location=="Global"])/
  max(Incidence_age$val[Incidence_age$metric=="Number"&Incidence_age$location!="Global"])

# 绘图，并赋值给p
p <- ggplot() +
  # 针对绝对例数，以SDI分组绘制柱状图
  geom_col(data = subset(Incidence_age,metric=='Number'&location!="Global"), 
           aes(x = age_new, y = val, fill = group)) +
  # 针对率，绘制Global折线图
  geom_line(data = subset(Incidence_age,metric=='Rate'&location=="Global"),
            aes(x = age_new, y = val/ad_factor, color = sex, group = sex), size = 1) +  
  # 针对率，增加区间ribbon图
  geom_ribbon(data = subset(Incidence_age,metric=='Rate'&location=="Global"),
              aes(x = age_new, ymin = lower/ad_factor, ymax = upper/ad_factor, fill = sex), alpha = 0.2) +
  #针对绝对例数，手动设置填充色，并更改图例名称
  scale_fill_manual(name="Gender, SDI region (Number)",
                    values = c("a" = "#338a57", 
                               "b" = "#5bb577",
                               "c" = "#90d191",
                               "d" = "#c9e9c2",
                               "e" = "#f1f9ec",
                               "f" = "#ca3352",
                               "g" = "#f3624d",
                               "h" = "#fda364",
                               "i" = "#fed67e",
                               "j" = "#ffffc1"),
                    labels=c(
                      "a"="Male,High SDI",
                      'b'='Male,High-middle SDI',
                      'c'='Male,Middle SDI',
                      'd'='Male,Low-middle SDI',
                      'e'='Male,Low SDI',
                      'f'='Female,High SDI',
                      'g'='Female,High-middle SDI',
                      'h'='Female,Middle SDI',
                      'i'='Female,Low-middle SDI',
                      'j'='Female,Low SDI'
                    )) +
  #针对率，手动设置填充色，并更改图例名称
  scale_color_manual(name="Gender, Global Rate (per 100,000)",
                     values = c("Male" = "#006d2b", "Female" = "#31a255"),
                     labels = c(
                       'Male'='Male,Global',
                       'Female'='Female,Global'
                     )) +
  
  # 设置x轴标签值
  scale_x_continuous(breaks = 1:20,
                     labels=c('<5 years','5-9 years','10-14 years','15-19 years','20-24 years',
                              '25-29 years','30-34 years','35-39 years','40-44 years','45-49 years',
                              '50-54 years','55-59 years','60-64 years','65-69 years','70-74 years',
                              '75-79 years','80-84 years','85-89 years','90-94 years','95+ years')) +
  #设置双y轴标签值，并更改右y轴的名称
  scale_y_continuous(sec.axis = sec_axis(~.*ad_factor, name = "Gender, Global Rate (per 100,000)",
                                         labels = function(x) format(abs(x), scientific = FALSE)),
                     labels = function(x) format(abs(x), scientific = FALSE)) +

  theme_bw() + #设置主题
  theme(legend.position = "right", #右置图例
        panel.grid.major = element_line(color = "gray90"), #网格线大区间颜色
        panel.grid.minor = element_line(color = "gray95"), #网格线小区间颜色
        axis.text.x = element_text(angle = 45, hjust = 1)) + #x轴标签值角度和与轴距离设置
  labs(title = "", #取消图标题
       x = 'Age', #x轴名称
       y = 'Number') #左y轴名称

p ###呈现图

###以png格式储存图片
png("P\\Figure 3.png", width = 1200, height = 800, units = "px")
p
dev.off()
                                        
###以jpg格式储存图片
jpeg("P\\Figure 3.jpg", width = 1200, height = 800, units = "px")
p
dev.off()

###以tiff格式储存图片
tiff("P\\Figure 3.tiff", width = 1200, height = 800, units = "px")
p
dev.off() 
```



**绘图结果：**

<img src="https://s2.loli.net/2024/09/14/XdQf9xgHroe4p5U.png" alt="Figure 3" style="zoom:80%;" />

注：补充了原文献图中70-74 years缺失的部分；



# 6 世界地图（变化百分比）

**文献原Figure 4：**

<img src="https://s2.loli.net/2024/09/13/Le7X8VpHb3ScCkM.jpg" alt="gr4_lrg" style="zoom:80%;" />

**注：**原文献中的C图存在NA，即缺失现象；后续复现时更改了区间设置，包含了原有缺失的部分；



**代码实操：**

```R
###装载和加载分析R包
if (!require('sf')) install.packages('sf')
if (!require('maps')) install.packages('maps')
if (!require('patchwork')) install.packages('patchwork')
library(sf)
library(maps)
library(patchwork)
library(dplyr)
library(ggplot2)
library(tidyr)


###Prevalence
### Change percentage
###创建新数据集
Prevalence_change <- IS[,-c(8,9)] %>% #去除lower，upper列
  #筛选变量
  filter(age =='All ages' &  #年龄
           metric == 'Number' & #绝对例数
           measure =='Prevalence'& #患病率数据
           sex =="Both" #性别
  ) %>% 
  filter(year == 1990 |
           year == 2021) %>% #年份
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location != 'Global' &
           location != 'Low SDI' &
           location != 'Low-middle SDI' &
           location != 'Middle SDI' &
           location != 'High-middle SDI' &
           location != 'High SDI' &
           location != 'Andean Latin America' &
           location != 'Australasia' &
           location != 'Caribbean' &
           location != 'Central Asia' &
           location != 'Central Europe' &
           location != 'Central Latin America' &
           location != 'Central Sub-Saharan Africa' &
           location != 'East Asia' &
           location != 'Eastern Europe' &
           location != 'Eastern Sub-Saharan Africa' &
           location != 'High-income Asia Pacific' &
           location != 'High-income North America' &
           location != 'North Africa and Middle East' &
           location != 'Oceania' &
           location != 'South Asia' &
           location != 'Southeast Asia' &
           location != 'Southern Latin America' &
           location != 'Southern Sub-Saharan Africa' &
           location != 'Tropical Latin America' &
           location != 'Western Europe' &
           location != 'Western Sub-Saharan Africa') %>% 
  pivot_wider(names_from = year, values_from = val) %>% #长表格变宽表格
  rename(val_1990 = '1990',
         val_2021 = '2021') %>% #更换列名
  mutate(change = (val_2021-val_1990)/val_1990) %>%  #计算1990-2021年变化值
  dplyr::select(,c(2,8)) #筛选location，change列



###读取绘制世界地图的经纬度等数据
world <- map_data('world')

###创建新数据集,Prevalence分析
Prevalence_change <- Prevalence_change %>%  
  mutate(val2 = cut(change, breaks = c(-0.6,-0.3,0,0.5,1.0,2.0,3.0,100000000),
                    labels = c("30% to 60% decrease","<30% decrease","<50% increase","50% to 100% increase",
                               "100% to 200% increase","200% to 300% increase",'>300% increase'),  
                    include.lowest = T,right = T)) #建立新列，连续变量转换成分类变量，包含最小值所在区间且包括左端点而不包括右端点

###地区名称转换，方便之后数据集合并
Prevalence_change$location[Prevalence_change$location == 'United States of America'] = 'USA'
Prevalence_change$location[Prevalence_change$location == 'Russian Federation'] = 'Russia'
Prevalence_change$location[Prevalence_change$location == 'United Kingdom'] = 'UK'
Prevalence_change$location[Prevalence_change$location == 'Congo'] = 'Republic of Congo'
Prevalence_change$location[Prevalence_change$location == "Iran (Islamic Republic of)"] = 'Iran'
Prevalence_change$location[Prevalence_change$location == "Democratic People's Republic of Korea"] = 'North Korea'
Prevalence_change$location[Prevalence_change$location == "Taiwan (Province of China)"] = 'Taiwan'
Prevalence_change$location[Prevalence_change$location == "Republic of Korea"] = 'South Korea'
Prevalence_change$location[Prevalence_change$location == "United Republic of Tanzania"] = 'Tanzania'
Prevalence_change$location[Prevalence_change$location == "Bolivia (Plurinational State of)"] = 'Bolivia'
Prevalence_change$location[Prevalence_change$location == "Venezuela (Bolivarian Republic of)"] = 'Venezuela'
Prevalence_change$location[Prevalence_change$location == "Czechia"] = 'Czech Republic'
Prevalence_change$location[Prevalence_change$location == "Republic of Moldova"] = 'Moldova'
Prevalence_change$location[Prevalence_change$location == "Viet Nam"] = 'Vietnam'
Prevalence_change$location[Prevalence_change$location == "Lao People's Democratic Republic"] = 'Laos'
Prevalence_change$location[Prevalence_change$location == "Syrian Arab Republic"] = 'Syria'
Prevalence_change$location[Prevalence_change$location == "North Macedonia"] = 'Macedonia'
Prevalence_change$location[Prevalence_change$location == "Micronesia (Federated States of)"] = 'Micronesia'
Prevalence_change$location[Prevalence_change$location == "Macedonia"] = 'North Macedonia'
Prevalence_change$location[Prevalence_change$location == "Trinidad and Tobago"] = 'Trinidad'
a <- Prevalence_change[Prevalence_change$location == "Trinidad",]
a$location <- 'Tobago'
Prevalence_change <- rbind(Prevalence_change,a)
Prevalence_change$location[Prevalence_change$location == "Cabo Verde"] = 'Cape Verde'
Prevalence_change$location[Prevalence_change$location == "United States Virgin Islands"] = 'Virgin Islands'
Prevalence_change$location[Prevalence_change$location == "Antigua and Barbuda"] = 'Antigu'
a <- Prevalence_change[Prevalence_change$location == "Antigu",]
a$location <- 'Barbuda'
Prevalence_change <- rbind(Prevalence_change,a)
Prevalence_change$location[Prevalence_change$location == "Saint Kitts and Nevis"] = 'Saint Kitts'
a <- Prevalence_change[Prevalence_change$location == "Saint Kitts",]
a$location <- 'Nevis'
Prevalence_change <- rbind(Prevalence_change,a)
Prevalence_change$location[Prevalence_change$location == "Côte d'Ivoire"] = 'Ivory Coast'
Prevalence_change$location[Prevalence_change$location == "Saint Vincent and the Grenadines"] = 'Saint Vincent'
a <- Prevalence_change[Prevalence_change$location == "Saint Vincent",]
a$location <- 'Grenadines'
Prevalence_change <- rbind(Prevalence_change,a)
Prevalence_change$location[Prevalence_change$location == "Eswatini"] = 'Swaziland'
Prevalence_change$location[Prevalence_change$location == "Brunei Darussalam"] = 'Brunei'

#合并数据集
Prevalence_change <- full_join(world,Prevalence_change,by = c('region'='location')) %>%
  filter(change != "NA")

###绘图
fig1 <- Prevalence_change %>%
  ggplot()+
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_void()+ #主题设置
  scale_fill_manual(name="Change in cases", #设置图例标题
                    values=c("#ffc412","#c4e437","#12cbc5",
                             "#fea6e0","#ec4c66","#cd3333","#8b2324")) + #手动添加颜色
  theme(legend.position = "right", #设置图例位置
        legend.text = element_text(color="black",
                                   size = 12,
        ), #设置图例文字
        plot.title =  element_blank(), #取消图标题
        panel.grid=element_blank(), #取消图网格线
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  ) 

fig1 ###呈现图片




###Incidence
### Change percentage
###创建新数据集
Incidence_change <- IS[,-c(8,9)] %>% #去除lower，upper列
  #筛选变量
  filter(age =='All ages' &  #年龄
           metric == 'Number' & #绝对例数
           measure =='Incidence'& #发病率数据
           sex =="Both" #性别
  ) %>% 
  filter(year == 1990 |
           year == 2021) %>% #年份
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location != 'Global' &
           location != 'Low SDI' &
           location != 'Low-middle SDI' &
           location != 'Middle SDI' &
           location != 'High-middle SDI' &
           location != 'High SDI' &
           location != 'Andean Latin America' &
           location != 'Australasia' &
           location != 'Caribbean' &
           location != 'Central Asia' &
           location != 'Central Europe' &
           location != 'Central Latin America' &
           location != 'Central Sub-Saharan Africa' &
           location != 'East Asia' &
           location != 'Eastern Europe' &
           location != 'Eastern Sub-Saharan Africa' &
           location != 'High-income Asia Pacific' &
           location != 'High-income North America' &
           location != 'North Africa and Middle East' &
           location != 'Oceania' &
           location != 'South Asia' &
           location != 'Southeast Asia' &
           location != 'Southern Latin America' &
           location != 'Southern Sub-Saharan Africa' &
           location != 'Tropical Latin America' &
           location != 'Western Europe' &
           location != 'Western Sub-Saharan Africa') %>% 
  pivot_wider(names_from = year, values_from = val) %>% #长表格变宽表格
  rename(val_1990 = '1990',
         val_2021 = '2021') %>% #更换列名
  mutate(change = (val_2021-val_1990)/val_1990) %>%  #计算1990-2021年变化值
  dplyr::select(,c(2,8)) #筛选location，change列



###读取绘制世界地图的经纬度等数据
world <- map_data('world')

###创建新数据集,Incidence分析
Incidence_change <- Incidence_change %>%  
  mutate(val2 = cut(change, breaks = c(-0.6,-0.3,0,0.5,1.0,2.0,3.0,100000000),
                    labels = c("30% to 60% decrease","<30% decrease","<50% increase","50% to 100% increase",
                               "100% to 200% increase","200% to 300% increase",'>300% increase'),  
                    include.lowest = T,right = T)) #建立新列，连续变量转换成分类变量，包含最小值所在区间且包括左端点而不包括右端点

###地区名称转换，方便之后数据集合并
Incidence_change$location[Incidence_change$location == 'United States of America'] = 'USA'
Incidence_change$location[Incidence_change$location == 'Russian Federation'] = 'Russia'
Incidence_change$location[Incidence_change$location == 'United Kingdom'] = 'UK'
Incidence_change$location[Incidence_change$location == 'Congo'] = 'Republic of Congo'
Incidence_change$location[Incidence_change$location == "Iran (Islamic Republic of)"] = 'Iran'
Incidence_change$location[Incidence_change$location == "Democratic People's Republic of Korea"] = 'North Korea'
Incidence_change$location[Incidence_change$location == "Taiwan (Province of China)"] = 'Taiwan'
Incidence_change$location[Incidence_change$location == "Republic of Korea"] = 'South Korea'
Incidence_change$location[Incidence_change$location == "United Republic of Tanzania"] = 'Tanzania'
Incidence_change$location[Incidence_change$location == "Bolivia (Plurinational State of)"] = 'Bolivia'
Incidence_change$location[Incidence_change$location == "Venezuela (Bolivarian Republic of)"] = 'Venezuela'
Incidence_change$location[Incidence_change$location == "Czechia"] = 'Czech Republic'
Incidence_change$location[Incidence_change$location == "Republic of Moldova"] = 'Moldova'
Incidence_change$location[Incidence_change$location == "Viet Nam"] = 'Vietnam'
Incidence_change$location[Incidence_change$location == "Lao People's Democratic Republic"] = 'Laos'
Incidence_change$location[Incidence_change$location == "Syrian Arab Republic"] = 'Syria'
Incidence_change$location[Incidence_change$location == "North Macedonia"] = 'Macedonia'
Incidence_change$location[Incidence_change$location == "Micronesia (Federated States of)"] = 'Micronesia'
Incidence_change$location[Incidence_change$location == "Macedonia"] = 'North Macedonia'
Incidence_change$location[Incidence_change$location == "Trinidad and Tobago"] = 'Trinidad'
a <- Incidence_change[Incidence_change$location == "Trinidad",]
a$location <- 'Tobago'
Incidence_change <- rbind(Incidence_change,a)
Incidence_change$location[Incidence_change$location == "Cabo Verde"] = 'Cape Verde'
Incidence_change$location[Incidence_change$location == "United States Virgin Islands"] = 'Virgin Islands'
Incidence_change$location[Incidence_change$location == "Antigua and Barbuda"] = 'Antigu'
a <- Incidence_change[Incidence_change$location == "Antigu",]
a$location <- 'Barbuda'
Incidence_change <- rbind(Incidence_change,a)
Incidence_change$location[Incidence_change$location == "Saint Kitts and Nevis"] = 'Saint Kitts'
a <- Incidence_change[Incidence_change$location == "Saint Kitts",]
a$location <- 'Nevis'
Incidence_change <- rbind(Incidence_change,a)
Incidence_change$location[Incidence_change$location == "Côte d'Ivoire"] = 'Ivory Coast'
Incidence_change$location[Incidence_change$location == "Saint Vincent and the Grenadines"] = 'Saint Vincent'
a <- Incidence_change[Incidence_change$location == "Saint Vincent",]
a$location <- 'Grenadines'
Incidence_change <- rbind(Incidence_change,a)
Incidence_change$location[Incidence_change$location == "Eswatini"] = 'Swaziland'
Incidence_change$location[Incidence_change$location == "Brunei Darussalam"] = 'Brunei'

#合并数据集
Incidence_change <- full_join(world,Incidence_change,by = c('region'='location')) %>%
  filter(change != "NA")

###绘图
fig2 <- Incidence_change %>%
  ggplot()+
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_void()+ #主题设置
  scale_fill_manual(name="Change in cases", #设置图例标题
                    values=c("#ffc412","#c4e437","#12cbc5",
                             "#fea6e0","#ec4c66","#cd3333","#8b2324")) + #手动添加颜色
  theme(legend.position = "right", #设置图例位置
        legend.text = element_text(color="black",
                                   size = 12,
        ), #设置图例文字
        plot.title =  element_blank(), #取消图标题
        panel.grid=element_blank(), #取消图网格线
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  ) 

fig2 ###呈现图片





###Deaths
### Change percentage
###创建新数据集
Deaths_change <- IS[,-c(8,9)] %>% #去除lower，upper列
  #筛选变量
  filter(age =='All ages' &  #年龄
           metric == 'Number' & #绝对例数
           measure =='Deaths'& #死亡率数据
           sex =="Both" #性别
  ) %>% 
  filter(year == 1990 |
           year == 2021) %>% #年份
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location != 'Global' &
           location != 'Low SDI' &
           location != 'Low-middle SDI' &
           location != 'Middle SDI' &
           location != 'High-middle SDI' &
           location != 'High SDI' &
           location != 'Andean Latin America' &
           location != 'Australasia' &
           location != 'Caribbean' &
           location != 'Central Asia' &
           location != 'Central Europe' &
           location != 'Central Latin America' &
           location != 'Central Sub-Saharan Africa' &
           location != 'East Asia' &
           location != 'Eastern Europe' &
           location != 'Eastern Sub-Saharan Africa' &
           location != 'High-income Asia Pacific' &
           location != 'High-income North America' &
           location != 'North Africa and Middle East' &
           location != 'Oceania' &
           location != 'South Asia' &
           location != 'Southeast Asia' &
           location != 'Southern Latin America' &
           location != 'Southern Sub-Saharan Africa' &
           location != 'Tropical Latin America' &
           location != 'Western Europe' &
           location != 'Western Sub-Saharan Africa') %>% 
  pivot_wider(names_from = year, values_from = val) %>% #长表格变宽表格
  rename(val_1990 = '1990',
         val_2021 = '2021') %>% #更换列名
  mutate(change = (val_2021-val_1990)/val_1990) %>%  #计算1990-2021年变化值
  dplyr::select(,c(2,8)) #筛选location，change列



###读取绘制世界地图的经纬度等数据
world <- map_data('world')

###创建新数据集,Deaths分析
Deaths_change <- Deaths_change %>%  
  mutate(val2 = cut(change, breaks = c(-0.7,-0.3,0,0.5,1.0,2.0,3.0,100000000),
                    labels = c("30% to 70% decrease","<30% decrease","<50% increase","50% to 100% increase",
                               "100% to 200% increase","200% to 300% increase",'>300% increase'),  
                    include.lowest = T,right = T)) #建立新列，连续变量转换成分类变量，包含最小值所在区间且包括左端点而不包括右端点

###地区名称转换，方便之后数据集合并
Deaths_change$location[Deaths_change$location == 'United States of America'] = 'USA'
Deaths_change$location[Deaths_change$location == 'Russian Federation'] = 'Russia'
Deaths_change$location[Deaths_change$location == 'United Kingdom'] = 'UK'
Deaths_change$location[Deaths_change$location == 'Congo'] = 'Republic of Congo'
Deaths_change$location[Deaths_change$location == "Iran (Islamic Republic of)"] = 'Iran'
Deaths_change$location[Deaths_change$location == "Democratic People's Republic of Korea"] = 'North Korea'
Deaths_change$location[Deaths_change$location == "Taiwan (Province of China)"] = 'Taiwan'
Deaths_change$location[Deaths_change$location == "Republic of Korea"] = 'South Korea'
Deaths_change$location[Deaths_change$location == "United Republic of Tanzania"] = 'Tanzania'
Deaths_change$location[Deaths_change$location == "Bolivia (Plurinational State of)"] = 'Bolivia'
Deaths_change$location[Deaths_change$location == "Venezuela (Bolivarian Republic of)"] = 'Venezuela'
Deaths_change$location[Deaths_change$location == "Czechia"] = 'Czech Republic'
Deaths_change$location[Deaths_change$location == "Republic of Moldova"] = 'Moldova'
Deaths_change$location[Deaths_change$location == "Viet Nam"] = 'Vietnam'
Deaths_change$location[Deaths_change$location == "Lao People's Democratic Republic"] = 'Laos'
Deaths_change$location[Deaths_change$location == "Syrian Arab Republic"] = 'Syria'
Deaths_change$location[Deaths_change$location == "North Macedonia"] = 'Macedonia'
Deaths_change$location[Deaths_change$location == "Micronesia (Federated States of)"] = 'Micronesia'
Deaths_change$location[Deaths_change$location == "Macedonia"] = 'North Macedonia'
Deaths_change$location[Deaths_change$location == "Trinidad and Tobago"] = 'Trinidad'
a <- Deaths_change[Deaths_change$location == "Trinidad",]
a$location <- 'Tobago'
Deaths_change <- rbind(Deaths_change,a)
Deaths_change$location[Deaths_change$location == "Cabo Verde"] = 'Cape Verde'
Deaths_change$location[Deaths_change$location == "United States Virgin Islands"] = 'Virgin Islands'
Deaths_change$location[Deaths_change$location == "Antigua and Barbuda"] = 'Antigu'
a <- Deaths_change[Deaths_change$location == "Antigu",]
a$location <- 'Barbuda'
Deaths_change <- rbind(Deaths_change,a)
Deaths_change$location[Deaths_change$location == "Saint Kitts and Nevis"] = 'Saint Kitts'
a <- Deaths_change[Deaths_change$location == "Saint Kitts",]
a$location <- 'Nevis'
Deaths_change <- rbind(Deaths_change,a)
Deaths_change$location[Deaths_change$location == "Côte d'Ivoire"] = 'Ivory Coast'
Deaths_change$location[Deaths_change$location == "Saint Vincent and the Grenadines"] = 'Saint Vincent'
a <- Deaths_change[Deaths_change$location == "Saint Vincent",]
a$location <- 'Grenadines'
Deaths_change <- rbind(Deaths_change,a)
Deaths_change$location[Deaths_change$location == "Eswatini"] = 'Swaziland'
Deaths_change$location[Deaths_change$location == "Brunei Darussalam"] = 'Brunei'

#合并数据集
Deaths_change <- full_join(world,Deaths_change,by = c('region'='location')) %>%
  filter(change != "NA")

###绘图
fig3 <- Deaths_change %>%
  ggplot()+
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_void()+ #主题设置
  scale_fill_manual(name="Change in cases", #设置图例标题
                    values=c("#ffc412","#c4e437","#12cbc5",
                             "#fea6e0","#ec4c66","#cd3333","#8b2324")) + #手动添加颜色
  theme(legend.position = "right", #设置图例位置
        legend.text = element_text(color="black",
                                   size = 12,
        ), #设置图例文字
        plot.title =  element_blank(), #取消图标题
        panel.grid=element_blank(), #取消图网格线
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  ) 

fig3 ###呈现图片





###DALYs
### Change percentage
###创建新数据集
DALYs_change <- IS[,-c(8,9)] %>% #去除lower，upper列
  #筛选变量
  filter(age =='All ages' &  #年龄
           metric == 'Number' & #绝对例数
           measure =='DALYs (Disability-Adjusted Life Years)'& #DALYs数据
           sex =="Both" #性别
  ) %>% 
  filter(year == 1990 |
           year == 2021) %>% #年份
  #筛选特定地区，Global+5 SDI regions+21 regions
  filter(location != 'Global' &
           location != 'Low SDI' &
           location != 'Low-middle SDI' &
           location != 'Middle SDI' &
           location != 'High-middle SDI' &
           location != 'High SDI' &
           location != 'Andean Latin America' &
           location != 'Australasia' &
           location != 'Caribbean' &
           location != 'Central Asia' &
           location != 'Central Europe' &
           location != 'Central Latin America' &
           location != 'Central Sub-Saharan Africa' &
           location != 'East Asia' &
           location != 'Eastern Europe' &
           location != 'Eastern Sub-Saharan Africa' &
           location != 'High-income Asia Pacific' &
           location != 'High-income North America' &
           location != 'North Africa and Middle East' &
           location != 'Oceania' &
           location != 'South Asia' &
           location != 'Southeast Asia' &
           location != 'Southern Latin America' &
           location != 'Southern Sub-Saharan Africa' &
           location != 'Tropical Latin America' &
           location != 'Western Europe' &
           location != 'Western Sub-Saharan Africa') %>% 
  pivot_wider(names_from = year, values_from = val) %>% #长表格变宽表格
  rename(val_1990 = '1990',
         val_2021 = '2021') %>% #更换列名
  mutate(change = (val_2021-val_1990)/val_1990) %>%  #计算1990-2021年变化值
  dplyr::select(,c(2,8)) #筛选location，change列



###读取绘制世界地图的经纬度等数据
world <- map_data('world')

###创建新数据集,DALYs分析
DALYs_change <- DALYs_change %>%  
  mutate(val2 = cut(change, breaks = c(-0.7,-0.3,0,0.5,1.0,2.0,3.0,100000000),
                    labels = c("30% to 70% decrease","<30% decrease","<50% increase","50% to 100% increase",
                               "100% to 200% increase","200% to 300% increase",'>300% increase'),  
                    include.lowest = T,right = T)) #建立新列，连续变量转换成分类变量，包含最小值所在区间且包括左端点而不包括右端点

###地区名称转换，方便之后数据集合并
DALYs_change$location[DALYs_change$location == 'United States of America'] = 'USA'
DALYs_change$location[DALYs_change$location == 'Russian Federation'] = 'Russia'
DALYs_change$location[DALYs_change$location == 'United Kingdom'] = 'UK'
DALYs_change$location[DALYs_change$location == 'Congo'] = 'Republic of Congo'
DALYs_change$location[DALYs_change$location == "Iran (Islamic Republic of)"] = 'Iran'
DALYs_change$location[DALYs_change$location == "Democratic People's Republic of Korea"] = 'North Korea'
DALYs_change$location[DALYs_change$location == "Taiwan (Province of China)"] = 'Taiwan'
DALYs_change$location[DALYs_change$location == "Republic of Korea"] = 'South Korea'
DALYs_change$location[DALYs_change$location == "United Republic of Tanzania"] = 'Tanzania'
DALYs_change$location[DALYs_change$location == "Bolivia (Plurinational State of)"] = 'Bolivia'
DALYs_change$location[DALYs_change$location == "Venezuela (Bolivarian Republic of)"] = 'Venezuela'
DALYs_change$location[DALYs_change$location == "Czechia"] = 'Czech Republic'
DALYs_change$location[DALYs_change$location == "Republic of Moldova"] = 'Moldova'
DALYs_change$location[DALYs_change$location == "Viet Nam"] = 'Vietnam'
DALYs_change$location[DALYs_change$location == "Lao People's Democratic Republic"] = 'Laos'
DALYs_change$location[DALYs_change$location == "Syrian Arab Republic"] = 'Syria'
DALYs_change$location[DALYs_change$location == "North Macedonia"] = 'Macedonia'
DALYs_change$location[DALYs_change$location == "Micronesia (Federated States of)"] = 'Micronesia'
DALYs_change$location[DALYs_change$location == "Macedonia"] = 'North Macedonia'
DALYs_change$location[DALYs_change$location == "Trinidad and Tobago"] = 'Trinidad'
a <- DALYs_change[DALYs_change$location == "Trinidad",]
a$location <- 'Tobago'
DALYs_change <- rbind(DALYs_change,a)
DALYs_change$location[DALYs_change$location == "Cabo Verde"] = 'Cape Verde'
DALYs_change$location[DALYs_change$location == "United States Virgin Islands"] = 'Virgin Islands'
DALYs_change$location[DALYs_change$location == "Antigua and Barbuda"] = 'Antigu'
a <- DALYs_change[DALYs_change$location == "Antigu",]
a$location <- 'Barbuda'
DALYs_change <- rbind(DALYs_change,a)
DALYs_change$location[DALYs_change$location == "Saint Kitts and Nevis"] = 'Saint Kitts'
a <- DALYs_change[DALYs_change$location == "Saint Kitts",]
a$location <- 'Nevis'
DALYs_change <- rbind(DALYs_change,a)
DALYs_change$location[DALYs_change$location == "Côte d'Ivoire"] = 'Ivory Coast'
DALYs_change$location[DALYs_change$location == "Saint Vincent and the Grenadines"] = 'Saint Vincent'
a <- DALYs_change[DALYs_change$location == "Saint Vincent",]
a$location <- 'Grenadines'
DALYs_change <- rbind(DALYs_change,a)
DALYs_change$location[DALYs_change$location == "Eswatini"] = 'Swaziland'
DALYs_change$location[DALYs_change$location == "Brunei Darussalam"] = 'Brunei'

#合并数据集
DALYs_change <- full_join(world,DALYs_change,by = c('region'='location')) %>%
  filter(change != "NA")

###绘图
fig4 <- DALYs_change %>%
  ggplot()+
  geom_polygon(aes(x = long, y = lat,group = group,fill=val2),
               colour="black",size=0.5) + #绘制地图
  theme_void()+ #主题设置
  scale_fill_manual(name="Change in cases", #设置图例标题
                    values=c("#ffc412","#c4e437","#12cbc5",
                             "#fea6e0","#ec4c66","#cd3333","#8b2324")) + #手动添加颜色
  theme(legend.position = "right", #设置图例位置
        legend.text = element_text(color="black",
                                   size = 12,
        ), #设置图例文字
        plot.title =  element_blank(), #取消图标题
        panel.grid=element_blank(), #取消图网格线
        axis.title.x = element_blank(), #取消x轴标题
        axis.text.x = element_blank(), #取消x轴标签
        axis.ticks.x = element_blank(), #取消x轴刻度标
        axis.title.y = element_blank(), #取消y轴标题
        axis.text.y = element_blank(), #取消y轴标签
        axis.ticks.y = element_blank(), #取消y轴刻度标
  ) 

fig4 ###呈现图片

###拼图，并创建新图fig
fig <- fig1+fig2+fig3+fig4+
  plot_layout(nrow=2,byrow=T)+ #两列，横向排列
  plot_annotation(tag_levels = "A") #添加字母A-D

###以png格式保存图片
png("P\\fig.png",width = 1800, height = 1000, units = "px")
fig
dev.off()


###以jpg格式保存图片
jpeg("P\\fig.jpg",width = 1800, height = 1000, units = "px")
fig
dev.off()


###以tiff格式保存图片
tiff("P\\fig.tiff",width = 1800, height = 1000, units = "px")
fig
dev.off()
```



**绘图结果：**

<img src="https://s2.loli.net/2024/09/13/opBfmZNQAz6duJW.png" alt="fig" style="zoom:80%;" />

**注：**Figure C中的NA即灰色部分在复现时做出了更改，同时也将图例中的第一个区间 ”30% to 60% decrease“ 改成了 ”30% to 70% decrease“



# 7 年龄、性别总体变化趋势

**文献原Figure 5：**

<img src="https://s2.loli.net/2024/09/14/G7J4CpfMaLNkAym.jpg" alt="gr5" style="zoom:80%;" />



**代码实操：**

```R
###加载R包
library(dplyr)
library(ggplot2)

###创建新数据集IS_age
IS_age <- IS %>% 
  filter(measure == "Prevalence" & #患病率数据
           sex != "Both" & #性别，非Both
           metric == "Rate") %>% #率
  #选择1990，2021年
  filter(year == 1990 |
           year == 2021) %>% 
  #选择特定年龄
  filter(age != "Age-standardized" &
           age != "All ages" &
           age != "<5 years" &
           age != "5-9 years" &
           age != "10-14 years") %>% 
  #选择特定地区
  filter(location == "Global" |
           location == "High SDI" |
           location == "High-middle SDI" |
           location == "Middle SDI" |
           location == "Low-middle SDI" |
           location == "Low SDI") %>% 
  #转化具体值，方便后续做分类变量处理
  mutate(year = case_when(
    year == 1990 ~ 'year_1990',
    year == 2021 ~ 'year_2021')) %>% 
  #转化具体值，方便后续做分组排序
  mutate(
    location = ifelse(
      location=='Global','a',ifelse(
        location=="High SDI",'b',ifelse(
          location=="High-middle SDI",'c',ifelse(
            location=="Middle SDI",'d',ifelse(
              location=="Low-middle SDI",'e','f'))))))

###绘图，并赋值p
p <- ggplot(IS_age, aes(x = val, y = age, shape = sex,color = year)) +
  geom_point(size = 2) + #绘制散点图
  geom_line(aes(group = interaction(age, year))) + #绘制线图
  #手动添加颜色，并更改变量名称
  scale_color_manual(values = c("year_1990" = "#0071d8", "year_2021" = "#d60058"),
                     labels = c(
                       "year_1990"='1990',
                       'year_2021'='2021'
                     )) +
  #手动更改点的形状
  scale_shape_manual(values = c("Male" = 16, "Female" = 17)) +
  #设置主题
  theme_bw() +
  theme(
    legend.position = "bottom", #将图例置于图片底端
    panel.grid.major = element_line(color = "gray90"), #网格线大区间颜色
    panel.grid.minor = element_line(color = "gray95"), #网格线小区间颜色
  ) +
  #设置图片分组，x轴区间不限制，3列，并更改分组标题名称
  facet_wrap(~location,scales = "free_x",
             ncol = 3,
             labeller = labeller(location=c(
               a="Global Prevalence rate (per 100k)",
               b="High SDI Prevalence rate (per 100k)",
               c="High-middle SDI Prevalence rate (per 100k)",
               d="Middle SDI Prevalence rate (per 100k)",
               e="Low-middle SDI Prevalence rate (per 100k)",
               f="Low SDI Prevalence rate (per 100k)"
             ))) +
  #设置轴标题名称
  labs(title = "", 
       x = "Prevalence rate (per 100k)", 
       y = 'Age Group')

###以png格式储存图片
png("P\\Figure 5.png", width = 1000, height = 800, units = "px")
p
dev.off()

###以jpg格式储存图片
jpeg("P\\Figure 5.jpg", width = 1000, height = 800, units = "px")
p
dev.off()

###以tiff格式储存图片
tiff("P\\Figure 5.tiff", width = 1000, height = 800, units = "px")
p
dev.off() 
```



**绘图结果：**

<img src="https://s2.loli.net/2024/09/14/1gNn8FpxDuPtE3T.png" alt="Figure 5" style="zoom:80%;" />



# 8 风险因素分布

**文献原Figure S7：**

<img src="https://s2.loli.net/2024/09/14/W6tAh2nMgdHbJO5.jpg" alt="mmc7" style="zoom:80%;" />



代码实操：

```R
###加载R包
library(ggplot2)


### 设定变量自定义顺序
order <- c('Global','High SDI','High-middle SDI','Middle SDI','Low-middle SDI',
           'Low SDI','Andean Latin America','Australasia','Caribbean','Central Asia',
           'Central Europe','Central Latin America','Central Sub-Saharan Africa',
           'East Asia','Eastern Europe','Eastern Sub-Saharan Africa','High-income Asia Pacific',
           'High-income North America','North Africa and Middle East','Oceania',
           'South Asia','Southeast Asia','Southern Latin America','Southern Sub-Saharan Africa',
           'Tropical Latin America','Western Europe','Western Sub-Saharan Africa')
order <- rev(order)
order <- factor(1:length(order),labels = order)

locations <- c('Low physical activity','High alcohol use',
               'High body-mass index','Tobacco')
locations <- factor(1:length(locations),labels = locations)

###将自定义顺序赋予研究数据集的对应变量上
RF_ad <- RF
RF_ad$location <- factor(RF_ad$location,levels = levels(order))
RF_ad$rei <- factor(RF_ad$rei,levels = levels(locations))

###绘图，并赋值p
p <- ggplot(RF_ad,aes(x=location,y=val*100,group=measure)) +
  geom_bar(aes(fill=measure),stat="identity",position='dodge')+ #画柱状图，并列格式
  scale_y_continuous(limits=c(0,100))+ #限定y轴区间
  #自定义颜色，更改变量名
  scale_fill_manual(values=c("#b54537",'#2070ad'),
                    labels=c(
                      'DALYs (Disability-Adjusted Life Years)'='DALYs'
                    ))+ 
  theme_bw() + #设置主题
  facet_wrap(~rei,scales="free_x",ncol=4)+ #分组绘图，x轴区间不限制，4列
  coord_flip()+ #反转图像
  #增加百分比文字
  geom_text(aes(label=paste0(round(val*100,1),"%"),y=val*100+15),
            position=position_dodge(0.9),vjust=0,
            size =2.5) +
  labs(x='',
       y='') #去除轴标题

###以png格式储存图片
png("P\\Figure S7.png", width = 1000, height = 1000, units = "px")
p
dev.off()

###以jpg格式储存图片
jpeg("P\\Figure S7.jpg", width = 1000, height = 1000, units = "px")
p
dev.off()

###以tiff格式储存图片
tiff("P\\Figure S7.tiff", width = 1000, height = 1000, units = "px")
p
dev.off() 
```



**绘图结果：**

<img src="https://s2.loli.net/2024/09/14/5mfkXBFyza7TuY1.png" alt="Figure S7" style="zoom:80%;" />



# 9 未来趋势预测

**文献原Figure 6：**

<img src="https://s2.loli.net/2024/09/14/PruvpXEWD3aAUVx.jpg" alt="gr6"  />



**代码实操：**

```R
###加载R包
if (!require('INLA')) install.packages("INLA",repos = "https://inla.r-inla-download.org/R/stable",dependencies = TRUE)
if (!require('BAPC')) install.packages("BAPC",repos = "http://R-Forge.R-project.org",dependencies = TRUE)
library(BAPC)
library(INLA)
library(data.table)
library(tidyverse)
library(dplyr)
library(ggplot2)
library(epitools)
library(reshape2)
library(openxlsx)

### 读取标准化人口数据
age_stand <- read.xlsx('Age standard.xlsx') 
###计算各年龄层标准人口占比
agestand <- c(age_stand$Percent_Population %>% as.numeric())/sum(age_stand$Percent_Population)

### 疾病年龄结构
ages <- c('<5 years','5-9 years','10-14 years','15-19 years','20-24 years',
          '25-29 years','30-34 years','35-39 years','40-44 years','45-49 years',
          '50-54 years','55-59 years','60-64 years','65-69 years','70-74 years',
          '75-79 years','80-84 years','85-89 years','90-94 years','95+ years')




###分别提取男性和女性Ischemic stroke患病率数据
###男性数据
### 获取男性，全球，不同年龄组的发病数
IS_Male_Prevalence <- IS %>% 
  filter(age %in% ages &
           measure == 'Prevalence' &
           metric == 'Number' &
           location == "Global" &
           sex == "Male") %>% 
  mutate(age = factor(age,
                      levels = ages))

### dcast的表达式：~的左边是行名，右边是列名，即两个变量的分类矩阵表格
IS_Male_Prevalence_n <- reshape2::dcast(data = IS_Male_Prevalence, year~age, value.var = "val") 

rownames(IS_Male_Prevalence_n) <- IS_Male_Prevalence_n$year ### 对行名重新命名
IS_Male_Prevalence_n <- IS_Male_Prevalence_n[,-1] %>% # 去除第一列变量year
  apply(c(1,2), as.numeric) %>% 
  apply(c(1,2), round) %>% 
  as.data.frame()  # 将数据转换成数值型,然后取整

###女性数据
### 获取女性，全球，不同年龄组的发病数
IS_Female_Prevalence <- IS %>% 
  filter(age %in% ages &
           measure == 'Prevalence' &
           metric == 'Number' &
           location == "Global" &
           sex == "Female") %>% 
  mutate(age = factor(age,
                      levels = ages))

### dcast的表达式：~的左边是行名，右边是列名，即两个变量的分类矩阵表格
IS_Female_Prevalence_n <- reshape2::dcast(data = IS_Female_Prevalence, year~age, value.var = "val") 

rownames(IS_Female_Prevalence_n) <- IS_Female_Prevalence_n$year ### 对行名重新命名
IS_Female_Prevalence_n <- IS_Female_Prevalence_n[,-1] %>% # 去除第一列变量year
  apply(c(1,2), as.numeric) %>% 
  apply(c(1,2), round) %>% 
  as.data.frame()  # 将数据转换成数值型,然后取整

###性别汇总
IS_Both_Prevalence_n <- IS_Male_Prevalence_n +IS_Female_Prevalence_n

### 读取人口学数据,筛选变量并进行名称更改
GBD_population <- fread('Population\\IHME-GBD_2021_DATA-07af5542-1.csv') %>% as.data.frame() %>% 
  filter(age_name %in% ages) %>% 
  dplyr::select(6,8,11,12) %>% 
  rename(sex=sex_name,
         age=age_name,
         pop=val) %>% 
  mutate(age=factor(age,
                    levels=ages))

###查看前六行数据
head(GBD_population)


#### 读取预测人口数据,筛选变量并进行名称更改
GBD_population_prediction <- fread('IHME_POP_2017_2100_POP_REFERENCE_Y2020M05D01.csv') %>% as.data.frame() %>% 
  mutate(age_group_name=sub(' to ',replacement = '-', age_group_name)) %>% 
  mutate(age_group_name=sub('95 plus',replacement = '95+', age_group_name)) %>% 
  mutate(age_group_name=str_c(age_group_name,' years')) %>% 
  filter(location_name == "Global") %>% 
  filter(age_group_name %in% ages) %>% 
  filter(year_id %in% 2022:2040) %>% 
  dplyr::select(4,6,7,14) %>%
  rename(year=year_id,
         age=age_group_name,
         pop=val) 

### 整合<5 years数据
GBD_population_prediction_under5 <- fread('IHME_POP_2017_2100_POP_REFERENCE_Y2020M05D01.csv') %>% as.data.frame() %>% 
  filter(age_group_name %in% c(
    "Early Neonatal", "Late Neonatal",
    "Post Neonatal", "1 to 4"
  )) %>% 
  filter(location_name == "Global") %>% 
  filter(year_id %in% 2022:2040) %>% 
  group_by(sex,year_id) %>% 
  reframe(sex,
          age="<5 years",
          pop=sum(val)) %>% 
  rename(year=year_id) %>% 
  distinct()

### 合并所有预测人口学数据
GBD_population_prediction <- GBD_population_prediction %>% 
  rbind(GBD_population_prediction_under5) %>% 
  mutate(age=factor(age,
                    levels=ages))

unique(GBD_population_prediction$age)


### 合并现人口数+预测人口数
GBD <- rbind(GBD_population,GBD_population_prediction)


### 提取对应性别的人口学数据
GBD_Global_Male <- GBD %>% filter(sex == 'Male')
GBD_Global_Female <-  GBD %>% filter(sex == 'Female')

GBD_Global_Male_n <- reshape2::dcast(data = GBD_Global_Male, 
                                     year ~ age ,
                                     value.var = c("pop")) %>% 
  select(-1) 
GBD_Global_Female_n <- reshape2::dcast(data = GBD_Global_Female, 
                                       year ~ age,
                                       value.var = c("pop")) %>% 
  select(-1)

###性别汇总
GBD_Global_Both_n <- GBD_Global_Female_n + GBD_Global_Male_n 

### 建立IS_pro数据集，用'NA'进行填充，并将行、列名进行重新命名成一样的名字，方便后面的合并
IS_pro <- matrix(data = NA, nrow = 2040-2021, ncol = ncol(GBD_Global_Male_n)) %>% as.data.frame()
rownames(IS_pro) <- seq(2022,2040,1)
colnames(IS_pro) <-  names(IS_Male_Prevalence_n)

IS_Male_Prevalence_n  <- rbind(IS_Male_Prevalence_n , IS_pro)
IS_Female_Prevalence_n  <- rbind(IS_Female_Prevalence_n , IS_pro)
IS_Both_Prevalence_n <- rbind(IS_Both_Prevalence_n , IS_pro)

###BAPC模型拟合
Male_esoph <- APCList(IS_Male_Prevalence_n, GBD_Global_Male_n, gf = 5)
Male_bapc_result <- BAPC(Male_esoph, predict = list(npredict = 19, retro = T),
                         secondDiff = FALSE, stdweight = agestand, verbose = F)

Female_esoph <- APCList(IS_Female_Prevalence_n, GBD_Global_Female_n, gf = 5)
Female_bapc_result <- BAPC(Female_esoph, predict = list(npredict = 19, retro = T),
                           secondDiff = FALSE, stdweight = agestand, verbose = F)

Both_esoph <- APCList(IS_Both_Prevalence_n, GBD_Global_Both_n, gf = 5)
Both_bapc_result <- BAPC(Both_esoph, predict = list(npredict = 19, retro = T),
                         secondDiff = FALSE, stdweight = agestand, verbose = F)

### 标准患病率——agestd.rate函数
Male_ASR <- agestd.rate(x = Male_bapc_result) %>% as.data.frame()
Male_ASR$mean <- Male_ASR$mean*100000
Male_ASR$year <- rownames(Male_ASR)

Female_ASR <- agestd.rate(x =Female_bapc_result) %>% as.data.frame()
Female_ASR$mean <- Female_ASR$mean*100000
Female_ASR$year <- rownames(Female_ASR)

Both_ASR <- agestd.rate(x =Both_bapc_result) %>% as.data.frame()
Both_ASR$mean <- Both_ASR$mean*100000
Both_ASR$year <- rownames(Both_ASR)


### 用到qapc函数将0.025以及0.975写入到BAPC结果中
Male_bapc_result <- qapc(Male_bapc_result,percentiles=c(0.025,0.975))
Female_bapc_result <- qapc(Female_bapc_result,percentiles=c(0.025,0.975))
Both_bapc_result <- qapc(Both_bapc_result,percentiles=c(0.025,0.975))

### 获取ASR以及95%CrI
Male_ASR <- agestd.rate(x = Male_bapc_result) %>% as.data.frame()*10^5
Female_ASR <- agestd.rate(x = Female_bapc_result) %>% as.data.frame()*10^5
Both_ASR <- agestd.rate(x = Both_bapc_result) %>% as.data.frame()*10^5
###创建时间列
Male_ASR$year <- 1990:2040
Female_ASR$year <- 1990:2040
Both_ASR$year <- 1990:2040
###创建性别列
Male_ASR$sex <- 'Male'
Female_ASR$sex <- 'Female'
Both_ASR$sex <- 'Both'


###合并成一个数据集
ASR <- Male_ASR %>% 
  rbind(Female_ASR) %>% 
  rbind(Both_ASR) %>% 
  rename(ASR=mean,
         lower='0.025Q',
         upper='0.975Q') %>% 
  dplyr::select(6,5,1,3,4)


###绘图
p <- ggplot() +
  geom_line(data=subset(ASR,year %in% 1990:2021),aes(year,ASR,color='Global',linetype='Observed')) + #绘制1990-2021年直线
  geom_line(data=subset(ASR,year %in% 2021:2040),aes(year,ASR,linetype="Predicted"),color="#565bab") + #绘制2021-2040年直线
  geom_ribbon(data=subset(ASR,year %in% 2021:2040),aes(x=year,ymin=lower,ymax=upper),fill='#565bab',alpha=.1) + #绘制2021-2040年区间条带
  geom_vline(xintercept = 2021,linetype=2)+ #绘制2021竖虚线
  scale_y_continuous(breaks=seq(600,1200,200))+ #调整y轴值标签
  scale_linetype_manual(name="line",
                        values=c('Observed'=1,
                                 "Predicted"=2 #手动更改线形状，并更改命名
                        )) +
  scale_color_manual(name="group",
                     values=c('Global'='#565bab'
                     )) + #手动改更改线条颜色，并更改命名
  facet_wrap(~sex) + #分组绘图，以性别为依据
  labs(title = "Prevalence", 
       y = 'Age-standardzied rate (per 100000 population)') #增加图标题和更改y轴名称



###以png格式储存图片
png("p\\Prevalence.png",width = 1000, height = 800, units = "px")
p
dev.off()

###以jpg格式储存图片
jpeg("p\\Prevalence.jpg",width = 1000, height = 800, units = "px")
p
dev.off()

###以tiff格式储存图片
tiff("p\\Prevalence.tiff",width = 1000, height = 800, units = "px")
p
dev.off()




###分别提取男性和女性Ischemic stroke发病率数据
###男性数据
### 获取男性，全球，不同年龄组的发病数
IS_Male_Incidence <- IS %>% 
  filter(age %in% ages &
           measure == 'Incidence' &
           metric == 'Number' &
           location == "Global" &
           sex == "Male") %>% 
  mutate(age = factor(age,
                      levels = ages))

### dcast的表达式：~的左边是行名，右边是列名，即两个变量的分类矩阵表格
IS_Male_Incidence_n <- reshape2::dcast(data = IS_Male_Incidence, year~age, value.var = "val") 

rownames(IS_Male_Incidence_n) <- IS_Male_Incidence_n$year ### 对行名重新命名
IS_Male_Incidence_n <- IS_Male_Incidence_n[,-1] %>% # 去除第一列变量year
  apply(c(1,2), as.numeric) %>% 
  apply(c(1,2), round) %>% 
  as.data.frame()  # 将数据转换成数值型,然后取整

###女性数据
### 获取女性，全球，不同年龄组的发病数
IS_Female_Incidence <- IS %>% 
  filter(age %in% ages &
           measure == 'Incidence' &
           metric == 'Number' &
           location == "Global" &
           sex == "Female") %>% 
  mutate(age = factor(age,
                      levels = ages))

### dcast的表达式：~的左边是行名，右边是列名，即两个变量的分类矩阵表格
IS_Female_Incidence_n <- reshape2::dcast(data = IS_Female_Incidence, year~age, value.var = "val") 

rownames(IS_Female_Incidence_n) <- IS_Female_Incidence_n$year ### 对行名重新命名
IS_Female_Incidence_n <- IS_Female_Incidence_n[,-1] %>% # 去除第一列变量year
  apply(c(1,2), as.numeric) %>% 
  apply(c(1,2), round) %>% 
  as.data.frame()  # 将数据转换成数值型,然后取整

###性别汇总
IS_Both_Incidence_n <- IS_Male_Incidence_n +IS_Female_Incidence_n

### 读取人口学数据,筛选变量并进行名称更改
GBD_population <- fread('Population\\IHME-GBD_2021_DATA-07af5542-1.csv') %>% as.data.frame() %>% 
  filter(age_name %in% ages) %>% 
  dplyr::select(6,8,11,12) %>% 
  rename(sex=sex_name,
         age=age_name,
         pop=val) %>% 
  mutate(age=factor(age,
                    levels=ages))

###查看前六行数据
head(GBD_population)


#### 读取预测人口数据,筛选变量并进行名称更改
GBD_population_prediction <- fread('IHME_POP_2017_2100_POP_REFERENCE_Y2020M05D01.csv') %>% as.data.frame() %>% 
  mutate(age_group_name=sub(' to ',replacement = '-', age_group_name)) %>% 
  mutate(age_group_name=sub('95 plus',replacement = '95+', age_group_name)) %>% 
  mutate(age_group_name=str_c(age_group_name,' years')) %>% 
  filter(location_name == "Global") %>% 
  filter(age_group_name %in% ages) %>% 
  filter(year_id %in% 2022:2040) %>% 
  dplyr::select(4,6,7,14) %>%
  rename(year=year_id,
         age=age_group_name,
         pop=val) 

### 整合<5 years数据
GBD_population_prediction_under5 <- fread('IHME_POP_2017_2100_POP_REFERENCE_Y2020M05D01.csv') %>% as.data.frame() %>% 
  filter(age_group_name %in% c(
    "Early Neonatal", "Late Neonatal",
    "Post Neonatal", "1 to 4"
  )) %>% 
  filter(location_name == "Global") %>% 
  filter(year_id %in% 2022:2040) %>% 
  group_by(sex,year_id) %>% 
  reframe(sex,
          age="<5 years",
          pop=sum(val)) %>% 
  rename(year=year_id) %>% 
  distinct()

### 合并所有预测人口学数据
GBD_population_prediction <- GBD_population_prediction %>% 
  rbind(GBD_population_prediction_under5) %>% 
  mutate(age=factor(age,
                    levels=ages))

unique(GBD_population_prediction$age)


### 合并现人口数+预测人口数
GBD <- rbind(GBD_population,GBD_population_prediction)


### 提取对应性别的人口学数据
GBD_Global_Male <- GBD %>% filter(sex == 'Male')
GBD_Global_Female <-  GBD %>% filter(sex == 'Female')

GBD_Global_Male_n <- reshape2::dcast(data = GBD_Global_Male, 
                                     year ~ age ,
                                     value.var = c("pop")) %>% 
  select(-1) 
GBD_Global_Female_n <- reshape2::dcast(data = GBD_Global_Female, 
                                       year ~ age,
                                       value.var = c("pop")) %>% 
  select(-1)

###性别汇总
GBD_Global_Both_n <- GBD_Global_Female_n + GBD_Global_Male_n 

### 建立IS_pro数据集，用'NA'进行填充，并将行、列名进行重新命名成一样的名字，方便后面的合并
IS_pro <- matrix(data = NA, nrow = 2040-2021, ncol = ncol(GBD_Global_Male_n)) %>% as.data.frame()
rownames(IS_pro) <- seq(2022,2040,1)
colnames(IS_pro) <-  names(IS_Male_Incidence_n)

IS_Male_Incidence_n <- rbind(IS_Male_Incidence_n , IS_pro)
IS_Female_Incidence_n <- rbind(IS_Female_Incidence_n , IS_pro)
IS_Both_Incidence_n <- rbind(IS_Both_Incidence_n , IS_pro)

###BAPC模型拟合
Male_esoph <- APCList(IS_Male_Incidence_n, GBD_Global_Male_n, gf = 5)
Male_bapc_result <- BAPC(Male_esoph, predict = list(npredict = 19, retro = T),
                         secondDiff = FALSE, stdweight = agestand, verbose = F)

Female_esoph <- APCList(IS_Female_Incidence_n, GBD_Global_Female_n, gf = 5)
Female_bapc_result <- BAPC(Female_esoph, predict = list(npredict = 19, retro = T),
                           secondDiff = FALSE, stdweight = agestand, verbose = F)

Both_esoph <- APCList(IS_Both_Incidence_n, GBD_Global_Both_n, gf = 5)
Both_bapc_result <- BAPC(Both_esoph, predict = list(npredict = 19, retro = T),
                         secondDiff = FALSE, stdweight = agestand, verbose = F)

### 标准发病率——agestd.rate函数
Male_ASR <- agestd.rate(x = Male_bapc_result) %>% as.data.frame()
Male_ASR$mean <- Male_ASR$mean*100000
Male_ASR$year <- rownames(Male_ASR)

Female_ASR <- agestd.rate(x =Female_bapc_result) %>% as.data.frame()
Female_ASR$mean <- Female_ASR$mean*100000
Female_ASR$year <- rownames(Female_ASR)

Both_ASR <- agestd.rate(x =Both_bapc_result) %>% as.data.frame()
Both_ASR$mean <- Both_ASR$mean*100000
Both_ASR$year <- rownames(Both_ASR)


### 用到qapc函数将0.025以及0.975写入到BAPC结果中
Male_bapc_result <- qapc(Male_bapc_result,percentiles=c(0.025,0.975))
Female_bapc_result <- qapc(Female_bapc_result,percentiles=c(0.025,0.975))
Both_bapc_result <- qapc(Both_bapc_result,percentiles=c(0.025,0.975))

### 获取ASR以及95%CrI
Male_ASR <- agestd.rate(x = Male_bapc_result) %>% as.data.frame()*10^5
Female_ASR <- agestd.rate(x = Female_bapc_result) %>% as.data.frame()*10^5
Both_ASR <- agestd.rate(x = Both_bapc_result) %>% as.data.frame()*10^5
###创建时间列
Male_ASR$year <- 1990:2040
Female_ASR$year <- 1990:2040
Both_ASR$year <- 1990:2040
###创建性别列
Male_ASR$sex <- 'Male'
Female_ASR$sex <- 'Female'
Both_ASR$sex <- 'Both'


###合并成一个数据集
ASR <- Male_ASR %>% 
  rbind(Female_ASR) %>% 
  rbind(Both_ASR) %>% 
  rename(ASR=mean,
         lower='0.025Q',
         upper='0.975Q') %>% 
  dplyr::select(6,5,1,3,4)


###绘图
p <- ggplot() +
  geom_line(data=subset(ASR,year %in% 1990:2021),aes(year,ASR,color='Global',linetype='Observed')) + #绘制1990-2021年直线
  geom_line(data=subset(ASR,year %in% 2021:2040),aes(year,ASR,linetype="Predicted"),color="#ce9494") + #绘制2021-2040年直线
  geom_ribbon(data=subset(ASR,year %in% 2021:2040),aes(x=year,ymin=lower,ymax=upper),fill='#ce9494',alpha=.1) + #绘制2021-2040年区间条带
  geom_vline(xintercept = 2021,linetype=2)+ #绘制2021竖虚线
  scale_y_continuous(breaks=seq(600,1200,200))+ #调整y轴值标签
  scale_linetype_manual(name="line",
                        values=c('Observed'=1,
                                 "Predicted"=2 #手动更改线形状，并更改命名
                        )) +
  scale_color_manual(name="group",
                     values=c('Global'='#ce9494'
                     )) + #手动改更改线条颜色，并更改命名
  facet_wrap(~sex) + #分组绘图，以性别为依据
  labs(title = "Incidence", 
       y = 'Age-standardzied rate (per 100000 population)') #增加图标题和更改y轴名称



###以png格式储存图片
png("p\\Incidence.png",width = 1000, height = 800, units = "px")
p
dev.off()

###以jpg格式储存图片
jpeg("p\\Incidence.jpg",width = 1000, height = 800, units = "px")
p
dev.off()

###以tiff格式储存图片
tiff("p\\Incidence.tiff",width = 1000, height = 800, units = "px")
p
dev.off()





###分别提取男性和女性Ischemic stroke死亡率数据
###男性数据
### 获取男性，全球，不同年龄组的发病数
IS_Male_Deaths <- IS %>% 
  filter(age %in% ages &
           measure == 'Deaths' &
           metric == 'Number' &
           location == "Global" &
           sex == "Male") %>% 
  mutate(age = factor(age,
                      levels = ages))

### dcast的表达式：~的左边是行名，右边是列名，即两个变量的分类矩阵表格
IS_Male_Deaths_n <- reshape2::dcast(data = IS_Male_Deaths, year~age, value.var = "val") 

rownames(IS_Male_Deaths_n) <- IS_Male_Deaths_n$year ### 对行名重新命名
IS_Male_Deaths_n <- IS_Male_Deaths_n[,-1] %>% # 去除第一列变量year
  apply(c(1,2), as.numeric) %>% 
  apply(c(1,2), round) %>% 
  as.data.frame()  # 将数据转换成数值型,然后取整

###女性数据
### 获取女性，全球，不同年龄组的发病数
IS_Female_Deaths <- IS %>% 
  filter(age %in% ages &
           measure == 'Deaths' &
           metric == 'Number' &
           location == "Global" &
           sex == "Female") %>% 
  mutate(age = factor(age,
                      levels = ages))

### dcast的表达式：~的左边是行名，右边是列名，即两个变量的分类矩阵表格
IS_Female_Deaths_n <- reshape2::dcast(data = IS_Female_Deaths, year~age, value.var = "val") 

rownames(IS_Female_Deaths_n) <- IS_Female_Deaths_n$year ### 对行名重新命名
IS_Female_Deaths_n <- IS_Female_Deaths_n[,-1] %>% # 去除第一列变量year
  apply(c(1,2), as.numeric) %>% 
  apply(c(1,2), round) %>% 
  as.data.frame()  # 将数据转换成数值型,然后取整

###性别汇总
IS_Both_Deaths_n <- IS_Male_Deaths_n +IS_Female_Deaths_n

### 读取人口学数据,筛选变量并进行名称更改
GBD_population <- fread('Population\\IHME-GBD_2021_DATA-07af5542-1.csv') %>% as.data.frame() %>% 
  filter(age_name %in% ages) %>% 
  dplyr::select(6,8,11,12) %>% 
  rename(sex=sex_name,
         age=age_name,
         pop=val) %>% 
  mutate(age=factor(age,
                    levels=ages))

###查看前六行数据
head(GBD_population)


#### 读取预测人口数据,筛选变量并进行名称更改
GBD_population_prediction <- fread('IHME_POP_2017_2100_POP_REFERENCE_Y2020M05D01.csv') %>% as.data.frame() %>% 
  mutate(age_group_name=sub(' to ',replacement = '-', age_group_name)) %>% 
  mutate(age_group_name=sub('95 plus',replacement = '95+', age_group_name)) %>% 
  mutate(age_group_name=str_c(age_group_name,' years')) %>% 
  filter(location_name == "Global") %>% 
  filter(age_group_name %in% ages) %>% 
  filter(year_id %in% 2022:2040) %>% 
  dplyr::select(4,6,7,14) %>%
  rename(year=year_id,
         age=age_group_name,
         pop=val) 

### 整合<5 years数据
GBD_population_prediction_under5 <- fread('IHME_POP_2017_2100_POP_REFERENCE_Y2020M05D01.csv') %>% as.data.frame() %>% 
  filter(age_group_name %in% c(
    "Early Neonatal", "Late Neonatal",
    "Post Neonatal", "1 to 4"
  )) %>% 
  filter(location_name == "Global") %>% 
  filter(year_id %in% 2022:2040) %>% 
  group_by(sex,year_id) %>% 
  reframe(sex,
          age="<5 years",
          pop=sum(val)) %>% 
  rename(year=year_id) %>% 
  distinct()

### 合并所有预测人口学数据
GBD_population_prediction <- GBD_population_prediction %>% 
  rbind(GBD_population_prediction_under5) %>% 
  mutate(age=factor(age,
                    levels=ages))

unique(GBD_population_prediction$age)


### 合并现人口数+预测人口数
GBD <- rbind(GBD_population,GBD_population_prediction)


### 提取对应性别的人口学数据
GBD_Global_Male <- GBD %>% filter(sex == 'Male')
GBD_Global_Female <-  GBD %>% filter(sex == 'Female')

GBD_Global_Male_n <- reshape2::dcast(data = GBD_Global_Male, 
                                     year ~ age ,
                                     value.var = c("pop")) %>% 
  select(-1) 
GBD_Global_Female_n <- reshape2::dcast(data = GBD_Global_Female, 
                                       year ~ age,
                                       value.var = c("pop")) %>% 
  select(-1)

###性别汇总
GBD_Global_Both_n <- GBD_Global_Female_n + GBD_Global_Male_n 

### 建立IS_pro数据集，用'NA'进行填充，并将行、列名进行重新命名成一样的名字，方便后面的合并
IS_pro <- matrix(data = NA, nrow = 2040-2021, ncol = ncol(GBD_Global_Male_n)) %>% as.data.frame()
rownames(IS_pro) <- seq(2022,2040,1)
colnames(IS_pro) <-  names(IS_Male_Deaths_n)

IS_Male_Deaths_n <- rbind(IS_Male_Deaths_n , IS_pro)
IS_Female_Deaths_n <- rbind(IS_Female_Deaths_n , IS_pro)
IS_Both_Deaths_n <- rbind(IS_Both_Deaths_n , IS_pro)

###BAPC模型拟合
Male_esoph <- APCList(IS_Male_Deaths_n, GBD_Global_Male_n, gf = 5)
Male_bapc_result <- BAPC(Male_esoph, predict = list(npredict = 19, retro = T),
                         secondDiff = FALSE, stdweight = agestand, verbose = F)

Female_esoph <- APCList(IS_Female_Deaths_n, GBD_Global_Female_n, gf = 5)
Female_bapc_result <- BAPC(Female_esoph, predict = list(npredict = 19, retro = T),
                           secondDiff = FALSE, stdweight = agestand, verbose = F)

Both_esoph <- APCList(IS_Both_Deaths_n, GBD_Global_Both_n, gf = 5)
Both_bapc_result <- BAPC(Both_esoph, predict = list(npredict = 19, retro = T),
                         secondDiff = FALSE, stdweight = agestand, verbose = F)

### 标准死亡率——agestd.rate函数
Male_ASR <- agestd.rate(x = Male_bapc_result) %>% as.data.frame()
Male_ASR$mean <- Male_ASR$mean*100000
Male_ASR$year <- rownames(Male_ASR)

Female_ASR <- agestd.rate(x =Female_bapc_result) %>% as.data.frame()
Female_ASR$mean <- Female_ASR$mean*100000
Female_ASR$year <- rownames(Female_ASR)

Both_ASR <- agestd.rate(x =Both_bapc_result) %>% as.data.frame()
Both_ASR$mean <- Both_ASR$mean*100000
Both_ASR$year <- rownames(Both_ASR)


### 用到qapc函数将0.025以及0.975写入到BAPC结果中
Male_bapc_result <- qapc(Male_bapc_result,percentiles=c(0.025,0.975))
Female_bapc_result <- qapc(Female_bapc_result,percentiles=c(0.025,0.975))
Both_bapc_result <- qapc(Both_bapc_result,percentiles=c(0.025,0.975))

### 获取ASR以及95%CrI
Male_ASR <- agestd.rate(x = Male_bapc_result) %>% as.data.frame()*10^5
Female_ASR <- agestd.rate(x = Female_bapc_result) %>% as.data.frame()*10^5
Both_ASR <- agestd.rate(x = Both_bapc_result) %>% as.data.frame()*10^5
###创建时间列
Male_ASR$year <- 1990:2040
Female_ASR$year <- 1990:2040
Both_ASR$year <- 1990:2040
###创建性别列
Male_ASR$sex <- 'Male'
Female_ASR$sex <- 'Female'
Both_ASR$sex <- 'Both'


###合并成一个数据集
ASR <- Male_ASR %>% 
  rbind(Female_ASR) %>% 
  rbind(Both_ASR) %>% 
  rename(ASR=mean,
         lower='0.025Q',
         upper='0.975Q') %>% 
  dplyr::select(6,5,1,3,4)


###绘图
p <- ggplot() +
  geom_line(data=subset(ASR,year %in% 1990:2021),aes(year,ASR,color='Global',linetype='Observed')) + #绘制1990-2021年直线
  geom_line(data=subset(ASR,year %in% 2021:2040),aes(year,ASR,linetype="Predicted"),color="#847aad") + #绘制2021-2040年直线
  geom_ribbon(data=subset(ASR,year %in% 2021:2040),aes(x=year,ymin=lower,ymax=upper),fill='#847aad',alpha=.1) + #绘制2021-2040年区间条带
  geom_vline(xintercept = 2021,linetype=2)+ #绘制2021竖虚线
  scale_y_continuous(breaks=seq(600,1200,200))+ #调整y轴值标签
  scale_linetype_manual(name="line",
                        values=c('Observed'=1,
                                 "Predicted"=2 #手动更改线形状，并更改命名
                        )) +
  scale_color_manual(name="group",
                     values=c('Global'='#847aad'
                     )) + #手动改更改线条颜色，并更改命名
  facet_wrap(~sex) + #分组绘图，以性别为依据
  labs(title = "Deaths", 
       y = 'Age-standardzied rate (per 100000 population)') #增加图标题和更改y轴名称



###以png格式储存图片
png("p\\Deaths.png",width = 1000, height = 800, units = "px")
p
dev.off()

###以jpg格式储存图片
jpeg("p\\Deaths.jpg",width = 1000, height = 800, units = "px")
p
dev.off()

###以tiff格式储存图片
tiff("p\\Deaths.tiff",width = 1000, height = 800, units = "px")
p
dev.off()



###分别提取男性和女性Ischemic stroke DALYs数据
###男性数据
### 获取男性，全球，不同年龄组的发病数
IS_Male_DALYs <- IS %>% 
  filter(age %in% ages &
           measure == 'DALYs (Disability-Adjusted Life Years)' &
           metric == 'Number' &
           location == "Global" &
           sex == "Male") %>% 
  mutate(age = factor(age,
                      levels = ages))

### dcast的表达式：~的左边是行名，右边是列名，即两个变量的分类矩阵表格
IS_Male_DALYs_n <- reshape2::dcast(data = IS_Male_DALYs, year~age, value.var = "val") 

rownames(IS_Male_DALYs_n) <- IS_Male_DALYs_n$year ### 对行名重新命名
IS_Male_DALYs_n <- IS_Male_DALYs_n[,-1] %>% # 去除第一列变量year
  apply(c(1,2), as.numeric) %>% 
  apply(c(1,2), round) %>% 
  as.data.frame()  # 将数据转换成数值型,然后取整

###女性数据
### 获取女性，全球，不同年龄组的发病数
IS_Female_DALYs <- IS %>% 
  filter(age %in% ages &
           measure == 'DALYs (Disability-Adjusted Life Years)' &
           metric == 'Number' &
           location == "Global" &
           sex == "Female") %>% 
  mutate(age = factor(age,
                      levels = ages))

### dcast的表达式：~的左边是行名，右边是列名，即两个变量的分类矩阵表格
IS_Female_DALYs_n <- reshape2::dcast(data = IS_Female_DALYs, year~age, value.var = "val") 

rownames(IS_Female_DALYs_n) <- IS_Female_DALYs_n$year ### 对行名重新命名
IS_Female_DALYs_n <- IS_Female_DALYs_n[,-1] %>% # 去除第一列变量year
  apply(c(1,2), as.numeric) %>% 
  apply(c(1,2), round) %>% 
  as.data.frame()  # 将数据转换成数值型,然后取整

###性别汇总
IS_Both_DALYs_n <- IS_Male_DALYs_n +IS_Female_DALYs_n

### 读取人口学数据,筛选变量并进行名称更改
GBD_population <- fread('Population\\IHME-GBD_2021_DATA-07af5542-1.csv') %>% as.data.frame() %>% 
  filter(age_name %in% ages) %>% 
  dplyr::select(6,8,11,12) %>% 
  rename(sex=sex_name,
         age=age_name,
         pop=val) %>% 
  mutate(age=factor(age,
                    levels=ages))

###查看前六行数据
head(GBD_population)


#### 读取预测人口数据,筛选变量并进行名称更改
GBD_population_prediction <- fread('IHME_POP_2017_2100_POP_REFERENCE_Y2020M05D01.csv') %>% as.data.frame() %>% 
  mutate(age_group_name=sub(' to ',replacement = '-', age_group_name)) %>% 
  mutate(age_group_name=sub('95 plus',replacement = '95+', age_group_name)) %>% 
  mutate(age_group_name=str_c(age_group_name,' years')) %>% 
  filter(location_name == "Global") %>% 
  filter(age_group_name %in% ages) %>% 
  filter(year_id %in% 2022:2040) %>% 
  dplyr::select(4,6,7,14) %>%
  rename(year=year_id,
         age=age_group_name,
         pop=val) 

### 整合<5 years数据
GBD_population_prediction_under5 <- fread('IHME_POP_2017_2100_POP_REFERENCE_Y2020M05D01.csv') %>% as.data.frame() %>% 
  filter(age_group_name %in% c(
    "Early Neonatal", "Late Neonatal",
    "Post Neonatal", "1 to 4"
  )) %>% 
  filter(location_name == "Global") %>% 
  filter(year_id %in% 2022:2040) %>% 
  group_by(sex,year_id) %>% 
  reframe(sex,
          age="<5 years",
          pop=sum(val)) %>% 
  rename(year=year_id) %>% 
  distinct()

### 合并所有预测人口学数据
GBD_population_prediction <- GBD_population_prediction %>% 
  rbind(GBD_population_prediction_under5) %>% 
  mutate(age=factor(age,
                    levels=ages))

unique(GBD_population_prediction$age)


### 合并现人口数+预测人口数
GBD <- rbind(GBD_population,GBD_population_prediction)


### 提取对应性别的人口学数据
GBD_Global_Male <- GBD %>% filter(sex == 'Male')
GBD_Global_Female <-  GBD %>% filter(sex == 'Female')

GBD_Global_Male_n <- reshape2::dcast(data = GBD_Global_Male, 
                                     year ~ age ,
                                     value.var = c("pop")) %>% 
  select(-1) 
GBD_Global_Female_n <- reshape2::dcast(data = GBD_Global_Female, 
                                       year ~ age,
                                       value.var = c("pop")) %>% 
  select(-1)

###性别汇总
GBD_Global_Both_n <- GBD_Global_Female_n + GBD_Global_Male_n 

### 建立IS_pro数据集，用'NA'进行填充，并将行、列名进行重新命名成一样的名字，方便后面的合并
IS_pro <- matrix(data = NA, nrow = 2040-2021, ncol = ncol(GBD_Global_Male_n)) %>% as.data.frame()
rownames(IS_pro) <- seq(2022,2040,1)
colnames(IS_pro) <-  names(IS_Male_DALYs_n)

IS_Male_DALYs_n <- rbind(IS_Male_DALYs_n , IS_pro)
IS_Female_DALYs_n <- rbind(IS_Female_DALYs_n , IS_pro)
IS_Both_DALYs_n <- rbind(IS_Both_DALYs_n , IS_pro)

###BAPC模型拟合
Male_esoph <- APCList(IS_Male_DALYs_n, GBD_Global_Male_n, gf = 5)
Male_bapc_result <- BAPC(Male_esoph, predict = list(npredict = 19, retro = T),
                         secondDiff = FALSE, stdweight = agestand, verbose = F)

Female_esoph <- APCList(IS_Female_DALYs_n, GBD_Global_Female_n, gf = 5)
Female_bapc_result <- BAPC(Female_esoph, predict = list(npredict = 19, retro = T),
                           secondDiff = FALSE, stdweight = agestand, verbose = F)

Both_esoph <- APCList(IS_Both_DALYs_n, GBD_Global_Both_n, gf = 5)
Both_bapc_result <- BAPC(Both_esoph, predict = list(npredict = 19, retro = T),
                         secondDiff = FALSE, stdweight = agestand, verbose = F)

### 标准DALYs——agestd.rate函数
Male_ASR <- agestd.rate(x = Male_bapc_result) %>% as.data.frame()
Male_ASR$mean <- Male_ASR$mean*100000
Male_ASR$year <- rownames(Male_ASR)

Female_ASR <- agestd.rate(x =Female_bapc_result) %>% as.data.frame()
Female_ASR$mean <- Female_ASR$mean*100000
Female_ASR$year <- rownames(Female_ASR)

Both_ASR <- agestd.rate(x =Both_bapc_result) %>% as.data.frame()
Both_ASR$mean <- Both_ASR$mean*100000
Both_ASR$year <- rownames(Both_ASR)


### 用到qapc函数将0.025以及0.975写入到BAPC结果中
Male_bapc_result <- qapc(Male_bapc_result,percentiles=c(0.025,0.975))
Female_bapc_result <- qapc(Female_bapc_result,percentiles=c(0.025,0.975))
Both_bapc_result <- qapc(Both_bapc_result,percentiles=c(0.025,0.975))

### 获取ASR以及95%CrI
Male_ASR <- agestd.rate(x = Male_bapc_result) %>% as.data.frame()*10^5
Female_ASR <- agestd.rate(x = Female_bapc_result) %>% as.data.frame()*10^5
Both_ASR <- agestd.rate(x = Both_bapc_result) %>% as.data.frame()*10^5
###创建时间列
Male_ASR$year <- 1990:2040
Female_ASR$year <- 1990:2040
Both_ASR$year <- 1990:2040
###创建性别列
Male_ASR$sex <- 'Male'
Female_ASR$sex <- 'Female'
Both_ASR$sex <- 'Both'


###合并成一个数据集
ASR <- Male_ASR %>% 
  rbind(Female_ASR) %>% 
  rbind(Both_ASR) %>% 
  rename(ASR=mean,
         lower='0.025Q',
         upper='0.975Q') %>% 
  dplyr::select(6,5,1,3,4)


###绘图
p <- ggplot() +
  geom_line(data=subset(ASR,year %in% 1990:2021),aes(year,ASR,color='Global',linetype='Observed')) + #绘制1990-2021年直线
  geom_line(data=subset(ASR,year %in% 2021:2040),aes(year,ASR,linetype="Predicted"),color="#b68664") + #绘制2021-2040年直线
  geom_ribbon(data=subset(ASR,year %in% 2021:2040),aes(x=year,ymin=lower,ymax=upper),fill='#b68664',alpha=.1) + #绘制2021-2040年区间条带
  geom_vline(xintercept = 2021,linetype=2)+ #绘制2021竖虚线
  scale_y_continuous(breaks=seq(600,1200,200))+ #调整y轴值标签
  scale_linetype_manual(name="line",
                        values=c('Observed'=1,
                                 "Predicted"=2 #手动更改线形状，并更改命名
                        )) +
  scale_color_manual(name="group",
                     values=c('Global'='#b68664'
                     )) + #手动改更改线条颜色，并更改命名
  facet_wrap(~sex) + #分组绘图，以性别为依据
  labs(title = "DALYs", 
       y = 'Age-standardzied rate (per 100000 population)') #增加图标题和更改y轴名称



###以png格式储存图片
png("p\\DALYs.png",width = 1000, height = 800, units = "px")
p
dev.off()

###以jpg格式储存图片
jpeg("p\\DALYs.jpg",width = 1000, height = 800, units = "px")
p
dev.off()

###以tiff格式储存图片
tiff("p\\DALYs.tiff",width = 1000, height = 800, units = "px")
p
dev.off()
```



**绘图结果：**

1）Prevalence

<img src="https://s2.loli.net/2024/09/18/lLd6m7AkTZhB4UK.png" alt="Prevalence" style="zoom:80%;" />



2）Incidence

<img src="https://s2.loli.net/2024/09/18/H42Y1i7cA8QfDxs.png" alt="Incidence" style="zoom:80%;" />



3）Deaths

<img src="https://s2.loli.net/2024/09/18/TgnyYIw8HRLWkjX.png" alt="Deaths" style="zoom:80%;" />



4）DALYs

<img src="https://s2.loli.net/2024/09/18/BsKAvc1jN2ex9Qp.png" alt="DALYs" style="zoom:80%;" />



# 小结

（1）课程资料包括**GBD数据库对标柳叶刀子刊-从选题到复现全部代码（数据提取、趋势图、趋势表、世界地图、年龄变化趋势、世界地图、总体变化趋势、风险因素分布、未来趋势预测）、课程数据和结果、对标文章、课程讲义等**。关注公众号“诺维医研”，回复“`gbd2401`”，获取课程资料链接。

<img src="https://s2.loli.net/2024/10/24/AazocY64kM2wpHC.jpg" alt="image-20241024200943" style="zoom:80%;" />



（2）**医学公共数据数据库学习训练营**已开班，论文指导精英班学员可获取推荐审稿人信息，欢迎咨询课程助理！

[了解详情|医学公共数据库学习训练营](http://mp.weixin.qq.com/s?__biz=MzAwNzc1MTA1Mw==&mid=2247491271&idx=1&sn=9d2ffddddd7c0b15462c32f9334cd0a9&chksm=9b780a25ac0f8333bce016a8825c9532b99eac62147a87af29dd845ca902a67853c708cc99d9&scene=21#wechat_redirect)

![image-训练营](https://s2.loli.net/2024/10/20/JwE64MTIUsKYvkf.png)

(http://mp.weixin.qq.com/s?__biz=MzAwNzc1MTA1Mw==&mid=2247491271&idx=1&sn=9d2ffddddd7c0b15462c32f9334cd0a9&chksm=9b780a25ac0f8333bce016a8825c9532b99eac62147a87af29dd845ca902a67853c708cc99d9&scene=21#wechat_redirect)

（3）**数据提取和数据分析定制**，具体扫码咨询课程助理。

<img src="https://gitee.com/shenghuaxiong/typora/raw/master/img/202410150704181.png" alt="image-20240914140249094" style="zoom: 67%;" />

（4）视频号课程推荐
