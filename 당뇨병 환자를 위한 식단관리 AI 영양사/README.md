# 당뇨병 환자를 위한 식단관리 AI 영양사



## :pushpin:**프로젝트요약**
- 대상기업과 한양대 창업지원단이 공동으로 진행한 푸드테크 공모전이었습니다. 공모전은 식품 관련 서비스업에 <br/>정보통신기술(ICT) 등의 혁신적인 서비스를 접목한 창의적인 아이디어 발굴을 목적으로 개최되었습니다.<br/>
&nbsp; 
- 프로젝트는 2022.04 ~ 2022.05 동안 진행되었고 프로젝트를 함께한 팀원은 저를 포함해 총 7명이었습니다.<br/>
&nbsp; 




## :pushpin:**문제인식**
![스크린샷(1387)](https://user-images.githubusercontent.com/99727385/175970665-b9c38402-dd47-4e59-93da-7b20aa7beccd.png)
>  대한당뇨병협회의 2020년 자료조사에 따르면 약 4명 중 3명 이상의 당뇨 환자들은 혈당 조절에 실패하고 영양 불균형의 문제를<br/>가지고 있습니다. 식단 관리가 당뇨 관리의 핵심 요소임에도 번거로움, 지식 부족 등을 이유로 제대로 이뤄지지 않기 때문입니다.<br/>


![스크린샷(1388)](https://user-images.githubusercontent.com/99727385/175970669-0b274103-5c5e-4302-9f51-03610eaf1058.png)
> 현재 당뇨환자의 식단관리 방법은 임상 영양사와 상담이나 당뇨식 도시락의 정기 구매 서비스등이 있습니다. 하지만 임상 영양사를 이용하는 방식은 비용이 많이 들고, 상담 이후 관리의 지속성이 떨어집니다. 당뇨식 정기 구매방식 역시 경제적 부담이 있고 식단 선택에 자율성이 없습니다.<br/>이에 대한 대안으로 저희 서비스와 같이 식단을 제공해주는 서비스가 시도되고 있지만, 식품 데이터가 충분치 못해 식단의 다양성이 확보되지 않았고, 사용자 입장에서의 편리성이 떨어졌습니다. 또한 좋은 평가를 받는 해외 앱 서비스는 해외 음식 위주로 식단이 구성되기 때문에 우리나라 사람들이 이용하기에 부적합합니다.<br/>



![스크린샷(1389)](https://user-images.githubusercontent.com/99727385/175970672-bae487e4-67f9-4af4-89b0-2e3a12f89e99.png)
> 당뇨환자들의 식단관리를 돕기위해 저희는 당뇨병 환자들을 위한 식단 관리 AI영양사 서비스를 기획했습니다. 저희 서비스에서는 서비스 사용자의 데이터를 입력받아 사용자 개인에 맞는 식단을 추천해줍니다. 머신러닝과 알고리즘 기반의 식단 추천 자동화를 통해서 식단관리에 드는 비용을 획기적으로 줄일 수 있습니다. 뿐만 아니라 추천 식단의 간편구매 기능을 제공하고, 조리식품의 경우에는 식단의 레시피까지 제공함으로써 사용자가 편리하게 식단을 관리할 수 있도록 하였습니다.<br/>

&nbsp; 

## :pushpin:**핵심기능**
![스크린샷(1390)](https://user-images.githubusercontent.com/99727385/175970673-931eb745-92e4-42cb-9c9f-bca43d2bea89.png)
>  기술 구현을 위해 식품의약품 안전처에서 제공하는 총 9만여 종의 방대한 식품 데이터를 활용합니다. 이를 통해 소비자 별로 가지각색인 성향에 맞추면서도 높은 다양성을 가진 추천 식단을 구성할 수 있습니다. 뿐만 아니라 3백만 장의 다양한 음식 사진을 바탕으로 사용자 편의성을 증진하는 다양한 시각 정보를 제공할 수 있습니다.
활용 기술로는 식단 제약조건에 따른 식단 최적화 알고리즘과 식단 선호도를 반영해서 식단을 추천해주는 추천 알고리즘이 있습니다.


![스크린샷(1391)](https://user-images.githubusercontent.com/99727385/175970675-efbe388c-669e-4be8-b57a-88c2b67cc120.png)
> 수집한 데이터와 알고리즘을 바탕으로 통합 DB를 구축하고 사전에 입력받은 사용자 데이터와 연계하면 사용자에 맞는 식단을 추천할 수 있습니다. 사진은 전체적인 서비스의 구상도입니다. 또한 추천받은 식단에 대해서도 사용자가 자유롭게 변경할 수 있도록 구성하였고, 이렇게 변경되는 식단을 바탕으로 사용자의 식품 기호도를 파악해 보다 고도화된 추천 식단을 제공하는 피드백 구조를 갖습니다.

![스크린샷(1392)](https://user-images.githubusercontent.com/99727385/175970678-bf8334a3-1b31-4961-9da0-eeaba93fbb78.png)
> 앱을 실행하면 최초 사용자의 개인정보를 입력받습니다. 사용자의 알레르기 여부 등을 조사해 메뉴추천에 반영합니다. 뿐만 아니라 조리식단과 즉석식품에 비율을 선택할 수 있도록 함으로써, 요리 경험이 없거나 직장생활로 조리에 번거로움을 느끼는 사용자들이 편리하게 식단관리를 할 수 있습니다.

![스크린샷(1393)](https://user-images.githubusercontent.com/99727385/175970679-8c5fe278-8a4b-42a6-b2a2-d4ba7f748c47.png)
> 앞선 사용자 설문 데이터와 이전에 식품 DB를 기반으로 추천 식단을 제공합니다. 제안된 식단에서 비선호 메뉴는 비슷한 영양조건을 충족하는 다른 메뉴로 바꿀 수 있도록 이용자의 자율성을 부여합니다. 수정 전 메뉴는 비선호 식품으로, 수정 후 메뉴는 선호 식품으로 가중치가 부여 돼 다음 식단 추천은 이러한 선호도를 바탕으로 보다 고도화됩니다.

![스크린샷(1394)](https://user-images.githubusercontent.com/99727385/175970680-766a1be6-3976-4951-9d64-104886e1ea64.png)
> 사용자는 추천 조리식단의 레시피를 확인은 물론 필요한 재료도 시각적으로 확인할 수 있습니다. 조리 및 구매의 번거로움을 해소하고자, 주간 추천 식단의 조리 총량을 환산한 레시피와 더불어 추천식단 식료품을 한번에 구매할 수 있는 구매서비스를 제공합니다. 대상을 예로 든다면 식단 추천메뉴에 백김치가 있다면 종가집 브랜드의 백김치를 쉽게 구매할 수 있도록 지원하는 방식입니다.

&nbsp; 

## :pushpin:**비즈니스모델**
![스크린샷(1395)](https://user-images.githubusercontent.com/99727385/175970685-1057190c-1bcc-40f2-938a-4bdd06d4dca3.png)
> 저희 서비스의 수익채널은 크게 B2B와 B2C로 나눌 수 있습니다. B2B의 경우, 식품 구매 서비스를 바탕으로 식품유통업체로부터의 로열티, 식품 제조업체 제품개발 연구에 필요한 식품 기호 데이터 사업, 고객 건강관리가 중요한 보험사와의 제휴 등이 있습니다. B2C의 경우 무료로 제공하는 추천 서비스 외에, 다양한 고객군에 맞춘 프리미엄 서비스를 제공하고자 합니다.

&nbsp; 

## :pushpin:**시장현황 및 차별점**
![스크린샷(1396)](https://user-images.githubusercontent.com/99727385/175970686-ea22d746-e313-426d-b6d7-38126bb06f6b.png)
> 현재 식단관리와 관련해서는 다음과 같이 3가지 서비스가 있습니다. 해당 서비스들의 한계는 여전히 비용이 부담되거나, 무료더라도 정확한 고객층과 고객 맞춤 서비스가 없다는 점 입니다. 저희는 AI 및 머신러닝 추천 알고리즘을 적극 활용해 기본 서비스 이용료가 없고, 개인 맞춤서비스를 비롯해 원클릭 구매 등 다양한 편의기능을 바탕으로 아직 잠재수요를 제대로 만족시키지 못한 식단 서비스 시장에서 빠르게 성장할 수 있을 것이라 생각합니다.

&nbsp; 

## :pushpin:**성장 가능성**
![스크린샷(1397)](https://user-images.githubusercontent.com/99727385/175970690-aacb0699-a4f6-44f4-9057-9ad7459f0c51.png)

&nbsp; 

## :pushpin:**사진/동영상**
![KakaoTalk_20220628_00290205112333](https://user-images.githubusercontent.com/99727385/175979028-6a53e48c-75c3-48cd-a28b-6932fbe79a8a.jpg)


