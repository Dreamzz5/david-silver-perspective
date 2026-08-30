# 01 Writings And Systematic Arguments

## Scope

This file covers David Silver's papers, position essays, teaching material, and recurring systematic arguments. Credibility labels:

- Primary: written by Silver or official paper/project page.
- Primary coauthored: coauthored paper where the idea should not be attributed to Silver alone.
- Secondary: institutional or media interpretation.
- Inference: synthesis from repeated evidence.

## Core Sources

| Source | Type | What it supports |
|------|------|------|
| David Silver publications: https://davidstarsilver.wordpress.com/publications/ | Primary index | Long arc from Computer Go and MCTS to AlphaGo, AlphaZero, MuZero, Reward is Enough, and Era of Experience. |
| Reward is Enough: https://www.sciencedirect.com/science/article/pii/S0004370221000862 | Primary coauthored | Reward maximization as a possible sufficient basis for intelligence and associated abilities. |
| The Era of Experience: https://storage.googleapis.com/deepmind-media/Era-of-Experience%20/The%20Era%20of%20Experience%20Paper.pdf | Primary coauthored | Future AI progress should come from agents learning from experience, grounded rewards, long streams, and environment interaction. |
| AlphaGo 2016 Nature: https://www.nature.com/articles/nature16961 | Primary coauthored | Deep neural networks plus tree search, trained from expert games and self-play, defeated a professional Go player. |
| AlphaGo Zero 2017 Nature: https://www.nature.com/articles/nature24270 | Primary coauthored | Self-play reinforcement learning without human data or domain knowledge beyond game rules. |
| AlphaZero arXiv: https://arxiv.org/abs/1712.01815 | Primary coauthored | A general reinforcement learning algorithm achieved superhuman chess, shogi, and Go performance from random play. |
| MuZero arXiv: https://arxiv.org/abs/1911.08265 | Primary coauthored | Planning with a learned model that predicts reward, policy, and value rather than full dynamics. |
| Deterministic Policy Gradient Algorithms: https://proceedings.mlr.press/v32/silver14.html | Primary coauthored | Scalable policy learning in continuous/high-dimensional action spaces. |

## Repeated Theses

### Reward maximization as a unifying frame

- Evidence: `Reward is Enough` argues that intelligence and associated abilities can arise from reward maximization.
- Cross-domain recurrence: appears in position papers, WIRED interviews, and the later experience-first company mission.
- Caveat: This is a hypothesis and a coauthored thesis. It should be used as a frame, not as a settled truth.

### Experience over imitation

- Evidence: AlphaGo Zero and AlphaZero remove human games as training data; Era of Experience argues human data is finite and agents need their own experience streams.
- Cross-domain recurrence: board games, Atari, long-horizon agents, scientific discovery, superlearner mission.
- Caveat: Needs environments and feedback that are rich enough, safe enough, and not trivial to game.

### Learning plus planning

- Evidence: AlphaGo combines policy/value networks with MCTS; MuZero plans with a learned reward/policy/value model.
- Earlier lineage: simulation-based search in Computer Go and POMCP.
- Caveat: Planning can be computationally expensive and model errors compound over long horizons.

### Reduce handcrafted knowledge

- Evidence: AlphaGo uses expert data; AlphaGo Zero removes human data; AlphaZero generalizes across games with only rules; MuZero removes known dynamics.
- Interpretation: The research direction is not "no human input ever," but a systematic diet of human priors.
- Caveat: Architectures, objectives, environments, and evaluation remain human-designed.

### Experience as future data source

- Evidence: Era of Experience states that future agents should learn from streams of experience, grounded actions/observations, grounded rewards, and planning about action consequences.
- Connection: Ineffable Intelligence's mission states that superlearning is driven by reinforcement learning and self-generated experience.
- Caveat: This is the newest and least independently validated part of the arc.

## Candidate Mental Models

1. Reward Compass
2. Experience Over Imitation
3. Search-Learning Loop
4. Self-Play Curriculum
5. Human-Knowledge Diet

## Contradictions And Tensions

- Ambition vs evidence: The broad claim aims at general intelligence, but strongest empirical evidence comes from games, simulators, and structured domains.
- Fewer priors vs necessary scaffolding: The work removes some human knowledge while relying on human-designed learning systems.
- Reward clarity vs human values: Scalar or learned reward signals may not capture multi-objective social values.
