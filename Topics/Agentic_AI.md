# Grappling with Shortage of Agentic AI Experts

[Blog Index](../index.md)

Speaking at TiE Con in Mumbai, [Narayan Murthy](https://www.businesstoday.in/technology/news/story/silly-old-programs-narayana-murthy-calls-out-indias-overhyped-ai-claims-467801-2025-03-13) was quite vocal and extremely skeptic about the hype around AI in India.  He told the audience that what many IT companies parade as AI is nothing but "silly old programs." Back in November 2024, after the launch of [Sarvam 1 on October 2024](https://www.sarvam.ai/about-us), Murthy was [critical](https://timesofindia.indiatimes.com/technology/tech-news/infosys-founder-narayana-murthy-on-why-india-should-not-build-its-own-ai-models-the-indian-mindset-is-still-not/articleshow/115304666.cms) of Indian IT companies attempting to jump into bandwagon of foundational research on LLM.  Since LLM research is resource-intensive, both Narayan Murthy and Nandan Nilekani feel that the effort to build home-grown LLM tools from scratch is an unwise decision.  We still have to create a large database.  Without a big database, an LLM tool would not make sense. 

Meanwhile, much water has flowed and flooded Pakistan's side on the banks of Jhelum and Chenab. Recently, Sarvam was selected to build [India's sovereign LLM](https://www.msn.com/en-in/news/India/india-s-foundational-ai-model-to-support-reasoning-in-indic-languages-will-be-ready-in-six-months-sarvam-ai-s-vivek-raghavan/ar-AA1DET1z?ocid=winp2fptaskbar&cvid=60ac2b3ff0344ac7f94167aad4d5e14e&ei=26).  So, we have moved beyond the question whether Indian IT companies focus on foundational research on building LLM tools.  Agentic AI is going to be a topic of discussion for some time. 

I read some reports saying that India has only [half of Agentic AI experts](https://economictimes.indiatimes.com/tech/artificial-intelligence/india-facing-shortage-of-agentic-ai-professionals-amid-surge-in-demand/articleshow/120651512.cms?from=mdr) than its requirement.  The total requirement of Agentic AI experts is 200,000 against the 100,000 we have in India.  The news article makes a big hype about agentic AI.  It is, therefore, essential to understand how Agentic AI is different from generative AI and the classical distributed agent-based solutions.  We will specifically address the question: "Do we have to re-orient the CS education syllabus to train Agentic AI experts?" 

Traditional AI is rule-based or depends on human prompts (intervention).  Agentic AI can autonomously make decisions, take actions, and adapt to environmental changes.  In other words, Agentic AI systems consist of a network of agents capable of reasoning, planning, and executing tasks across complex workflows.  Agentic AI systems are being used increasingly to automate customer services.  They can reschedule deliveries, process cancellations, or recommend replacements without human intervention.  They incorporate logic and reasoning under environmental constraints to adjust to new workflows.  JP Morgan deployed an Agentic AI system called [COIN (COntract INtelligence)](https://www.productmonk.io/p/meet-coin-jpmorgan-s-efficiency-wizard) to read and analyze thousands of contracts identifying critical issues and ensure compliances with banking regulations.

The idea of [distributed agent-based systems](https://ieeexplore.ieee.org/abstract/document/8352646) is not new.  However, agent-based software did not have many takers due to serious concerns about security and privacy.  Traditional agentic systems were not allowed to access resources across Autonomous Systems (AS).  There are several issues in allowing software agents to migrate from one AS to another.  Agentic AI systems will also encounter similar problems.  Some of these are:
- Collaboration and Interoperability
- Cross-border AI services
- Regulatory compliances with Data access
- Data sovereignty
- Scalability and resource availability
- Trust and governance
- Security and privacy

We can solve interoperability primarily through standardizations.  However, it will be difficult to fully meet cross-border AI services and regulatory compliance for data accessibility in a foreign domain.  The requirement for data sovereignty is the key impediment to regulatory compliance.  Scalability and resource availability will remain unresolved with or without AI.  Security, trust, and data governance problems are closely linked to data sovereignty requirements.  Therefore, we can deploy an Agentic AI system under the tight control of a subdomain of a home Autonomous System.  It is almost impossible for network administrators to adjust to allowing foreign agents to execute workflows in their ASes without withstanding iron-clad guarantees concerning data sovereignty and regulatory compliance.  Therefore, Agentic AI systems are restricted to static AI agents and pre-scheduling their execution.  Pre-scheduling a program is not new (Unix cron allows it).  The following three characteristics distinguish an Agentic AI system  from a traditional distributed agent system:
- Statistical Inference (pattern recognition, predictions).
- Context awareness (dynamic, multi-source situational awareness).
- Ability to synthesize results (orchestrating components into adaptive, goal-driven workflows)

Synthesis is the unique transformative capability that distinguishes agentic AI from the classical distributed agent-based solutions.  Though one may argue that theoretically, the rule-based synthesis of component results from distributed agents is just an additional post-processing step, traditional distributed agents do not have it.  However, the learning capability of an Agentic AI that is mainly dependent on leveraging the generative power of LLM cannot be matched. 

The background discussion between classical distributed agents and the Agentic AI system is essential to understanding the additional updates to CSE curricula for training students with Agentic AI expertise. 

The requirement of traditional theory and research behind programming will remain relevant while expertise on AI-driven automation and agentic AI become increasingly crucial for the job market.  So, the foundational CS topics, like algorithms, data structures, operating systems, databases, and software architecture, remain relevant as usual, as mentioned in an earlier post.  In another post, we dealt with ethics in computing.  Ethics issues will become more significant in dealing with the deployment of Agentic AI.  Therefore, courses like Ethics and Governance of AI will significantly add to CSE curricula.  Since experts with Agentic AI training will demand higher compensation than ordinary CS graduates, employers will also demand greater productivity from the employees.  So, increasing the practice of using AI assistance in coding also assumes significance.  In summary, the requirements are:  

- Machine learning, deep learning, and AI ethics alongside traditional programming.
- AI-driven software development, where students learn to integrate AI models into applications.
- AI-assisted coding tools (like GitHub Copilot)
- Distributed Systems with emphasis on agent and P2P systems. 
- At one course on AI bias, fairness, and responsible AI development.

The debate on the choice of **first programming language** becomes narrower than before.  Increased significance will be required in teaching AI-integrated languages such as Python, Julia, and Rust.  Furthermore, training in R, MATLAB, SQL, SCALA, Lisp, and Prolog will also be advantageous for creating applications.  However, a significant shift in collaborative AI coding is essential for training Agentic AI expertise.

[Back to Index](../index.md)
