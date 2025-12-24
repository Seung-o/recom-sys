# 추천 시스템 프로젝트

이 프로젝트는 다양한 추천 시스템 알고리즘을 구현하고 실험하기 위한 환경입니다.

## 환경 설정

### 1. 가상환경 생성 및 활성화

```bash
# 가상환경 생성
python -m venv venv

# 가상환경 활성화 (Mac/Linux)
source venv/bin/activate

# 가상환경 활성화 (Windows)
venv\Scripts\activate
```

### 2. 필요한 패키지 설치

```bash
pip install -r requirements.txt
```

### 3. Jupyter Notebook 실행

```bash
jupyter notebook
```

또는

```bash
jupyter lab
```

## 프로젝트 구조

```
recom-sys/
├── data/                  # 데이터 파일 저장 폴더
│   └── README.md         # 데이터 설명
├── notebooks/            # Jupyter notebook 파일들
│   └── 01_getting_started.ipynb
├── models/               # 학습된 모델 저장 폴더
├── requirements.txt      # Python 패키지 의존성
└── README.md            # 프로젝트 설명 (이 파일)
```

## 사용 방법

1. `data/` 폴더에 데이터를 업로드합니다.
2. `notebooks/` 폴더에서 Jupyter notebook을 실행합니다.
3. 실험 결과와 모델은 `models/` 폴더에 저장됩니다.

## 주요 기능

- 협업 필터링 (Collaborative Filtering)
- 콘텐츠 기반 필터링 (Content-based Filtering)
- 하이브리드 추천 시스템
- 딥러닝 기반 추천

