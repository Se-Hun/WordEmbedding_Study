# WordEmbedding_Study
워드 임베딩을 공부하고 워드 임베딩 모델을 구현하여 실제로 학습시켜봄.

## torchtext 라이브러리 설치하기
torchtext는 torchvision과 달리 기본 PyTorch 설치에 빠져 있다.

따라서, torchtext는 따로 설치를 해주어야만 한다.

**pip 이용시** : `pip install torchtext`

**conda 이용시** : `conda install -c pytorch torchtext`

## 사용한 데이터셋
IMDB : 영화 후기 데이터셋

IMDB 데이터셋을 이용하면 영화 리뷰가 긍정인지, 부정인지 아니면 구분할 수 없는지를 계산하는 감성 분류기를 만들 수 있다.

