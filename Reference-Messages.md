An easy-to-reference collection of messages that we'll want to point to from time to time. 

### [On debugging RL algorithms](https://discord.com/channels/765294874832273419/765294874832273422/771326797571948564), @bt

i'd really like to see an in-depth article on debugging RL, although i understand how difficult it would be to give general advice to what are usually very specific problems. i've found the following pretty helpful though: 
- http://amid.fish/reproducing-deep-rl
- https://www.youtube.com/watch?v=8EcdaCk9KaQ (written up: https://github.com/williamFalcon/DeepRLHacks)
- https://www.reddit.com/r/reinforcementlearning/comments/9sh77q/what_are_your_best_tips_for_debugging_rl_problems/e8p2as5/
- https://www.reddit.com/r/reinforcementlearning/comments/iudzsn/help_trying_to_implement_policy_gradient_in/g5ktdvn/?context=3

### [On JAX frontends](https://discord.com/channels/765294874832273419/765939632327229440/771864560931962921), @inoryy
They're done by different teams inside Alphabet to match their different use cases, e.g. Flax by Google Research and Haiku by DeepMind. They are all actively used and developed internally with a clear roadmap for '21 at least. Your best bet is to look through examples of all 3 and decide for yourself. Of course if you're interested in using acme then Haiku is probably a good idea.

JAX should work well on GPUs but its bread and butter are TPU workloads.

For the use cases I'd say JAX shines as a reseach framework so the weirder things you want to do the better your relative experience will be. On the other hand if you have a very well defined applied ML problem you would need to quickly develop and deploy then maybe not the best option.

Oh and of course JAX shines at distributed ML workflows, probably the only sane way to run TPU pod+ scale setups (>1k devices)