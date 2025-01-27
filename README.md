## 2020 서울시 빅데이터캠퍼스 공모전

2020 서울시 빅데이터캠퍼스 공모전 서울특별시장상(1등) 코드/피피티입니다.

### 참가 인원

권남택(25기), 김지원(24기), 최수진(24기), 최순일(24기)

--------------------------------------------------
### 레포 구성

- 전체 분석코드/분석결과 시각화 png 파일
- 공모전 발표용 PPT
- 성균관대학교 통계분석학회 P-Sat 20-01 주제분석 PPT
  - 공모전 이전에 학회 발표를 준비하며 좋은 평가를 받아 공모전에 나가게 되었습니다.

--------------------------------------------------
### 전체과정의 요약

1) 빅데이터캠퍼스/서울 열린데이터 광장에서 데이터 가져와 전처리
2) 부정확한 주소에 대해서 구글/카카오 API를 사용해 적절한 행정동을 추출
3) 사용된 변수들을 통해 클러스터링 진행
  - Kmeans/Kmedoids/Hierarchical/GMM 네 가지 클러스터링을 진행하되, 일반화된 결과를 위해 행정동별 보팅 시행 (타겟 행정동 선정 분산 감소)
4) 카카오 API를 통한 실수요 면적 계산, 상위 5개 행정동에 대한 구체적인 입지선정 진행
5) 자체적인 최적화 알고리즘과, P-Median 알고리즘을 통해 구체적인 입지 제안
6) 결과에 대한 카카오 API를 활용한 자바스크립트 시각화
