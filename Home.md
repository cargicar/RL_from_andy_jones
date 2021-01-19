This is the wiki for the [reinforcement learning Discord](https://discord.gg/xhfNqQv).

As well as this main page, there's also [details of our Saturday meets](https://github.com/andyljones/reinforcement-learning-discord-wiki/wiki/Saturday-Meets). 

## Content of this Wiki
0. [First Steps](#first-steps)
1. [Debugging Advice](#debugging-advice)
1. [Things We Recommend](#things-we-recommend)
   - [Written Introductions](#written-introductions)
   - [Lecture Videos](#lecture-videos)
   - [Blogs](#blogs)
   - [Miscellaneous](#miscellaneous)
2. [Things We Made](#things-we-made)
3. [Things We Found](#things-we-found)
   - [Lecture Videos](#lecture-videos-1)
   - [Blogs](#blogs-1)
   - [Other Communities](#other-communities)
   - [Miscellaneous](#miscellaneous-1)
   - [RL Environments](#rl-environments)
   - [RL Frameworks & Reference Implementations](#rl-frameworks--reference-implementations)
4. [Future considerations](#future-considerations)

## First Steps
**If you're entirely new to reinforcement learning**, the best thing to do is to poke through the resources listed in [Written Introductions](#written-introductions) and [Video Introductions](#video-introductions) and see which ones suit your learning style.

All of these cover roughly the same material, and all have roughly the same prerequisites: 
 * you should be comfortable with probability, statistics, linear algebra and multivariable calculus at a first-year-undergrad level, 
 * you should be comfortable with programming in Python,
 * and you should be familiar with deep learning concepts like convolutions and gradient descent.

**If you're entirely new to probability/statistics/linear algebra/multivariable calculus**, we'll make a weak recommendation for Khan Academy's [stats](https://www.khanacademy.org/math/statistics-probability)/[lin alg](https://www.khanacademy.org/math/linear-algebra)/[calc](https://www.khanacademy.org/math/multivariable-calculus) courses, or for the [Mathematics for Machine Learning](https://mml-book.github.io/) book. These resources suit a lot of people well.

**If you're entirely new to programming in Python**, [the /r/python wiki has a range of introductory resources](https://www.reddit.com/r/python/wiki/index#wiki_online_books_and_resources) and we'll make a weak recommendation for [Automate the Boring Stuff With Python](https://automatetheboringstuff.com/) as a book that suits many people well. 

**If you're entirely new to deep learning**, [the /r/ML wiki has a range of introductory resources](https://www.reddit.com/r/MachineLearning/wiki/index), and we'll make a weak recommendation for [fast.ai](https://course.fast.ai/) as a course that suits many people well. 

## Debugging Advice
* [Amid Fish's advice](http://amid.fish/reproducing-deep-rl)
* [John Schulman's advice](https://github.com/williamFalcon/DeepRLHacks)
* [Spinning Up's advice](https://spinningup.openai.com/en/latest/spinningup/spinningup.html#learn-by-doing)
* [Marcin Gumer's advice](https://www.reddit.com/r/reinforcementlearning/comments/9sh77q/what_are_your_best_tips_for_debugging_rl_problems/e8p2as5/)
* [Stable Baseline's advice](https://stable-baselines3.readthedocs.io/en/master/guide/rl_tips.html)
* [Andy Jones's advice](https://andyljones.com/posts/rl-debugging.html)

If you go through these and you're still stuck, come ask for help in #practical on the Discord. Keep in mind that debugging RL is extraordinarily tricky even when you've direct access, so don't expect miracles! It helps a lot if you can share a minimal example, describe the problem in detail, and explain how you've tried to fix it so far. The more detail you put into your question, the more likely it'll be a good answer! 

## Things We Recommend
These resources are things we have first-hand experience of and can testify to the quality of.

If you've had a good experience with a resource, edit this page and increment the 👍. Feel free to move stuff from the things-we-found section up to here if you've personally had a good experience with it. If you're uncertain, come discuss it in #wiki first.

### Written Introductions
 * 3👍 [Spinning Up](https://spinningup.openai.com/) is somewhere between an extended tutorial and a short course, with a practical bent. 
 * 5👍 [Sutton & Barto's *Introduction to Reinforcement Learning*](http://incompleteideas.net/book/RLbook2020.pdf) is the standard intro textbook.
 * 1👍 [Deep Reinforcement Learning Series](https://medium.com/@jonathan_hui/rl-deep-reinforcement-learning-series-833319a95530) by [Jonathan Hui](https://medium.com/@jonathan_hui)
 * 1👍 [Algorithms for Decision Making](http://algorithmsbook.com/) by Mykel J. Kochenderfer, Tim A. Wheeler, and Kyle H. Wray. Great introduction for RL. Lots of great resources on various subjects. 

### Video Introductions
 * 5👍 [Introduction to Reinforcement Learning with David Silver](https://www.youtube.com/playlist?list=PLqYmG7hTraZBiG_XpjnPrSNw-1XQaM_gB), with [slides](https://www.davidsilver.uk/teaching/)
 * 2👍 [Deep RL Course by Thomas Simonnini](https://simoninithomas.github.io/deep-rl-course/)
 * 2👍 [Reinforcement Learning Specialization on Coursera](https://www.coursera.org/specializations/reinforcement-learning) from Martha and David White, professors at UAlberta
   * Unlike all the other materials listed here, this is not free. Our opinions on paywalled courses are divided, so take this as a qualified recommendation - only go down this route if you have a strong preference for MOOC-style learning. If you don't, any of the other free material is just as good.

### Miscellaneous
 * 2👍 [Lilian Weng's Blog on RL](https://lilianweng.github.io/lil-log/tag/reinforcement-learning), a *phenomenal* set of survey posts on different areas of RL.
 * 3👍 [RL Subreddit](https://www.reddit.com/r/reinforcementlearning/), the main hub for the RL community
 * 2👍 [TalkRL Podcast](https://www.talkrl.com/) is all about Reinforcement Learning


## Things We Made
These resources have been *written* by people on our Discord. The advantage of these resources is that you can ask the author questions about them! 

* [RL Lib](https://github.com/DarylRodrigo/rl_lib), by @-D-
* [BootlegAlphaZero](https://github.com/instance01/BootlegAlphaZero/), by @aylmao
* [Hindsight Experience Replay research](https://github.com/jscriptcoder/Hindsight-Experience-Replay), and [article](https://medium.com/@jscriptcoder/yet-another-hindsight-experience-replay-backstory-4285c43ff168), by @fran
* [Upside-Down RL research](https://github.com/jscriptcoder/Upside-Down-Reinforcement-Learning), and [article](https://medium.com/@jscriptcoder/demystifying-upside-down-reinforcement-learning-a-k-a-%EA%93%A4-b7bd4214b33f), by @fran
* [GraBZero](https://github.com/instance01/GRAB0/), by @aylmao
* [Open RL Benchmark](http://cleanrl.costa.sh/), and [Gym-MicroRTS](https://github.com/vwxyzjn/gym-microrts) by @Costa

## Things We Found
This is a broad-strokes collection of things we've found in our journey through RL that we think might be useful to others. It is much more lightly curated than the other sections.

### Lecture Videos
 * [Reinforcement Learning Course | DeepMind & UCL](https://www.youtube.com/playlist?list=PLqYmG7hTraZBKeNJ-JE_eyJHZ7XgBoAyb)
 * [CS285@berkeley - Deep Reinforcement Learning](http://rail.eecs.berkeley.edu/deeprlcourse/)
 * [CS234@stanford - Reinforcement Learning Winter 2019](https://www.youtube.com/playlist?list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u)
 * [Deep RL Bootcamp 2017](https://sites.google.com/view/deep-rl-bootcamp/lectures)
 * [RL course by Balaraman Ravindran (IIT Madras)](http://www.cse.iitm.ac.in/~ravi/courses/Reinforcement%20Learning.html)
 * [CS 330: Deep Multi-Task and Meta Learning](http://cs330.stanford.edu/)
 * [CS885@UWaterloo Spring 2018 - Reinforcement Learning](https://cs.uwaterloo.ca/~ppoupart/teaching/cs885-spring18/)

### Blogs
 * [BAIR](https://bair.berkeley.edu/blog/) Berkeley Artificial Intelligence Research.
 * [RL Weekly](https://v1.endtoend.ai/rl-weekly/) is a weekly newsletter highlighting important progress in reinforcement learning in research or industry.

### Other Communities
 * Active 
   * [/r/reinforcementlearning](https://www.reddit.com/r/reinforcementlearning/): the main hub for the RL community.
   * [Artificial Intelligence](https://discord.gg/gFCT9jm): an extremely large general AI discussion server, with an RL channel.
   * [EleutherAI](https://discord.com/invite/vtRgjbM): language-model focussed, but a lot of good general AI safety and scaling discussion too.
   * [TPU Podcast](https://t.co/ccHAqPgIiZ): GAN focussed, but a lot of good general ML discussion. Origin of the EleutherAI discord and project.
   * [ODS.ai](https://ods.ai/): their Slack has an active Russian-language community.
 * Less-active
   * [RL Group](https://discord.gg/2hz4kzK): previously the most active RL server, though now abandoned by the admin.
   * [International Reinforcement Learning Group](https://discord.gg/2Z98qcQ): another not-very-active RL discussion server, though apparently it has a busier private channel.

### Miscellaneous
 * [University of Alberta simple RL algorithm flow chart](https://cdn.discordapp.com/attachments/765294874832273422/768753225783836682/rl_algorithms_diagram.png)

### RL Environments
 * [OpenAI Gym](https://gym.openai.com/)
 * [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents)
 * [PyBullet Gymperium](https://github.com/benelot/pybullet-gym): Open-source implementations of OpenAI Gym MuJoCo environments
 * [osim-rl](http://osim-rl.stanford.edu/): Reinforcement learning with musculoskeletal models in OpenSim
 * [Project Malmö](https://github.com/Microsoft/malmo): platform for Artificial Intelligence experimentation and research built on top of Minecraft
 * [Multi-agent particle environment](https://github.com/openai/multiagent-particle-envs) used in the paper Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments
 * [Environment](https://github.com/hackthemarket/gym-trading) for reinforcement-learning algorithmic trading models
 * [Framework](https://github.com/tensortrade-org/tensortrade) for training, evaluating, and deploying robust trading agents
 * [Doom-based AI Research Platform](https://github.com/mwydmuch/ViZDoom) for Reinforcement Learning from Raw Visual Information
 * [OpenSpiel](https://github.com/deepmind/open_spiel): Collection of RL environments and algorithms
 * [ns3-gym](https://github.com/tkn-tub/ns3-gym): The Playground for Reinforcement Learning
 * [Reco-gym](https://github.com/criteo-research/reco-gym): A Reinforcement Learning Environment for the problem of Product Recommendation in Online Advertising
 * [RLBench](https://sites.google.com/view/rlbench): Robot Learning Benchmark
 * [OpenAI Gym trading environment](https://github.com/AminHP/gym-anytrading)
 * [Sairen](https://doctorj.gitlab.io/sairen/): OpenAI Gym Reinforcement Learning Environment for the Stock Market
 * [Meta-World](https://meta-world.github.io/): A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning
 * [Voyage Deepdrive](https://deepdrive.voyage.auto/): self-driving simulator
 * [CARLA](http://carla.org/): Open-source simulator for autonomous driving research
 * [Habitat](https://aihabitat.org/): A simulation platform for research in embodied AI
 * [MineRL](https://minerl.io/): Towards AI in Minecraft
 * [D4RL](https://sites.google.com/view/d4rl/home): Datasets for Deep Data-Driven Reinforcement Learning
 * [Multi-Agent-Learning-Environments](https://github.com/Bigpig4396/Multi-Agent-Reinforcement-Learning-Environment)
 * [PettingZoo](https://www.pettingzoo.ml/): Multi-agent RL environments
 * [MiniGrid](https://github.com/maximecb/gym-minigrid): Minimalistic Gridworld Environment
 * [endtoendAI](https://www.endtoend.ai/envs/): compilation of RL environments
 * [List of environments and competitions for RL and AI training](https://github.com/dbobrenko/ai-learning-environments)
 * [Official OpenAI environments](https://github.com/openai/gym/blob/master/docs/environments.md), and third party environments
 * [Awesome RL environment list](https://github.com/clvrai/awesome-rl-envs)

### RL Frameworks & Reference Implementations
 * [OpenAI Baselines](https://github.com/openai/baselines)
 * [Stable Baselines](https://stable-baselines.readthedocs.io/en/master/)
 * [Stable Baselines in Pytorch](https://stable-baselines3.readthedocs.io/en/master/)
 * [SLM Lab: Modular Deep Reinforcement Learning framework in PyTorch](https://slm-lab.gitbook.io/slm-lab/)
 * [Reinforcement Learning Coach](https://nervanasystems.github.io/coach/)
 * [Framework for training, evaluating, and deploying robust trading agents](https://github.com/tensortrade-org/tensortrade)
 * [RLBench: Robot Learning Benchmark](https://sites.google.com/view/rlbench)
 * [Meta-World: A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning](https://meta-world.github.io/)
 * [Denny Britz's implementations](https://github.com/dennybritz/reinforcement-learning) of basic RL algorithms.
 * [CleanRL](https://github.com/vwxyzjn/cleanrl/tree/master/cleanrl), single-file implementations of basic RL algorithms.
 * [RLlib by Ray](https://docs.ray.io/en/master/rllib.html)


## TODO
 * Split resources into academic and applied if it gets too big
 * Still need a 'maths hub' to point to, as well as specific recommendations 