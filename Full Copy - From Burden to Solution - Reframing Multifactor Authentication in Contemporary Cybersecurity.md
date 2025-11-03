## 1. Title
>**From Burden to Solution**: *Reframing Multifactor Authentication in Contemporary Cybersecurity*
## 2. Description
### What cybersecurity problems am I addressing?
- User fatigue with multifactor authentication and lack of adoption
- Lack of information about best practices for general public
- Lack of consistent communication from the security community.
### Why is this topic important and relevant to the cybersecurity community?
- Cybersecurity relies on end users: the better the adoption of strong security practices, the better the overall posture of the industry
###  What is the main goal or research question of my presentation?
- Improve the public adoption / acceptance of MFA
	- Redefine multifactor authentication for ourselves and for others
	- Present a dynamic range of approaches for pitching / delivering MFA
	- Empower CS professionals to begin changing the public perception of MFA
		1. As individuals
		2. As a community
		3. As experts
### What approach, techniques, or methods did I use?
- Tested and implemented "sales style" strategies for communication regarding Authentication and Authorization.
- Encouraged user literacy as a means for generating engagement through email campaigns and town hall meetings.
- Led small group "info sessions" with key client stakeholders to generate understanding and buy-in, while also using these sessions to hone in on effective and straightforward talking points.
- Reviewed public studies and surveys to confirm the trends I have seen over the last 5 years regarding MFA adoption (linked at the end of the outline)
- Example reflective of the current perception of MFA: Twitter's requirement of Twitter Blue in order to use SMS OTP
- Personal Stories (joy of Yubikeys, forcing Hardware TOTP tokens, adoption during disaster)
### What potential impact or implications does my presentation have for practitioners, researchers, or the industry?
- Easier rollouts, improved adoption, and better personal/profession communication regarding MFA.
  
---

## 3. Outline
### 0. Hook / Intro
- **Let's tackle the hardest part of MFA — convincing people to actually use it.**
- This is not a presentation of "which MFA method is best", but rather an outline for how to encourage the highest feasible method for authentication while utilizing sales and adult learning concepts to maximize adoption.
- {Engage with audience}: Poll for who has MFA methods: Yubikey/Passkeys, Duo/Msft Auth, Software/Hardware TOTP, SMS/Email, or no MFA.
### I. About Me
-  Who am I, and what is my background in cybersecurity?
> Sam Fleming, worked in IT with a focus on Multifactor Authentication and Conditional Access Policies. Before working in IT, I worked as a Sales Innovation Specialist, helping craft sales strategies for clients including Google, T-Mobile, and Grubhub.
> I also am a competitive West Coast Swing dancer, and I have taught WCS and Ballroom. It has absolutely nothing to do with MFA, but the pictures are pretty awesome.
-  How has my experience informed my understanding of MFA challenges and solutions?
> Coming from a background of sales has helped me work with users of all technical levels, and deliver MFA as a soft-sell, rather than as a necessary evil. Reframing this for myself has rippled out to those I work with, and eventually to the users I have supported.
-  Why am I passionate about improving MFA adoption?
> I realized that individually, I can empower an individual with a better approach to conditional access. However, by sharing the strategies and techniques I have learned with other tech professionals, we can continue the ripple out even further, and positively shift today's general security posture.
### II. Introduction
-  What is multifactor authentication (MFA), and why is it important in today’s cybersecurity landscape?
> Multifactor Authentication (MFA) is a security measure that requires users to provide multiple forms of identification before gaining access to accounts, systems, or applications. It typically involves a combination of at least two of the following factors:
*Something you know*: A password or PIN.
*Something you have*: A mobile device, smartcard, or hardware token.
 *Something you are*: Biometrics like fingerprints or facial recognition.
-  What is the current state of MFA adoption and perception among users?
>[!warning] Content Moved
>Moving the "three factors of MFA to the beginning of section 3"


>*I asked myself, "What is the current perception of MFA?": BAD.*
Multifactor authentication is largely viewed as a frustration, a waste of time, another thing to keep up with, etc.
*(create a wordmap showing the most common negative descriptions of MFA)*
-  Why is user fatigue and misinformation a significant barrier to MFA effectiveness?
>Unwise practices and a delayed public adoption of recommended methods have led the public as a whole to view more secure methods of authentication as a hinderance, leading to an over-reliance on legacy methods that cause fatigue and encourage bad habits. The general consensus now places an over-reliance on easily-spoofed methods of authentication (such as SMS codes) while negatively viewing secure methods like FIDO2 passkeys.
-  What is the purpose and scope of this presentation?
> This presentation will describe a novel approach to promoting the use of MFA, enabling more members of the IT and CS communities to encourage the use of secure methods, communicate effectively with non-technical users, and promote best practices within the security landscape.

### III. What Has Been Done: Current Landscape and Challenges
-  What existing MFA technologies and practices are commonly used?
> Common MFA methods include:
--  **Time-based One-Time Passwords (TOTP):** Authenticator apps (Google Authenticator, YubiKey) generate short-lived codes.
--  **SMS Verification Codes:** Codes sent via text message, though vulnerable to interception.
--  **Push Notifications:** Approval prompts sent to registered devices (e.g., Duo Security).
--  **Biometric Authentication:** Fingerprint, facial recognition on mobile devices.
--  **Hardware Security Keys:** Physical devices providing strong cryptographic authentication.
These methods are typically combined with passwords to enhance security.

- What efforts have been made to promote MFA adoption among the general public?
> Key promotion efforts include:
--  Public awareness campaigns (e.g., National Cybersecurity Awareness Month).
--  Platforms encouraging or requiring MFA by default (Google, Microsoft, Twitter).
--  MFA setup integrated into onboarding.
--  Regulatory incentives pushing organizations to adopt MFA.
--  Innovations aimed at improving user experience (passwordless, biometrics).

- What are the documented challenges and limitations?
>Challenges include:
--  **User fatigue:** Frequent prompts cause frustration.
--  **Usability issues:** Complex setup and device compatibility problems.
--  **Misinformation:** Lack of understanding or misconceptions about MFA.
--  **Accessibility:** Some methods exclude users without smartphones or with disabilities.
--  **Security trade-offs:** Some MFA types (e.g., SMS) are less secure.
--  **Organizational resistance:** Lack of training or leadership support.
### IV. What Can Be Done: Reframing and Strategies for Improvement
- **What gaps remain in public understanding and acceptance of MFA?**
>Remaining gaps are:
--  Low awareness and understanding of MFA’s importance.
--  Perception that MFA is complicated or unnecessary.
--  Privacy and trust concerns about biometric and third-party tools.
--  Generic messaging that doesn’t address diverse user needs.
--  Limited support for users facing MFA issues.
--  Cultural and behavioral resistance in some groups.
Closing these gaps requires targeted education, empathetic communication, and ongoing user support.

-  **How can MFA be reframed from a burden to a solution in messaging and practice?**
>-- Emphasize personal empowerment and convenience over security mandates.
-- Use case studies and real-world scenarios to show MFA's practical benefits.
-- Frame MFA as a proactive step to protect personal and professional digital lives.
-- Stress the positive impact of MFA on daily security habits.

-  **What dynamic approaches can be employed to pitch MFA effectively to different audiences?**
>Use interactive workshops, webinars, and personalized consultations.
Tailor messaging to the audience's needs:
**Non-technical users:** Use analogies (e.g., a dual-lock door system), and step-by-step walkthroughs utilizing adult learning concepts to make trainings more accessible.
**Business leaders:** Focus on protecting assets and maintaining trust.
**Technical audiences:** Highlight advancements and security protocol integration.

-  **What practical strategies can cybersecurity professionals use to improve MFA adoption?**
>-- Provide clear onboarding instructions and continuous support.
-- Integrate MFA smoothly into existing processes with user-friendly tools.
-- Minimize setup friction and encourage user feedback to understand pain points.
-- Highlight industry trends towards passwordless solutions to appeal to progressives.

-  **How can communication and education be enhanced to address misconceptions?**
>-- Use empathetic communication acknowledging user frustrations.
-- Deliver clear facts about MFA’s importance through targeted content like FAQs, myth-busting articles, and success stories.
-- Leverage social media platforms and tech influencers to amplify messages.

### V. Role of the Cybersecurity Community and Professionals
-  **What responsibilities do individuals, communities, and experts have in changing MFA perceptions?**
>-- Model best practices and articulate MFA’s benefits.
-- Foster a security-minded culture through shared experiences and troubleshooting.
-- Develop and promote user-centric solutions.

-  **How can advocacy, leadership, and collaboration drive better MFA adoption?**
>-- Inspire voluntary adoption with stories of positive impact.
-- Set examples by implementing MFA within organizations.
-- Collaborate across sectors for unified strategies to foster adoption.

-  **What tools or frameworks can support community-driven efforts?**
> **Collaborative Platforms:**
> -- Use chat and social media platforms like Slack, Discord, Signal, and BlueSky to facilitate real-time communication and collaboration among cybersecurity professionals and enthusiasts.
> -- Organize virtual  and in-person meetups or webinars to discuss best practices, share success stories, and brainstorm solutions.

> **Feedback Loops:**
> -- Implement regular feedback mechanisms such as surveys or polls to gather group, community, or private input on MFA challenges and success stories.
> -- Use collected data to iterate and refine MFA practices and communication strategies.

> **Success Story Sharing:**
> -- Highlight case studies where effective MFA implementation has prevented security breaches, using these narratives to inspire and educate others.
> -- Use storytelling and real-world examples in training sessions to make the benefits of MFA relatable and tangible.
### VI. Illustrative Examples and Personal Insights
- **What examples or case studies demonstrate successful MFA adoption or innovative approaches?**

> **Innovative Communication Strategies:**
> -- Utilization of "sales style" communication strategies improved user engagement and comprehension of the Authentication and Authorization process.
> -- Conducted email campaigns and town hall meetings to boost user security literacy and engagement.

> **Corporate Influence and Policy Changes:**
> -- Reviewed and validated public studies showing trends in MFA adoption to draw parallels to successful corporate strategies.

> **Refinement through Stakeholder Engagement:**
> -- Led small group "info sessions" with client stakeholders to solidify understanding and gain buy-in, effectively using these sessions to refine messaging and strategies.

**How do personal experiences (e.g., using hardware tokens, navigating MFA during crises) highlight practical challenges and solutions?**

> **Experiences with Hardware Tokens:**
> -- Positive experiences with tools like Yubikeys demonstrated ease and increased security, fostering greater acceptance among users wary of digital security tools.
> -- For users who were resistant during an app-based authentication rollout, we only allowed the alternative of legacy hardware TOTP tokens. This incovenience led to many users "suddenly" being able to use the mobile app for MFA.

> **Adoptation during Crises:**
> -- While breaches and cybersecurity events are never desired, they can create opportunity and motivate stakeholders to make the necessary changes.
> -- Jamie Grant, former Florida CIO during Covid: "Never let a crisis go to waste. When the shit hits the fan, the bureaucracy fades away. If you're PREPARED in that moment, you can make huge strides"


### VII. Conclusion and Future Directions
(Concept closing remarks. Subject to rewording/rewriting)
In closing, remember that the role of each of us as cybersecurity advocates is to encourage more widespread and effective use of multifactor authentication (MFA) through empathy and understanding.
-    **What You Can Do:** Start by securing your own digital life with MFA and share your positive experiences to motivate others. Use simple, relatable examples to illustrate how MFA can protect against everyday risks without sounding technical or overwhelming.
-    **Impact:** By approaching conversations with empathy and simplicity, you can help reduce resistance to MFA, making it more accessible and appealing to diverse audiences. This helps foster a culture where digital security feels personal and achievable rather than daunting.
-    **Communicate with Care:** Use the concepts discussed here to frame your discussions around MFA. Avoid jargon and instead use analogies, such as comparing MFA to using both a seatbelt and an airbag for protection, to convey its importance in an understandable way.
-    **Empower Through Stories:** Share personal anecdotes not as instructions, but as stories highlighting how MFA has made a difference in protecting your accounts, allowing others to see the value through your experiences without feeling condescended to.

Let's empower each other to approach MFA advocacy with the reminder that everyone’s journey to better security starts with better understanding.

### VIII. References
-  What sources, reports, or studies support the analysis and recommendations in this presentation?
	- https://pushsecurity.com/blog/which-mfa-methods-should-you-use/
	- https://fidoalliance.org/fido2/
	- https://cloudsecurityalliance.org/blog/2020/07/31/strong-mfa-the-first-stop-on-the-path-to-passwordless#
	- Personal Interview with Jamie Grant, April 25 2025
	- https://www.researchgate.net/publication/335233025_Evaluating_User_Perception_of_Multi-Factor_Authentication_A_Systematic_Review
	- https://www.prove.com/blog/prove-identity-2023-state-of-mfa-report-consumer-attitudes-multi-factor-authentication
	- https://iacis.org/iis/2021/3_iis_2021_69-80.pdf

