# Goorm-project

구름 국비 사업에서 진행한 자연어처리 과정에서 참여했던 프로젝트 3개를 올렸습니다.

1. 문장분류기 프로젝트로 영어 문장에 대한 이진 분류 주제를 Baseline코드를 통해 어느 조가 가장 많이 Kaggle에서 점수를 올리는 것에 관한 프로젝트 입니다.
저희 조는 Sentimental sentence를 BERT 모델을 기반하여 학습시켜 sentimental classification 모델을 구축,BERT를 fine-tuning 하는 방식으로 진행했습니다.

활용 라이브러리
Huggingface Transformers
BERT모델(BERT-base-uncased , BERT-large-uncased)
XLNet 모델(XLnet-base-cased) 
GPT 모델과 BERT 모델의 장점들을 활용한 모델
WandB, Sweep
Docker를 이용한 개발환경 구축 및 이미지화

이 프로젝트에서 저는 아래와 같은 역할을 하였습니다.
- 데이터 분석
- 회의 내용 정리
- 정규식과 파이썬 메소드를 이용한 데이터 정규화
- hyper parameter 조정 및 wandb를 이용한 데이터 기록
- task에 맞게 모델 fine-tuning
- 데이터 수집 및 정리

2. 한국어 지문을 보고 질문에 맞는 답을 생성하는 모델을 만들어 보자.

이 프로젝트는 한국어 지문을 통해 지문 안에서 답을 찾아내는 것을 Kaggle을 통해 진행했ㅅ브니다.
저희 조의 활용 라이브러리 및 프레임워크, 모델은 아래와 같습니다.
- Huggingface Transformers
- KoELECTRA
- KoBigBird
- WandB
- Sweep

이 프로젝트에서 저는 아래와 같은 역할을 하였습니다.
- 모델 파인튜닝 및 성능 개선
- 실험 결과 정리 및 분석, 시각화
- 데이터 분석 및 전처리
- WandB를 이용한 learning rate별 성능 분석
- 발표자료 정리
- 다양한 모델 앙상블 적용
- huggingface의 fine-tuned 모델 탐색 및 실험

3. 저희 조에서 한 마지막 프로젝트는 노래 가사를 번역하는 프로그램을 만들었습니다. 노래가 실행되며 영어와 한국어 양방향 번역이 가능하며 번역된 가사가 출력이 됩니다.
데모 홈페이지의 경우 현재 닫혀있으며 저는 데모 프로그램에는 참여하지 않았으므로 데모코드는 올리지 않았습니다.

이 프로젝트에서 저는 아래와 같은 역할을 하였습니다.
- 데이터 전처리
- 데이터 분석
- hyper parameter tuning
- 발표 자료 정리
