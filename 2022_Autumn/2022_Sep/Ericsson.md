---
title: "Internship Experience at Ericsson Research"
category: "Experiences"
date: "2022-09-11 12:00:00 +05:30"
desc: "Join Kranthi as he talks about his internship experience at Ericsson research where he worked on building reinforcement learning environments and analysing risk profiles."
thumbnail: "./images/Ericsson_Kranthi.jpg"
authors: "Kranthi Sedamaki"
starred: "false"
abio: ""
alt: "Internship Experience at Ericsson Research"
---
## A bit about myself

I am Kranthi, a senior at IIT Tirupati, pursuing a bachelor's in Computer Science and Engineering. I worked as an intern at Ericsson Research during my summer. I am planning to pursue a master's after my B. Tech, and therefore I believed that a research internship would add more value to my resume.

## The selection process

After an initial resume screening, an interview was held for the shortlisted candidates. The questions asked were based on the applications of Artificial Intelligence (AI) and Machine Learning (ML) in the supply chain. It mainly centered around the topic I would be working on after being selected. The interviewer was interested in understanding how I would approach the problem. Even though I was a bit shaky on some of the questions, I spelled out my initial thoughts. As the interview progressed, I built on top of those thoughts. It turns out that did the trick, and I got in!

## The internship

Ericsson orders electronic components from many suppliers and delivers them to its end-user companies. The problem statement was to profile suppliers' risk index based on their delivery patterns. Additionally, we could work on developing a Reinforcement Learning (RL) environment and train agents to anticipate delays and place orders among suppliers based on their risk profile if we had stable methods for the initial problem statement. I was a bit overwhelmed at first because I did not understand the data, the jargon of the supply chain industry, and most of all, since I hadn't applied reinforcement learning anywhere.

I was a bit relieved when I learned that I had the flexibility to work on my schedule — two 30-minute meetings with my mentor per week to sync up on the progress. My mentor offered me much freedom to choose my direction to proceed. I was comfortable with the basics of machine learning applications. Here's vital learning: most of the time, it's about the data and less about the model you are using. The ML models available in libraries like sci-kit-learn are stable and will produce excellent results without hyperparameter tuning. The critical part of improving a model's performance is fully engineering and pre-processing features from the dataset. Identifying such factors and creating new features using domain knowledge helps a lot in terms of the interpretability of the ML models.

After a few iterations, we settled on a stable model for profiling the suppliers. We moved on to the next phase of developing an environment and training RL agents to split the order between the suppliers based on their risk index. It was my first time playing with RL, and once I got a few basic environments and agents up and running, it boosted my confidence. It was like teaching a child and watching it grow! My understanding from ML has translated well to RL as well. A library called [stable baselines3](https://stable-baselines3.readthedocs.io/en/master/) implements popular RL algorithms, which work well without any fine-tuning. It was up to the environment design that determined how the agent behaved. It was a bit tricky because creating an environment that captures the stochasticity of the company while being practical enough to train is a tricky balance. After making realistic assumptions covering most of the scenarios, the agent learned well.

As everything was wrapping up, I developed a web-based tool that could be used by the stakeholders, which incorporates both of the components of my internship. My mentor suggested I write a research paper covering everything we have done because these techniques are novel in the supply chain industry. For the last few weeks of my internship, my mentor and I worked on a paper we would submit to a conference. The company said it would sponsor us to file for a patent for the developed methods if we were applying for it. The paper is under review as of this writing.

Overall, I am delighted with the outcome of this internship, and it looks like my mentor is also impressed. He offered to recommend me for a data scientist role at an international office after my master's. I was super pleased to hear it! I believe the research paper and the patent will benefit me when I apply for my master's. My favorite bit was the flexibility to work on my own hours. This internship offered me the chance to put my skills to real-world use and tie up loose ends in my understanding of these concepts.
