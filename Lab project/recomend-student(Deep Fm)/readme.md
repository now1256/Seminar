<h1>Deep FM를 이용한 학생-기업 과목 추천</h1>
<img src = https://github.com/now1256/Seminar/assets/94968792/8bf2c384-e913-4e6e-854f-9391a6238146 width=60% height=auto>
<h2>Data</h2>
<li> 강원대학교 내부 학생 수강 데이터 </li>
<h2>reference</h2> 
<li> https://arxiv.org/abs/1703.04247 </li>
<li> https://github.com/shenweichen/DeepCTR-Torch/blob/master/deepctr_torch/models/deepfm.py </li>
<h2> Update</h2>
<li> 2023.11.25 </li>
<h2>version</h2>
python=3.9, torch == 1.12.1 + cu11.6
<h2>Result</h2>

| Prcision|Recall
|--|--|--|
| 10  |0.09|0.05|
| 25  |0.09|0.11|
| 50  |0.08|0.18|
| 100 |0.06|0.27|

