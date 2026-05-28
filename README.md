<p align="center">
  <img src="logo.png" alt="Microeconomists Building AI" width="200">
</p>

# Microeconomists Building AI: Resources

A community-maintained collection of resources for economists applying microeconomic theory, game theory, econometrics, industrial organization, and behavioral economics to the development of AI systems: post-training, alignment, safety, mechanism design for AI, and multi-agent systems.

Contributions are welcome. If you know of a resource that should be listed here, please [open an issue](https://github.com/econ-ai-guide/resources/issues) or submit a pull request.

> This guide grew out of [Kireyev and Maura-Rivero (2026), "From Microeconomics to AI Research: A Guide for Economists"](https://arxiv.org/) (arXiv link forthcoming).

---

## Suggested Reading

- Ouyang et al. (2022) -- [**InstructGPT**](https://arxiv.org/abs/2203.02155). The foundational RLHF paper.
- Rafailov et al. (2023) -- [**DPO**](https://arxiv.org/abs/2305.18290). Collapses reward modeling and policy optimization into a single objective.
- Christiano et al. (2017) -- [**Deep RL from Human Preferences**](https://arxiv.org/abs/1706.03741). The original deep RLHF paper; foundational for understanding how human preferences train policies.
- Bai et al. (2022) -- [**Constitutional AI**](https://arxiv.org/abs/2212.08073). How to use AI-generated feedback (RLAIF) instead of or in addition to human feedback.
- Lambert et al. (2024) -- [**Tulu 3**](https://arxiv.org/abs/2411.15124). Introduces reinforcement learning from verifiable rewards (RLVR) as a post-training method using deterministic reward signals.
- DeepSeek-AI (2025) -- [**DeepSeek-R1**](https://arxiv.org/abs/2501.12948). Demonstrates RLVR at scale, producing strong reasoning capabilities.
- Vaswani et al. (2017) -- [**Attention Is All You Need**](https://arxiv.org/abs/1706.03762). The transformer architecture.
- UK AI Safety Institute (2025) -- [**Economic Theory and Game Theory for AI Alignment**](https://alignmentproject.aisi.gov.uk/research-area/economic-theory-and-game-theory). Research agenda with concrete open problems for economists.
- Conitzer et al. (2024) -- [Social choice should guide AI alignment](https://arxiv.org/abs/2404.10271). Maps RLHF to social choice theory.
- Dafoe et al. (2021) -- [**Cooperative AI**](https://www.nature.com/articles/d41586-021-01170-0). The case for game theory in multi-agent AI.
- Igami (2020) -- [AI as structural estimation](https://doi.org/10.1093/ectj/utaa005). Translates RL into structural econometric language, making the conceptual bridge between dynamic programming in IO and RL explicit.
- Rahwan, Parkes et al. (2019) -- [**Machine Behaviour**](https://www.nature.com/articles/s41586-019-1138-y). Argues for studying AI systems as behavioural agents using tools from the social sciences.
- Athey & Luca (2019) -- [Economists (and Economics) in Tech Companies](https://www.aeaweb.org/articles?id=10.1257/jep.33.1.209). How economists came to play a central role in tech; context for the next frontier in AI labs.
- Breiman (2001) -- [**Statistical Modeling: The Two Cultures**](https://projecteuclid.org/journals/statistical-science/volume-16/issue-3/Statistical-Modeling--The-Two-Cultures-with-comments-and-a/10.1214/ss/1009213726.full). Foundational essay framing the data-modeling vs. algorithmic-modeling divide that runs between econometrics and ML.
- Sutton (2019) -- [**The Bitter Lesson**](http://www.incompleteideas.net/IncIdeas/BitterLesson.html). Influential ML manifesto: general methods that leverage compute outperform hand-engineered structure.
- Varian (2014) -- [**Big Data: New Tricks for Econometrics**](https://www.aeaweb.org/articles?id=10.1257/jep.28.2.3). First major JEP piece introducing the ML toolkit to economists.
- Mullainathan & Spiess (2017) -- [**Machine Learning: An Applied Econometric Approach**](https://www.aeaweb.org/articles?id=10.1257/jep.31.2.87). Reframes the divide as prediction vs. estimation; the sharpest introduction for economists.
- Athey & Imbens (2019) -- [**Machine Learning Methods That Economists Should Know About**](https://www.annualreviews.org/content/journals/10.1146/annurev-economics-080217-053433). The standard bridge survey.
- Kaplan et al. (2020) -- [**Scaling Laws for Neural Language Models**](https://arxiv.org/abs/2001.08361). Original power-law forms in parameters, data, and compute.
- Hoffmann et al. (2022) -- [**Training Compute-Optimal LLMs (Chinchilla)**](https://arxiv.org/abs/2203.15556). Compute-optimal allocation between parameters and data.
- Snell et al. (2024) -- [**Scaling LLM Test-Time Compute**](https://arxiv.org/abs/2408.03314). Test-time compute can substitute for parameters (ICLR 2025).
- Gao, Schulman & Hilton (2023) -- [**Scaling Laws for Reward Model Overoptimization**](https://arxiv.org/abs/2210.10760). The cleanest scaling result for RLHF specifically (ICML 2023).

## Curriculum and Learning Resources

| Resource | Topic | Link |
|----------|-------|------|
| Andrew Ng's Machine Learning | Supervised learning, regularization, evaluation | [Coursera](https://www.coursera.org/learn/machine-learning) |
| MIT 6.S191: Introduction to Deep Learning | Neural architectures, training dynamics, updated annually | [introtodeeplearning.com](https://introtodeeplearning.com/) |
| DeepMind RL Course (UCL) | Reinforcement learning foundations | [YouTube](https://www.youtube.com/playlist?list=PLqYmG7hTraZDVH599EItlEWsUOsJbAodm) |
| Andrej Karpathy: Neural Networks Zero to Hero | Transformers, attention, tokenization, full training pipeline | [YouTube](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) |
| Hugging Face Transformers + `trl` | Standard library for working with pretrained LLMs; `trl` provides RLHF/DPO fine-tuning pipelines | [huggingface.co](https://huggingface.co/docs/trl/) |
| Sutton & Barto: *Reinforcement Learning: An Introduction* | The standard RL textbook, freely available online | [incompleteideas.net](http://incompleteideas.net/book/the-book-2nd.html) |
| LeetCode | Algorithmic interview preparation (non-negotiable for industry roles) | [leetcode.com](https://leetcode.com/) |

## Research Communities

| Community | Description | Link |
|-----------|-------------|------|
| **Cooperative AI Foundation** | Research and events on game theory and multi-agent AI. YouTube channel connects economic theory to AI. | [cooperativeai.com](https://www.cooperativeai.com/) |
| **UK AI Safety Institute** | Research agenda on economic theory and game theory for AI alignment, with concrete open problems for economists. | [Alignment Project](https://alignmentproject.aisi.gov.uk/research-area/economic-theory-and-game-theory) |
| **ACM EC community** | The annual ACM Conference on Economics and Computation. Natural home for economists publishing on AI topics. | [sigecom.org](https://www.sigecom.org/) |
| **SC4AI** (Social Choice for AI) | Workshop series on how social choice can help with AI alignment. | [SC4AI](https://sites.google.com/view/sc4ai/home) |
| **MDAIS** (Mechanism Design for AI Safety) | Reading group and seminar on mechanism design, social choice, and game theory applied to AI alignment. Roughly monthly meetings. | [Alignment Forum](https://www.alignmentforum.org/posts/FhqZZFydyQG9WTSKR/announcing-mechanism-design-for-ai-safety-reading-group) |
| **CHAI** (Center for Human-Compatible AI) | Stuart Russell's center at UC Berkeley. Frames alignment in decision-theoretic and principal-agent terms; natural fit for economists. | [humancompatible.ai](https://humancompatible.ai/) |
| **Alignment Forum** | Central online hub for alignment research discussion and debate. | [alignmentforum.org](https://www.alignmentforum.org/) |
| **BATES** (Bay Area Tech Economics Seminars) | Seminar series at Stanford bringing together economists from academia and industry working on the technology economy, including AI. Free and open. | [Stanford Data Science](https://datascience.stanford.edu/causal/bay-area-tech-economics-seminars) |
| **CEPR AI Research Policy Network** | Led by Anton Korinek (UVA/Brookings). Webinar series and annual conference. Broad scope, but covers mechanism design, alignment, and compute governance alongside other AI economics topics. | [CEPR AI Network](https://cepr.org/research/research-policy-networks/artificial-intelligence) |
| **GovAI researcher network** | The Centre for the Governance of AI at Oxford maintains an active researcher network and runs workshops relevant to compute governance and AI cooperation. | [governance.ai](https://www.governance.ai/) |

## Summer Schools and Intensive Programs

| Program | Description | Link |
|---------|-------------|------|
| **EEML** (Eastern European Machine Learning Summer School) | Intensive exposure to cutting-edge ML research with strong networking opportunities. | [eeml.eu](https://www.eeml.eu/) |
| **M2L** (Mediterranean Machine Learning Summer School) | Similar format with focus on deep learning and applications. | [m2lschool.org](https://www.m2lschool.org/) |
| Extensive list of ML summer schools | Community-maintained directory. | [awesome-mlss](https://github.com/awesome-mlss/awesome-mlss) |

## Fellowship Programs

For economists interested in the intersection of economic theory and AI safety, particularly mechanism design, social choice, and principal-agent problems applied to alignment.

| Program | Description | Link |
|---------|-------------|------|
| **BlueDot Impact** | Online course providing foundational knowledge in AI safety principles. Good starting point. | [bluedot.org](https://bluedot.org/) |
| **MATS** (ML Alignment Theory Scholars) | Competitive fellowship pairing researchers with mentors at leading alignment labs. | [matsprogram.org](https://www.matsprogram.org/) |
| **PrincInt** (Principles of Intelligence) | Summer fellowship for researchers applying insights from social science and biology to AI safety. Formerly PIBBSS. | [princint.ai](https://princint.ai/) |
| **PIVOTAL** | Fellowship program for AI safety research. | [pivotal-research.org](https://www.pivotal-research.org/) |
| **Constellation** | Astra Fellowship supporting independent AI safety research. | [constellation.org](https://www.constellation.org/programs/astra-fellowship) |
| **LASR** (London AI Safety Research Labs) | 13-week research program in London. Small teams produce an AI safety paper with expert supervision. | [lasrlabs.org](https://www.lasrlabs.org/) |
| **Anthropic Fellowship** | Fellowship at Anthropic for safety-focused research. | [anthropic.com](https://alignment.anthropic.com/2024/anthropic-fellows-program/) |
| **ARENA** (AI Research Experience for Academics and Newcomers) | Structured program for researchers transitioning into AI. | [arena.education](https://www.arena.education/) |
| **GovAI Summer Fellowship** | Summer fellowship at the Centre for the Governance of AI, Oxford. Relevant for economists working on compute governance and mechanism design for AI regulation. | [governance.ai](https://www.governance.ai/opportunities) |
| **AI Safety Camp** | Collaborative research program where small teams work on focused AI safety projects over several months. Multiple cohorts per year. | [aisafety.camp](https://aisafety.camp/) |
| **SPAR** (Supervised Program for Alignment Research) | Semester-long, virtual, part-time mentored alignment research. Lower commitment than MATS or PrincInt. | [sparai.org](https://sparai.org/) |
| **CAIRF** (Cooperative AI Research Fellowship) | 3-month in-person fellowship in Cape Town. Tracks in multi-agent safety, cooperative AI, and gradual disempowerment. | [cai-research-fellowship.com](https://www.cai-research-fellowship.com/) |

---

## Contributing

Found a dead link, a new fellowship, or a resource that should be here? Please [open an issue](https://github.com/econ-ai-guide/resources/issues) or submit a pull request. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.
