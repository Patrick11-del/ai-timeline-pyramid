# AI Insights: The Timeline Pyramid

**PY-SECTION 2 · Research, design, content, and presentation pack**

## Project introduction

Artificial intelligence has developed through a long sequence of philosophical questions, mathematical ideas, symbolic programs, statistical learning methods, and increasingly capable generative systems. This pyramid places the broad intellectual and scientific foundations at its base and moves upward through increasingly specialised methods toward modern multimodal AI, AI safety, and unresolved questions about artificial general intelligence (AGI).

## Tier 1 — Research: milestone register

The table below exceeds the required 15 milestones. It records the year, event, subfield, and a one-line significance note. The wording deliberately distinguishes a historical idea from an implemented AI system and avoids implying that AI progress was continuous or inevitable.

| # | Year | Milestone | Subfield / theme | One-line significance |
|---:|---|---|---|---|
| 1 | Before 1950 | Myths, automata & the idea of artificial life | Philosophy · Foundations | Ancient myths and automata established a long-running human fascination with artificial beings and mechanical behaviour. |
| 2 | 1943 | McCulloch–Pitts artificial neuron model | Neural Networks · Computational Neuroscience | The paper showed that simplified networks of neuron-like units could, in principle, compute logical functions. |
| 3 | 1950 | Alan Turing proposes the imitation game | Philosophy of AI · Foundations | Turing gave AI researchers a famous behavioural framing for debating machine intelligence. |
| 4 | 1955–1956 | The Dartmouth proposal names artificial intelligence | AI Field History · Foundations | The Dartmouth proposal coined “artificial intelligence”; the 1956 workshop helped establish AI as a research field. |
| 5 | 1955–1956 | Logic Theorist demonstrates machine reasoning | Symbolic AI · Automated Reasoning | One of the first AI programs showed that heuristic search could automate mathematical reasoning. |
| 6 | 1966 | ELIZA demonstrates text conversation | Natural Language Processing · Chatbots | ELIZA made computer conversation tangible and exposed the risk of mistaking fluent replies for understanding. |
| 7 | 1974–1980 | The first AI winter | AI Field History · Research Funding | The first AI winter exposed the cost of overpromising before the technology was ready. |
| 8 | 1978–1981 | Expert systems enter commercial use: R1/XCON | Symbolic AI · Expert Systems | XCON demonstrated that rule-based expert systems could solve valuable, specialised business problems at scale. |
| 9 | 1986 | Backpropagation popularises multi-layer neural-network training | Neural Networks · Machine Learning | The 1986 paper helped make multi-layer neural networks trainable and accelerated modern connectionist AI. |
| 10 | 1987–1993 | The second AI winter | AI Field History · Expert Systems | The second AI winter showed that useful demonstrations do not automatically translate into robust, economical products. |
| 11 | 1997 | Deep Blue defeats world chess champion Garry Kasparov | Game AI · Search · High-Performance Computing | Deep Blue demonstrated how specialised search and hardware could outperform a human champion in chess. |
| 12 | 2004–2007 | DARPA Grand and Urban Challenges advance autonomous driving | Robotics · Autonomous Vehicles | DARPA’s competitions turned autonomous driving into a measurable engineering challenge and built a research community. |
| 13 | 2006–2009 | The Netflix Prize accelerates recommendation research | Machine Learning · Recommender Systems | The Netflix Prize made large-scale personalisation a high-profile machine-learning challenge. |
| 14 | 2009–2010 | ImageNet creates a large-scale visual benchmark | Computer Vision · Data | ImageNet provided a large, labelled dataset and benchmark that helped accelerate computer vision research. |
| 15 | 2011 | IBM Watson wins Jeopardy! | Natural Language Processing · Question Answering | Watson made natural-language question answering a highly visible enterprise AI capability. |
| 16 | 2012 | AlexNet sparks the deep-learning breakthrough in vision | Deep Learning · Computer Vision | AlexNet made the power of GPU-trained deep convolutional networks unmistakable in computer vision. |
| 17 | 2014 | Generative Adversarial Networks (GANs) are introduced | Generative AI · Deep Learning | GANs made adversarial training a major approach to generating synthetic images and other data. |
| 18 | 2017 | The Transformer architecture is published | Deep Learning · Large Language Models | The Transformer became the core architecture behind many modern large language models. |
| 19 | 2018 | BERT advances bidirectional language understanding | Natural Language Processing · Transformers | BERT helped establish large-scale pretraining as a central method for modern NLP. |
| 20 | 2020 | GPT-3 demonstrates large-scale few-shot language learning | Large Language Models · Generative AI | GPT-3 made prompt-based, few-shot use of a large language model a widely recognised capability. |
| 21 | 2022 | ChatGPT brings conversational generative AI to the mainstream | Generative AI · Large Language Models | ChatGPT turned conversational generative AI into a mainstream public experience. |
| 22 | 2023 | GPT-4 expands multimodal model capability | Large Language Models · Multimodal AI | GPT-4 brought image-and-text input into a widely discussed large-model product. |
| 23 | 2024 | GPT-4o advances real-time multimodal interaction | Multimodal Generative AI | GPT-4o illustrated the shift from text-first assistants toward real-time multimodal interaction. |
| 24 | 2024 | Reasoning-focused language models emerge | LLMs · Reasoning Models | Reasoning-focused models made deliberate multi-step problem solving a distinct direction in LLM development. |
| 25 | 2026 | International AI Safety Report assesses the frontier | AI Safety · Evaluation · Governance | The 2026 report frames current general-purpose AI progress alongside evidence gaps, limitations, and emerging risks. |
| 26 | Future | Artificial General Intelligence (AGI) remains an open question | AGI · AI Safety · Future Research | AGI and superintelligence are open future questions, not established achievements or guaranteed outcomes. |

## Tier 2 — Design: pyramid architecture

### Layer map

| Layer | Width / position | Group | Narrative purpose |
|---|---|---|---|
| 5 · Apex | Narrowest (54%) | Present & Open Questions | Shows the current frontier, assessment of risks, and unresolved questions about AGI. |
| 4 | 76% | Generative AI & Large Language Models | Covers GANs, Transformers, pretrained language models, chat assistants, multimodal systems, and reasoning-focused models. |
| 3 | 88% | Machine Learning & Deep Learning | Shows applied learning, robotics, recommender systems, computer vision, and neural-network breakthroughs. |
| 2 | 96% | Symbolic AI & Early Systems | Covers early conversational software, expert systems, neural-network training, and the two AI winters. |
| 1 · Base | Widest (100%) | Foundations | Holds ancient ideas, early mathematical models, the Turing Test, Dartmouth, and Logic Theorist. |

### Wireframe / mockup

```text
                 /------------------------\
                /  5 · PRESENT / FUTURE     \
               /----------------------------\
              /  4 · GENERATIVE AI & LLMs     \
             /--------------------------------\
            /   3 · MACHINE LEARNING & DEEP     \
           /------------------------------------\
          /    2 · SYMBOLIC AI & EARLY SYSTEMS    \
         /----------------------------------------\
        /             1 · FOUNDATIONS               \
       /--------------------------------------------\

Each band contains clickable event cards: [YEAR] [MILESTONE] [SUBFIELD].
Click → detail panel: What happened | Why it matters | Impact | Sources.
```

### Tooling choice

**Platform:** self-contained HTML5 page using CSS and vanilla JavaScript. This was chosen because the brief explicitly allows a simple HTML page; it supports click-to-open milestone details, responsive layout, search, layer filters, source links, and printing without requiring an account or external JavaScript library. The finished page works offline once downloaded.

### Interaction and colour plan

- Each milestone is a button with a visible year, title, and subfield.
- Clicking a button opens a detail panel containing all four required content parts and source links.
- Search and layer filters let visitors narrow the milestones.
- The legend uses consistent colours for foundations, symbolic AI, NLP, neural networks / machine learning, vision / robotics, generative AI, LLMs, and the AI frontier.
- A compact research register provides the 26 milestone rows in a scan-friendly format.

## Tier 3 — Content creation: explanatory notes

Every milestone uses the required four-part structure. “Subfield” is shown as a dedicated field in each note; “Impact” describes an industry or everyday-life connection without claiming that one event alone caused a modern product.

### 1. Before 1950 — Myths, automata & the idea of artificial life

**What happened:** Ancient stories describe artificial beings such as Talos, the bronze guardian of Crete, while engineers in the ancient Mediterranean built mechanical automata powered by water, air, or mechanisms. These were cultural and mechanical precursors—not modern AI systems.

**Why it matters:** They show that the question of whether human-like behaviour can be created artificially is much older than computer science. The distinction between imagined intelligent beings and engineered automata also helps us separate cultural ideas from technical achievements.

**Subfield:** Philosophy · Foundations

**Impact:** There was no modern AI industry at this stage. The ideas influenced philosophy, storytelling, and later science fiction, shaping how people imagine robots, assistants, and autonomous machines.

**Sources:** [Oxford Research Encyclopedia: Robots and cyborgs in antiquity (2023)](https://academic.oup.com/edited-volume/61673/chapter-abstract/550526398); [MIT Press Reader: The ancient history of intelligent machines](https://thereader.mitpress.mit.edu/the-ancient-history-of-intelligent-machines/)

### 2. 1943 — McCulloch–Pitts artificial neuron model

**What happened:** Warren McCulloch and Walter Pitts published a mathematical account of simplified neuron-like units whose activity could be described using propositional logic. Their model showed how networks of simple units could perform logical computations.

**Why it matters:** It provided an early theoretical bridge between biological nervous systems, logic, and computation. Later neural-network research developed far beyond this simple model, but the paper became one of the foundations of connectionism.

**Subfield:** Neural Networks · Computational Neuroscience

**Impact:** The work did not create a commercial product immediately. Its ideas helped establish the research foundations behind neural networks, which later became important in speech recognition, image analysis, forecasting, and generative AI.

**Sources:** [McCulloch & Pitts (1943), A logical calculus of the ideas immanent in nervous activity](https://doi.org/10.1007/BF02478259)

### 3. 1950 — Alan Turing proposes the imitation game

**What happened:** In his paper “Computing Machinery and Intelligence,” Alan Turing discussed whether machines could think and proposed the imitation game, later commonly called the Turing Test. A judge communicates through text and assesses whether a machine can imitate a human convincingly.

**Why it matters:** Turing shifted discussion away from trying to define thought directly and toward observable machine behaviour. The paper became a landmark in debates about intelligence, evaluation, and human–computer interaction.

**Subfield:** Philosophy of AI · Foundations

**Impact:** The test did not become a complete measure of intelligence, but it influenced chatbot evaluation, conversational interface design, and public discussion about what it means for a computer to appear intelligent.

**Sources:** [A. M. Turing (1950), Computing Machinery and Intelligence, Mind](https://academic.oup.com/mind/article/LIX/236/433/986238)

### 4. 1955–1956 — The Dartmouth proposal names artificial intelligence

**What happened:** John McCarthy, Marvin Minsky, Nathaniel Rochester, and Claude Shannon submitted a 1955 proposal for a Dartmouth summer research project on artificial intelligence. The 1956 workshop brought researchers together to explore whether aspects of learning and intelligence could be described precisely enough for machines to simulate them.

**Why it matters:** The proposal coined the term “artificial intelligence,” and the workshop is widely treated as the formal starting point of AI as a named research field. It helped create a shared agenda for symbolic reasoning, learning, language, and problem-solving.

**Subfield:** AI Field History · Foundations

**Impact:** The field developed into university laboratories, research programmes, and eventually commercial AI industries. Its subfields now support search, recommendation, translation, robotics, and generative tools used in everyday work.

**Sources:** [Dartmouth: The founding and future of AI](https://ai.dartmouth.edu/our-story)

### 5. 1955–1956 — Logic Theorist demonstrates machine reasoning

**What happened:** Allen Newell, Herbert A. Simon, and J. C. Shaw developed the Logic Theorist, an early program designed to prove theorems in symbolic logic. It proved 38 of the first 52 theorems in a section of Principia Mathematica and found a shorter proof for one theorem.

**Why it matters:** It showed that a computer could perform a task associated with high-level human reasoning. Its use of heuristics—rules that guide a search toward promising possibilities—became influential in early symbolic AI.

**Subfield:** Symbolic AI · Automated Reasoning

**Impact:** Automated reasoning later informed theorem proving, planning, configuration, and verification tools used in research and specialised engineering. The Logic Theorist itself was a research demonstration, not a mass-market product.

**Sources:** [Johns Hopkins University: Introduction to AI lecture, Logic Theorist](https://www.cs.jhu.edu/~phi/ai/slides/lecture-introduction.pdf)

### 6. 1966 — ELIZA demonstrates text conversation

**What happened:** Joseph Weizenbaum published ELIZA, a program that used keyword detection and scripted transformations to respond to typed sentences. Its best-known DOCTOR script imitated a Rogerian psychotherapist, even though ELIZA did not understand language as people do.

**Why it matters:** ELIZA demonstrated both the appeal and limitations of conversational software. It also became an early example of the “ELIZA effect,” in which people attribute more understanding to a computer than its methods justify.

**Subfield:** Natural Language Processing · Chatbots

**Impact:** It helped inspire later conversational interfaces and chatbot research. Today, the same lesson matters in customer service, education, and personal assistants: a fluent conversation can feel human without proving that a system truly understands.

**Sources:** [Joseph Weizenbaum (1966), ELIZA, Communications of the ACM](https://doi.org/10.1145/365153.365168)

### 7. 1974–1980 — The first AI winter

**What happened:** During the first AI winter, research funding and enthusiasm declined as ambitious promises about machine intelligence outpaced what available computers and methods could deliver. The Lighthill Report in the UK and funding reductions in the United States contributed to the downturn.

**Why it matters:** The period showed that progress in AI is not a straight line. It encouraged more careful claims, narrower goals, and attention to the limits of computation and problem complexity.

**Subfield:** AI Field History · Research Funding

**Impact:** Some research programmes lost support, and companies became more cautious about AI claims. The setbacks also helped the field reassess priorities while research continued in areas such as expert systems and neural networks.

**Sources:** [Actuaries Institute: History of AI winters](https://www.actuaries.asn.au/research-analysis/history-of-ai-winters)

### 8. 1978–1981 — Expert systems enter commercial use: R1/XCON

**What happened:** Digital Equipment Corporation worked with researcher John McDermott on R1, later known as XCON, an expert system for configuring VAX computer orders. It went into operation in 1981 and applied thousands of production rules to select compatible system components.

**Why it matters:** XCON became a prominent commercial example of knowledge-based AI delivering measurable business value. It showed that specialist knowledge could be encoded into rules to support repeatable decisions.

**Subfield:** Symbolic AI · Expert Systems

**Impact:** The system was reported to save DEC about US$25 million annually at its peak. Expert systems were used in configuration, diagnostics, finance, and industrial decision support, although they could be expensive to update and maintain.

**Sources:** [TIME (1988): Technology—Putting Knowledge to Work](https://content.time.com/time/subscriber/article/0,33009,967102-4,00.html); [Middlesex University: Configuration with R1/XCON](https://www.cwa.mdx.ac.uk/bis2040/lect6ES2/xCon.html)

### 9. 1986 — Backpropagation popularises multi-layer neural-network training

**What happened:** David Rumelhart, Geoffrey Hinton, and Ronald Williams published influential work showing how backpropagation could train networks of neuron-like units by adjusting connection weights to reduce output errors. The method had earlier roots, so 1986 is a landmark in its renewed demonstration and influence—not its first-ever invention.

**Why it matters:** Backpropagation made it practical to train multi-layer neural networks to learn internal representations from examples. This was an essential ingredient in the later deep-learning era.

**Subfield:** Neural Networks · Machine Learning

**Impact:** The method underpins many systems used for image recognition, speech processing, machine translation, prediction, and generative models. These applications now appear in phones, cloud services, manufacturing, and healthcare research.

**Sources:** [Rumelhart, Hinton & Williams (1986), Nature: Learning representations by back-propagating errors](https://www.nature.com/articles/323533a0)

### 10. 1987–1993 — The second AI winter

**What happened:** A second downturn followed the collapse of parts of the expert-systems market and disappointment with specialised AI hardware and systems. Funding, investment, and confidence weakened from the late 1980s into the early 1990s.

**Why it matters:** The downturn highlighted the maintenance burden of rule-based systems and the difficulty of scaling narrowly encoded knowledge to changing real-world settings.

**Subfield:** AI Field History · Expert Systems

**Impact:** Businesses became more cautious about AI deployments, while researchers pursued statistical machine learning and other approaches that later benefited from more data and computing power.

**Sources:** [Actuaries Institute: History of AI winters](https://www.actuaries.asn.au/research-analysis/history-of-ai-winters)

### 11. 1997 — Deep Blue defeats world chess champion Garry Kasparov

**What happened:** IBM’s Deep Blue defeated Garry Kasparov in a six-game match under standard tournament conditions in May 1997. Its chess strength relied heavily on fast search, evaluation functions, specialised chess chips, and parallel computing.

**Why it matters:** The match became a public milestone for computer performance in a complex intellectual game. It also illustrates that a system can outperform people in a narrow domain without possessing general human intelligence.

**Subfield:** Game AI · Search · High-Performance Computing

**Impact:** The achievement raised public awareness of AI and showcased specialised high-performance computing. Search and optimisation techniques are also relevant to scheduling, logistics, and other decision problems.

**Sources:** [IBM: Deep Blue](https://www.ibm.com/history/deep-blue)

### 12. 2004–2007 — DARPA Grand and Urban Challenges advance autonomous driving

**What happened:** DARPA’s 2004 and 2005 Grand Challenges tested driverless vehicles on difficult desert routes; the 2007 Urban Challenge required vehicles to handle traffic, intersections, merging, and parking in a mock urban environment. The 2004 event had no course finisher; five vehicles completed the 2005 course and six completed the 2007 event.

**Why it matters:** The competitions accelerated research in sensing, mapping, localisation, planning, and vehicle control by setting difficult real-world goals and encouraging teams to combine disciplines.

**Subfield:** Robotics · Autonomous Vehicles

**Impact:** The work influenced autonomous-vehicle research and robotics for transport, logistics, agriculture, mining, and hazardous environments. Commercial self-driving deployment remains much harder than completing a controlled challenge.

**Sources:** [DARPA: Grand Challenge](https://www.darpa.mil/about/innovation-timeline/grand-challenge); [DARPA: Urban Challenge](https://www.darpa.mil/about/innovation-timeline/darpa-urban-challenge)

### 13. 2006–2009 — The Netflix Prize accelerates recommendation research

**What happened:** Netflix launched a US$1 million competition in October 2006 to improve its movie-rating prediction system by at least 10%. In September 2009, the prize was awarded to BellKor’s Pragmatic Chaos after a multi-year competition involving researchers around the world.

**Why it matters:** The challenge made recommender systems a visible applied machine-learning problem and encouraged collaboration on matrix factorisation, ensembles, and evaluation methods.

**Subfield:** Machine Learning · Recommender Systems

**Impact:** Recommendation algorithms shape what people discover on streaming platforms, shopping sites, music services, and social feeds. The competition also raised questions about privacy when large preference datasets are shared for research.

**Sources:** [Associated Press / Los Angeles Times (2006): Netflix offers $1 million prize](https://www.latimes.com/archives/la-xpm-2006-oct-03-fi-netflix3-story.html); [UC San Diego: Netflix awards the $1 million Netflix Prize (2009)](https://jacobsschool.ucsd.edu/news/release/888?id=888)

### 14. 2009–2010 — ImageNet creates a large-scale visual benchmark

**What happened:** Jia Deng, Wei Dong, Richard Socher, Li-Jia Li, Kai Li, and Li Fei-Fei introduced ImageNet in a 2009 research paper. The ImageNet Large Scale Visual Recognition Challenge began in 2010, giving researchers a shared benchmark for large-scale image classification and object recognition.

**Why it matters:** Large labelled datasets and shared competitions made it easier to compare methods and train models at scale. ImageNet became a crucial benchmark in the deep-learning breakthrough that followed.

**Subfield:** Computer Vision · Data

**Impact:** Computer vision now supports photo search, product cataloguing, quality inspection, medical-image research, and driver-assistance systems. These uses depend on careful data curation and evaluation, not just model size.

**Sources:** [Deng et al. (2009), CVPR: ImageNet: A large-scale hierarchical image database](https://ieeexplore.ieee.org/abstract/document/5206848/); [ImageNet: Large Scale Visual Recognition Challenge 2010](https://www.image-net.org/challenges/LSVRC/2010/)

### 15. 2011 — IBM Watson wins Jeopardy!

**What happened:** IBM Watson defeated Jeopardy! champions Ken Jennings and Brad Rutter in a televised contest in February 2011. Its DeepQA system combined natural-language processing, information retrieval, evidence scoring, and confidence estimation.

**Why it matters:** The result demonstrated that computer systems could process complex natural-language clues and retrieve likely answers under time pressure. It also showed that question answering required more than keyword matching.

**Subfield:** Natural Language Processing · Question Answering

**Impact:** Watson prompted enterprise interest in language-based decision support, including research and pilots in healthcare and customer service. It helped popularise the idea of computers assisting people with large information collections.

**Sources:** [IBM: Watson, Jeopardy! champion](https://www.ibm.com/history/watson-jeopardy)

### 16. 2012 — AlexNet sparks the deep-learning breakthrough in vision

**What happened:** Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton trained a deep convolutional neural network on ImageNet using an efficient GPU implementation. Their 2012 paper reported a substantial improvement over previous image-classification results.

**Why it matters:** AlexNet showed how large labelled datasets, deep neural networks, and GPU computing could combine to produce a major performance gain. It helped trigger wider adoption of deep learning across AI research.

**Subfield:** Deep Learning · Computer Vision

**Impact:** Deep-learning vision systems became useful in photo organisation, industrial inspection, medical imaging research, retail analytics, and driver-assistance technologies. Deployment still requires testing for bias, reliability, and safety.

**Sources:** [Krizhevsky, Sutskever & Hinton (2012), NeurIPS: ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)

### 17. 2014 — Generative Adversarial Networks (GANs) are introduced

**What happened:** Ian Goodfellow and co-authors introduced Generative Adversarial Networks. A generator creates synthetic samples while a discriminator tries to distinguish generated samples from real examples; training pits the two networks against one another.

**Why it matters:** GANs established a powerful framework for learning to generate data rather than only classify or predict labels. They expanded research into realistic image synthesis and other generative tasks.

**Subfield:** Generative AI · Deep Learning

**Impact:** GAN-based methods have been explored for image editing, creative production, simulation, and data augmentation. They also contributed to risks such as deepfakes and misleading synthetic media.

**Sources:** [Goodfellow et al. (2014), NeurIPS: Generative Adversarial Nets](https://proceedings.neurips.cc/paper/2014/hash/f033ed80deb0234979a61f95710dbe25-Abstract.html)

### 18. 2017 — The Transformer architecture is published

**What happened:** The paper “Attention Is All You Need” introduced the Transformer, an architecture based on attention mechanisms rather than recurrent or convolutional sequence processing. It was designed to improve quality and parallelisation in machine translation.

**Why it matters:** Transformers made it easier to train large models on sequences and to capture relationships between tokens across context. The architecture became the basis for many later language and multimodal models.

**Subfield:** Deep Learning · Large Language Models

**Impact:** Transformer-based systems power translation, search, summarisation, coding assistants, document analysis, and conversational tools used in education and workplaces.

**Sources:** [Vaswani et al. (2017): Attention Is All You Need](https://arxiv.org/abs/1706.03762)

### 19. 2018 — BERT advances bidirectional language understanding

**What happened:** Researchers introduced BERT (Bidirectional Encoder Representations from Transformers), a model pretrained to build deep bidirectional representations from unlabelled text. It could then be fine-tuned for tasks such as question answering and language inference.

**Why it matters:** BERT showed how pretraining on large text collections could produce reusable language representations that adapt to many tasks with relatively little task-specific architecture.

**Subfield:** Natural Language Processing · Transformers

**Impact:** Transformer-based language understanding improved search relevance, document classification, question answering, and text analysis. These capabilities affect how people find information online and how organisations process documents.

**Sources:** [Devlin et al. (2018): BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://aclanthology.org/N19-1423/)

### 20. 2020 — GPT-3 demonstrates large-scale few-shot language learning

**What happened:** OpenAI researchers presented GPT-3, an autoregressive language model with 175 billion parameters. The paper showed that scaling the model improved few-shot performance on tasks such as translation, question answering, and text generation, while also documenting limitations.

**Why it matters:** GPT-3 helped demonstrate the broad task flexibility of large language models: users could specify tasks in natural language or provide examples instead of training a separate model for every task.

**Subfield:** Large Language Models · Generative AI

**Impact:** Large language models enabled new products and workflows for drafting, summarising, coding, classification, and customer support. They also made factual errors, bias, and data provenance important practical concerns.

**Sources:** [Brown et al. (2020): Language Models are Few-Shot Learners](https://openai.com/index/language-models-are-few-shot-learners/)

### 21. 2022 — ChatGPT brings conversational generative AI to the mainstream

**What happened:** OpenAI introduced ChatGPT on 30 November 2022 as a research preview. The dialogue format was designed to answer follow-up questions, acknowledge mistakes, and respond to user instructions; the system was trained using methods including reinforcement learning from human feedback.

**Why it matters:** ChatGPT made interaction with a general-purpose language model simple for a very large public audience. It moved generative AI from a specialist topic into everyday discussion and experimentation.

**Subfield:** Generative AI · Large Language Models

**Impact:** People began using conversational AI for study support, brainstorming, drafting, translation, coding assistance, and customer-service experiments. Its mistakes and confident fabrications also highlighted the need for human review.

**Sources:** [OpenAI (30 November 2022): Introducing ChatGPT](https://openai.com/index/chatgpt/)

### 22. 2023 — GPT-4 expands multimodal model capability

**What happened:** OpenAI announced GPT-4 in March 2023, describing it as a large multimodal model that accepts image and text inputs and generates text. The announcement also emphasised that the system remained imperfect and could make factual mistakes.

**Why it matters:** GPT-4 represented a step beyond text-only interaction and demonstrated stronger performance across a range of professional and academic benchmarks, while reinforcing the importance of evaluation and alignment.

**Subfield:** Large Language Models · Multimodal AI

**Impact:** Multimodal assistants can help users interpret diagrams, documents, screenshots, and visual information. In work settings, they support analysis and accessibility, but outputs still need verification.

**Sources:** [OpenAI (14 March 2023): GPT-4](https://openai.com/index/gpt-4-research/)

### 23. 2024 — GPT-4o advances real-time multimodal interaction

**What happened:** OpenAI announced GPT-4o in May 2024. The model was designed to reason across audio, vision, and text in real time, accepting combinations of modalities and generating text, audio, and image outputs.

**Why it matters:** The announcement highlighted a move toward more natural human–computer interaction in which people can speak, show, and type rather than relying on text prompts alone.

**Subfield:** Multimodal Generative AI

**Impact:** Real-time multimodal tools can support language practice, accessibility, live assistance, visual troubleshooting, and more natural interfaces. They also raise privacy, consent, and reliability questions when systems interpret audio or imagery.

**Sources:** [OpenAI (13 May 2024): Hello GPT-4o](https://openai.com/index/hello-gpt-4o/)

### 24. 2024 — Reasoning-focused language models emerge

**What happened:** In September 2024, OpenAI introduced o1-preview, a model series trained to spend more time reasoning before responding. The company described improvements on challenging mathematics, coding, and scientific tasks.

**Why it matters:** This marked a visible shift toward post-training and inference-time methods intended to improve multi-step problem solving, not only fluent text generation or larger pretraining datasets.

**Subfield:** LLMs · Reasoning Models

**Impact:** Reasoning-focused models can assist with software development, analytical work, and scientific problem solving. Their answers still require evaluation because high benchmark scores do not guarantee dependable real-world performance.

**Sources:** [OpenAI (12 September 2024): Learning to reason with LLMs / o1](https://openai.com/index/learning-to-reason-with-llms/)

### 25. 2026 — International AI Safety Report assesses the frontier

**What happened:** The 2026 International AI Safety Report examines general-purpose AI capabilities and emerging risks. It describes systems that can handle a wide range of tasks, while also noting limitations such as unreliable outputs, uneven performance, and difficulty completing complex real-world work.

**Why it matters:** As AI systems become more capable and widely deployed, independent assessment is needed to track evidence, uncertainties, and risk-management gaps. The report provides a shared reference point rather than a prediction that any single future outcome is inevitable.

**Subfield:** AI Safety · Evaluation · Governance

**Impact:** The findings matter to governments, businesses, educators, developers, and the public because they inform decisions about evaluation, safeguards, cybersecurity, fairness, privacy, and responsible deployment.

**Sources:** [International AI Safety Report 2026](https://internationalaisafetyreport.org/publication/2026-report-executive-summary)

### 26. Future — Artificial General Intelligence (AGI) remains an open question

**What happened:** Artificial General Intelligence is commonly used for a hypothetical AI system that can perform most or almost all cognitive tasks at a level comparable to or beyond humans. There is no universally agreed definition or test, and superintelligence describes a still more speculative possibility.

**Why it matters:** The goal raises foundational questions about capability, autonomy, reliability, alignment with human values, accountability, and control. It is important to distinguish a future research objective from capabilities demonstrated by current systems.

**Subfield:** AGI · AI Safety · Future Research

**Impact:** If systems with broadly general capabilities are developed, they could affect many industries and everyday activities. The timing, form, benefits, and risks are uncertain, so safety research, governance, and public deliberation remain essential.

**Sources:** [International AI Safety Report 2026](https://internationalaisafetyreport.org/publication/2026-report-executive-summary)

## Tier 4 — Presentation: how to use and share the artifact

1. Open `index.html` in Chrome, Firefox, Edge, or another modern browser. No internet connection is required for the pyramid, filters, search, or detail panels. Internet access is only needed to open linked source references.

2. Click every milestone card to review its detail panel. Use Previous / Next to move through visible results; Esc or the close button closes the panel.

3. Test search and each layer filter. Confirm that the research register updates to match the visible results.

4. Use Print / Save as PDF for a non-interactive handout. Share `index.html` for the interactive experience, or share the complete ZIP pack when you want the guide and wireframe included.

5. Before submission, add squad member names and replace the role descriptions with accurate reflections of each member’s actual contribution. A hosted public URL still requires uploading the HTML file to a hosting service; this pack itself is a ready-to-share offline artifact, not a published website.


### Acceptance-criteria check

| Requirement | Status in this pack |
|---|---|
| At least 15 significant AI milestones | **Met** — 26 milestones. |
| Historical background and major advances | **Met** — foundations, symbolic AI, machine learning, deep learning, generative AI, LLMs, multimodal systems, and future questions. |
| Impact on industries and everyday life stated for every event | **Met** — each detail panel includes an Impact section. |
| User-friendly, interactive, visually engaging timeline | **Met** — responsive five-layer pyramid, search, filters, and clickable cards. |
| Each event clickable with explanatory notes | **Met** — every card opens a detailed panel. |
| Legend explaining layers and subfield colour-coding | **Met** — layer labels and a colour legend are included. |
| Title and one-paragraph introduction | **Met** — included at the top of the page. |
| Shareable digital file | **Met** — self-contained `index.html`; ZIP includes supporting materials. |
| Squad member reflection | **Template included** — add real names and actual contributions before submission. |

## Squad reflection template

Use one short paragraph per squad member. Example structure: “**[Name] — [Role]:** I contributed by [specific task completed]. My work supported the project by [how it helped the research, design, content, or presentation]. One challenge I addressed was [challenge] and I handled it by [action].”

**Important:** The role cards in the HTML are suggested contribution summaries, not claims about your actual squad. Replace them with your true member names and work.

## Sources and references

- [Oxford Research Encyclopedia: Robots and cyborgs in antiquity (2023)](https://academic.oup.com/edited-volume/61673/chapter-abstract/550526398)
- [MIT Press Reader: The ancient history of intelligent machines](https://thereader.mitpress.mit.edu/the-ancient-history-of-intelligent-machines/)
- [McCulloch & Pitts (1943), A logical calculus of the ideas immanent in nervous activity](https://doi.org/10.1007/BF02478259)
- [A. M. Turing (1950), Computing Machinery and Intelligence, Mind](https://academic.oup.com/mind/article/LIX/236/433/986238)
- [Dartmouth: The founding and future of AI](https://ai.dartmouth.edu/our-story)
- [Johns Hopkins University: Introduction to AI lecture, Logic Theorist](https://www.cs.jhu.edu/~phi/ai/slides/lecture-introduction.pdf)
- [Joseph Weizenbaum (1966), ELIZA, Communications of the ACM](https://doi.org/10.1145/365153.365168)
- [Actuaries Institute: History of AI winters](https://www.actuaries.asn.au/research-analysis/history-of-ai-winters)
- [TIME (1988): Technology—Putting Knowledge to Work](https://content.time.com/time/subscriber/article/0,33009,967102-4,00.html)
- [Middlesex University: Configuration with R1/XCON](https://www.cwa.mdx.ac.uk/bis2040/lect6ES2/xCon.html)
- [Rumelhart, Hinton & Williams (1986), Nature: Learning representations by back-propagating errors](https://www.nature.com/articles/323533a0)
- [IBM: Deep Blue](https://www.ibm.com/history/deep-blue)
- [DARPA: Grand Challenge](https://www.darpa.mil/about/innovation-timeline/grand-challenge)
- [DARPA: Urban Challenge](https://www.darpa.mil/about/innovation-timeline/darpa-urban-challenge)
- [Associated Press / Los Angeles Times (2006): Netflix offers $1 million prize](https://www.latimes.com/archives/la-xpm-2006-oct-03-fi-netflix3-story.html)
- [UC San Diego: Netflix awards the $1 million Netflix Prize (2009)](https://jacobsschool.ucsd.edu/news/release/888?id=888)
- [Deng et al. (2009), CVPR: ImageNet: A large-scale hierarchical image database](https://ieeexplore.ieee.org/abstract/document/5206848/)
- [ImageNet: Large Scale Visual Recognition Challenge 2010](https://www.image-net.org/challenges/LSVRC/2010/)
- [IBM: Watson, Jeopardy! champion](https://www.ibm.com/history/watson-jeopardy)
- [Krizhevsky, Sutskever & Hinton (2012), NeurIPS: ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper_files/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html)
- [Goodfellow et al. (2014), NeurIPS: Generative Adversarial Nets](https://proceedings.neurips.cc/paper/2014/hash/f033ed80deb0234979a61f95710dbe25-Abstract.html)
- [Vaswani et al. (2017): Attention Is All You Need](https://arxiv.org/abs/1706.03762)
- [Devlin et al. (2018): BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://aclanthology.org/N19-1423/)
- [Brown et al. (2020): Language Models are Few-Shot Learners](https://openai.com/index/language-models-are-few-shot-learners/)
- [OpenAI (30 November 2022): Introducing ChatGPT](https://openai.com/index/chatgpt/)
- [OpenAI (14 March 2023): GPT-4](https://openai.com/index/gpt-4-research/)
- [OpenAI (13 May 2024): Hello GPT-4o](https://openai.com/index/hello-gpt-4o/)
- [OpenAI (12 September 2024): Learning to reason with LLMs / o1](https://openai.com/index/learning-to-reason-with-llms/)
- [International AI Safety Report 2025: general-purpose AI and definitions](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2025)
- [International AI Safety Report 2026](https://internationalaisafetyreport.org/publication/2026-report-executive-summary)

---
**Research date:** 24 November 2026. Historical dates and technical claims were cross-checked against the linked papers, institutional histories, and technical reports. Some historical categories (such as the exact boundaries of AI winters) are conventional periodisations rather than universally fixed dates.
