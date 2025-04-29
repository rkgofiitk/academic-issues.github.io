# Beyond Algorithms: Reimagining CS Curricula for Agentic AI


[Blog Index](../index.md)

Speaking at TiE Con in Mumbai, [Narayan Murthy](https://www.businesstoday.in/technology/news/story/silly-old-programs-narayana-murthy-calls-out-indias-overhyped-ai-claims-467801-2025-03-13) expressed significant skepticism regarding the enthusiasm surrounding AI in India.  He told the audience that what many IT companies tout as AI is simply "silly old programs." Back in November 2024, after the launch of [Sarvam 1 on October 2024](https://www.sarvam.ai/about-us), Murthy voiced [his concerns](https://timesofindia.indiatimes.com/technology/tech-news/infosys-founder-narayana-murthy-on-why-india-should-not-build-its-own-ai-models-the-indian-mindset-is-still-not/articleshow/115304666.cms) about Indian IT companies eagerly trying to engage in foundational research on large language models (LLMs).  Both Murthy and Nandan Nilekani contend that the pursuit of developing home-grown LLM tools from the ground up is misguided, given that LLM research is resource-intensive. They emphasized the need for a substantial database, noting that without one, an LLM tool would lack viability.

Meanwhile, much water has flowed and flooded Pakistan's side on the banks of Jhelum and Chenab. Recently, Sarvam was selected to build [India's sovereign LLM](https://www.msn.com/en-in/news/India/india-s-foundational-ai-model-to-support-reasoning-in-indic-languages-will-be-ready-in-six-months-sarvam-ai-s-vivek-raghavan/ar-AA1DET1z?ocid=winp2fptaskbar&cvid=60ac2b3ff0344ac7f94167aad4d5e14e&ei=26).  This indicates that we have moved past the question of whether Indian IT companies are prioritizing foundational research in the creation of LLM tools. The topic of agentic AI is set to remain a point of discussion for the foreseeable future.

I read some reports saying that India has only [half of Agentic AI experts](https://economictimes.indiatimes.com/tech/artificial-intelligence/india-facing-shortage-of-agentic-ai-professionals-amid-surge-in-demand/articleshow/120651512.cms?from=mdr) than its requirement. The total requirement of Agentic AI experts is 200,000 against the 100,000 we have in India. The news article makes a big hype about agentic AI. It is, therefore, essential to understand how Agentic AI is different from generative AI and the classical distributed agent-based solutions. We will specifically address the question: "Do we have to re-orient the CS education syllabus to train Agentic AI experts?" 

Traditional AI is rule-based or depends on human prompts (intervention). Agentic AI can autonomously make decisions, take actions, and adapt to environmental changes. In other words, Agentic AI systems consist of a network of agents capable of reasoning, planning, and executing tasks across complex workflows. Agentic AI systems are being used increasingly to automate customer services. They can reschedule deliveries, process cancellations, or recommend replacements without human intervention. They incorporate logic and reasoning under environmental constraints to adjust to new workflows. JP Morgan deployed an Agentic AI system called [COIN (COntract INtelligence)](https://www.productmonk.io/p/meet-coin-jpmorgan-s-efficiency-wizard) to read and analyze thousands of contracts identifying critical issues and ensure compliances with banking regulations.

The idea of [distributed agent-based systems](https://ieeexplore.ieee.org/abstract/document/8352646) is not new. However, agent-based software did not have many takers due to serious concerns about security and privacy. Traditional agentic systems were not allowed to access resources across Autonomous Systems (AS). Several issues exist in allowing software agents to migrate from one AS to another. Agentic AI systems will also encounter similar problems. Some of these are:
- Collaboration and Interoperability
- Cross-border AI services
- Regulatory compliances with Data access
- Data sovereignty
- Scalability and resource availability
- Trust and governance
- Security and privacy

Interoperability can primarily be addressed through standardization. However, fully achieving cross-border AI services and ensuring regulatory compliance regarding data accessibility in foreign domains presents significant challenges. Data sovereignty is a critical requirement for regulatory compliance, yet maintaining it across Autonomous Systems (ASes) can severely complicate migration, scalability, and resource availability. Furthermore, issues related to security, trust, and data governance are intricately connected to the demands of data sovereignty. 

As a solution, we can implement an Agentic AI system, which operates under the strict control of a designated subdomain within a home Autonomous System. Network administrators face considerable difficulty in permitting foreign agents to execute workflows within their ASes, as they demand robust gaurantees on data sovereignty for compliance with regulations. Consequently, Agentic AI systems are often constrained to static AI agents with pre-scheduled execution. While pre-scheduling programs is a familiar concept (as exemplified by Unix cron), an Agentic AI system can be distinguished from a conventional distributed agent system by three specific characteristics:
- **Statistical Inference** (pattern recognition, predictions).
- **Context awareness** (dynamic, multi-source situational awareness).
- **Ability to synthesize results** (orchestrating components into adaptive, goal-driven workflows)

Synthesis is the unique transformative capability that distinguishes agentic AI from the classical distributed agent-based solutions. Though one may argue that theoretically, the rule-based synthesis of component results from distributed agents is just an additional post-processing step, traditional distributed agents do not have it. However, the learning capability of an Agentic AI that is mainly dependent on leveraging the generative power of LLM cannot be matched. 

The background discussion between classical distributed agents and the Agentic AI system is essential to understanding the additional updates to CSE curricula for training students with Agentic AI expertise. 

The foundational theories and research underpinning traditional programming will continue to be relevant, even as expertise in AI-driven automation and agentic AI becomes increasingly vital in the job market. Core computer science topics, such as algorithms, data structures, operating systems, databases, and software architecture, will remain important as ever, as noted in a [previous post](./AI_components_in_CS.md). Additionally, we explored the [subject of ethics in computing in another article](ethical_computing.md). Ethical considerations are poised to gain importance, particularly in the context of deploying agentic AI, making courses like Ethics and Governance of AI essential additions to the computer science and engineering (CSE) curriculum. Given that professionals trained in agentic AI are likely to command higher salaries than their traditional computer science counterparts, employers will also expect elevated levels of productivity from their teams. Consequently, the increasing integration of AI assistance in coding practices will be key to achieving success. In summary, the key requirements are:

- Machine learning, deep learning, and AI ethics alongside traditional programming.
- AI-driven software development, where students learn to integrate AI models into applications.
- AI-assisted coding tools (like GitHub Copilot)
- Distributed Systems with emphasis on agent and P2P systems. 
- At least one course on AI bias, fairness, and responsible AI development.

The discussion surrounding the selection of a **first programming language** is becoming more focused than ever. There is a growing importance placed on teaching AI-integrated languages such as Python, Julia, and Rust. Additionally, gaining proficiency in R, MATLAB, SQL, SCALA, Lisp, and Prolog will prove beneficial for application development. However, a notable transformation in collaborative AI coding is crucial for fostering expertise in Agentic AI.

[Back to Index](../index.md)
