# GDFed
GDFed

연합 학습은 분산 컴퓨팅 리소스를 사용하여 모델을 학습하는 것을 가능하게 했다. 
가장 많이 사용되는 Fedavg 방식은 구조가 단순하고 성능이 좋다. 
그러나 Fedavg는 각 사용자 기기의 성능을 고려하지 않는 단점이 있다. 
이 문제를 해결하기 위해 각 사용자 장치의 성능과 실시간 상태를 이해하고 학습을 진행하는 연합 학습 구조인 GFed를 제안한다. 
GFed는 각 장치의 현재 기능을 고려하여 사전 훈련된 GNN 모델을 사용하여 장치를 클러스터링하고 연합 학습에 참여하는 아키텍처이다. 
실험에서 GDFed 방식은 Fedavg방법과 비교했을 때 성능은 유지하면서 지연시간을 43.3%까지 감축시킬 수 있었다.


## Acknowledgement
이 성과는 2023년도 정부(과학기술정보통신부)의 재원으로 정보통신기획평가원의 지원(No.2019-0-01287-005, 분산 엣지를 위한 진화형 딥러닝 모델생성 플랫폼)과 2023년도 정부(과학기술정보통신부)의 재원으로 정보통신기획평가원의 지원을 받아 수행됨(No.RS-2022-00155911, 인공지능융합혁신인재양성(경희대학교))

## License
Copyright (c) 2023 Networking Intelligence
Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
