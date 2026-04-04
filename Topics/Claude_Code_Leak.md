## Claude Source Code Leaks

On 31st March there is an accidental leak of Claude source code on GitHub repository. The leak is huge as much as a half million lines of code is now in public domain. The code contains [specific signs of users' frustration with Claude code assistant](https://www.scientificamerican.com/article/anthropic-leak-reveals-claude-code-tracking-user-frustration-and-raises-new/#:~:text=On%20March%2031%20artificial%20intelligence,prompts%20for%20signs%20of%20frustration). One may ask "Why this is important?" The AI companies don't care about privacy of the user is always in the knowledege of the developers. USA does not have a single data privacy law. The privacy protection in USA are protected by a set of laws:
- HIPA
- COPPA
- GLBA
- CCPA

These laws are meant for sector-wise protection of data. CCPA has only California jurisdiction. So privacy protection depends on sectors. For example, CCPA which applies in California provides limited protection such as opt-out or delete for sale. More specifically, the protection is either opt-out or implied depending on sector. There is no restriction on localization. Enforcement by FTC, local AG, sector regulatos, penalities may vary no standard punitive liabilities. USA data protection is essentially a  loose  patch work several laws. The strongest one is HIPA. EU data privacy protection is the gold standard. India DPDP Act was more aligned to EU GDPR and universal in applications. However, the broader government exemptions may dilute the restrictions. Since most AI companies are registered in USA, unless the Government specific mandate to operate in a geographical area cannot prevent them from toying with privacy protections. The US court jurisdictions may also prevent persons or class of persons from getting any punitive reliefs from misuse. 

On the flip side the EU law places most restrictive cost for business to operate, but loaded in favor of consumers. Therefore, many argue that AI companies find it expensive to create products in compliance of EU GDPR.

Anthropic accidentally shipped a .map file along with Claude code npm package that contained full readable source code of CLI tool. Package has been already pulled out. [Alex Kim's blog post](https://alex000kim.com/posts/2026-03-31-claude-code-source-leak/#kairos-the-unreleased-autonomous-agent-mode) gives a detailed analysis ot the implications code exposure. 
