**Day 1:**

• Pledged to participate in the 60daysofudacity challenge.

• Finished the first project of the lesson 6, Playing with Remote Tensors.

• Looked for an opportunity to join/host a local meetup.

• Revisited my final project for the lesson 5 to see if I can make any improvement.

---

**Day 2:**

• Watched course videos on remote arithmetic and garbage collection with PySyft (Lesson 6).

• Finished the project "Learn a Simple Linear Model".

(Planning to start reading "The Algorithmic Foundations of Differential Privacy".)

(Also planning to read research papers on Deep Learning with Differential Privacy, and PATE analysis.)

(Going to find virtual meetups or host one since finding some people to have local meetups here seems quite challenging.)

---

**Day 3:**

• Finished Lesson 6: Federated Learning

• Started and finished the second section project: Federated Learning on MNIST—the project description does not give any detailed instruction, so I just decided to stick with MNIST. (GitHub link: https://github.com/wytyang00/private-ai/blob/master/final_projects/Section%202%20-%20Federated%20Learning.ipynb?fbclid=IwAR3TVBHX0CtHIEItuyCu1ucxtLJijX4Sn5ICy7MRcx4XGtgnz9_V09xUXb8)

---

**Day 4:**

• Started Lesson 7: Securing Federated Learning

• Finished the first project of Lesson 7: Federated Learning with a Trusted Aggregator (https://github.com/wytyang00/private-ai/blob/master/Section%203%20-%20Securing%20Federated%20Learning.ipynb?fbclid=IwAR3Fc4FVbuo1gsI4akUooADPifR7jZgrB3TqlFXusr1VVgsrmQUHTRsJo7I)

• Joined a study group with @<u>Abhimanyu</u>, @<u>Bhadresh Savani</u>, @<u>Mukul Kathpalia</u>, and many others!

• Had the first online group meetup with @<u>Abhimanyu</u>, @<u>Bhadresh Savani</u>, @<u>Mukul Kathpalia</u>!

---

**Day 5:**

• Formed a local Korean group with 2 other Koreans (+ and potentially one more in the future)

• Scheduled our first local meetup.

• Trying a different approach—the one Andrew demonstrated—to the first project of Lesson 8: Federated Learning with Trusted Aggregator. (Currently experiencing bugs, but I'll fix it by tomorrow.)

---

**Day 6:**

• Continuing on my second attempt to the Lesson 8's first project: Federated Learning with Trusted Aggregator. Narrowed down where things were going wrong, but still can't grasp exactly why it's happening :(

• Discussed a bit about the study group form with both groups I'm in. Still needs to make decisions before we can submit the forms.

• Watched the lectures about Additive Secret Sharing

---

**Day 7:**

• Helped a local fellow scholar debug his PPO code.

• Watched the intro & demo videos on the Lesson 8's second project: Encrypt, Decrypt, and Add.

• Finished the project—Encrypt, Decrypt, and Add—as well.

---

**Day 8:**

• Went to a DL conference and saw brief or detailed overview of many interesting topics: Graph Neural Networks, Knowledge Distillation, Intuition behind DQN extensions, Relational Learning

• Watched all the videos left in the lesson 8: Securing Federated Learning (Fixed Precision Encoding, Doing it using PySyft, Final Project Description)

---

**Day 9:**

• Went half-way through the final project of section 3. Planning to change the training code so that it encodes the gradients or parameters, encrypt them, share them among workers, and then finally aggregate them in the trusted worker.

• Had a virtual meet-up in which we introduced ourselves, discussed any doubts or questions on the course, and talked about project ideas. (@<u>Shivam Raisharma</u> @<u>nabhanpv</u> @<u>Alejandro Galindo</u> @<u>Dharmendra Choudhary</u> @<u>Alejandro Galindo</u> @<u>Ricardo Pretelt</u> @<u>Ingus Terbets</u> @<u>Droid</u> @<u>Sadmi Bouhafs</u> @<u>souvikb1812</u> @<u>Abhishek Tandon</u>)

---

**Day 10:**

• Finished the final project of Section 3 - Securing Federated Learning. I replaced the trusted aggregator with additive secret shares and fixed precision, and the problem suddenly became clearer and simpler! (Notebook link: https://github.com/wytyang00/private-ai/blob/master/final_projects/Section%203%20-%20Securing%20Federated%20Learning.ipynb)

---

**Day 11:**

• Started on the Lesson 9: Encrypted Deep Learning.

• Learned about the field arithmetic involved in the addition, subtraction, and public multiplication with encrypted shares.

• Implemented a PPO agent in a stock training gym environment.

• Skimmed through the BigBiGANs paper.

---

**Day 12:**

• Began the first project of the lesson 8: Encrypted Deep Learning

• Project: started training both PPO and Rainbow DQN agents in trading gym environments.

---

**Day 13:**

• Finished the Encrypted Database project in lesson 9: Encrypted Deep Learning!

• Applied my Rainbow DQN code in the trading gym environment, and it performed much better than our implementation of a PPO agent! (@jeffrey Lim_2)

---

**Day 14:**

• Finished the lessons from 9.6 through the end of the course!

Now I need to start working on the keystone project. I'm thinking of doing it as a group...

---

**Day 15:**

• Decided to continue with my music generation project: https://github.com/wytyang00/undertale_deltarune_soundtrack_generator

• Searched for ideas & examples of models used for music (or any sequential data) generation. I've found several things I could try: **Professor Forcing**, **Scheduled Sampling**, **PixelRNN**, **PixelCNN++**

• Resources I've found:

  * https://www.youtube.com/watch?v=nA3YOFUCn4U

  * https://towardsdatascience.com/auto-regressive-generative-models-pixelrnn-pixelcnn-32d192911173

  * https://arxiv.org/abs/1610.09038

---

**Day 16:**

• Attended a local Korean meet-up in the evening with @Yujin, @jeffrey Lim_2, @GwKim! We introduced ourselves to each other, shared recent activities, and discussed some concepts and projects.

---

**Day 17:**

• Edited part of my code for the Section 3 project, mainly to clarify the steps for updating the global model using the trained local models: (https://github.com/wytyang00/private-ai/blob/master/final_projects/Section%203%20-%20Securing%20Federated%20Learning.ipynb)

• Currently following the walk-through of _Attention Is All You Need_ and a PyTorch implementation of Transformer: (http://nlp.seas.harvard.edu/2018/04/03/attention), (https://github.com/wytyang00/Transformer-Hands-On-Tutorial)

---

**Day 18:**

• After downloading the trading history of BNB/BTC, configuring the _Buying_ and _Selling_ mechanisms in our custom trading environment, and scaling the rewards with respect to the initial budget, @jeffrey Lim_2 and I finally started training a Rainbow DQN to see whether it can learn anything in the environment. (https://github.com/deconlabs/Binanace_trading_simulation)

• I'm still following through the article _Annotated Transformer_. I'm not so familiar with using masks, so I'm trying to understand their roles in this algorithm...

---

**Day 19:**

• Finally got in to one of the core parts of our trading simulation project: training many agents with different "risk-aversion" parameter in parallel. Due to the size of the replay memory growing bigger for each Rainbow agent—which is an improved version of DQN—we could fit only about 30 agents using 126GB of RAM—we still have quite a bit of space in vRAM, but the lack of CPU RAM is not allowing us to fully utilize our GPUs... (https://github.com/deconlabs/Binanace_trading_simulation)

---

**Day 20:**

• Found out that the code in here(http://nlp.seas.harvard.edu/2018/04/03/attention) contains many deprecated or significantly changed functions. Spent most of my time on this notebook fixing it so that it's compatible with the latest PyTorch version... Seems like actually understanding the Transformer algorithm would take a few more days. (https://github.com/wytyang00/Transformer-Hands-On-Tutorial)

---

**Day 21:**

• Still investigating the Transformer code.

• Started training a set of copies of trained DRL agents in a trading environment with different fee configuration.

---

**Day 22:**

• Continued re-training the RL agents in trading environments with different fees.

• Found a similar study done by another group and started reading the paper to see how they approached this problem (http://www.nada.kth.se/~ann/exjobb/marcus_elwin.pdf)

---

**Day 23:**

• Visualized each part of the Transformer implemented in the code so that I can grasp how they are connected together: https://github.com/wytyang00/Transformer-Hands-On-Tutorial

---

**Day 24:**

• Understood most part of the Transformer architecture. Trying to understand the implementation for the multi-head attention.

---

**Day 25:**

• Started training my own agent with LSTM and self-attention in the trading environment while other agents are being trained.

• Also, fixed some parts of the training code where some values were held constant when they were supposed to be variable.

---

**Day 26:**

• Continued to train DRL trading agents based on bidirectional LSTM and Multi-head Self-Attention in two different environment configurations—more configurations are planned.

• Implemented "Integrated Gradients" method for computing feature importance values.

---

**Day 27:**

• Visualized feature importance and attention weights of trading agents. (https://github.com/deconlabs/Binanace_trading_simulation)

• Started training another agent with attention with increasing number of timesteps per episode.

---

**Day 28:**

• Continuing my music generation project, this time using Professor Forcing method (https://arxiv.org/abs/1610.09038)—it's very similar to GANs. Still a work in progress (https://github.com/wytyang00/undertale_deltarune_soundtrack_generator).

---

**Day 29:**

• Defined the generator and discriminator models that will be used for training a generative RNN model using Professor Forcing method. (https://github.com/wytyang00/undertale_deltarune_soundtrack_generator)

---

**Day 30:**

• Implemented a free-running sequence generation function for my generator model. It's yet to be tested, but it should pass starting inputs to the generator model and sequentially generate a new sequence by letting the generator use its last output as current input. (https://github.com/wytyang00/undertale_deltarune_soundtrack_generator?fbclid=IwAR2vhPqbPo3Kz9BcJir6MOb8H-lt9FRubjmL6SpcfV-wh6Vprub_T5tCEvs)

---

**Day 31:**

• Implementation of Discriminator Loss Function for Professor Forcing is in progress. Trying to be cautious here since this is the most important part of the training... (https://github.com/wytyang00/undertale_deltarune_soundtrack_generator)

---

**Day 32:**

• Began my attempt to solve Pong with Rainbow DQN.

• Implemented the Generator Loss Function for Professor Forcing training. (https://github.com/wytyang00/undertale_deltarune_soundtrack_generator)
