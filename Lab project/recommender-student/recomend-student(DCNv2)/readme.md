<h1>DCNv2를 이용한 학생-기업 과목 추천</h1>
<img src = https://github.com/now1256/Seminar/assets/94968792/bc41fc2c-f7f2-4af9-bdf1-6554faf2de45 width=80% height=auto>
<h2>Data</h2>
<li> 강원대학교 내부 학생 수강 데이터 </li>
<h2>reference</h2> 
<li> https://arxiv.org/pdf/2008.13535.pdf </li>
<h2>Update</h2>
<li> 2024.02.05 </li>
<h2>version</h2>
python=3.9, torch == 1.12.1 + cu113
<h2>Result</h2>

| |Prcision|Recall|mAP|
|--|--|--|--|
| 10 | 0.193 |0.104|0.355|
| 25 | 0.154 |0.208|0.304|
| 50 | 0.121 |0.325|0.258|
| 100| 0.089 |0.475|0.218|
