# LLM & cognitive-psychology Paper List

## 目录
1. [LLM consistent with humans](#section1)
2. [LLM inconsistent with humans](#section2)
3. [Cognitive psychology](#section3) 

## LLM consistent with humans <a name="section1"></a>

1. Avalon's Game of Thoughts: Battle Against Deception through Recursive Contemplation.
  
   https://arxiv.org/abs/2310.01320

   Agent for Avalon

2. EmotionPrompt: Leveraging Psychology for Large Language Models Enhancement via Emotional Stimulus.

   https://arxiv.org/abs/2307.11760

   prompt里面加上“This is very important to my career” 可以增加reason的能力

3. War and Peace (WarAgent): Large Language Model-based Multi-Agent Simulation of World Wars

   https://arxiv.org/pdf/2311.17227.pdf

   LLM agent, 模拟世界大战

 4. TURNING LARGE LANGUAGE MODELS INTO COGNI- TIVE MODELS

    https://arxiv.org/abs/2306.03917

    finetune llm on psychological experiment data, and turn it into the cognitive model. align better with human behavior, and can generalize to other cognitive tasks. (maybe have learned the cognitive pattern/ability)

5. Personality Traits in Large Language Models

   https://arxiv.org/abs/2307.00184

   根据心理测量学，llm具有稳定的个性。而且这些个性可以被有意识地改变。

6. ReAct: Synergizing Reasoning and Acting in Language Models

   https://arxiv.org/pdf/2210.03629.pdf

7. What makes Chain-of-Thought Prompting Effective? A Counterfactual Study

   https://aclanthology.org/2023.findings-emnlp.101.pdf

8. Language models and psychological sciences

   https://www.frontiersin.org/articles/10.3389/fpsyg.2023.1279317/full

   Carefully evaluating LLMs with the tools of cognitive psychology will further understand the building blocks of the human mind.

9. Improving Factuality and Reasoning in Language Models through Multiagent Debate

    https://arxiv.org/abs/2305.14325

10. Large pre-trained language models contain human-like biases of what is right and wrong to do

    https://arxiv.org/abs/2103.11790

11. Capturing Failures of Large Language Models via Human Cognitive Biases

    http://arxiv.org/abs/2202.12299

12. Thought Cloning: Learning to Think while Acting by Imitating Human Thinking

    https://arxiv.org/pdf/2306.00323.pdf

    RL agent做下一个动作的时候考虑了thought

13. Think Twice: Perspective-Taking Improves Large Language Models’Theory-of-Mind Capabilities

    https://arxiv.org/pdf/2311.10227.pdf

14. Ask Again, Then Fail: Large Language Models' Vacillations in Judgement

    https://arxiv.org/pdf/2310.02174.pdf

    当面对挑战或误导信息时，LLMs经常会改变它们最初的正确判断，导致判断一致性下降

15. Learning From Mistakes Makes LLM Better Reasoner

    https://arxiv.org/pdf/2310.20689.pdf

16. Eliminating Reasoning via Inferring with Planning: A New Framework to Guide LLMs’ Non-linear Thinking

    https://arxiv.org/pdf/2310.12342.pdf

    LLM can own Non-linear Thinking like humans.

17. Decomposition Enhances Reasoning via Self-Evaluation Guided Decoding

    https://arxiv.org/abs/2305.00633

    人类会通过将长形问题分解成子步骤来认知地解决问题，LLM可以通过问题分解的明确阶段和细致的反馈来提高其可信度

18. Re-Reading Improves Reasoning in Language Models

    https://arxiv.org/abs/2309.06275

    在prompt里加“read the question again: xxxx” 可以增加正确率

19. ADAPTING LARGE LANGUAGE MODELS VIA READING COMPREHENSION

    https://openreview.net/pdf?id=y886UXPEZ0

    预训练大模型的时候将data comprehensive read
    
20. How Large Language Models Implement Chain-of-Thought?

    https://openreview.net/pdf?id=b2XfOm3RJa

21. LARGE LANGUAGE MODELS CAN SELF-IMPROVE

    https://arxiv.org/pdf/2210.11610.pdf

    加了个voting 自己训练自己

22. Large Language Models as Analogical Reasoners

    https://arxiv.org/pdf/2310.01714.pdf


## LLM inconsistent with humans <a name="section2"></a>

1. Large Language Models Fail on Trivial Alterations to Theory-of-Mind Tasks

   https://arxiv.org/abs/2302.08399

2. Large Language Models Can Be Easily Distracted by Irrelevant Context

   https://arxiv.org/abs/2302.00093

   容易被无关信息打扰

3. LLMs cannot find reasoning errors, but can correct them!

   https://arxiv.org/pdf/2311.08516.pdf

4. Large language models cannot self-correct reasoning yet

   https://arxiv.org/pdf/2310.01798.pdf

5. Do LLMs exhibit human-like response biases? A case study in survey design

   https://arxiv.org/pdf/2311.04076.pdf
   
6. The Reversal Curse: LLMs trained on "A is B" fail to learn "B is A"

   https://arxiv.org/abs/2309.12288

7. It's Not Easy Being Wrong: Evaluating Process of Elimination Reasoning in Large Language Models

   https://arxiv.org/abs/2311.07532

   知道正确答案，无法选出错误答案

8. Let there be a clock on the beach: Reducing Object Hallucination in Image Captioning

   https://openaccess.thecvf.com/content/WACV2022/html/Biten_Let_There_Be_a_Clock_on_the_Beach_Reducing_Object_WACV_2022_paper.html

   LVLMs are sensitive to additional contextual information.

9. LARGE LANGUAGE MODELS ARE NOT ROBUST MULTIPLE CHOICE SELECTORS

    https://openreview.net/pdf?id=shr9PXz7T0

   对选择题放各个选项有bias

10. Multilingual Large Language Models Are Not (Yet) Code-Switchers

    https://arxiv.org/pdf/2305.14235.pdf

    不能multilingual

11. Prompting is not a substitute for probability measurements in large language models

    https://arxiv.org/pdf/2305.13264.pdf

    internal和external 的probability不一致

12. Conceptual structure coheres in human cognition but not in large language models

    https://arxiv.org/abs/2304.02754

    difference between LLMs and human cognition in Conceptual structure

13. Cognitive Dissonance: Why Do Language Model Outputs Disagree with Internal Representations of Truthfulness?

    https://arxiv.org/abs/2312.03729

    同11， internal 和 external做classifier不一致


14. Role-Play with Large Language Models

    https://arxiv.org/abs/2305.16367

    大模型只是在角色扮演，大模型，在人前表现得彬彬有礼、知书达理的样子，其实都只是装出来的。事实上，他们并不具有人类的情感，也没什么像人的地方。
   


## Cognitive psychology <a name="section3"></a>
1. A little overview of Cog Psych

2. Using cognitive psychology to understand GPT-3

   https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9963545/

   Using cognitive psychology tools to assess GPT-3’s capabilities of decision-making, information search, deliberation, and causal reasoning

3. An integrated theory of language production and comprehension(detailed)

   https://eprints.gla.ac.uk/82858/1/82858.pdf

   挑战将语言处理视为生产（说话，写作）和理解（听，读）分开活动的传统观点。

4. When Should We Prefer Offline Reinforcement Learning Over Behavioral Cloning?

   https://arxiv.org/abs/2204.05618

   行为克隆和强化学习是学习决策策略的两大主要训练方案。它们在定义目标（损失）时的微妙差异可以在人类的认知和行为过程中找到其根源。

5. Embodied intelligence via learning and evolution
  
   https://www.nature.com/articles/s41467-021-25874-z

   虽然进化强化学习能够使多样化的代理形态进化以学习复杂环境中的挑战性移动和操纵任务，我们是否可以类似地探询如何研究LLMs以模仿人类认知过程的进化呢？

