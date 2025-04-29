# Dearth of Agentic AI Experts

[Blog Index](../index.md)

Speaking at TiE Con in Mumbai, [Narayan Murthy](https://www.businesstoday.in/technology/news/story/silly-old-programs-narayana-murthy-calls-out-indias-overhyped-ai-claims-467801-2025-03-13) was quite vocal and extremently skeptic about the hype around AI in India. He told the audience that what many IT companies parade as AI are nothing but "silly old programs." Back in November 2024, after the launch of [Sarvam 1 on October 2024](https://www.sarvam.ai/about-us), [Narayan Murthy](https://timesofindia.indiatimes.com/technology/tech-news/infosys-founder-narayana-murthy-on-why-india-should-not-build-its-own-ai-models-the-indian-mindset-is-still-not/articleshow/115304666.cms) was critical of Indian IT companies attempting to jump into bandwagon of foundational research on LLM. Since LLM research is resource-intensive, both Narayan Murthy and Nandan Nilekani feel that effort to build home-grown LLM tools from scratch is an unwise decision. We still have to build large database. Without big database, a LLM tool does not make sense. 

Meanwhile, a lot of water have flowed and flooded Pakistan side on the banks of Jhelam and Chenab. Recently, Sarvam was selected to build [India's soverign LLM](https://www.msn.com/en-in/news/India/india-s-foundational-ai-model-to-support-reasoning-in-indic-languages-will-be-ready-in-six-months-sarvam-ai-s-vivek-raghavan/ar-AA1DET1z?ocid=winp2fptaskbar&cvid=60ac2b3ff0344ac7f94167aad4d5e14e&ei=26). So, we have moved beyond the question whether Indian IT companies focus on foundational research on building LLM tools. The topic of the current post is on Agentic AI which I think is going to be topic of discussion for sometime. 

I read some reports saying that India has only [half of Agentic AI experts]( https://economictimes.indiatimes.com/tech/artificial-intelligence/india-facing-shortage-of-agentic-ai-professionals-amid-surge-in-demand/articleshow/120651512.cms?from=mdr) than its requirement. The total requirement of Agentic AI experts is 200,000 as against 100,000 we have in India. The news article seems to make a big hype about agentic AI. It is, therefore, important to understand how Agentic AI is different from generative AI and the classical distributed agent-based solutions. We will specifically address the question: "Do we have to re-orient CS education syllabus to train Agentic AI experts?" 

Traditional AI is rule-based or depend on human prompts (intervention). Agentic AI can autonomously make decisions, take actions and adopt to changes in the environment. In other words, Agentic AI systems consisting of network of agents capable of reasoning, planning and executing tasks across complex workflows. Agentic AI systems are being used increasingly to automate customer services. They can reschedule deliveries, process cancellation, or recommend replacements without human interventions. They incorporate logic and reasoning under environmental constraints to adjust to new workflows. JP Morgan deployed an Agentic AI system called [COIN (COntract INtelligence)](https://www.productmonk.io/p/meet-coin-jpmorgan-s-efficiency-wizard) to read and analyze thousands of contracts identifying critical issues and ensure compliances with banking regulations.

The idea of [distributed agent-based system](https://ieeexplore.ieee.org/abstract/document/8352646) is not new. However, agent-based softwares did not have many takers due to serious concerns about security and privacy issue. Traditional agentic systems were not allowed to access resources across Autonomous Systems (AS). There are several issues in allowing software agents to migrate from one AS to another. Agentic AI systems will also encounter similar problems. Some of these are:
- Collaboration and Interoperability
- Cross border AI services
- Regulatory compliances of Data accesses
- Data sovereignity
- Scalability and resource availability
- Trust and governance
- Security and privacy

Interoperability can be solved largely through standardizations. However, it will be difficult to fully meet cross-border AI services and the regulatory compliance for data accessibility in a foreign domains. The requirement for Data Sovereignity is the key impedements to regulatory compliances.  Scalability and resource availability will remain unresolved with or without AI. Security, trust, data governance problems are closely linked to the requirement of Data Sovereignity. Therefore, if at all, Agentic AI system can be deployed under tight control of a subdomain of a home Autnomous System. It is almost impossible for network administrators to adjust to the idea of allowing foreign agents to execute workflows in their ASes not withstanding iron-clad gaurantees concerning data sovereignity and regulatory compliance. Therefore, in reality Agentic AI systems is restricted to static AI agents, and pre-scheduling their execution. The concept of pre-scheduling a program is not new (Unix cron allows it). The following three characteristics distinguishes an Agentic AI system  from a traditional distributed agent system:
- Statistical Inference (pattern recognition, predictions).
- Context awareness (dynamic, multi-source situational awareness).
- Ability to synthesize results (orchestrating components into adaptive, goal-driven workflows)

Synthesis is the unique transformative capability that distinguishes agentic AI from the classical distributed agent-based solutions. Though one may argue that theoretically the rule-based synthesis of component results from distributed agents just an additional post processing step, traditional distributed agents do not have it. However, the learning capability of an Agentic AI that is largely dependent on leveraging generative power of LLM, cannot be matched. 

The background discussion between classical distributed agent and Agentic AI system is essential to understand the additional updates to CSE curricula for trainging students with Agentic AI expertise. 

The requirement of traditional theory and research behind programming will remain relevant while expertise on AI-driven automation and agentic AI become increasingly important for job market. So, the foundational CS topics, like algorithms, data structures, operating systems, database and software architecture remain relevant as usual as mentioned in an earlier post. In another post, there was a mention about ethics in computing. Ethics issue will become more significant in dealing with deployment of Agentic AI. Therefore, I guess a course like Ethics and Governance of AI will be great addition to CSE curricula.  Since experts with Agentic AI training will demand higher compensations than ordinary CS graduates, I believe the employers will also demand greater productivity from the employees. So, increasing practice on using AI assistance in coding also assumes significance. In summary the requirements are:  

- Machine learning, deep learning, and AI ethics alongside traditional programming.
- AI-driven software development, where students learn to integrate AI models into applications.
- AI-assisted coding tools (like GitHub Copilot)
- Distributed Systems with emphasis on agent and P2P systems. 
- At one course on AI bias, fairness, and responsible AI development.

The debate on the choice of **first programming language** becomes narrower than before. There will be a requirement for increased significance in teaching AI-integrated languages such as Python, Julia, and Rust. Furthermore training in R, MATLAB, SQL, SCALA, Lisp and Prolog will also be advantageous from point of view of creating applications. However, significant shift in collaborative AI coding is essential for training Agentic AI expertise.

[Back to Index](../index.md)
