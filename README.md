# CAN

창의적인 사고를 요하는 예술 분야는 늘 인간만의 영역으로 간주되어 왔고, 또한 사람들이 인공지능이 가장 대체하기 힘들 것이라고 말하는 분야 중 하나이다.  
&nbsp;그러나 2017년, 인공지능이 창의적이면서 인간의 예술과 가깝게 그림을 만드는 방법을 제시한 CAN(Creative Adversarial Networks) 제목의 논문이 발표되었다. <br>
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2Fbjib4t%2FbtqD9OaYDpb%2FomlbBTuJw1VBPJkzLBorkk%2Fimg.png" title="Block diagram of the CAN system" width="480"></img><br>
### CAN의 원리
첫 번째로, 랜덤 노이즈를 통해 생성자(Generator)가 생성한 새로운 그림이 기존에 인간이 만든 예술 스타일 어디에도 속하면 안 된다. 이를 위해 구별자(Discriminator)가 생성자(Generator)가 만든 그림을 기존에 존재하는 특정한 어떤 스타일로 구별할 수 없게 해야 한다. 이 과정은 인공지능이 창의적으로 사고하게 하기 위함이다.  <br><br>
&nbsp;두 번째로, 생성자가 생성한 새로운 그림이 인간의 그림의 형태와 유사해야 한다. 이를 위해 구별자가 인간의 그림과 생성자의 그림 중 가짜인 것 하나를 고르게 했을 때 맞출 확률이 50%에 근접하게 해야 한다.  <br>
<img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2F0kUu8%2FbtqD9OPDNIa%2FwHcY5gRXkO0c6nvWXNKlNK%2Fimg.png" title="Block diagram of the CAN system" width="600"></img><br>

https://arxiv.org/pdf/1706.07068.pdf
