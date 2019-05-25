## CVPR Tutorial On Distributed Private Machine Learning for Computer Vision: Federated Learning, Split Learning and Beyond

<a href=""><img src="nopeekcvpr.github.io/title.png" align="left" height="325" width="600"> </a>

This tutorial presents different methods for protecting confidential data on clients
while still allowing servers to train models. In particular, we focus on distributed deep learning
approaches under the constraint that local data sources of clients (e.g. photos on phones or
medical images at hospitals) are not allowed to be shared with the server or amongst other
clients due to privacy, regulations or trust. We describe such methods that include federated
learning, split learning, homomorphic encryption, and differential privacy for securely learning
and inferring with neural networks. We also study their trade-offs with regards to computational
resources and communication efficiency in addition to sharing practical know-how of deploying
such systems. 
<br/><br/>
**Takeaways:** Attendees will get an overview of secure, private distributed deep learning for
images and videos. Hands on examples of different distributed deep learning techniques that
operate while protecting confidential patterns in data will be shared. Finally, several in depth
examples demonstrating how these techniques can be implemented across various
configurations in different application domains will be shared.
<br/><br/>
**Tutorial Schedule: <br/>
00:00 -- 00:30 Module I: Introduction to Secure ML and Distributed Deep Learning <br/> by
Ramesh Raskar, MIT <br/><br/>
00:30 -- 01:30 Module II: Federated Learning at Google - Overview <br/> by
Brendan McMahan, Google <br/><br/>
01:30 -- 01:40 Q&A and Break<br/><br/>
01:40 -- 02:20 Module III: Split Learning <br/> by Praneeth Vepakomma, MIT and Otkrist Gupta, LendBuzz<br/><br/>
02:20 -- 03:00 Module IV: Federated Learning at Google - Research <br/> by
Jakub Konečný, Google<br/><br/>
03:00 -- 03:10 Q&A and Break<br/><br/>
03:10 -- 03:50 Module V:  Homomorphic Encryption for Neural Networks & Privacy Policies in Cloud <br/> by
Hassan Takabi, UNT <br/><br/>
03:50 -- 04:00 Discussion of Open Problems <br/><br/>**
**Duration:** Half-day (4 hours)<br/><br/>
**Organizers:**<br/>
Brendan McMahan (Google, USA)<br/>
Hassan Takabi (University of North Texas, Texas, USA)<br/>
Praneeth Vepakomma (MIT Media Lab, Cambridge, Massachusetts, USA)<br/>
Ramesh Raskar (MIT Media Lab, Cambridge, Massachusetts, USA)<br/>

**Lecturers:**<br/>
Brendan McMahan (Google, USA)<br/>
Jakub Konečný (Google, USA)<br/>
Otkrist Gupta (LendBuzz)<br/>
Ramesh Raskar (MIT Media Lab, Cambridge, Massachusetts, USA)<br/>
Hassan Takabi (University of North Texas, Texas, USA)<br/>
Praneeth Vepakomma (MIT Media Lab, Cambridge, Massachusetts, USA) <br/>

**References** <br/>
The key papers from the authors are:<br/>
1.) **(Federated learning)** Federated learning: Strategies for improving communication efficiency, <br/>Jakub Konečný, Brendan McMahan, Felix X. Yu, Ananda Theertha Suresh & Dave Bacon, [PDF](https://arxiv.org/pdf/1610.05492) (2016).<br/><br/>
2.) **(Split learning)** Distributed learning of deep neural network over multiple agents,<br/> Otkrist Gupta and Ramesh Raskar, Journal of
Network and Computer Applications, [PDF](https://www.sciencedirect.com/science/article/pii/S1084804518301590) (2018) <br/><br/>
3.) **(Split learning)** Reducing leakage in distributed deep learning for sensitive health data,<br/> Praneeth Vepakomma, Otkrist Gupta, Abhimanyu Dubey, Ramesh Raskar, Accepted to ICLR 2019 Workshop on AI for social good, [PDF](https://aiforsocialgood.github.io/iclr2019/accepted/track1/pdfs/29_aisg_iclr2019.pdf) (2019).<br/><br/>
4.) **(Split learning)** Split learning for health: Distributed deep learning without sharing raw patient data, <br/> Praneeth Vepakomma, Otkrist Gupta, Tristan Swedish, Ramesh Raskar, Accepted to ICLR 2019 Workshop on AI for social good, [PDF](https://arxiv.org/pdf/1812.00564.pdf) (2018).<br/><br/>
5.) **(Homomorphic encryption for deep learning)** CryptoDL: Deep Neural Networks over Encrypted Data, <br/> Ehsan Hesamifard, Hassan Takabi, and Mehdi Ghasemi, [PDF](https://arxiv.org/pdf/1711.05189) (2017).<br/><br/>
6.) **(Survey paper)** No Peek: A Survey of private distributed deep learning, <br/> Praneeth Vepakomma, Tristan Swedish, Ramesh Raskar, Otkrist Gupta, Abhimanyu Dubey, [PDF](https://arxiv.org/pdf/1812.03288.pdf) (2018).<br/><br/>
