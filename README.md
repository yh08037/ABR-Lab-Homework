# ABR-Lab-Summer_Project

```tensorflow```와 ```keras```가 통합되고, ```tensorflow```에서도 고수준의 API들이 지원되면서, 기존의 Placeholder, Session, feed_dict 구조의 기존의 ```tensorflow``` 코드가 더이상 지원되지 않을 것이라는 경고(deprecated)를 많이 보게 되었다. 따라서 이번 기회에 ```fastai, keras와 tensorflow 2.0```의 API을 활용해서 개인 프로젝트 과제를 수행해보기로 하였다.

image dataset을 정하여 CNN 모델을 적용하여 학습시켜 보는 것이 이번 과제의 목표이다. 처음에는 ```intel image classification``` dataset을 학습해보려 하였으나, label이 6개 밖에 되지 않는 데이터 셋이어서 label이 더 많은 dataset을 사용하기로 하였다. ```cifar 100``` 과 ```stanford dog breed dataset``` 중 고민을 하였다. dog breed classification을 수행하는 것이 2019년 1학기의 과제로 나왔었는데, 완성시키지 못하고 흐지부지된 것이 아쉬워 ```standford dog breed dataset```을 학습시켜보기로 결정하였다.

