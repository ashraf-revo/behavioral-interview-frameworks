```markdown
# Mock Interview: Tech Lead

**Candidate:** Maria, a software engineer with 8 years of experience, with the last 2 as a Tech Lead.

**Interviewer:** Ken, a Director of Engineering at a large tech company.

---

### Introduction

**Ken:** Hi Maria, thanks for coming in. I'm Ken, a Director of Engineering here. My group is responsible for the consumer-facing product lines. To start, could you give me a summary of your background and what you're looking for?

**Maria:** Hi Ken, thanks for having me. I'm Maria. I've been in software for about 8 years. I started as a backend engineer working on API development and eventually moved into a role with more architectural responsibilities. For the last two years, I've been the Tech Lead for a team of five engineers. In that role, I'm responsible for the team's technical direction, project delivery, and mentoring the other engineers. I'm looking for a role where I can continue to lead challenging technical projects while also helping to grow a team.

---

### Behavioral Questions

**Ken:** Great. Let's talk about leadership. Describe your leadership style with a specific example.

**Maria:**
*   **Situation:** My team inherited a critical but legacy service that was a single point of failure for several other systems. It was poorly documented, had no tests, and was a source of frequent production incidents. The team was hesitant to touch it.
*   **Task:** My goal was to lead the team to modernize this service, making it reliable and maintainable. I needed to do this without a top-down mandate, but by getting the team's buy-in.
*   **Action:** I started by framing the problem not as "we have to fix this," but as an opportunity for us to learn and have a major impact. I time-boxed an investigation phase where we collectively mapped out the service's dependencies and failure points. I then facilitated a series of brainstorming sessions where we designed a new, more resilient architecture. I made sure everyone's voice was heard, from the junior engineer to the senior members. I took on the task of creating the initial proof-of-concept to de-risk the new approach, and then we broke down the migration into small, manageable pieces that the team could work on in parallel.
*   **Result:** The team successfully migrated the service to the new architecture over three months. Production incidents related to the service dropped to zero. More importantly, the team's confidence grew, and they began proactively looking for other areas of our system to improve. My style is to lead from the front by setting a clear vision, empowering the team to find the solution, and clearing any roadblocks for them.

**Ken:** That's a strong example. Tell me about a time you had to make a trade-off between people, time, and scope.

**Maria:**
*   **Situation:** We were working on a major new feature with a hard deadline for a big industry conference. Two months into the six-month project, a key engineer on the team decided to leave the company.
*   **Task:** I had to figure out how to deliver the project on time without burning out the rest of the team.
*   **Action:** I immediately re-evaluated our project plan. I saw that we couldn't deliver the full scope with the reduced team size without requiring everyone to work significant overtime, which I was not willing to do. I met with the product manager and laid out the situation with a few options. Option A was to cut a few of the "nice-to-have" features to reduce the scope. Option B was to see if we could get a temporary loan of an engineer from another team. Option C was to push the deadline, which we knew was not really an option.
*   **Result:** The product manager agreed that cutting scope was the best path. We worked together to identify the non-essential features, and I communicated the change to the team, making it clear that this was to ensure a sustainable pace. The team was relieved and motivated. We delivered the core functionality on time for the conference, and it was a success. We then added the "nice-to-have" features in the following quarter. It was a classic trade-off, but being transparent and proactive made all the difference.

**Ken:** How do you handle technical disagreements within your team?

**Maria:**
*   **Situation:** Two senior engineers on my team had a strong disagreement about the right database to use for a new service. One advocated for a relational database for its consistency, while the other argued for a NoSQL database for its scalability and flexibility.
*   **Task:** I needed to help the team reach a decision that was technically sound and that both engineers could commit to.
*   **Action:** I scheduled a meeting with both engineers to let them present their cases. I asked them to come prepared with data, not just opinions—things like performance benchmarks, operational costs, and how each choice would align with our long-term strategy. During the meeting, I acted as a facilitator, ensuring the discussion remained respectful and focused on the technical merits. It became clear that the core of the disagreement was about different assumptions about our future traffic patterns.
*   **Result:** We decided to run a small, time-boxed proof-of-concept for both options to gather more data. The results showed that for our expected scale in the next 1-2 years, the relational database was more than sufficient and was simpler to operate. The engineer who had advocated for NoSQL agreed with the data-driven decision. By creating a structured, data-focused process, we were able to resolve the conflict and move forward with a decision everyone understood and supported.

**Ken:** Tell me about a time you improved an agile process that wasn't working.

**Maria:**
*   **Situation:** Our team's retrospectives had become stale. The same few people would talk, and we weren't generating any actionable insights.
*   **Task:** I wanted to make our retrospectives more engaging and productive.
*   **Action:** I introduced a new format for our retrospectives. Instead of just asking "what went well" and "what didn't," I used different techniques like "start, stop, continue" and "mad, sad, glad." I also made a point of calling on quieter members of the team to ensure everyone had a chance to contribute.
*   **Result:** The new format made our retrospectives more dynamic and inclusive. We started generating more concrete action items, and the team's morale improved as a result.

**Ken:** Describe how you manage agile ceremonies (e.g., retrospectives, planning) to ensure they are productive.

**Maria:**
*   **Situation:** Our sprint planning meetings were often running long and ending without a clear commitment.
*   **Task:** I needed to make our sprint planning more efficient and effective.
*   **Action:** I started by setting a clear agenda for each meeting and sending it out in advance. I also made sure that all user stories were well-defined and estimated before the meeting. During the meeting, I kept the discussion focused on the sprint goals and time-boxed conversations to avoid getting bogged down in details.
*   **Result:** Our sprint planning meetings became much more productive. We were able to consistently finish on time with a clear sprint backlog that the entire team was committed to.

**Ken:** Give an example of when you set the direction for a team or project.

**Maria:**
*   **Situation:** My team was responsible for a number of legacy services that were becoming increasingly difficult to maintain.
*   **Task:** I wanted to create a long-term vision for modernizing our technology stack and reducing our technical debt.
*   **Action:** I started by conducting a thorough audit of our existing services and identifying the biggest pain points. I then worked with the team to create a roadmap for modernizing our stack, including migrating to a new microservices architecture and adopting a new CI/CD pipeline. I presented this roadmap to the engineering leadership team and secured their buy-in.
*   **Result:** The roadmap provided a clear direction for the team and helped us to prioritize our work. We successfully migrated several legacy services to the new architecture, resulting in improved reliability, scalability, and developer productivity.

**Ken:** Tell me about a time you had to hold someone accountable. How did you approach it and what was the result?

**Maria:**
*   **Situation:** A senior engineer on my team was not following our team's coding standards, which was causing inconsistencies in our codebase.
*   - **Task:** I needed to address the issue and ensure that everyone on the team was following the same standards.
*   **Action:** I had a private conversation with the engineer and explained the importance of following our team's coding standards. I also pointed out specific examples of where their code was not compliant. I then worked with them to create a plan to address the issue, including setting up automated linting and code formatting tools.
*   **Result:** The engineer agreed to follow the team's coding standards, and the automated tools helped to ensure compliance. Our codebase became more consistent and easier to maintain as a result.

**Ken:** Share an example of influencing senior stakeholders with limited authority.

**Maria:**
*   **Situation:** I believed that our company should invest in a new technology that would significantly improve our product's performance. However, I didn't have the authority to make the decision.
*   **Task:** I needed to convince the senior stakeholders to invest in the new technology.
*   **Action:** I started by building a business case for the new technology, including a detailed analysis of the potential benefits, costs, and risks. I then presented my business case to the senior stakeholders and offered to do a proof-of-concept to demonstrate the technology's capabilities.
*   **Result:** The senior stakeholders were impressed with my business case and agreed to fund the proof-of-concept. The proof-of-concept was successful, and the company decided to invest in the new technology.

**Ken:** Describe a time you had to scale processes, hiring, or operations.

**Maria:**
*   **Situation:** Our team was growing rapidly, and our ad-hoc onboarding process was not scaling. New hires were taking a long time to ramp up and were not getting a consistent onboarding experience.
*   **Task:** I needed to create a more structured and scalable onboarding process.
*   **Action:** I started by documenting our existing onboarding process and identifying the biggest pain points. I then created a new onboarding checklist that included everything from setting up a development environment to meeting with key team members. I also created a set of onboarding documents and training materials.
*   **Result:** The new onboarding process made it much easier for new hires to ramp up quickly. We received positive feedback from new hires, and the team's productivity improved as a result.

**Ken:** Tell me about a time you improved an agile process that wasn't working.

**Maria:**
*   **Situation:** Our team was struggling to meet our sprint commitments. We were consistently overcommitting and carrying over stories from one sprint to the next.
*   **Task:** I needed to help the team improve their sprint planning and execution.
*   **Action:** I started by analyzing our sprint data and found that we were not accurately estimating our work. I then introduced a new estimation technique called "planning poker" to help the team come up with more realistic estimates. I also encouraged the team to break down large stories into smaller, more manageable tasks.
*   **Result:** The team's estimation accuracy improved, and we started to consistently meet our sprint commitments. The team's morale also improved as they felt more in control of their work.
```