<h1>NCF를 이용한 학생-기업 과목 추천</h1>
<img src = https://github.com/now1256/Seminar/assets/94968792/b4902ba8-f20f-444f-92ac-fd89e10ad1ef width=80% height=auto>
<h2>Data</h2>
<li> 강원대학교 내부 학생 수강 데이터 </li>
<h2>reference</h2> 
<li> https://arxiv.org/pdf/1708.05031.pdf?source=post_page </li>
<li> https://github.com/doheelab/NCF </li>
<h2>Update</h2>
<li> 2023.09.25 </li>
<h2>version</h2>
python=3.7, torch == 1.7.1 + cu110 
<h2>Result</h2>

| | Hit-ratio |Prcision|Recall
|--|--|--|--|
| 10 | 0.83 |0.19|0.03|
| 50 | 0.96 |0.13|0.13|
| 100| 0.97 |0.09|0.19|
