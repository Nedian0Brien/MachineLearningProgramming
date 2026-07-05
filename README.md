<div align="center">

# MachineLearningProgramming

**데이터 과학과 머신러닝 프로그래밍 실습 노트북 모음**

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

[English](./README.en.md)

</div>

---

## 소개

이 저장소는 데이터 이해, NumPy, Pandas, 시각화, 전처리, 선형회귀, 로지스틱 회귀, KNN, Titanic/iris/주택가격 예측 등 머신러닝 수업 실습 자료를 모은 notebook 저장소입니다.

각 주차 폴더에 실습 코드와 데이터 파일이 함께 들어 있어, 순서대로 열어보면 데이터 과학 기초에서 분류/회귀 실습까지 이어지는 흐름을 볼 수 있습니다.

## 주요 기능

| 기능 | 설명 |
|---|---|
| 기초 데이터 분석 | 2주차 자료에서 데이터 이해, NumPy, Pandas, 시각화를 다룹니다. |
| 데이터 전처리 | 3주차 자료에서 정형/비정형 데이터 전처리를 다룹니다. |
| 회귀 실습 | 4주차 자료와 과제에서 선형회귀와 주택가격 예측을 다룹니다. |
| 분류 실습 | 5주차 자료에서 로지스틱 회귀, Titanic 생존자 예측, 붓꽃 분류를 다룹니다. |
| 실습 데이터 포함 | CSV, Excel, 텍스트, 이미지 데이터가 notebook과 함께 들어 있습니다. |

## 저장소 구조

| 경로 | 역할 |
|---|---|
| 2주차 실습코드/ | Data understanding, NumPy, Pandas, visualization |
| 3주차-실습코드/ | Data preprocessing notebooks and datasets |
| 4주차-실습코드/ | Linear regression basics and practice |
| 5주차_실습자료/ | Logistic regression, Titanic, iris, Teachable Machine practice |
| 과제1/ | Linear regression assignment notebooks and data |

## 빠른 시작

### Jupyter 실행

```bash
jupyter lab
```

### 노트북 목록 확인

```bash
find . -name "*.ipynb" | sort
```

### 권장 순서

2주차 -> 3주차 -> 4주차 -> 5주차 -> 과제1

## 검증

| 항목 | 명령 |
|---|---|
| Notebook count | `find . -name "*.ipynb" | wc -l` |

## 운영 메모

- 수업 자료 성격의 저장소이므로 모든 notebook이 한 번에 재실행되도록 정리되어 있지는 않을 수 있습니다.
- 데이터 파일 경로가 notebook 상대 경로와 맞는지 먼저 확인하세요.

## 문서 작성 근거

이 README는 저장소 안의 다음 파일과 문서를 기준으로 작성했습니다.

- `2주차 실습코드/`
- `3주차-실습코드/`
- `4주차-실습코드/`
- `5주차_실습자료/`
- `과제1/`
