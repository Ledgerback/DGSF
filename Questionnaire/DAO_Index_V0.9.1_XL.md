# Overall Comments

1. For BSP, 
	1. it might be useful to separate out the structure and practice of stakeholder governance. For example, it might be helpful to have a participatory structure; however, how much participation and the alliances/coalitions in actual governing activities might present a different picture. 
	2. What about the presence of foundation or other legal entities that control IP or some other resources of the DAO? If this is important, we should consider how individuals in the foundation are elected and monitored. 
2. For CBC
	1. I fail to see how this is relevant. We've discussed this before, but let's reopen the examination on this one. First, how can we even comprehensively confirm the geolocation of DAO members? Second, why does geolocation matter? My thinking is that geolocation has more to do with how well DAO can achieve consensus given diverse interests and values (e.g., culture, education related) among stakeholders.
3. For PDC,
	1. looking at the various aspects covered by PDC, it makes me think that maybe we should think about the levels of priorities in the framework: principles vs. organizational design. 
	2. Like what i have demonstrated in BSP, we can add a tag for something like organizational design dimension.
	3. As a result, we can organize measurements/factors by both principles and design dimension and we can decide which level should come first. To me, having design dimension comes first make more sense. But for others, the opposite might be true. Overall, having the option available and being able to validate the factors under both typology could be useful.
4. For IDA,
	1. we might need to separate out different aspects of organizational activities – internal operation (e.g., what contributors are working on), external operational (e.g., collaboration with external parties), and governance (e.g., voting dashboards, proposal posting/repo).
5. For D2D,
	1. why does this matter? I think we have discussed about this but I can't recall if we reached a consensus. 
	2. would this be more about what kind of partners that a DAO chooses to engage with? 
	3. What do you mean by transactions? if it's about a DAO's product being used, why does the identity of the partner matter? I was thinking more about what kind of tokens that are in a DAO's treasury? 
	4. I'm trying to figure out what D2D really aims to capture, and maybe it can be merged into other principles where we compare how a DAO collaborates with DAOs vs. firms to carry out its activities.
6. For OT,
	1. similar to D2D, i think it would be useful to look at the choices of a DAO when it designs its structures, where it faces choices between web 3 vs. web 2 tools.
7. 7. For HCAG.
	1. We should expand on this one. For example, we need to consider whether human consensus can override algorithmic output (like addressing losses due to bugs or vulnerabilities of smart contracts). 
	2. Also, how do we account for forks?
	3. what do we really mean by saying "human-centered"? 
	4. Again, this might benefit from having both principles and design dimensions to see a more comprehensive picture of what's happening in DAOs. 

# Broad Stakeholder Participation

- BSP-01
  - Indicators: Economic Inequality
  - ==Organizational design dimension: Ownership structure ==
  - Questions: Is the DAO's Gini Coefficient for ~~economic~~ governance tokens less than or equal to fifty percent (<=50%)?
- BSP-02
  - Indicators: Voting Power
  - ==Organizational design dimension: Voting power structure
  - Questions: ~~Is the Banzhaf Index for each individual member less than or equal to twenty-five percent (<=25.0%)?~~ Gini Coefficient but for voting power (how many wallets does it take to control 50% of voting power)
  - ==Change rationale: Banzhaf Index seems to capture similar thing if we only look at token ownership. Perhaps we can combine Gini Coefficient and Banzhaf Index in terms of **token ownership** together for BSP-01?==
  - ==Comment: How do we think about different quorum requirements, which may affect the exercise of voting power? ==
- BSP-04
  - Indicators: Identity
  - Questions: Does the DAO explicitly require members to verify that they have a unique digital identity?
  - ==Comment: Why do we need this? ==
- BSP-05
  - Indicators: Management
  - Questions: Does the DAO have any ==formal== leadership roles?
  - ==Comment: I think it should be combined with BSP-06 if it's about formal leadership (as discussed in the Google Doc). If it's about informal leadership (e.g., Rune for MakerDAO), where community members clearly identify some "leaders" then we can keep this here.==
- BSP-06
  - Questions: Does the DAO have any ==operational== management roles?
  - ==Comment: It is unclear to me how this relates to BSP. Perhaps we could say how they are elected and monitored?==
- BSP-07
  - Indicators: Conduct
  - Questions: Does the DAO require members to adhere to a standard of conduct, such as described in a code of conduct?
  - ==Comment: This appears to be more about cultural value. Instead, we should talk about whether a DAO has a declaration of intent, which speaks to how stakeholders converge on a shared goal(s)?==
- BSP-08
  - Indicators: Language
  - Questions: Does the DAO provide a glossary of internal terms?
  - ==Comment: I don't think we need this
- BSP-09
  - Indicators: Governance
  - Questions: Does the DAO use a participatory governance model?
  - ==Comment: I think it should be more about participation rate, and we would need to come up with a way to say something about the number of voters and percentage of voting power exercised and associated frequency.==
- BSP-10
  - Indicators: Dispute Resolution
  - Questions: Does the DAO have an explicitly defined dispute resolution mechanism?
  - ==Comment: we can delete this one? token voting itself is a dispute resolution mechanisms. Also, it might be more interesting to see how often voters diverge in their voting options (i.e., do they always vote together?)
- BSP-11
  - Indicators: Ownership
  - Questions: Does the DAO have a shared ownership model?
  - ==we should probably **delete** this one? Isn't shared ownership a prerequisite? what are we trying to capture here?
- BSP-12
  - Indicators: Management
  - Questions: Does the DAO have a well-defined procedure for how members can take defined leadership or management roles?
  - ==Comment: combine it with BSP-05, this would become more about the structure to grant individuals with some sort of authority (hence management role). To add to it, we can explore whether there are structures/mechanisms in place to ensure accountability (e.g., collusion, conflict of interests, mismanagement of funds). 
- BSP-13
  - Indicators: Economic
  - Questions: Does the DAO provide members multifaceted activities to receive rewards?
  - ==Comment: we should expand this by considering different incentive structures for contributing to operation (e.g., developing protocol), security (e.g., bug bounty), and governance (e.g., direct or proxy voting).

# Cross-border Coordination

- CBC-01
  - Indicators: Geolocation
  - Questions: Does the DAO have leadership from multiple geographic regions?
- CBC-02
  - Indicators: Geolocation
  - Questions: Does the DAO have members in multiple geographic regions?
- CBC-03
  - Indicators: Geolocation
  - Questions: Does the DAO have managers from multiple geographic regions?

# Practicing DAO Cooperativism

- PDC-01
  - Indicators: Economic
  - Questions: Does the DAO have a collective treasury (or multisig account)?
- PDC-02
  - Indicators: Measurement
  - Questions: Does the DAO have currencies recognizing value beyond financial relations, such as labor, contributor well-being, or environmental impact?
- PDC-03
  - Indicators: Identity
  - Questions: Does the DAO have a collective membership mark to signify membership in the DAO?
- PDC-04
  - Indicators: Economic
  - Questions: Does the DAO redistribute profits/surplus on a basis other than capital holdings?
- PDC-05
  - Indicators: Accountability
  - Questions: Does the DAO have any accountability mechanisms that subject the power of leaders and managers to the members?
  - ==Comment: This seems to overlap with PDC-06.==
- PDC-06
  - Indicators: Accountability
  - Questions: Does the DAO have an amendment procedure for its rules, procedures or policies?
  - ==Comment: To distinguish from PDC-05, we may need to think about what goes beyond the rules, procedures, or policies related to leaders and managers. One initial thought is that this is about changing the meta-rules (e.g., high level governance) for collective governance where no delegation of authority has occurred (hence no leaders or managers).==
- PDC-07
  - Indicators: Accountability
  - Questions: Does the DAO have a decision-making matrix?
- PDC-08
  - Indicators: Measurement
  - Questions: Does the DAO have metrics beyond governance and finance, such as contributor well-being or happiness?
- PDC-09
  - Indicators: Ownership
  - Questions: Does the DAO have separate tokens for governance and economic rights?
- PDC-10
  - Indicators: Economic
  - Questions: Does the DAO not make governance tokens tradeable?
- PDC-11
  - Indicators: Engagement
  - Questions: Does the DAO provide education and training opportunities for members to meaningful participate in governance?

# Cultural Patterns and Brand

- CPB-01
  - Indicators: Narratives
  - Questions: Does the DAO publish content on its activites in its' public channels?
  - ==Comment: how is this different from the questions about access to governance and operational information/analytics? Is this more about marketing like having X or Instagram accounts?==
- CPB-02
  - Indicators: Identity
  - Questions: Does the DAO make an explicit, clearly articulated statement of its purpose, values and norms?
  - ==Comment: this relate to BSP-07, as they are both about a DAO having a clear goal(s).==

# Information & Data Transparency

- BSP-03
  - Indicators: Communication
  - Questions: Does the DAO explicitly state that private communication channels are for sensitive or confidential matters?
  - ==Comment: as we discussed, it is unclear how this is good or bad. Also, what about statements around delegates talking to each other, disclosure of potential conflict of interests?== Further, how do we judge this? does chat messages where contributors disclose their private communication channels exist count? Or does it have to be a statement somewhere official?
- IDA-01
  - Indicators: Analytics
  - Questions: Does the DAO provide an organizational analytics dashboard?
  - ==Comment: we might need to separate out operational and governance analytics.
- IDA-02
  - Indicators: Information
  - Questions: Does the DAO make its governance activities (e.g., proposals, decisions) publicly accessible at free to low-cost?
- IDA-03
  - Indicators: Information
  - Questions: Does the DAO make its organizational documents (bylaws, policies, strategic plan, etc.) publicly accessible at free to low-cost?
- IDA-04
  - Indicators: Information
  - Questions: Does the DAO make its technologies open source or source available, and publicly accessible at free to low-cost?
- IDA-05
  - Indicators: Audit
  - Questions: Does the DAO explicitly report whether any Web3 tools it uses, internally or externally, have been audited?
  - ==Comment: what about web 2 tools where they might use open-source vs. closed resource? What about audits of codes? Does the identity of the auditor matter – DAO, web 3 firm, freelancers?==
- IDA-06
  - Indicators: Information
  - Questions: Does the DAO explicitly state that it operates on, or interacts with, more than one (1) blockchain?
  - ==Comment: this seems to be about operational transparency, so overlapping with IDA-01?==
- IDA-07
  - Indicators: Compensation
  - Questions: Does the DAO explicitly describe it's financial incentive or compensation structure for contributors?
  - ==Comment: i think this goes beyond description. What about streaming payments via smart contracts and monitoring mechanisms for such smart contracts? again, this might overlap with IDA-01.

# DAO2DAO

- D2D-01
  - Indicators: Transactions
  - Questions: Does the DAO have any planned transactions with another DAO?
- D2D-02
  - Indicators: Transactions
  - Questions: Does the DAO have any current transactions with another DAO?

# Organizational Technology

- OT-01
  - Indicators: Tool
  - Questions: Does the DAO currently use any Web3 organizational technology for business-to-business operations?
- OT-02
  - Indicators: Tool
  - Questions: Does the DAO currently use any Web3 organizational technology for treasury management?
- OT-03
  - Indicators: Tool
  - Questions: Does the DAO currently use any Web3 organizational technology for contribution-tracking?
- OT-04
  - Indicators: Tool
  - Questions: Does the DAO currently use any Web3 organizational technology for decision-making?

# Human-centered Algorithmic Governance

- HCAG-01
  - Indicators: Accountability
  - Questions: Does the DAO explicitly acknowledge the possible vulnerabilities of algorithmic decision-making?
- HCAG-02
  - Indicators: Engagement
  - Questions: Does the DAO educate its members on the development and use of algorithms, as they pertain to the DAO?
- HCAG-03
  - Indicators: Fairness & Bias
  - Questions: Does the DAO explicitly consider the shortand long-term social consequences of the algorithmic systems in the development and use of algorithms?
  - ==Comment: I'm not sure what this means.==