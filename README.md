# GDFed: Dynamic Federated Learning for Heterogenous Device Using Graph Neural Network

## Overview
Federated learning has made it possible to learn models using distributed computing resources. The most commonly used, Fedavg method has a simple structure and shows good performance. However, Fedavg has the disadvantage of not considering the performance of each user device in real-time. To solve this problem, we propose GDFed. It is a federated learning structure that understands the performance and realtime status of each user device during proceeds learning. GNN learns from the graph-type dataset and can perform tasks such as node clustering or node classification through the feature of each node (in this case, the device). GDFed is an architecture that clusters devices using pre-trained GNN models and proceeds with federated learning, taking into account the current capabilities of each device. In the experiment, we show the GDFed method outperforms the Fedavg method by 43.3% in reducing the delay time.

![image info](./image/GDFedFig.png)

## Version
- python 3.8
- Pytorch 2.0.0

## Acknowledgement
This work was supported by the National Research Foundation of Korea (NRF) grant funded by the Korea government (MSIT) (No. 2020R1A4A1018607) and in part by Institute of Information communications Technology Planning Evaluation (IITP) grant funded by the Korea government(MSIT) (No.RS-2022-00155911, Artificial Intelligence Convergence Innovation Human Resources Development (Kyung Hee University))*Dr. CS Hong is the corresponding author.


## License
Copyright (c) 2023 Networking Intelligence
Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
