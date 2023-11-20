# 🚉 CBNU assignment : Recommand the area where electronic car can build charge station


## Abstract
> 광양시에 전기차 충전할 수 있는 위치 각 20곳 추천하기

<h2> 👪 Team </h2>

> Name : Infrain

<h3> 👪 Members </h3>
<table>
  <tr>
    <td> <div align=center>  1 </div> </td>
    <td> <div align=center>  2 </div> </td>
  </tr>
  <tr>
    <td> <div align=center> <b>김다운</b> </div> </td>
    <td> <div align=center> <b>이상헌</b> </div> </td>
  </tr>
  <tr>
    <td> <img alt="Github" src ="https://github.com/kingwangzzang1234/conventional-repo/assets/76687996/35d08f55-b916-4e57-a60f-8f0d869ca640" width="200" height="300"/> </td>
    <td> <img alt="Github" src ="https://github.com/kingwangzzang1234/conventional-repo/assets/76687996/a7ad8130-03ed-4ee1-b886-51fc0cf15ac1" width="200" height="300"/> </td>
  </tr>
  <tr>
    <td> <div align=center> <a href="https://github.com/Daw-ny"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </div> </td>
    <td> <div align=center> <a href="https://github.com/dlt3"> <img alt="Github" src ="https://img.shields.io/badge/Github-181717.svg?&style=plastic&logo=Github&logoColor=white"/> </div> </td>
  </tr>
</table>

<h3> 🛑 Role & Rule </h3>

> ### Ground Rule
> - 업무가 과중되지 않게 하기 위해 같이 있을때만 진행한다.
> - 회의를 통해 각자의 역할을 정하고 다음 회의까지 진행된 상황을 공유하여 서로의 피드백을 듣고 필요한 부분은 수정하였다.


<table>
  <tr>
    <td> <div align=center> <b> 이름 </b> </div> </td>
    <td> <div align=center> <b> 역할 </b> </div> </td>
  </tr>
  <tr>
    <td> <div align=center> <b> 김다운 </b> </div> </td>
    <td> <b>EDA </b>(데이터 별 결측치 및 이상치 탐색, 대한민국 지도 시각화)</br>
         <b>파생변수 </b>(교통 상황과 관련된 변수 생성 및 전처리)</td>
  </tr>
  <tr>
    <td> <div align=center> <b> 이상헌 </b> </div> </td>
    <td> <b>EDA </b>(데이터 별 결측치 및 이상치 탐색)</br>
	       <b>데이터 크롤링과 병합 </b>(자기 조직화 모델 적합, 추천 위치 20곳 선정)</td>
  </tr>
</table>

<h3> 📽️ Project Intro </h3>

<table>
  <tr>
    <td> <div align=center> <b> Subject </b> </div> </td>
    <td> 전기충전소 완속, 급속 조건에 따른 20곳 각각 추천 알고리즘 구현 </td>
  </tr>
  <tr>
    <td> <div align=center> <b> Processing </b> </div> </td>
    <td> 1. 데이터의 각 칼럼이 어떤 의미를 갖는지 확인하고 각 칼럼의 분포 및 결측, 이상치 존재여부 확인 </br>
  2. 데이터 맞춤 전처리 및 이상치 대치 이후 EDA적용 및 SOM(자기 조직화 학습 모델) 적합
  </td>
  </tr>
  <tr>
    <td> <div align=center> <b> Develop Enviroment </b> </div> </td>
    <td> <tt>Tool</tt>: Jupyter Notebook </td>
  </tr>
  <tr>
    <td> <div align=center> <b> Communication Enviroment </b> </div> </td>
    <td> <tt> Whiteboard </tt>: 사용변수 EDA를 위한 역할분담, 아이디어 브레인 스토밍 기록 </br>
         <tt> Offline Meeting </tt>: 실시간 대면 회의 </td>
  </tr>
</table>

<h3> 📆 Project Procedure </h3>

>  자세한 진행 내용은 [InfraIn](https://www.notion.so/Team-Project-2-10907b994ad248e58b9265bfdb57532e?pvs=4)에서 확인하실 수 있습니다.

<h3> 📂 Project Structure </h3>

> - Code
>> 01_project_eda.ipynb
>> - cirrhosis 관련 데이터 탐색과 간단한 heatmap 코드가 포함되어 있습니다.
>>
>> 02_Cirrhoisi_detail.ipynb
>> - 본격적으로 각 변수의 분포를 확인하고 ANOVA, Tukey's HSD를 진행하였습니다.
>>
>> 03_cancer.ipynb
>> - cancer 데이터를 활용하여 plotly animation figure을 생성하였습니다.
>>
>> 04_hepatitis.ipynb
>> - hepatitis B에 대해 변수의 분포와 관계에 대해 확인하고 logistic regression을 적합하였습니다.
>>
>> 05_codebook.ipynb
>> - 코드북을 쉽게 만들기 위해 사용했습니다.
>>
>> 06_hepatitis_c.ipynb
>> - 기초통계량 표를 만들기 위해 활용하였습니다.
