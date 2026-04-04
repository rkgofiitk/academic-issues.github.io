## Claude Source Code Leaks

On 31st March there is an accidental leak of Claude source code on GitHub repository. The leak is huge as much as a half million lines of code is now in public domain. The code contains [specific signs of users' frustration with Claude code assistant](https://www.scientificamerican.com/article/anthropic-leak-reveals-claude-code-tracking-user-frustration-and-raises-new/#:~:text=On%20March%2031%20artificial%20intelligence,prompts%20for%20signs%20of%20frustration). Anthropic accidentally shipped a .map file along with Claude code npm package that contained full readable source code of CLI tool. Package has been already pulled out. [Alex Kim's blog post](https://alex000kim.com/posts/2026-03-31-claude-code-source-leak/#kairos-the-unreleased-autonomous-agent-mode) gives a detailed analysis ot the implications code exposure. Mr Kim points out that only 10 days back before the accidental shipping happened Anthropic sent a legal notice to Open Code to remove built-in Claude authentication as third-party tools were using Claude intrnsl APIs at Opus subscription rates instead of pay-per use rates incurring a substantial loss of revenue. Howver, the accidental exposure of CLI tool's source code allowed rivals and competitors across the board to have a fairly good idea of security architecture and roadmap. Such insight will potentially accelerate the AI tool develpment projects by the competeitors. It also lets them analyze pitfalls and other vulnerabiliites that Claude's security architecture may have. Anthropic was planning for an IPO of 350 billion USD when this code exposure occured. Therefore, it may now raise doubts abouts the company's risk management and internal control issues. I think Anthropic has to now go for a rearchituring of the leaked part resulting in set backs in terms of company's abilities to restore confidence in its AI products.

The leaks provied a strategic peek into Anthropic's projects like:
-	BUDDY: Likely a personalized assistant mode.
-	KAIROS: Time-sensitive reasoning or scheduling.
-	ULTRAPLAN: Advanced planning/long-horizon reasoning.
-	Mythos: Possibly narrative generation or cultural reasoning.

These projects reveal Anthropic’s strategic roadmap—moving beyond prompts into more personalized, context-aware AI. Competitors now know where Anthropic is heading.

One may ask "Why this is important?" The AI companies don't care about privacy of the user is always in the knowledege of the developers. USA does not have a single data privacy law. The privacy protection in USA are protected by a set of laws:
- HIPA
- COPPA
- GLBA
- CCPA

These laws are meant for sector-wise protection of data. CCPA has only California jurisdiction. So privacy protection depends on sectors. For example, CCPA which applies in California provides limited protection such as opt-out or delete for sale. More specifically, the protection is either opt-out or implied depending on sector. There is no restriction on localization. Enforcement by FTC, local AG, sector regulatos, penalities may vary no standard punitive liabilities. USA data protection is essentially a  loose  patch work several laws. The strongest one is HIPA. EU data privacy protection is the gold standard. India DPDP Act was more aligned to EU GDPR and universal in applications. However, the broader government exemptions may dilute the restrictions. Since most AI companies are registered in USA, unless the Government specific mandate to operate in a geographical area cannot prevent them from toying with privacy protections. The US court jurisdictions may also prevent persons or class of persons from getting any punitive reliefs from misuse. 

On the flip side the EU law places most restrictive cost for business to operate, but loaded in favor of consumers. Therefore, many argue that AI companies find it expensive to create products in compliance of EU GDPR.

