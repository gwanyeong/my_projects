# 숙제 · 좋은 그림 그리기 (15 ~ 17강)

화학데이터사이언스 2026-2

## Colab 에서 열기 (파일을 올릴 필요 없음)

[학생용 노트북 열기](https://colab.research.google.com/github/gwanyeong/my_projects/blob/master/chem-data-science/hw_plotting/HW_plotting_%ED%95%99%EC%83%9D%EC%9A%A9.ipynb)

- 링크로 연 다음 `파일 → Drive에 사본 저장` 을 하면 자기 드라이브에 저장된다.
- 데이터는 노트북의 `BASE` 주소 (이 폴더의 `data/`) 에서 바로 읽는다.

## 과제

- 카드 A ~ G 의 목표 그림 중 **2 장 이상**을 처음부터 다시 그리고 **더 좋게** 고친다. 목표 그림에는 고칠 점이 숨어 있다.
- 목표 그림 없이 **자유 그림 1 장 이상**.
- AI 도구 사용 가능. 노트북 맨 아래에 사용 기록을 남긴다.

## data/

| 파일 | 내용 | 출처 |
|---|---|---|
| `titration.csv` | 0.100 M 산 25.00 mL 를 0.100 M NaOH 로 적정할 때 pH (HCl · 아세트산 · 인산) | 문헌 pKa 로 전하 균형식을 풀어 계산 |
| `speciation.csv` | pH 0–14 화학종 분율 (탄산 · 인산 · 시트르산 · 글라이신), 긴 표 | 문헌 pKa 로 계산 |
| `cathode_composition.csv` | 양극재 9 종의 원소 질량 백분율 · 몰질량 · 이론 용량 | 화학식으로 계산 (pymatgen) |
| `tio2_xrd.csv` | TiO₂ 아나타제 · 루타일 XRD 패턴 (Cu Kα) | 결정 구조로 계산 (pymatgen) + 잡음. 측정값 아님 |
| `elements.csv` | 원소 86 개의 주기 · 족 · 블록 · 전기음성도 · 원자 반지름 · 이온화에너지 · 녹는점 · 밀도 | pymatgen 원소 자료 |
| `liquids.csv` | 액체 6 종의 온도별 증기압 · 밀도 · 점도 (1 atm) | CoolProp 물성 상태식 |

## targets/

카드 A ~ G 의 목표 그림.
