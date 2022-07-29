# Deep-Project
distingush diseases by pictures of crop leaves
ResNet50으로 transfer learning후 작물 질병 판단

image preprocessing

model
- ResNet 50
- textCNN

국민신문고 크롤링
국민신문고 청원 내용을 크롤링하여 내용을 요약

text preprocessing

model
- textCNN

libray
- requests
- bs4
- json
- re
- konlpy.Okt
- gensim

cycle GAN
cycle GAN을 사용하여 인물 사진을 만화그림으로 바꾸기
cycle loss, generator loss, identity loss를 적용해서 generator 학습
real loss, fake loss를 적용해서 discriminator 학습

image preprocessing

model
- cycle GAN
- residual block

library
- torchvision


scream distincion
비명이 녹음된 음원을 라벨링하여 일반 음원과 분류를 학습하였고, 앱 실행시 마이크로 들리는 소리가 비명인지 구별하기
sound preprocessing
- frame processing
- feature extraction
- mel_spectrogram

model
- 3 layers CNN

library
- librosa
- sklearn
- PyQt5
- QtWidgets
