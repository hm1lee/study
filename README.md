# 💻 파이토치(Pytorch) -  Tutorials

- - - 

#### 1. why pytorch?

(1) 파이토치 장단점

 장점 
 - numpy와 매우 비슷한 문법
 - 동적으로 back-propagation 경로 생성 가능
 - 너무나도 훌륭한 documentation
 - 난이도에 비해서 자유도 높음

단점
- TensorFlow에 비해서 낮은 상용화 지원
- TensorFlow는 구글에서 pytorch는 페이스북에서 만듬 (단점은 아니고 특징)

- - -

#### 2. pytorch install

- 'pytorch.org' 사이트 : 컴퓨터 운영체제 / 사양마다 설치할 수 있는 명령어가 있음
- 'conda install pytorch torchvision torchaudio -c pytorch'로 설치
- 설치 완료가 잘 되었는지 확인 (ipython)
- In [1] import torch // 설치 확인 
- In [2] torch.__version__ // 버전 확인

- - - 

#### 3. 데이터셋이란?

(1) In order to do this

- 가상의 함수(ground-truth)를 통해서 데이터 쌍\[x,y\]을 입력한다.
- 데이터 쌍은 벡터로 표현이 가능할 것이다.

<img width="620" alt="스크린샷 2021-07-09 오전 2 20 37" src="https://user-images.githubusercontent.com/36816671/125114855-5c6cfb00-e09f-11eb-8d20-ed6a8c567fb5.png">



(2) example : Tabular Dataset

- 여러 column 으로 이루어진 테이블로 구성된 데이터셋 (e.g. 엑셀 파일)
- 한 row가 한 sampled을 의미함
- 한 column 개수가 벡터의 차원을 의미함



- - -

#### 4. 텐서란?
