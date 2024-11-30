# P-Hacking in AI for Non-Replicable Research 

[Blog Index](../index.md)

Generative AI works by creating new text, images or videos by training from a massive amount of data. It 
learns patterns from those data and generates similar content. The principle
of extension is the key feature to generative AI. It cannot generate vacously. From the point of view of an 
user's interaction generative AI appear to be a dialogue based 
programming interface. Many experts view that this prompt-based interface is an extension to 
[test and debugging interface](https://dl.acm.org/doi/pdf/10.1145/3673861) for the domain
of machine learning. There are two main concerns about the interface. 
- The prompt-based interface is rather loose and unoptimized
- It may, therefore, generate rather risky outputs

The question that AI experts need to ponder about is that 
- Whether they would risk on building critical application on top of generative AI model

The problem with prompting stems from the fact that it is not same as being able to communicate in natural 
language. When we communicate in natural language, the collaborators or the partners do understand inherent 
subtleness verbal conversation; and when they don't clarifications are sought. In human conversation, 
perceived intent in speaker's utterance plays and important role. It is extremely critical to understand
the intent. Double entendre is often used in political discourse. So, extension of true natural language
prompting could create confusion for users of generative AI tools. It may lead to similar near catastrophic
results as exhibited by heuritics driven soft computing methods even after lots of training.

Prompt-hacking could add or excerbate the problem obfuscating the intent in user's query. A recent article 
published in CACM, [Morris](https://dl.acm.org/doi/pdf/10.1145/3673861) argues that "p-hacking" could be 
the main reason for "replication crisis" in AI research. She observes that social sciences already 
experiencing p-hacking crisis. She hastens to add that her observation should not be viewed to imply that social
science researchers engaging in "neferious intent". However, I believe much of her observation
may extend equally well in Indian context. The Indian retraction rate is 44 per million of published papers which
is more than 2.5 times of average rate. It is true that the high retraction rate is not entirely be
due to generative AI, because the tool is a fairly recent additon in search kit of researchers. I
believe the replication crisis could actually lead to a drop in retraction rate. Because the researchers
may carefully craft prompts to extract their desired results. It will become difficult figure out original
work from AI generated work.

The question is how do we address this seemingly invincible technique? Plagiarism detection tools are 
clearly inadequate to deal with p-hacking. So, how are we going to detect p-hacked papers? The answer
to it not straightforward. It opens up several possibilities.
- Developing clear set of prompting standards
- More investment on natural language interface.
- Prompt log registration could be enforced.
- Prompt may be restrictive to disallow p-hacking.

However, restricting prompt formats will rob the generative AI's most unique characteristics, i.e., 
natural language query interface. Enforcing pre-registration of prompts will affect the natural evolution
of queries from human interlocutor. However, it certain help in p-hacking attempts. I believe more
investment on natural language interface is probably the only safe way out. Reducing replication 
crisis will be possible with better understanding of natural language queries. It means the race 
between LLM and human interlocutors is fiercer than ever. Unless we address it the LLM model will
reduce the innovation to midocre level. 
 
[Back to Index](../index.md)
