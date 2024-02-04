<h1>xDeep FM를 이용한 학생-기업 과목 추천</h1>
<img src = https://github.com/now1256/Seminar/assets/94968792/dfdcb4bb-7d0a-44d2-a041-200583656365 width=60% height=auto>
<h2>Data</h2>
<li> 강원대학교 내부 학생 수강 데이터 </li>
<h2>reference</h2> 
<li> https://arxiv.org/pdf/1803.05170.pdf </li>
<li> https://github.com/shenweichen/DeepCTR-Torch/blob/master/deepctr_torch/models/xdeepfm.py </li>
<h2> Update</h2>
<li> 2023.11.25 </li>
<h2>version</h2>
python=3.9, torch == 1.12.1 + cu11.6
<h2>Result</h2>

| |Prcision|Recall|mAP|
|--|--|--|--|
| 10  |0.184|0.103|0.348|
| 25  |0.146|0.204|0.299|
| 50  |0.115|0.318|0.253|
| 100 |0.084|0.463|0.213|

