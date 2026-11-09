# 화학데이터사이언스 · Lecture 19 — 논문 그림 그리기

Taylor Sparks, *Python to make nice figures* Part III 를 따라가는 실습.

## Colab 에서 열기 (파일을 올릴 필요 없음)

| 노트북 | Colab |
|---|---|
| 학생용 | [Open in Colab](https://colab.research.google.com/github/gwanyeong/my_projects/blob/master/chem-data-science/lecture19/Lecture19_학생용.ipynb) |
| 교수용 (정답 · 시연) | [Open in Colab](https://colab.research.google.com/github/gwanyeong/my_projects/blob/master/chem-data-science/lecture19/Lecture19_교수용.ipynb) |

- 링크로 연 다음 `파일 → Drive에 사본 저장` 을 하면 자기 드라이브에 저장된다.
- 데이터는 노트북의 `BASE` 주소 (이 저장소의 `data/` 폴더) 에서 바로 읽는다.

## data/

| 파일 | 내용 | 원본 |
|---|---|---|
| `generic_single_plot.csv` | 입자 크기에 따른 세 물질의 기여도 | Sparks · MSE2001python |
| `cobalt_production.csv` | 1998 ~ 2015 코발트 생산 점유율 (%) · 22 개 나라 | Sparks 코드 속 숫자를 표로 |
| `spectroscopy.csv` | 전기변색 소재의 파장별 투과율 | Sparks · MSE2001python |
| `heatmap.csv` | 압력별 X 선 회절 패턴 21 개 | Sparks · MSE2001python |
| `multiple_axes.csv` | 배터리 사이클별 용량 · 효율 · 에너지 밀도 | Sparks `multiple_axes.xlsx` 를 한 표로 |
| `XRD_Rietveld.csv` | 리트벨트 측정 · 모형 · 배경 · 봉우리 위치 | Sparks · MSE2001python |

원본: [sp8rks/MSE2001python](https://github.com/sp8rks/MSE2001python) `module_examples/data_for_exercises/`
