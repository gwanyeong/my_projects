# 숙제 · 좋은 그림 그리기 (15 ~ 17강) — 데이터

화학데이터사이언스 2026-2. 과제 내용은 수업 공지를 본다.

## 불러오기 (Colab)

```python
import pandas as pd
BASE = "https://raw.githubusercontent.com/gwanyeong/my_projects/master/chem-data-science/hw_plotting/data/"
titration = pd.read_csv(BASE + "titration.csv")
```

## data/

| 파일 | 내용 | 출처 |
|---|---|---|
| `titration.csv` | 0.100 M 산 25.00 mL 를 0.100 M NaOH 로 적정할 때 pH (HCl · 아세트산 · 인산) | 문헌 pKa 로 전하 균형식을 풀어 계산 |
| `speciation.csv` | pH 0–14 화학종 분율 (탄산 · 인산 · 시트르산 · 글라이신), 긴 표 | 문헌 pKa 로 계산 |
| `cathode_composition.csv` | 양극재 9 종의 원소 질량 백분율 · 몰질량 · 이론 용량 | 화학식으로 계산 (pymatgen) |
| `tio2_xrd.csv` | TiO₂ 아나타제 · 루타일 XRD 패턴 (Cu Kα) | 결정 구조로 계산 (pymatgen) + 잡음. 측정값 아님 |
| `elements.csv` | 원소 86 개의 주기 · 족 · 블록 · 전기음성도 · 원자 반지름 · 이온화에너지 · 녹는점 · 밀도 | pymatgen 원소 자료 |
| `liquids.csv` | 액체 6 종의 온도별 증기압 · 밀도 · 점도 (1 atm) | CoolProp 물성 상태식 |
