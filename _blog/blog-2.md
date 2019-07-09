---
title: "My Thoughts on RSS'19"
excerpt: "Robotics: Science and Systems Conference, Freiburg 2019"
collection: blog
firstdate: 2019-07-01
update: n
---

# Declaimer
Just before getting into details, let me clarify some things. This blog does not reflect the view of the employer I am affiliated with. Most of the mentioned points are obviously subjective and are slightly biased towards my personal opinion. Moreover, I work in legged locomotion, so some of the technical notes here will be towards optimization, robotics, learning and control theory (especially the workshops). Shot out to [Romeo Orsolino](https://orsoromeo.github.io/) for helping me out in writing this review. 

---
# The conference
For those of you who might not be familiar with [RSS](http://www.roboticsconference.org/), it is one of the top three conferences in robotics (alongside ICRA and IROS). RSS this year was in Freiburg, Germany during June 22-26th. RSS was for five days, two days for the workshops and three days for the main (single track) conference. I personally enjoyed the entire conference but I think the workshops were better. Follow till the end, I will detail more on the workshops I attended. 

The conference had 272 paper submissions and 85 accepted papers. It had 5 spotlight talks per day (total of 15 spotlights). Each spotlight had roughly 5 presentations from the authors of the accepted papers followed by 10 minute Q&As. The conference also had 4 keynote talks and 2 early career talks. 

As verbally mentioned by A. Bicchi, the received papers were 40% higher than last year. Yet, the conference managed to keep the acceptance rate around 30%. Other statistics that were shown in the closing presentation are attached below. 

<center>
<img width="560"
src="/assets/images/1.jpg" alt="Markdown Monster icon"/>
</center>
<br>
<center>
<img width="560"
src="/assets/images/2.jpg" alt="Markdown Monster icon"/>
</center>
<br>
<center>
<img width="560"
src="/assets/images/3.jpg" alt="Markdown Monster icon"/>
</center>

<center>
Slides from A. Bicchi during the closing presentation. 
</center>

<br>
Apart from the technical details, I really enjoyed all of the presentations. They were exceptionally smooth with a great transition between speakers. I just hoped that speakers would have had a bit more time in presenting their work. Maybe not all of them, but a selection of presenters that can have longer presentations. Also, the “catch box” mic! Amazing idea. 

The quality of the papers, was great as expected from RSS. The topics were diverse and were tackling multiple trending problems in Robotics.  There was also a noticeable amount of industry partners and collaborators.

## Diversity
Just walking in the conference was joyful in terms of diversity. However, the gender ratio is still unbalanced. There were couple of initiatives/meet-ups that were advocating for women in robotics and LGBTQ+. For people who organize conferences, please learn and expand such such initiatives! Also for under-represented groups. Furthermore, I also over heard people talking about child-care. Although was not mentioned by the organizers as far as I know, but I did see some paid attention towards that. Again, please learn and expand such initiatives! Lastly, I really hoped the organizers would have gathers a statistic about gender ratio, ethnicity ratio, etc. 

## Research Trends
As expected, “deep learning” was the most dominant keyword in the conference. However, very few papers caught my interest that were exceptional. I guess it is a trend in deep learning that most of the papers that are in conferences are already outperformed by couple of more papers on ArXiV. 

Fun fact, I was asking a famous reinforcement learning researcher what he thinks of the deep RL papers in the conference. He said he wasn't a huge fan of the trend that is happening in deep RL in robotics. He specifically mentioned that most of the deep learning accepted papers this year might not be even read. The funny part is that while reading Chip Huyen’s [blog](https://huyenchip.com/2019/05/12/top-8-trends-from-iclr-2019.html) on ICLR, a similar point was noted! Now I am curious if it was the same researcher :) .

Although as a keyword it wasn't on the list, some researchers claimed that soft robotics is the current second biggest trend in robotics after deep learning.

## My Favorite Presentations and Papers
All of the keynote presentations were interesting. I personally enjoyed A. Schoelling’s and M. Riedmiller’s the most. Some papers you might want to take a look at:
- [Wagener, Nolan, et al. "An Online Learning Approach to Model Predictive Control."](http://www.roboticsproceedings.org/rss15/p33.pdf)
- [Bruder, Daniel, et al. "Modeling and Control of Soft Robots Using the Koopman Operator and Model Predictive Control."
](http://www.roboticsproceedings.org/rss15/p60.pdf)
- [Karkus, Peter, et al. "Differentiable Algorithm Networks for Composable Robot Learning."](http://www.roboticsproceedings.org/rss15/p39.pdf)
- [Zeng, Andy, et al. "TossingBot: Learning to Throw Arbitrary Objects with Residual Physics."](http://www.roboticsproceedings.org/rss15/p04.pdf)

You can still go see the the paper presentations and keynotes via this [link](https://www.youtube.com/channel/UCeEbAUGjtBlzmqWO5u6VeGg).

## There is always a room for improvement
During the last three days of the conference, the wifi was awfully bad. Every single person that I knew was complaining about it. I seriously was using my mobile data to check my emails. 

Also, a notable amount of authors were not able to attend due to visa issues. From what I understood is the letters of invitation were late. I believe that researchers and conference organizers should pay more attention to the visa issues (given what happened in RSS'19 and NeurIPS'19)

It felt like most of the sessions were not “field based”. A session would be having a presentation about model based control in locomotion and in the same session another a presentation about semantics in manipulation. Apples and oranges.

At this point, if you a Bosch AI employer, skip this part and go directly to the workshops. If not, proceed :)
Okay, seriously, Bosch AI, I think it your presence as a sponsor a little bit pervasive. We really, REALLY, don’t want to know about anything between the first dish and the main one. We also REALLY don’t want to watch yet another presentation between dinner and dessert. 

---
# Workshops
There were around 20+ parallel workshops over the first two days. It was impossible to attend all of the workshops but some honorable mentions would be 
[Women in Robotics](https://sites.google.com/view/rss2019women/home), 
[Scalable Learning for Integrated Perception and Planning](https://scalableroboticlearning.github.io/)
and [Combining Learning and Reasoning - Towards Human-Level Robot Intelligence](https://sites.google.com/view/rss19-learning-and-reasoning).

I tried to sneak into some workshops but I mainly attended the [Numerical Optimization for Online Multi-Contact Motion Planning and Control](https://sites.google.com/view/num-opt-for-legged-locomotion/)
and the [Closing the Reality Gap in Sim2real Transfer for Robotic Manipulation](http://sim2real.github.io/) one. 

## 1. [Numerical Optimization for Online Multi-Contact Motion Planning and Control](https://sites.google.com/view/num-opt-for-legged-locomotion/)
The workshop, from its name, was focusing on numerical optimization for legged robots.  The speakers were diverse ranging from numerical optimization, locomotion planning and control, legged robotics, polytopes, etc. The workshop had a detailed interactive discussion between the speakers and the attendees in the following points:

### Contact Modeling 
  - Is a trending topic (including contact modeling/scheduling). 
  - People are diverging away from the rigid contact model. Either for computational reasons or for modeling of compliant environments.  Yet, "It's complicated", as Andrea del Prete said.
  - Mujoco and its soft contact modeling seems to be taking over the community. Not just the simulator itself, but also the state of the art techniques used in trajectory optimization are competing.    

### Whole Body Optimization
- Whole-body optimization (including whole-body control (WBC) and whole-body MPC) is getting more and more important. Initialization (with offline optimization or ML) of such nonlinear systems is a key point.

- Researchers are moving far from the cascaded (pipelined) architecture of locomotion (the famous locomotion architecture from from the DARPA Robotics Challenge).

- MPC and control theory experts (e.g. Moritz Diehl) are finally getting interested in state-dependent switching dynamic systems (such as legged robots).

<!--- Justin Carpentier stuff-->

### (Deep) Learning
In the workshop, researchers were not happy with end-to-end learning. They agree that indeed RL is an essential tool in locomotion. But not to tackle locomotion as a single problem (end-to-end). As a personal opinion here, I believe there is a lot of challenges to solve in locomotion and surely deep learning (deep RL included) has a lot of potential to solve these challenges efficiently. Yet, I believe that researchers working on deep RL in locomotion must understand that they should let go of simulation papers and start tackling real world problems. This I believe would be rather more challenging in case of end-to-end learning.



## 2. [Closing the Reality Gap in Sim2real Transfer for Robotic Manipulation](http://sim2real.github.io/)
The workshop was focusing on Sim2Real transfer approaches in robotics (both manipulation and locomotion). I personally find it essential for researchers working in robotics learning to think critically in bridging the gap from simulation to the real world. Being recently interested in robotics learning, and coming from a robotics background, I think there are a lot of open problems that could be solved using learning. 
However, most of the of deep learning approaches (especially in legged locomotion) rely heavily on simulation (that are not even perfected yet). And in that perspective, sim2real becomes essential. 

I enjoyed most of the talks especially the ones from Erwin Coumans and Jean-Baptiste Mouret. Emo Todorov was shinning (as usual). The workshop featured  a super cool discussion by the speakers. The discussion was starring Emo Todorov who was positively criticizing the way research in being deal with. Below are some notes I found interesting to share:

### Emo Todorov
- Emo verbally mentioned that he is less in favor of model free RL. Todorov clarified by saying that stochasticity is not essential, the world (and controls) is rather deterministic. I remember that he raised a similar argument in CoRL'18 saying that "the robot only gets shaky when you plug in a model free RL to it".
- Emo also was in favor of working on something like feedback linearizion. In a sense that we should make a controller that makes the robot behave like in simulation rather than perfecting a simulator.

### Learning Locomotion
Although the workshop was mainly about sim2real for manipulation. There were two main talks given by 
[Jean-Baptiste Mouret](https://sim2real.github.io/assets/slides/mouret_rss_reality_gap-light.pdf) and [Erwin Coumans](https://drive.google.com/file/d/1cnYzhKEdjWK88G6WybAQgk6SyAHAGN0O/view) on sim2real for locomotion.

Jean's presentation was not mainly about sim2real but about online adaptation strategies for learning locomotion.
Jean mentioned in the presentation the importance of learning in locomotion.
He mentioned that one of the main challenges in locomotion is the ability
of the robot to recover and adapt its motion after failure. 
He mentioned some application if the robot falls or loses a limb. 
He also briefly described his current work on
online adaptation in case of damage
and also, learning the unmodeled non-linear dynamics of the legged robot. 

While briefly talking with Jean, he agrees that we shouldn’t be building learning strategies from scratch. We should heavily learn from the current state of the art in optimization techniques and exploit the experience of the experts in locomotion. 


Erwin's presentation was rather general. He mainly focused on the 
current research of his lab. Most importantly, he mentioned multiple
engineering topics that his lab is working on. 
For example, he mentioned the robot's that they are using. 
Also, their software framework which seems modular and intuitive.

I personally like the fact that Erwin is trying to find some method in the madness. 
In particular, the fact that his lab is working heavily on engineering, system identification and robotics research rather than just deep learning/RL in a perfectly simulated environment (that unfortunately most people are doing nowadays). 
I can see that the lab is working also in implementing classical locomotion 
techniques for comparison and benchmarking. 
For example, Erwin showed in the presentation that the lab also implemented
classical locomotion approaches such as hybrid zero dynamics and Raibert heuristics.
However, I did not see any comparison in Erwin's (and co-authors) papers against
these techniques (especially their last work on [Learning to Walk via Deep RL](https://arxiv.org/pdf/1812.11103.pdf) that did not even compare against the previous work of the authors).

During my discussions with Erwin and Jean, I really respected their commitment in contributed to the open source as well as being active on social media and open for discussions. Shot out to these guys!

Just as a side note, it would have been great if the workshop was recorded. I believe it is essential now a days to give access to such workshops. Given that the number of people attending the workshops/conferences are limited. 


---
# Final Thoughts
RSS'19 was amazing as usual. The workshops and papers were diverse and high quality. 
The community is getting more and more diverse in terms of research ethnicity/gender but also in terms of research fields. However, there is still always a room for improvement. 
I will keep updating this blog. I am totally open for discussions or suggestions to improve this blog.
