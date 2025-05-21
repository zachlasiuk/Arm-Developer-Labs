---
title: "DRAFT - Building Better Products on Arm with the Responsible AI methodology, Yellow Teaming"

subjects:
    - ML
    - Security
    - CI-CD
    - Performance and Architecture 
---

## Description

AI products are becoming more capable by the day. But unless we think carefully about how we build AI systems, we risk amplifying harm as fast as we’re scaling performance. Even AI products that seem successful in narrow metrics like `number of users` and `engagement` can lead to a degradation of user trust in your company, reputational risk, and drive negative societal outcomes. A more systematic product development approach is necessary for this next generation of tech to ensure we get the benefits of AI without the downsides.

This project introduces "Yellow Teaming", a structured methodology for stress-testing AI products by exploring the full spectrum of consequences when products succeed, not just fail. You will Yellow Team your Arm-based product and apply the learnings to make your product better. To aid in this process, you will optionally create or leverage a YellowTeamGPT to assist with your analysis. This exercise is an excellent way for software developers, product managers, and designers to elevate their products through thoughtful design choices above a crowded competitive landscape.

Tutorials are linked below for you to build your own YellowTeamGPT using a Llama model, or using an already-ready CustomGPT through ChatGPT. Participants can also Yellow Team without an LLM by applying the methodology themselves without an LLM assistant. You can perform Yellow Teamingas part of your product design, sprint retrospectives, Git-based code reviews, and beyond.

**Key Objectives of Your Project**
- Showcase Responsible AI Practices: Highlight how developers anticipate and address potential societal and ethical impacts of their AI solutions.
- Promote Arm-Based AI Development: Demonstrate the capabilities and advantages of deploying AI applications on Arm architectures, such as AWS Graviton processors or smartphones.

**Expected Output**
A PDF or similar report that details how you applied Yellow Teaming to your Arm-based project of choice. The report should include details such as:
- Tools/prompts used to facilitate analysis (did you build your own PyTorch LLama model and use that? Or the custom GPT linked below? Or manual analysis only with no LLM assistance?)
- List of identified consequences (including direct and 2nd order effects at least, spanning across short and long term consequences on users, society, and your company)
- Strategies you implemented to mitigate identified negative product impacts, and/or new net-positive features ideated (did you add new processes? Modify or add a product feature? etc.)

High-quality submissions will be evaluated on:
- If the product being Yellow Teamed runs on an Arm platform and uses AI in some way
- Depth and creativity of consequence analysis
- Thoughtfulness of mitigation strategies
- Clarity and structure of the report



## Hardware, Software and Skills Required

If deploying a private Llama model -> 
- **Hardware**:
  - Access to an Arm-based cloud instance, for example Arm-based Graviton4 processors.
- **Software**:
  - PyTorch and Hugging Face account
  - `torchchat` repo and dependencies
  - Hugging Face CLI for LLM download
  - Git, Python 3.10+, and various common build essentials (e.g., `make`, `g++`)
- **Skills**:
  - Proficiency in Python and PyTorch
  - [Hugging Face account](https://huggingface.co/)
  - Understanding of LLMs and prompting techniques

If using a public LLM ->
- **Hardware**:
  - None needed
- **Software**:
  - Access to a public LLM
- **Skills**:
  - Understanding of LLMs and prompting techniques

## Resources 

- [Mitigating Harmful Consequences course module by the Center for Humane Technology](https://www.humanetech.com/course) -- **highly reccommended reading for learning how to analyze product consequences.**
- [Development In Progress essay by the Consilience Project](https://consilienceproject.org/development-in-progress/) -- in-depth essay overviewing the need for Yellow Teaming and thoughtful design practices.
- Blog on Yellow Teaming - COMING SOON
- Custom YellowTeamGPT on ChatGPT platform - COMING SOON

### Benefits

1. Standout projects could be internally referred for relevant positions at Arm! :page_with_curl:

2. If your submission is approved, you may receive a recognised badge that you can list on your CV and shared on LinkedIn. A great way to stand out from the crowd! :mortar_board:

3. Co-promotion opportunities of your product with Arm.
  
4. Problem-Solving Experience: Opportunity to gain experience with new methodologies that make your company, product, and society better. 

6. Industry Relevance: Hands-on experience with Arm-based architectures, applicable to genomics research and cloud computing.  
