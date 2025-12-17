# Kaggle Competition Portfolio

이 저장소는 Kaggle 경진대회 참여 노트북과 분석 자료를 정리한 포트폴리오입니다.

## 📁 프로젝트 구조

```
kaggle/
├── README.md
├── code/                       # 코드 및 노트북 디렉토리
│   └── [competition-name]/
│       ├── *.ipynb            # Jupyter 노트북 파일
│       ├── *.qmd              # Quarto 문서 파일
│       └── *.html             # Quarto 렌더링 결과
├── input/                      # 입력 데이터 디렉토리
│   └── [competition-name]/
│       └── *.csv              # 경진대회 원본 데이터
└── output/                     # 출력 결과 디렉토리
    └── [competition-name]/
        └── submission.csv     # 제출 파일
```

## 🏆 Competition Projects

### 1. [Bike Sharing Demand](./code/bike-sharing-demand/)
- **설명**: 자전거 공유 시스템의 수요 예측
- **코드**: `code/bike-sharing-demand/`
  - `bicycle_demand_prediction.ipynb` - Jupyter 노트북 분석
  - `bike-sharing-demand.qmd` - Quarto 문서
- **데이터**: `input/bike-sharing-demand/*.csv`
- **제출 파일**: `output/bike-sharing-demand/submission.csv`

### 2. [Titanic - Machine Learning from Disaster](./code/titanic/)
- **설명**: 타이타닉 생존자 예측
- **코드**: `code/titanic/`
  - `titanic.qmd` - Quarto 문서
- **데이터**: `input/titanic/*.csv`
- **제출 파일**: `output/titanic/`

---

## 🛠 개발 환경

- **편집기**: Neovim
- **주요 도구**: 
  - Jupyter Notebook (`.ipynb`)
  - Quarto (`.qmd`)
  - Python & R

## 📊 디렉토리 구성 원칙

각 competition은 다음과 같이 세 개의 디렉토리로 분리되어 관리됩니다:

1. **code/[competition-name]/**: 분석 노트북 및 코드
   - `.ipynb` - Jupyter 노트북
   - `.qmd` - Quarto 문서
   - `.html` - Quarto 렌더링 결과

2. **input/[competition-name]/**: 경진대회 원본 데이터
   - `train.csv`, `test.csv` 등 제공된 데이터셋

3. **output/[competition-name]/**: 결과 파일
   - `submission.csv` - 최종 제출용 예측 결과

## 📝 사용 방법

1. `input/[competition-name]/` 디렉토리에 데이터셋 배치
2. `code/[competition-name]/` 디렉토리의 노트북으로 분석 진행
   - `.ipynb` 파일은 Jupyter Notebook으로 실행
   - `.qmd` 파일은 Quarto로 렌더링 (`quarto render`)
3. 결과 파일은 `output/[competition-name]/` 디렉토리에 저장

## 📫 Contact

프로젝트에 대한 문의사항이나 피드백은 이슈로 등록해주세요.

---

*Last Updated: 2025-12-08*
