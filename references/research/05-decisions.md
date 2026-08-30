# 05 Decisions And Project Arc

## Evidence Key

- Fact: directly sourced event.
- Logic: stated by Silver, a coauthoring team, or a reputable institution.
- Inference: synthesis from multiple sources, not directly stated.

## Elixir Studios To Games As Intelligence Substrate

- Fact: After Cambridge, Silver co-founded Elixir Studios and served as CTO/lead programmer. Source: UCL inaugural lecture note.
- Inference: This looks like the practical systems/game-AI apprenticeship before his academic RL pivot.

## University Of Alberta And Rich Sutton

- Fact: Silver returned to academia in 2004 for a PhD in reinforcement learning with Rich Sutton, studying simulation-based search in Computer Go.
- Logic: This is where RL, temporal-difference learning, search, and Go became one technical lineage.
- Source: UCL note and David Silver publications.

## UCL

- Fact: Silver received a Royal Society University Research Fellowship in 2011 and became a lecturer/professor at UCL.
- Inference: UCL gave him a teaching and research base while DeepMind gave him scale.
- Source: UCL and Royal Society profile.

## DeepMind

- Fact: Silver consulted for DeepMind from its inception and joined full-time in 2013.
- Logic: The lab's AGI mission matched his RL-as-intelligence framing.
- Source: UCL note and personal site.

## AlphaGo

- Fact: Silver led AlphaGo, which defeated a top professional Go player and then Lee Sedol.
- Logic: Go was a grand challenge because ordinary brute-force methods and hand-coded evaluation struggled.
- Decision pattern: choose a hard but clean domain where learning and search can be tested decisively.
- Sources: Royal Society, Google DeepMind AlphaGo page, Nature 2016.

## AlphaGo Zero And AlphaZero

- Fact: AlphaGo Zero learned without human data; AlphaZero generalized self-play learning to chess, shogi, and Go.
- Logic: Remove human priors where possible; let the system become its own teacher.
- Decision pattern: after proving the hybrid approach, strip away human examples and domain-specific heuristics.
- Sources: DeepMind AlphaGo Zero, Nature 2017, AlphaZero arXiv/Science coverage.

## AlphaStar And MuZero

- Fact: Silver co-led AlphaStar; MuZero mastered Go, chess, shogi, and Atari without known rules/dynamics.
- Logic: Test whether self-play/planning ideas survive partial information, multi-agent settings, and unknown environments.
- Decision pattern: move from clean board games toward messier and less fully specified environments.
- Sources: DeepMind AlphaStar, DeepMind MuZero, Royal Society.

## Ineffable Intelligence

- Fact: Silver's personal site lists him as CEO of Ineffable Intelligence. Ineffable states a mission to build a superlearner that discovers knowledge from experience through reinforcement learning.
- Logic: The company extends the AlphaZero thesis from games toward general superlearners.
- Caveat: Public detail about internal methods is limited.
- Sources: David Silver personal site, Ineffable Intelligence website, GOV.UK announcement, WIRED 2026 profile.

## Decision Heuristic Extracted

Silver repeatedly seems to choose domains or institutions where:

1. Feedback exists.
2. The system can generate its own training data.
3. Search/planning can amplify learning.
4. Human priors can be reduced over time.
5. Success or failure is empirically visible.
