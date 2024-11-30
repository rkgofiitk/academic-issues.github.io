# P-Hacking in AI for Non-Replicable Research 

[Blog Index](../index.md)

Generative AI creates new text, images, or videos by training from massive data. It 
learns patterns from those data and generates similar content. The principle
of extension is the key feature of generative AI. It cannot generate vacuously. From the point of view of a 
user's interaction, generative AI appears to be a dialogue-based 
programming interface. Many experts view this prompt-based interface as an extension to 
[test and debugging interface](https://dl.acm.org/doi/pdf/10.1145/3673861) for machine learning. 
There are two main concerns about the interface. 
- The prompt-based interface is rather loose and unoptimized
- It may, therefore, generate somewhat risky outputs

The question that AI experts need to ponder about is that 
- Whether they would risk building critical applications on top of the generative AI model

The problem with prompting stems from the fact that it is not the same as being able to communicate in 
pure natural language. When we communicate in natural language, the collaborators or the partners
understand the inherent subtleness of verbal conversation; when they don't, clarifications are sought. 
In human conversation, perceived intent is an essential element in a speaker's utterances. It is highly
critical to understand the intent. Double entendre is often used in political discourse. So, extending 
natural language as the prompting interface could confuse users of generative AI tools. 
It may lead to similar near-catastrophic results as often exhibited by heuristic-driven soft 
computing methods, even after lots of training.

Prompt hacking could exacerbate the problem, obfuscating the intent of the user's query. In a recent
article published in CACM, [Morris](https://dl.acm.org/doi/pdf/10.1145/3673861) argues that "p-hacking"
could be the main reason for the "replication crisis" in AI research. She observes that social sciences 
are already experiencing a p-hacking crisis. She hastens to add that her observation should not be 
viewed to imply that social science researchers are engaging in "nefarious intent." However, much of 
her observations may extend equally well to the context of science and engineering research in India.
The Indian retraction rate is 44 per million published papers, more than 2.5 times the average. 
Of course, the high retraction rate is not entirely due to generative AI because the tool is a 
reasonably recent addition to researchers' search kits. The replication crisis may actually lead to 
a drop in retraction rate. Because the researchers may carefully craft prompts to extract 
desired results. It will become difficult to figure out an original work from an AI-generated work.
The question is, how do we address this seemingly invincible technique? 

Sometime back, we received a large number of submissions from a Chinese institution to an
International Conference we were organizing. At first, we were a little perplexed. A closer examination
revealed that the submissions were clever cut-and-paste jobs. We had to spend a considerable time to 
discover the sources. Another submission was from an Indian researcher that dealt with the network 
sharing of USB file systems. I was thoroughly impressed with the submission and thought it could be 
an ideal candidate for the best paper award. At that time, we did not have access to plagiarism 
detection tools. Suddenly, while reviewing the paper, I came across an identical copy of the paper
from the USENIX conference but by a set of different authors. Indeed, the paper received the Best Paper 
award at the USENIX conference. 

Plagiarism detection tools are not sufficiently improved to deal with p-hacking. So, how are we going to
detect p-hacked papers? The answer to this needs to be more straightforward. It opens up several 
possibilities apart from improving Plagiarism detection tools.
- Developing a clear set of prompting standards
- More investment in natural language interface.
- Prompt log registration could be enforced.
- Prompt may be restrictive in disallowing p-hacking.

However, restricting prompt formats will rob generative AI's most unique characteristics, i.e., 
natural language query interface. Enforcing pre-registration of prompts will surely help in dampening 
p-hacking attempts. However, it will affect the natural evolution of queries from human interlocutors. 
More investments in the natural language interface is probably the only safe way out. Reducing the
replication crisis will be possible with a better understanding of natural language queries. It means
that the race between LLM and human interlocutors is fiercer than ever. Unless we address it, the LLM
model will reduce human innovations to a mediocre level. 
 
[Back to Index](../index.md)
