# PJT_FINAL_AI_Styling_Recommendation_Service

1. [본 프로젝트 메인 깃허브](https://github.com/sara4kyj/finalPJT_ClosetCloud)

2. [프로젝트 발표자료](https://github.com/jibook/PJT_FINAL_AI_Styling_Recommendation_Service/blob/master/Cloud_Closet__AI_Styling_Recommendation_Service.pdf)


# 1.1 프로젝트 개요
## 1.1.1. 문제 정의 및 목적
- 온라인 시장이 확대됨에 따라 소비자들은 더욱 개인화된 추천 서비스에 대한 요구가 커지고 있음.
- 그럼에도 수 많은 소비자를 개별적으로 대응할 수 있는 서비스가 많이 없음.

## 1.1.2. 주제
- 의식주 중 '의'에 도움주기 위한 서비스를 제공하고자 함.
- 카메라로 촬영한 옷들을 DB에 저장하고 이를 기반으로 선택한 스타일에 따라 옷을 추천해주는 개인별 맞춤 스타일링 정보 제공 웹/앱 서비스 개발.

# 1.2. 사용 데이터 정보
## 1.2.1. 패션 상품 및 착용 이미지

- 출처 : AIhub([https://aihub.or.kr/aidata/30755](https://aihub.or.kr/aidata/30755))
- 데이터 유형 : 이미지 (jpg, xml)
- 구축 데이터량 : 32만건
- 설명
    - 단색 배경에서 촬영한 전신 패션 스튜디오 및 패션 상품 영상 데이터
    - 이미지(jpg)와 라벨(xml) 쌍으로 구성되어 있으며, 단수/복수 상품 이미지가 제공됨
- 세부 정보는 출처 페이지, 혹은 페이지 내 [데이터설명서](https://aihub.or.kr/sites/default/files/2021-06/12.%20%5B%ED%8C%A8%EC%85%98%EC%83%81%ED%92%88%20%EB%B0%8F%20%EC%B0%A9%EC%9A%A9%20%EC%98%81%EC%83%81%20%EA%B3%BC%EC%A0%9C%5D%20%ED%8C%A8%EC%85%98%EC%83%81%ED%92%88%20%EB%B0%8F%20%EC%B0%A9%EC%9A%A9%20%EC%98%81%EC%83%81.pdf) 참고

## 1.2.2.  K-Fashion 이미지

- 출처 : AIhub([https://aihub.or.kr/aidata/7988](https://aihub.or.kr/aidata/7988))
- 데이터 유형 : 이미지 (jpg, xml)
- 구축 데이터량 : 120만건
- 설명
    - 패션 영역과 속성, 스타일 정보를 인식 및 도출할 수 있도록 학습용 이미지 데이터셋 구축
    - 한국형 패션 인지 및 트렌드 파악과 AI기반 시각지능 기술 및 서비스 개발에 활용
    - 이미지(jpg)와 라벨(xml) 쌍으로 구성되어 있으며, 단수/복수 상품 이미지가 제공됨
- 세부 정보는 출처 페이지, 혹은 페이지 내 [데이터설명서](https://aihub.or.kr/sites/default/files/2021-06/19.%20%5B%EA%B8%B0%ED%83%80%20%EC%98%81%EC%97%AD%5D%20K-Fashion%20%EC%9D%B4%EB%AF%B8%EC%A7%80.pdf) 참고