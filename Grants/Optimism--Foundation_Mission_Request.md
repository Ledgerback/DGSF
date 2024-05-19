# [Foundation Mission Request - Measuring the Concentration of Power in the Collective](https://github.com/orgs/ethereum-optimism/projects/31/views/1?pane=issue&itemId=61734705)

_To take on this project, submit a proposal to this thread by June 3. Read more about Missions [here](https://gov.optimism.io/t/token-house-missions/5881)._

- **Foundation Mission Request Summary:** Develop a metric for concentration of power in the Optimism Collective
- **S5 Intent**: Governance Accessibility
- **Proposal Tier**: [Ember](https://gov.optimism.io/t/collective-trust-tiers/5877)
- **Baseline grant amount:** 9,000 OP
- **Should this Foundation Mission Request be fulfilled by one or multiple Alliances:** Multiple
- **Optimism Foundation point-of-contact:** [@elizarileyoak](https://github.com/elizarileyoak) until Jun 10, [@C-Emily-Furlong](https://github.com/C-Emily-Furlong) after Jun 10
- **Submit by**: June 3
- **Selection by**: July 3

---

**How will this Foundation Mission Request help accomplish the above Intent?:**

In order to reach our goal of governance accessibility, we need to understand how to reduce the concentration of power in the Collective. To recap, we refer to governance accessibility as follows:

> “Accessibility” includes enabling a diversity of perspectives to participate in governance, facilitating better knowledge sharing to develop more informed voters, and lowering barriers to participation for more culturally diverse involvement in the governance process. Increasing the votable supply and reducing the concentration of voting power are important byproducts of improved accessibility.”

To understand how to reduce the concentration of power in the Collective, we need clear metrics that we can observe. The objective of this Mission Request is to have one or more measures of the concentration of power in the Collective. These measures will enable us to document the impact of various governance initiatives on concentration of power, including initiatives under the ‘Improving Governance Accessibility’ Intent.

**What is required to execute this Foundation Mission Request?**

Various approaches have already been proposed to measure the concentration of power or level of centralization of a decentralized governance system. Common approaches include the [Nakamoto Coefficient](https://arxiv.org/pdf/2204.01176.pdf), [Voting Bloc Entropy](https://arxiv.org/abs/2311.03530), [Minimum Quorum](https://arxiv.org/html/2305.17655v2), or [Shannon Entropy](https://arxiv.org/pdf/2205.04256.pdf). We aim to build on these prior approaches to define a metric tailored to the specific design of the Optimism Collective.

In the Collective, there there are multiple parameters for consideration beyond token holdings, voting behavior, or correlation of votes, for instance taking into account that a voter might hold power in multiple governing bodies and councils across the Collective. There are also different voting mechanisms employed across the Collective, for example one-token-one-vote in the Token House but a version of one-person-one vote in the Citizens House.

**The desired outcome of this mission is:**

- A metric that captures the concentration of power in the Collective and allows Collective participants to continually track performance on this metric (i.e. is accessible in a public location like a Dune dashboard)
- This metric could take into consideration:
    - Voting power distribution in the Token House + Citizen’s House (including the fact that some individuals are active in both Houses)
    - Positions of influence across Councils (Grants Council, Developer Advisory Board, Security Council, Code of Conduct Council, Anticapture Commission)
    - The social graph of voters (e.g., via Farcaster)
    - How voting power distributions may be obfuscated via voting blocks, spreading voting power over multiple wallets, informal coalitions, etc.
- A metric that captures the contribution of the Token House to the overall concentration of power.
- A metric that captures the contribution of the Citizen’s House to the overall concentration of power.

The code running these metrics should be open sourced so teams can fork and measure the impact of their own initiatives on this important outcome.

**What milestones will help the Collective track progress towards completion of this Foundation Mission Request?**

**1. Research and planning**  
a. At the end of this milestone share your proposed approach with the Mission Request authors for feedback, listing explicit assumptions that your approach relies on and noting how this improves upon prior approaches for measuring centralization.  
b. The approach should include a suggestion for how to measure the performance of the metric.

**2. Prototype development and testing**  
a. Applicants will test the performance of the metric with real and dummy data, that can be provided by the Foundation team.  
b. At the end of this milestone share your prototype with the Mission Request authors for feedback

**3. Production development**  
a. At the end of this milestone the metric(s) should be trackable and accessible to the public

**How should badgeholders measure impact upon completion of this Foundation Mission Request?**

- If this Mission Request is successful, Collective stakeholders will be able to track the concentration of power in the Collective and measure the impact of initiatives against this important measure.
- The quality of the metric itself should be measured by its performance on existing and dummy data. Changes to the real and dummy data should result in the expected effects on the metrics.
- If the metric is implemented by the Collective, grantees are encouraged to apply for additional rewards in the August 2024 governance-themed Retro Funding Round 6.

## Application instructions

_To apply for this Foundation Mission Request, please complete the form in the expandable section below and leave your response as a comment on this issue thread. Submissions will be open until June 3, at which time the Foundation will review all submissions and select at least **one** individual/team to complete the work defined here._

# Application

%% 
Can focus on:

1. Network analysis

	1. for engagement (voting, discussions, etc.)
		1. really emphasize use of community science (refer to apiary.xyz) (or org network analysis) to go beyond simply voting or governance activity ()
	2. for production (proposal creators)

2. Concentration metrics (mention Palma Ratio, Banzhaf Power Index)

3. Optimism Member Surveys (get qualitative insights into how concentration is understood or perceived in the organization's members)

Can also mention that we will review DAO-related academic and grey lit. (or integrative lit. rev.) to find possible concentration metrics to apply
%%

_Copy the entire application below and leave a comment on this issue with your answers completed. A representative from the Optimism Foundation may reach out using the contact info provided to request more information as necessary._

## Foundation Mission (RFP) Application

**Please verify that you meet the qualifications for submitting at the above [Tier](https://gov.optimism.io/t/collective-trust-tiers/5877/2)**

- **Alliance Lead:** Charles Adjovu
- **Contact info:** 
- **L2 recipient address:** 
- **Please list the members of your Alliance and link to any previous work:** Charles Adjovu, Xule Lin, Valerie Spina; you can find our previous work listed here

Read more about Alliances [here](https://gov.optimism.io/t/season-4-alliance-guide/5873)

---

**What makes your Alliance best-suited to execute this Mission?**

- Our alliance proposed the DAO Index, ...
- As part of the DAO Index, we conduct qualitative and quantiatative assesments of DAOs to provide a holsitic basis for benchmarking and comparing DAOs
- We seek to improve our methods, and one way of doing so, is providing more quantiative measures, including concentration metrics, to give us a more holistic understnading of DAOs
- We have (maybe Val?) researched DAOs f
- We have assisted DAOs in the past, monst notably, Decred with an update to their consitutino in 2019.

**Please describe your proposed solution based on the above Solution Criteria (if applicable):**

- Determine concentration metrics relevant to DAOs, 
- Analyze the Token House and Citizen’s House for each concentraion metric, 
- Share our results publicly via dashboards and publications
- [...]

**Please outline your step-by-step plan to execute this Mission, including expected deadlines to complete each peice of work:**

- Conduct a literature review to find concentration metrics (e.g., Banzhaf Power Index for voting power, Palma Ratio and Herfin-... for economic power) relevant to DAOs
- Determine appropriate concentration metrics at multiple levels, including governance and communications, to apply to  Token House and Citizen’s House
- Develop Jupyter notebooks covering our quantitative analyses of concentration metrics, as applied to  to  Token House and Citizen’s House, and share our results publicly via dashboards and publications
- Compare analyses of Optimism with other DAOs to determine standards for concentration metrics

**Please define the [critical milestone(s)](https://gov.optimism.io/t/grant-policies/5833) that should be used to determine whether you’ve executed on this proposal:**

- [...]
- [...]

**Please list any additional support your team would require to execute this mission (financial, technical, etc.):**

- Assistance recruiting new team members skilled in data science and poltiical science 
- Assistance from the Optimism Governance team 

**Grants are awarded in OP, locked for one year. Please let us know if access to upfront capital is a barrier to completing your Mission and you would like to be considered for a small upfront cash grant:** _(Note: there is no guarantee that approved Missions will receive up-front cash grants.)_

- I would like to be considered for a small upfront cash grant to be able to afford access to APIs from DAO and Web3 data providers

---

Please check the following to make sure you understand the terms of the Optimism Foundation RFP program:

- [ ]  I understand my grant for completing this RFP will be locked for one year from the date of proposal acceptance.
- [ ]  I understand that I will be required to provide additional KYC information to the Optimism Foundation to receive this grant
- [ ]  I understand my locked grant may be clawed back for failure to execute on critical milestones, as outlined in the [Operating Manual](https://github.com/ethereum-optimism/OPerating-manual/blob/main/manual.md#valid-proposal-types)
- [ ]  I confirm that I have read and understand the [grant policies](https://gov.optimism.io/t/token-house-grant-policies/5833)
- [ ]  I understand that I will be expected to following the public grant reporting requirements outlined [here](https://gov.optimism.io/t/suggested-public-reporting-requirements-for-grantees/4176)

-- end of application --