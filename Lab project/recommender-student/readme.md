<h1>NCF를 이용한 학생-기업 과목 추천</h1>
<img src = https://github.com/now1256/Seminar/assets/94968792/5c3d7681-baba-4892-a02d-7f597951c755 width=80% height=auto>
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

| |Prcision|Recall|
|--|--|--|
| 10  |0.09|0.05|
| 25  |0.09|0.11|
| 50  |0.08|0.18|
| 100 |0.06|0.27|

<h1>xDeep FM를 이용한 학생-기업 과목 추천</h1>
<img src = https://github.com/now1256/Seminar/assets/94968792/881a8c1a-4eda-4c80-ace5-461d5a889cb5 width=60% height=auto>
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

<h1>DCNv2를 이용한 학생-기업 과목 추천</h1>
<img src = https://github.com/now1256/Seminar/assets/94968792/1a2aefac-8842-4c69-a323-93346be0a96f width=80% height=auto>
<h2>Data</h2>
<li> 강원대학교 내부 학생 수강 데이터 </li>
<h2>reference</h2> 
<li> https://arxiv.org/pdf/2008.13535.pdf </li>
<li>https://velog.io/@jinseock95/%EB%85%BC%EB%AC%B8DCN-V2-Improved-Deep-Cross-Network-and-Practical-Lessons-for-Web-scale-Learning-to-Rank-Systems2020-Ruoxi-Wang</li>
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

<h1>AFN+를 이용한 학생-기업 과목 추천</h1>
<img src = https://github.com/now1256/Seminar/assets/94968792/574c934f-5d4a-4438-99ca-a4a2c3ee6a99 width=80% height=auto>
<h2>Data</h2>
<li> 강원대학교 내부 학생 수강 데이터 </li>
<h2>reference</h2> 
<li> https://arxiv.org/abs/1909.03276 </li>
<h2>Update</h2>
<li> 2024.02.05 </li>
<h2>version</h2>
python=3.9, torch == 1.12.1 + cu113
<h2>Result</h2>

| |Prcision|Recall|mAP|
|--|--|--|--|
| 10 | 0.194 |0.109|0.352|
| 25 | 0.153 |0.215|0.304|
| 50 | 0.118 |0.331|0.260|
| 100| 0.085 |0.478|0.221|

<h1>EulerNet를 이용한 학생-기업 과목 추천</h1>
<img src = https://github.com/now1256/Seminar/assets/94968792/d206f571-2bb8-40cd-b4ce-3abb5adc21ff width=70% height=auto>
<h2>Data</h2>
<li> 강원대학교 내부 학생 수강 데이터 </li>
<h2>reference</h2> 
<li> https://arxiv.org/abs/2304.10711 </li>
<li>https://github.com/RUCAIBox/EulerNet</li>
<h2>Update</h2>
<li> 2024.02.05 </li>
<h2>version</h2>
python=3.9, torch == 1.12.1 + cu113
<h2>Result</h2>

| |Prcision|Recall|mAP|
|--|--|--|--|
| 10 | 0.110 |0.109|0.363|
| 25 | 0.156 |0.219|0.309|
| 50 | 0.121 |0.338|0.263|
| 100| 0.088 |0.488|0.223|






