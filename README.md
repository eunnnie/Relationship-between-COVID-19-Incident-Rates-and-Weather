
## 📌 Project Summary | 프로젝트 요약

- **📅 Date**: April 26, 2021  
- **🛠 Tool**:  
  - R (R Markdown 기반 분석)  
  - 사용 패키지: openintro, ggplot2, dplyr, ggmap 등  
- **🧪 Design**:  
  - Cross-sectional analysis (OECD 37개국 단면 자료)  
  - 단순 선형 회귀 모델 적용  
- **🎯 Goal**:  
  - 평균 기온이 COVID-19 발생률에 미치는 영향을 분석  
  - 기온이 낮을수록 감염률이 높아지는지 여부를 실증적으로 검증

---

## 📊 변수 설명 (Variables)

| 변수 | 설명 | 역할 |
|------|------|------|
| Incident Rate | 인구 대비 확진자 비율 (%) | 종속 변수 |
| Temperature | 국가별 평균 기온 (1991~2016 평균) | 독립 변수 |
| Country | OECD 회원국 (37개국) | 관측 단위 |

---

## 🔍 분석 방법 (Methodology)

- **데이터 출처**
  - COVID-19 확진자 수: Johns Hopkins CSSE
  - 기온 데이터: World Bank Climate Portal
  - 인구 통계: OECD Statistics

- **분석 설계**
  - 단면 분석 (cross-sectional)
  - 단순 선형 회귀 분석:
    Incident Rate = β₀ + β₁ * Temperature + ε

- **가정**: OECD 국가들 간 사회경제적 격차가 크지 않으므로 기온의 영향만을 상대적으로 순수하게 식별 가능

---

## 📈 주요 결과 요약

- 기온이 낮을수록 COVID-19 감염률(incident rate)이 높음
- 감염병의 계절성과 유사한 결과 (겨울철 전파력 증가)

---

## 🧠 해석 (Interpretation)

- 낮은 기온에서 면역력 저하 및 바이러스 생존률 증가 → 감염 확산 가능성 증가
- 기온은 사회적 조치와 무관한 **자연적 변수**로서 감염률의 구조적 리스크 요인
- 겨울철 방역 강화 필요성 강조

---

## 🧾 결론 (Conclusion)

- 본 연구는 기온이 COVID-19 발생률에 통계적으로 유의한 영향을 준다는 점을 실증함
- 계절성 감염병 대응은 기후요인 고려가 필수이며, 특히 **겨울철 방역 정책 강화**가 필요
