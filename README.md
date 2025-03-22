
## 📌 Project Summary | 프로젝트 요약

- **📅 Date**: April 26, 2021  
- **🛠 Tool | 도구**:  
  - R (R Markdown 기반 분석)  
  - Packages: openintro, ggplot2, dplyr, ggmap  
- **🧪 Design | 설계**:  
  - Cross-sectional analysis (OECD 37개국 단면 자료 분석)  
  - Simple Linear Regression (단순 선형 회귀 분석)  
- **🎯 Goal | 목표**:  
  - Analyze how average temperature affects COVID-19 incident rates across OECD countries  
  - OECD 국가들의 평균 기온이 COVID-19 발생률에 어떤 영향을 미치는지 분석

---

## 📊 Variables | 변수 설명

| 변수 (Variable) | 설명 (Description) | 역할 (Role) |
|------------------|--------------------|--------------|
| Incident Rate    | 확진자 수 / 인구 × 100 (%) | 종속 변수 (Dependent Variable) |
| Temperature       | 1991~2016 평균 기온 | 독립 변수 (Independent Variable) |
| Country           | 37개 OECD 국가 이름 | 분석 단위 (Observation Unit) |

---

## 🔍 Methodology | 분석 방법

- **Data Sources | 데이터 출처**
  - COVID-19: Johns Hopkins CSSE  
  - Temperature: World Bank Climate Portal  
  - Population: OECD Statistics

- **Model | 분석 모델**
  
Incident Rate = β₀ + β₁ × Temperature + ε

- **Assumptions | 가정**
  - OECD 국가들은 사회적/경제적 조건이 유사하므로, **기온의 영향만 상대적으로 순수하게 식별 가능**

---

## 📈 Key Findings | 주요 결과

- **Negative relationship between temperature and COVID-19 incident rate**  
- **기온이 낮을수록 감염률이 높아지는 음의 관계가 관찰됨**

---

## 🧠 Interpretation | 해석 

- 🧊 **Lower temperatures weaken the immune system and support virus survival**, leading to higher infection rates  
- 🧊 **기온이 낮을수록 면역력이 약화되고 바이러스 생존률이 높아져 감염률이 증가**  
- 📌 Temperature is a **natural, non-social factor** that sets a **baseline infection risk**  
- 📌 기온은 사회적 조치와 무관한 **자연적 요인**으로 감염 위험의 구조적 기준선을 형성함


## 🧾 Conclusion | 결론 

- ✅ Temperature has a **statistically significant negative effect** on COVID-19 incident rates  
- ✅ 기온은 COVID-19 발생률에 **통계적으로 유의한 음의 영향을 미침**
- 🧭 **Winter season preparedness is crucial for public health policy**  
- 🧭 **겨울철 방역 정책 및 감염병 대응 전략의 사전 준비가 필수적임**
- 💡 This study highlights the need to **integrate climate variables** in pandemic response planning  
- 💡 감염병 대응 정책에 **기후 요인을 반영하는 다변량적 접근의 중요성**을 시사함
