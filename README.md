# FastAI

> ### 학습 계기
> * 빅데이터로 활용할 수 있는 분야는 무궁무진하지만 그 중심에는 머신러닝(딥러닝)이 자리잡고 있다고 판단   
> 현재 머신러닝의 정상에 자리잡고 있는 파이썬 라이브러리는 **Pytorch**, **Tensorflow** 가 존재한다   
> 
> * 그 중에서 Pytorch를 통해 딥러닝을 효율적으로 구현해주는 소프트웨어가 있는데 바로 __FastAI__ 다.   
>
> * 해당 소프트웨어를 통해 딥러닝의 기초를 익히고자 하였으며,   
> 그 속에서도 활성함수, SGD, Vision_learner(pretrained model)의 작동방식을 섬세하게 학습하고자 한다.   

 
 

> ### FastAI의 장, 단점   
> * **+** FastAI에는 자체적으로 데이터셋을 보유하고 있어 다양한 딥러닝을 배울 때 각기 다른 데이터셋을 사용할 수 있어 편리함을 지닌다.   
> 현존하는 데이터 셋 : [FastAI External Data](https://docs.fast.ai/data.external.html)
>
> * **+** Pytorch를 베이스로 더 빠른 속도를 구현해준다.
>
> * **-** M1 Chipset을 지원하지 않는다.   
> tensorflow, pytorch까지는 M1의 GPU 러닝을 지원하는데(베타라도) 아직 FastAI는 진전이 없다. 그래서 강제로 Google Collab을 사용해야 한다.
>
> * **-** 커뮤니티가 매우 적다. 존재자체를 모르는 사람이 대다수며 국내 커뮤니티가 존재하지만 역시나 소규모다. 


 
 

> ### 학습에 사용되는 것들
> Machine : **Macbook M1 Pro (2021)**   
> Book : Deep Learning for coders with fastai & pytorch   
> github : [fastai](https://github.com/fastai/fastbook) << 책에는 오탈자가 많으므로 꼭 깃허브를 참조할 것!

 
 

> ### Commit & Branch
> Commit은 크게 _**Lesson X _ Month Day**_ 로 나뉜다.
>    
> 기본 Branch는 Main으로 구성되어 있으며 한 번에 학습하기 어려운 경우 Lesson과 관련된 브랜치를 만들어 거기서 작업한 뒤,    
> 최종적으로 Main에 Merge된다.
>
> 복습 중 새로운 것을 찾았다면 따로 Branch를 생성하지 않고 새로운 커밋으로 날짜 뒤에 (2)를 붙이거나, 기존의 커밋명에 날짜만 바꿔 커밋한다.   


 
 
< 본 레파지토리는 학습용이며 파일에 들어간 설명에는 개인적인 견해로 인한 잘못된 정보가 들어있을 수도 있습니다 >