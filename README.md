# MLOps Fastcampus

개발자를 위한 MLOps : 머신러닝 입문부터 추천 시스템 구축 강의 자료 예제 학습 코드

이 저장소는 Fastcampus MLOps 강의를 위한 Google Colab에서 실행 가능한 실습 예제를 제공합니다.

## 📚 강의 구성

### 1️⃣ 기본 머신러닝 (`notebooks/01-basic-ml/`)
- **train_simple_model.ipynb**: 기초 ML 모델 학습
  - 데이터 로드 및 전처리
  - Random Forest 모델 학습
  - 모델 평가 및 저장
  - 특성 중요도 분석

### 2️⃣ 실험 추적 (`notebooks/02-experiment-tracking/`)
- **mlflow_tracking.ipynb**: MLflow를 활용한 실험 관리
  - MLflow 설정 및 실험 생성
  - 파라미터 및 메트릭 로깅
  - 여러 모델 비교
  - 하이퍼파라미터 튜닝
  - 아티팩트 관리

### 3️⃣ 모델 버전 관리 (`notebooks/03-model-versioning/`)
- **model_registry.ipynb**: MLflow Model Registry
  - 모델 레지스트리에 모델 등록
  - 모델 버전 관리
  - 모델 단계 전환 (Staging, Production)
  - 모델 메타데이터 관리

### 4️⃣ 모델 배포 (`notebooks/04-deployment/`)
- **model_serving.ipynb**: REST API를 통한 모델 서빙
  - Flask API 구현
  - FastAPI 구현
  - 모델 예측 엔드포인트
  - Docker 배포 설정

### 5️⃣ 모델 모니터링 (`notebooks/05-monitoring/`)
- **model_monitoring.ipynb**: 프로덕션 모델 모니터링
  - 성능 메트릭 추적
  - 데이터 드리프트 감지
  - 예측 분포 모니터링
  - 알림 시스템

### 6️⃣ CI/CD 파이프라인 (`notebooks/06-cicd/`)
- **ml_pipeline.ipynb**: ML CI/CD 자동화
  - 파이프라인 설정
  - 자동화된 학습 및 평가
  - 모델 테스트 및 검증
  - GitHub Actions 워크플로우

## 🚀 시작하기

### Google Colab에서 실행

1. 각 노트북의 링크를 클릭하여 Google Colab에서 열기:
   - [01. 기본 ML 모델 학습](notebooks/01-basic-ml/train_simple_model.ipynb)
   - [02. MLflow 실험 추적](notebooks/02-experiment-tracking/mlflow_tracking.ipynb)
   - [03. 모델 버전 관리](notebooks/03-model-versioning/model_registry.ipynb)
   - [04. 모델 배포](notebooks/04-deployment/model_serving.ipynb)
   - [05. 모델 모니터링](notebooks/05-monitoring/model_monitoring.ipynb)
   - [06. CI/CD 파이프라인](notebooks/06-cicd/ml_pipeline.ipynb)

2. 각 노트북의 첫 번째 셀을 실행하여 필요한 라이브러리 설치

### 로컬 환경에서 실행

```bash
# 저장소 클론
git clone https://github.com/jjdevhub/mlops-fastcampus.git
cd mlops-fastcampus

# 가상환경 생성 (권장)
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 의존성 설치
pip install -r requirements.txt

# Jupyter 실행
jupyter notebook
```

## 📋 사전 요구사항

- Python 3.8 이상
- 기본적인 Python 프로그래밍 지식
- 머신러닝 기초 지식 (선택사항)

## 📦 주요 라이브러리

- **scikit-learn**: 머신러닝 모델
- **MLflow**: 실험 추적 및 모델 관리
- **Flask/FastAPI**: REST API 서버
- **pandas/numpy**: 데이터 처리
- **matplotlib/seaborn**: 데이터 시각화

## 🎯 학습 목표

이 과정을 완료하면 다음을 할 수 있습니다:

- ✅ 머신러닝 모델 개발 및 학습
- ✅ 실험 추적 및 관리
- ✅ 모델 버전 관리
- ✅ REST API를 통한 모델 배포
- ✅ 프로덕션 모델 모니터링
- ✅ CI/CD 파이프라인 구축

## 📖 추가 자료

- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
- [FastAPI Documentation](https://fastapi.tiangolo.com/)

## 🤝 기여하기

이슈나 개선 사항이 있으면 자유롭게 Issue를 생성하거나 Pull Request를 보내주세요!

## 📝 라이선스

이 프로젝트는 교육 목적으로 제공됩니다.

## 👨‍💻 문의

질문이나 피드백은 GitHub Issues를 통해 남겨주세요.
