---
title: Governance '#2 - Slashing Param Change
date: 2024-04-25 12:00:00 +0800
categories: [governance]
tags: [governance,vote,proposal]      # tag names should always be lowercase
---

# Proposal 2: Slashing Param Change

> NeutaroGuardian Voted: [YES](https://nms1.neutaro.tech/Neutaro/tx/8ADC81620E73F53EFD4408FB1073F5F9269D10A277196C8A76DC5249E0A33F8A)
{: .prompt-tip }


### Description
The community would like to request extending the downtime window before jailing the validator from currently 7 hours to 3 days. This will allow ample time for validators to address any unforeseen issues and restore their validator setup.

#### Arguments In-Favor
The majority of validators are operating smoothly. Providing validators with additional time to resolve issues will not pose any risks to the chain. Moreover, in the unlikely event of widespread validator misbehavior in the future, adjusting the requirements can be implemented as seamlessly as the current process for relaxation.

#### Arguments Against
I did not hear argument against prior to my vote.

[ Link to Governance Proposal 2: Slashing Param Change](https://nms1.neutaro.tech/Neutaro/gov/2)

### Timeline
* Submited at: 2024-04-23 21:26
* Deposited at: 2024-04-23 21:26
* Voting start from 2024-04-23 21:26
* Voting end 2024-05-07 21:26

### My Thoughts
I can understand the interest to increase the downtime window. The current time window of 7 hours allows for routine maintenance and unplanned short term outages. However if there is a hardware failure or something happens say within a VPS provider that is out of the owners control, 7 hours or even 24 hours feels too short.

Professional service availability targets four nines of uptime, or 99.99% yearly uptime. That equates to approximately 52.56 minutes of downtime per year. The current 7 hours is a close representation to that of three nines of uptime or 99.9% uptime yearly.

Moving the downtime window out to 3 days suggests we are permitting two nines of uptime or ~99% uptime yearly.  In this case though, we don't hold this downtime in aggregate for the year, it resets to 0 after 10,000 blocks.

Considering these points, I believe it is fair and reasonable to allow additional downtime for validators to manage their host without putting undue risk to the chain.

## Commitement to Governance Voting
Those delegating **deserve transparency** for how their shares are voting. As a committed contributor to Neutaro and Timpi, I will be participating in all governance voting.  I will post description of each proposal when announced, share my thoughts, and **explain how I'm casting the vote for the shares delegated**. 