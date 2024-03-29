# Instruction Tuning Datasets
All available datasets for Instruction Tuning of Large Language Models

### Gold standard datasets 
- P3: https://github.com/bigscience-workshop/promptsource, https://huggingface.co/datasets/bigscience/P3
  - Collection of prompted English datasets covering a diverse set of NLP tasks
  - 2000 prompt types over 270 datasets
- xP3: https://huggingface.co/datasets/bigscience/xP3mt
  - Mixture of 13 training tasks in 46 languages with prompts in 20 languages (machine-translated from English)
- Natural Instructions v2: https://github.com/allenai/natural-instructions
  - A benchmark of 1,616 diverse NLP tasks and their expert-written instructions, covering 76 distinct task types and 55 different languages.
- The Flan Collection: https://github.com/google-research/FLAN/tree/main/flan/v2 
  - superset of some of the datasets here
  -  1836 Tasks, 15m examples 
- Open Assistant: https://huggingface.co/datasets/OpenAssistant/oasst1
  - Human-annotated assistant-style conversation corpus consisting of 161,443 messages distributed across 66,497 conversation trees, in 35 different languages, annotated with 461,292 quality ratings
- LIMA: 1K high-quality instructions
  - https://huggingface.co/datasets/GAIR/lima
- databricks-dolly-15k: https://github.com/databrickslabs/dolly/tree/master/data
- PRESTO: https://github.com/google-research-datasets/presto
  - 550K contextual multilingual conversations between humans and virtual assistants
- BB3x: https://parl.ai/projects/bb3x/
- InstructCTG: https://github.com/MichaelZhouwang/InstructCTG
  - Framework for controlled generation https://arxiv.org/abs/2304.14293
- CrossFit: https://github.com/INK-USC/CrossFit
- tasksource: https://arxiv.org/abs/2301.05948
- ExMix: https://arxiv.org/abs/2111.10952
- InstructEval: https://github.com/declare-lab/instruct-eval
- M3IT: https://huggingface.co/datasets/MMInstruction/M3IT
  - https://arxiv.org/abs/2306.04387
  - 2.4M multi-modal instances and 400 instructions across 40 tasks and 80 languages
- MIMIC-IT: Multi-Modal In-Context Instruction Tuning : https://arxiv.org/abs/2306.05425
- MultiInstruct: https://github.com/VT-NLP/MultiInstruct
- COLLIE: https://github.com/princeton-nlp/Collie
- Mind2Web: Towards a Generalist Agent for the Web https://osu-nlp-group.github.io/Mind2Web/    
- Android in the Wild: A Large-Scale Dataset for Android Device Control: https://github.com/google-research/google-research/tree/master/android_in_the_wild
- FLASK: Fine-grained Language Model Evaluation Based on Alignment Skill Sets https://github.com/kaistAI/FLASK
- Safe-RLHF: https://arxiv.org/abs/2310.12773
  - https://arxiv.org/pdf/2310.12773.pdf#https%3A//github.com/PKU-Alignment/safe-rlhf
- HelpSteer: https://huggingface.co/datasets/nvidia/HelpSteer 


### Silver standard/Generated using LM

- Self-Instruct: https://github.com/yizhongw/self-instruct
- Unnatural Instructions: https://github.com/orhonovich/unnatural-instructions
- Alpaca: https://huggingface.co/datasets/tatsu-lab/alpaca
  - Alpaca-Clean: https://github.com/gururise/AlpacaDataCleaned
- Code Alpaca: https://github.com/sahil280114/codealpaca
- AlpacaGPT3.5Customized: https://huggingface.co/datasets/whitefox44/AlpacaGPT3.5Customized
- GPT4All: https://github.com/nomic-ai/gpt4all
  - GPT4All-pruned: https://huggingface.co/datasets/Nebulous/gpt4all_pruned
- ShareGPT: https://huggingface.co/datasets/RyokoAI/ShareGPT52K
- GPTeacher: https://github.com/teknium1/GPTeacher
- CAMEL🐪: https://www.camel-ai.org/
- Human ChatGPT Comparison Corpus: https://github.com/Hello-SimpleAI/chatgpt-comparison-detection
- InstructionWild: https://github.com/XueFuzhao/InstructionWild
- Instruction Tuning with GPT-4: https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM
- Guanaco: https://huggingface.co/datasets/JosephusCheung/GuanacoDataset
- The LongForm Dataset: https://github.com/akoksal/LongForm/tree/main/dataset
  - LLM instruction generation for a diverse set of corpus samples (27,739 instructions and long text pairs)
- UltraChat: https://huggingface.co/datasets/stingning/ultrachat
- LLaVA Visual Instruct 150K: https://huggingface.co/datasets/liuhaotian/LLaVA-Instruct-150K
  - GPT-generated multimodal instruction-following data
- GPT4Tools: https://github.com/StevenGrove/GPT4Tools
  - Instruction data to make API calls to several multi-modal models
- LaMini-Instruction: https://huggingface.co/datasets/MBZUAI/LaMini-instruction
  - 2.58M pairs of instructions and responses
- Evol-Instruct 70k: https://github.com/nlpxucan/WizardLM
- Dynosaur: https://dynosaur-it.github.io/
- Alpaca-Farm: https://github.com/tatsu-lab/alpaca_farm
  - https://huggingface.co/datasets/tatsu-lab/alpaca_farm
- ign_clean_instruct_dataset_500k: https://huggingface.co/datasets/ignmilton/ign_clean_instruct_dataset_500k
- airoboros: https://github.com/jondurbin/airoboros
- UltraFeedback: https://huggingface.co/datasets/openbmb/UltraFeedback
- WildChat: Corpus of 570K real-world user-ChatGPT interactions https://wildchat.allen.ai/
- Feedback Collection: https://arxiv.org/abs/2310.08491
  - https://huggingface.co/datasets/kaist-ai/Feedback-Collection

### Preference Datasets (can be used to train the reward model)
- HH-RLHF: https://huggingface.co/datasets/Anthropic/hh-rlhf
  - Contains human ratings of harmfulness and helpfulness of model outputs. The dataset contains ~160K human-rated examples, where each example in this dataset consists of a pair of responses from a chatbot, one of which is preferred by humans.
- OpenAI WebGPT: https://huggingface.co/datasets/openai/webgpt_comparisons
  - Includes a total of around 20K comparisons where each example comprises a question, a pair of model answers, and metadata. The answers are rated by humans with a preference score.
- OpenAI Summarization: https://huggingface.co/datasets/openai/summarize_from_feedback
  - Contains ~93K examples, each example consists of feedback from humans regarding the summarizations generated by a model. Human evaluators chose the superior summary from two options.
- Stanford Human Preferences Dataset (SHP): https://huggingface.co/datasets/stanfordnlp/SHP
  - 385K collective human preferences over responses to questions/instructions in 18 different subject areas
- Stack Exchange Preferences: https://huggingface.co/datasets/HuggingFaceH4/stack-exchange-preferences
- SLF5K: https://huggingface.co/datasets/JeremyAlain/SLF5K
- qa-from-hf: https://github.com/lil-lab/qa-from-hf
- Nectar: https://huggingface.co/datasets/berkeley-nest/Nectar
- JudgeLM-100K: https://huggingface.co/datasets/BAAI/JudgeLM-100K
- UltraFeedback: https://huggingface.co/datasets/openbmb/UltraFeedback
- 

### Misc
- OIG: https://huggingface.co/datasets/laion/OIG
  - Superset of some of the datasets here
- oa_leet10k: https://huggingface.co/datasets/ehartford/oa_leet10k
  - LeetCode problems solved in multiple programming languages
- ProSocial Dialog: https://huggingface.co/datasets/allenai/prosocial-dialog
- ConvoKit: https://convokit.cornell.edu/documentation/datasets.html
- CoT-Collection: https://github.com/kaist-lklab/CoT-Collection
- DialogStudio: https://github.com/salesforce/DialogStudio
- Chatbot Arena Conversations https://huggingface.co/datasets/lmsys/chatbot_arena_conversations
- lmsys 1M: https://huggingface.co/datasets/lmsys/lmsys-chat-1m
- Conversation Chronicles: https://conversation-chronicles.github.io/
