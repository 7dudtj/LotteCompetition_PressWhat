# LotteCompetition_PressWhat
* Team PressWhat, for Lotte Big Data Competition
* What to Press? PressWhat!
* 고객구매 데이터에 기반한 예측 모델 개발 및 개인화 마케팅 전략 제안
* 제공된 데이터는 대외비이므로, 해당 레포지토리에서는 공개되지 않음
---
## EDA를 통한 인사이트 도출

<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/67851701/188295625-33ff61dc-bc95-40ac-b941-823aa78354bc.png">
</p>  

* EDA를 통해 여러 결과와 지표를 확인할 수 있었음
* 그 중, 오프라인에서의 엘페이 이용률이 저조하다는 점에 주목함
* 자세한 EDA 내용은 [PressWhat 결과보고서](https://github.com/7dudtj/LotteCompetition_PressWhat/blob/main/Report.pdf) 에서 확인할 수 있습니다.
---
## 마케팅 전략 수립

<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/67851701/188295746-f84df7b6-024f-4b1b-97b9-9bd65038d695.png">
</p>  

* 어떻게 오프라인에서의 엘페이 이용을 유도할 수 있을까?
* 연령/성별에 따라 선호하는 구매 품목을 오프라인에서 엘페이로 구매하도록 하는 이벤트를 진행하자!
* 연령/성별에 따라 선호하는 구매 품목은 어떻게 될까?
* <ins>예측 모델을 개발</ins>하여 선호하는 구매 희망 품목을 알아보자!
---
## 예측 모델 개발

<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/67851701/188295831-0792b481-c1e2-40aa-8455-982c719d0369.png">
</p> 

* 외부 데이터를 도입하여 모델의 성능 향상
* 총 12개 그룹으로 인구 분포를 분류
* 엘페이 데이터, 인구 분포 데이터, 상품 구매 정보 데이터를 이용하여 모델 개발
* 예측 모델에 대한 자세한 내용은 [그룹 별 상품 구매 예측 모델 코드](https://github.com/7dudtj/LotteCompetition_PressWhat/blob/main/Code/Model/Lpay_Model.ipynb) 에서 확인할 수 있습니다.
---
## 예측 결과

<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/67851701/188296063-200f666d-72fc-442d-925d-4861bddee371.png">
</p> 

* 20대 남성이 구매하고자 하는 상품들의 예측 결과 (예시)
* 다른 그룹에 대한 예측 결과는 [PressWhat 결과보고서](https://github.com/7dudtj/LotteCompetition_PressWhat/blob/main/Report.pdf) 에서 확인할 수 있습니다.
---
## 마케팅 전략

<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/67851701/188296173-e7f21381-eb1e-4749-bb33-76e9a3fb54c7.png">
</p> 

* 20대를 대상으로 하는 마케팅 전략 (예시)
* 다른 그룹에 대한 마케팅 전략은 [PressWhat 결과보고서](https://github.com/7dudtj/LotteCompetition_PressWhat/blob/main/Report.pdf) 에서 확인할 수 있습니다.
---
## 마케팅 기대 효과

<p align="center">
  <img width="800" src="https://user-images.githubusercontent.com/67851701/188296269-814d914a-f86c-468d-afd2-0bd00ede1c20.png">
</p> 

* 엘페이 첫 이용자 수 증가
* 오프라인 엘페이 이용률 증가
* 잠재적 우수고객 확보
* 간편결제 시장 점유율 확보
* 엘페이 생태계 견고화
* 제휴사 매출 증가
---
## Copyleft / End User License
<details>
<summary>
내용 보기
</summary>
<div markdown="1">
<img align="right" src="http://opensource.org/trademarks/opensource/OSI-Approved-License-100x137.png">

The class is licensed under the [MIT License](http://opensource.org/licenses/MIT):

Copyright &copy; 2022 [7dudtj](https://github.com/7dudtj), [NeverAsking](https://github.com/NeverAsking), and [kgh1030](https://github.com/kgh1030).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
  </div>
  </details>
