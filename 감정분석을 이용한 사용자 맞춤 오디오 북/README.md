# 감정 분석을 이용한 사용자 맞춤 오디오 북

&nbsp;

## :pushpin:**프로젝트요약**
- 포스코 AI Big Data Academy에서 진행한 AI 프로젝트로 사용자의 현재 감정 상태를 분석하고 감정 상태에 따른 도서 추천이 이뤄집니다.
- 프로젝트는 2022.03 ~ 2022.04 동안 진행되었고 프로젝트를 함께한 팀원은 저를 포함한 총 6명이었습니다.

&nbsp;

## :pushpin:**추진배경**
![0000](https://user-images.githubusercontent.com/99727385/176441030-e4aceefd-1f71-4005-9972-3128e9ef0735.PNG)

&nbsp;

## :pushpin:**전체 시나리오**
![1111](https://user-images.githubusercontent.com/99727385/176441041-39a22e12-80bc-454c-b719-ee710f6d8164.PNG)

&nbsp;

## :pushpin:**핵심구현기술**

### 1. 감정분석을 위한 KoBERT 모델
> **BERT는 Bidirectional Encoder Representations from Transformer의 약자이다. 한국어 자연어처리 감정분류를 목적으로 개발되면서 KoBERT로 표현된다. 기존 자연어처리 모델은 앞의 텍스트 내용을 기반으로만 자연어를 처리하는 모델이기 때문에 반방향이다. 하지만 BERT 모델에서는 앞의 텍스트뿐만 아니라 뒤에 오는 텍스트의 내용을 기반으로 자연어를 처리하는 모델이기 때문에 더 높은 정확도를 가진다.**

&nbsp; 

### 2) Contents Based Filtering(추천 알고리즘)
> **추천 알고리즘은 사용자가 선호할 만한 아이템을 추측함으로써 여러 가지 항목 중 사용자에게 적합한 특정 항목을 추천하여 제공하는 알고리즘을 말한다.</br>
추천 알고리즘은 크게 추천할 학습 기반 데이터에 따라 콘텐츠 기반 필터링과 협업 필터링으로 분류된다. 콘텐츠 기반 필터링은 추천의 기준이 콘텐츠다. 이용자가 소비한 콘텐츠의 특성을 기준으로 그 사람의 취향과 선호를 파악한 뒤 그에 부합하는 콘텐츠를 제공하여 구매 의도를 높이는 것이 콘텐츠 기반 필터링이다.**

&nbsp;

### 3) 음성 합성 모델 Tacotron
> **TTS 기술은 Text-To-Speach의 약자로 문자데이터를 음성으로 변환해 출력해주는 기술이다. TTS는 입력 텍스트->단어전환->음소전환->DB저장->DB데이터 조합을 통한 음성합성->음성출력순으로 진행된다. 이러한 TTS기술에 인공지능 기술이 결합되어 음성합성이 진행되는 것이 Tacotron 모델이다.**

&nbsp;

## :pushpin:**기능도**
![2222](https://user-images.githubusercontent.com/99727385/176441043-04a323e5-a4b0-4bf8-a4ce-4cc98560147c.PNG)

&nbsp;

## :pushpin:**개선방향**
![33333](https://user-images.githubusercontent.com/99727385/176441046-9bf7563f-8ba2-4e5a-b3dd-e80c3c082e57.PNG)

&nbsp;

## :pushpin:**사진/동영상**
