### Chapter 2 Introducrion
---
이 책은 (지도학습) 머신러닝 모델을 해석하는 방법에 대해 설명해준다. 여러 chapter에 수식이 포함되어 있지만, 수식 없이도 수식 뒤 각 방법의 아이디어를 이해할 수 있어야한다. 이 책은 머신러닝을 바닥부터 배우려는 사람에게 적합하지 않다. 만약 머신러닝을 처음 접하는 사람이라면, 기본을 배울 수 있는 다양한 자료가 있다. “The Elements of Statistical Learning” by Hastie, Tibshirani, and Friedman (2009)과  Andrew Ng 교수님의 “Machine Learning” 코세라 온라인 강의를 추천한다. 소개한 책과 온라인 강의 모두 무료이다. 

머신러닝 모델의 새로운 해석 방법들은 무서운 속도로 발표되고있다. 모든 새로운 내용을 따라가는 것은 미친짓이고 불가능하다. 이 책에서 가장 novel하고 화려한 방법을 찾을 수 없는 이유이고, 이 책에서는 머신러닝 해석가능성에 대한 기본 개념과 기존 방법을 배울 것이다. 이러한 기본들은 머신러닝 모델을 해석가능하도록 도와줄 것이다. 기본 개념을 배우고 나면 arxiv.org에 발표되는 해석가능성에 대한 새로운 어느 내용이라도 5분안에 이해하고 평가할 수 있게 될것이다.(Internalizing the basic concepts also empowers you to better understand and evaluate any new paper on interpretability published on arxiv.org in the last 5 minutes since you began reading this book (I might be exaggerating the publication rate).)

이 책은 (디스토피아적) 짧은 이야기들로 시작되고 모든 이야기 내용을 이해할 필요는 없지만, 이야기 내용이 흥미를 돋구고 생각할 수 있게 만들어주었으면 한다. 그러고 나면 머신러닝 해석가능성에 대해 살펴볼 것이다. 우리는 해석가능성의 중요성과 현존하는 다양한 방법들에 대해 이야기 할것이다. 책에 나오는 용어는 용어집에서 찾아볼 수 있다. 대부분의 모델과 설명 방법은 data chapter에서 설명하는 실제 데이터를 사용한다. 머신러닝 모델을 해석하는 방법 중 하나는 linear model 또는 decision tree와 같은 설명가능한 모델을 사용하는 것이다. 다른 방법으로는 model-agnostic 해석 도구를 사용하는 방법이 있고 이는 모든 지도학습 모델에 적용할 수 있다. model-agnostic 방법은 모델의 평균적인 결과를 설명하는 global 방법과 하나의 결과를 설명하는 local 방법으로 나눌 수 있다. model-agnostic 방법 chapter에서는 partial dependence plot과 feature importance와 같은 방법들을 다룰 것이다. model-agnostic 방법은 입력값은 변경하고 출력값의 변화를 확인하는 방법으로 진행된다. 이 책은 해석가능한 머신러닝의 낙관적인 미래에 대해 이야기하며 마무리된다. 

책을 처음부터 끝까지 읽어도 좋고 관심있는 방법을 바로 읽어도 좋다. 

책 내용을 즐기기 바란다. 
