﻿# AV
Ajou software 캡스톤디자인

프로젝트 시작

팀명 :　AV (Any Voice)
과제의 개요
삼성과 엘지 내로라하는 기업 할거없이 스마트홈시 스템에 집중하고 있다. 현재 배포되어있는 스마트홈서비스는 (본인의) 스마트폰을 활용한다. 실제 스마트홈서비스를 사용해보니 불편했다 그래서 개선

목표:

목소리를 활용하여 제어할 수 있는 스마트홈 서비스, 남녀노소 쉽게 접근할 수 있다.

기대효과:

남녀노소 접근 할 수 있고, 스마트홈서비스의 실용성을 증가시켜준다.
라즈베리파이 – 집의 뇌
전등 , 선풍기, 청소기(전자기기) + 블루투스를 활용한 기기찾기

수행방법 :

라즈베리파이 인터넷전화번호를 할당한다. (VoIP)
클라우드 스피치 API를 활용해서 음성을 텍스트로 변환.
머신러닝을 활용해 변환된 텍스트를 하드웨어에 보낸다. 블루투스
그 하드웨어가 작동하면 다시신호를 보낸다.

문제점 : 

voip통신시, 녹음 및 speech to text 작업 이루어 지지 않음 -> 기기 두개를 연결해서 해결.

기술 : 
RX JAVA : https://github.com/ReactiveX/RxAndroid
speech to text : https://developer.android.com/reference/android/speech/package-summary
IOT : https://developers.meethue.com/


