[who-is-this-for]: #who-is-this-for
[what-makes-a-great-manager]: #what-makes-a-great-engineering-manager
[how-technical-should-i-be]: #how-technical-should-i-be
[one-on-ones]: #one-on-ones
[coaching]: #coaching
[giving-feedback]: #giving-feedback
[thinking-strategically]: #thinking-strategically
[making-decisions]: #making-decisions
[ticket-and-pr-process]: #ticket-and-pr-process
[hiring]: #hiring
[onboarding]: #onboarding
[announcing-change]: #announcing-change
[managing-up]: #managing-up
[further-reading]: #further-reading

# Manager's Playbook

Heuristics for effective management.

## Table of Contents

1. [Who is this for?][who-is-this-for]
1. [What makes a great engineering manager?][what-makes-a-great-manager]
1. [How technical should I be?][how-technical-should-i-be]
1. [One-on-ones][one-on-ones]
1. [Coaching][coaching]
1. [Giving Feedback][giving-feedback]
1. [Thinking strategically][thinking-strategically]
1. [Making decisions][making-decisions]
1. [Ticket and PR process][ticket-and-pr-process]
1. [Hiring][hiring]
1. [Onboarding][onboarding]
1. [Managing up][managing-up]
1. [Announcing change][announcing-change]
1. [Further reading][further-reading]

## Who is this for?

This is a collection of heuristics I've learned from my own experience and from other managers. It's meant to be a living document. I try to keep it short and to the point.

This is mostly advice for people starting their career as a manager. It's also useful for experienced managers who want to improve their skills.

## What makes a great engineering manager?

Your job first and foremost is to execute. As a manager, you are a leader who harnesses your team's skills to achieve specific goals. To accomplish this, you need to be an adept coach, communicator, and decision-maker. However, these roles are merely means to an end.

An exceptional engineering manager elevates the team's standards by fostering a culture of continuous improvement and innovation. Every week should mark a new milestone, with the team surpassing its previous achievements in efficiency, creativity, and problem-solving. You don’t just manage; you lead by example, inspiring a sharper focus and a profound sense of purpose. The progress is tangible and energizing. While staff engineers act as force multipliers through technology, you serve as a multiplier through people.

## How technical should I be?

Effective engineering managers ought to possess a strong technical background, having firsthand experience with the challenges their teams encounter. I advise individuals to consider transitioning into management only after reaching at least a senior engineer level and ideally have at least 10 years of technical individual contributor experience. It's essential to bear the battle scars of technical endeavors.

Such managers should comprehend the technical intricacies of a project and even be capable of contributing to it. They must be adept at making technical decisions and articulate the reasoning behind them. However, this doesn't imply they should be actively coding on the critical path or making all the decisions.

If you have more than 7 direct reports*, you should generally avoid coding in the critical path to ensure you're not blocking the team on critical features or incidents. [Tips](https://charity.wtf/2019/01/04/engineering-management-the-pendulum-or-the-ladder/) from Charity Majors:

1. Authoring a feature?  ⛔️
2. Covering on-call when someone needs a break?  ✅
3. Diving on the biggest project after a postmortem?  ⛔️
4. Code reviews?  ✅
5. Picking up a p2 bug that's annoying but never seems to become top priority?  ✅
6. Insisting that all commits be gated on their approval?  ⛔️
7. Cleaning up the monitoring checks and writing a library to generate coverage?  ✅

*this number may vary based on your meeting load

## One-on-ones

Never skip one-on-ones. They serve as an essential mechanism for coaching and providing feedback, as well as fostering a connection with your team member. Most engineers cherish these sessions, and if they don't, it's often because they haven't experienced a well-conducted one-on-one.

Do note that these recommendations primarily pertain to one-on-ones with individual contributors. One-on-ones with managers typically lean more towards "business" matters, emphasizing strategy, team well-being, and project planning.

Some general tips:

1. Aim for 30min bi-weekly one-on-ones but offer to adjust cadence based on your teammate's preference.
1. It's helpful to offer a shared document with your report where you can both write agenda items ahead of time and tracking action tiems. But it's also important to know when to go off script. Not all reports will value this.
1. I find it helpful to do a healthcheck every month or quarter by asking these "scale of 1 to 10" questions. Normally if I get something other than a 9 or 10, I go deeper to understand. "On a scale of 1-10 how would you rate:..."
    - Predictability: How clear do you feel about what's expected of you?
    - Ownership: Your satisfaction with decision power and direction?
    - Purpose: How much your work makes a difference for the team?
    - Progress: The sense of progression each week?
    - Belonging: Your feeling of connection to the team?
1. Additional questions to help motivate discussion:
    - Which part of your work is most fun?
    - What's not fun about working here?
    - What are the biggest time wasters for you each week?
    - What skills do you want to improve?
    - What career path are you looking for?
    - Who in the company would you be excited to learn more from?
    - What parts of the business would you like to be more involved in?
    - What don't you like about the product?
    - What's the biggest opportunity that we're missing out on?
    - What do you see as your top 3 priorities this quarter? The team’s? The org's?
    - If you were CEO, what would you do differently?
    - What could I do to support you better?
    - If you were me, what are 1 to 3 things you would change?
    - How do you feel about the amount of feedback you are getting?
    - I need feedback. What's one thing I can do differently?
    - What's one thing we could do to improve our way of collaborating?

Encourage your direct reports to bring up topics:  
<img src="images/1_1s.jpg" width="400">  

For further reading, see [Getting more from your one on ones](https://medium.com/@sbourke/getting-more-from-your-1-1s-8f71996e286e) for more thoughts on effective one on ones.

## Effective teams

It's your job as a manager to make sure your team is running as effectively as possible. To that end, every high performing team should possess three key attributes:

1. **Autonomy**: Teams should operate in a manner where their work streams are independent of other teams. This allows them to make decisions without requiring approvals from outside their team. Moreover, teams should be able to operate with minimal overhead. This is accomplished by having great developer tooling and a clear processes (e.g. testing, change management, etc.).
2. **Mastery of Domain**: Teams should be experts in their specific domain. This encompasses a deep knowledge of the product, the code base, and the business landscape.
3. **Purpose**: Teams need to comprehend the larger picture and discern how their contributions align with it. This understanding lends clarity to the 'why' behind their tasks. In addition, ruthlessly prioritize your projects and make sure your team isn't fragmented across too many initiatives. This allows them to focus on the most important work. Swarm where possible so that everyone feels like they're driving towards a common goal and there is knowledge sharing. Finally, The best engineers want to be challenged and to work on projects that matter. Teams should be tackling problems that are both important and urgent.

Lacking these pillars (credit to Dan Pink), teams risk being less effective and may experience diminished motivation.

For further reading, check out [Team Topologies](https://www.amazon.com/Team-Topologies-Organizing-Business-Technology/dp/1942788819), which goes deeper into team organization theory.

## Coaching

Coaching is the most important skill a manager can have. It's the best way to help your reports grow and take ownership of their work.

1. Default to open questions: ask questions starting with **what**, **how**, **who** instead of closed-ended ones like **do**, **have**, **is** to invite conversation and give ownership over a problem.
    - "What questions do you have?" is better than "Do you have any questions?".
    - "Why do you think this is the right approach?" is better than "Is this a good idea?".
    - Respond with "What are your thoughts so far?" when asked "What should I do?"
1. Summarize what the person is saying so you're both on the same page and are pinpointing the problem.
    - "It sounds like there are two issues, x and y. Which should we focus on first?"
1. Figure out how to make the meeting productive:
    - "What's the next step?"
    - "How should we track this?"

## Project management

There is no one right way to manage projects. It depends on the team's size, the type of project, and the team's maturity. Here are some general tips:

1. Break down projects into small chunks that can be completed in a week or two.
2. Prioritize projects that have the highest impact and are the most urgent.
3. Minimize parallelization. It's better to have one project completed than two half done.
4. Assign a single owner to each project. This person is responsible for driving the project forward and communicating progress. Have the create a tech spec and work backwards on the due date.

For an amazing book on project execution check out [How Big Things Get Done](https://www.amazon.com/How-Big-Things-Get-Done/dp/0593239512).

## Giving feedback

Giving great feedback to reports/managers/peers is one of the most impactful things you can do to drive alignment and build trust.

1. Be prompt, ideally providing feedback the same day of the event that prompted it. Wiating too long makes it seem like you're holding a grudge and they might not remember details after a couple of days.
1. Get buy-in about providing feedback and reduce mystery by giving context:
    - "Do you have 10 minutes?"  ⛔️
    - "Do you have 10 minutes to talk about this morning's stand up?"
    - "Can I share some thoughts with you about how we've been working together?"
1. Don't pad negative feedback by beginning with compliments; it gives mixed signals.
1. Be specific even if it's positive feedback.
    - "Good job!"  ⛔️
    - "I like the initiative you took to reduce the service's memory footprint. It encourages me to give you more ownership so that I can focus elsewhere."
1. Avoid praising for doing their job. You want to make sure it's sincere and not just a way to avoid giving negative feedback.
    - "Thanks for fixing that bug"  ⛔️
    - "Thanks for fixing that bug. It was critical to the customer and you got it done quickly."
1. Focus on data and not behavior:
    - "I noticed you didn't address any of the comments made in your last three PRs"
    - "I noticed that you didn't pick up the ticket I asked you to do"
    - "I noticed your last feature release didn't have any tests"
    - "Your code is buggy"  ⛔️
    - "You are always late"  ⛔️
1. Talk about why this matters and who it's affecting:
    - "I mention it because it's important we work as a team"
    - "I mention it because the ticket I assigned you is critical to this quarter's roadmap"
1. Figure out together how to fix the problem:
    - "What do you think of our process?"
    - "How do you see it?"
1. Agree on an action plan:
    - "How do we ensure we don't miss a ticket due date next time?"
    - "What are a couple of actions you could take right now?"
    - "What are our action items?"
1. Highlight positive patterns (remember to be specific).
    - "It's great to see you teach X about Y so that they're as proficient as you. That's a trait of a senior engineer."
1. Replay instinctive reactions to help frame the conversation:
    - "My initial reaction to your proposal is..."
    - "Here's what I would do" is better than "Here's what you should do"
    - "When you did X, I felt Y"

For further reading, see [The rise of feedback: Why feedback skills have become urgent](https://ideas.lifelabslearning.com/the-rise-of-feedback-why-feedback-skills-have-become-urgent) and [Want to get better feedback? Ask a better question. Here’s how.](https://medium.com/lifelabs-learning/want-to-get-better-feedback-ask-a-better-question-heres-how-64d679a598a).

## Thinking strategically

No matter what level you are in the organization, you should be thinking strategically and in the context of your team solving business problems. This means understanding the big picture and how your team's work fits into it.

Questions you should be asking yourself:

1. How is your team moving the needle? Are you focusing on the right things?
1. What are your product's mission and tenets?
1. What are the company's top priorities this year? Where should the company be three years from now?
1. Does solving this pieve of tech debt help accomplish business goals?
1. What company annual goals is your team driving and in what way?
1. What are your team's pain points? How can you move 2x faster?
1. If the company failed, what would be most likely reason?
1. What would you do with one more person?


Great books on strategy:

1. [Good Strategy/Bad Strategy](https://www.amazon.com/Good-Strategy-Bad-Difference-Matters/dp/0307886239)
2. [Innovator's Solution](https://www.amazon.com/Innovators-Solution-Sustaining-Successful-Christensen/dp/B00N1PDLAM)
3. [Crossing the Chasm](https://www.amazon.com/Crossing-Chasm-3rd-Disruptive-Mainstream/dp/0062292986)

## Making decisions

1. Determine if the decision is [reversible vs. irreversible](https://fs.blog/2018/04/reversible-irreversible-decisions/).
    - Reversible decisions can easily be changed. Examples: changing stand up time, contributing guidelines.
    - Irreversible decisions cannot be changed without significant rework. These decisions should take
  longer and be documented and discussed. Examples: architecture changes, hiring, org changes, data models.
    - A rubric on technology decisions by [Sam Newman](https://www.amazon.com/Monolith-Microservices-Evolutionary-Patterns-Transform/dp/1492047848):
    <img src="images/tech-decisions.jpg" width="400">
1. Whenever there is disagreement, focus on the intended outcome of the decision and make sure the team
is aware of your reasoning.
    - "While database X is better, I want us to standardize on one stack so that it's easier to maintain."
1. If someone disagrees with a reversible decision, set a date to revisit that decision with the team.
Ideally you also have metrics to define the success of that decision.
    - "I understand your concerns. Let's revisit this in a month and see where we stand."
    - "We're tracking X now, let's revisit next quarter if it improves with these changes."
1. If someone disagrees with an irreversible decision, give them the opportunity to present their case.
Regardless, everyone should be aware the decision is ultimately yours and the team needs
to [disagree and commit wholly](https://tomtunguz.com/disagree-and-commit/) to the decision made. In my experience, even dissenters will commit to the decision if they feel heard and appreciate you were decisive.
1. Document your decisions so that you can refer to why they were made and the tradeoffs your team faced.

## Ticket and PR process

1. Set contributing guidelines for the team.
1. Prioritize PRs to unblock tickets.
1. Avoid merge rot. I suggest using one of your standups to review the PR backlog and call out PRs more than 2 days old.
1. Automate opinions like style with linting or code formatters.

## Meeting

1. Avoid [shitty brainstorm sessions](https://erikbern.com/2017/12/29/toxic-meeting-culture.html) by encouraging proposals written before having a meeting. Whoever wants the meeting should write the proposal.
    > "Don’t defer decisions to meetings. Make decisions on the spot, communicate it over long-form writing, and use the meeting to discuss it." – Erik Bernhardsson
1. Favor long-form writing for proposals over presentations. Writing forces the author to think about the details and tradeoffs. I find it very helpul to create tech spec templates.
1. Dedicate time during meetings for reading and discussing proposals. This ensures everyone is on the same page and avoids the "I didn't have time to read it" excuse. It will also make sure it's the latest thing in everyone's memory buffer.
1. Avoid recurring meetings with no agenda. If you're invited to one, ask for an agenda.
1. Encourage Amazon-style ["6 pagers" and "2 pagers"](https://medium.com/@inowland/using-6-page-and-2-page-documents-to-make-organizational-decisions-3216badde909).
1. Always end a meeting with actions, owners and timing, so it's clear what next steps are.

<img src="images/write-like-an-amazonian.jpg" width="400">

## Hiring

> If you can 'hire tough,' you can 'manage easy' – Sue Tetzlaff, The Employee Experience

Hiring is the most important decision a manager makes. It's also the most difficult. It's a skill that can be learned and improved upon.

What to look for in engineers:

1. **Owner**. Takes ownership of a problem even when it's not 100% their responsibility; understands the why.
    1. "Tell me about a time when you took on something significant outside of your area of responsibility. Why was it important? What was the outcome?"
    1. "Tell me about a time when you made a hard decision to sacrifice short term gain for a longer term goal."
    1. "What's a major tradeoff that you had to make, and how did you make it?"
1. **Handles ambiguity**
    1. "Can you tell me about a time when you had to solve an ambitious problem? Why was the problem important?"
    1. "Can you tell me about a time when you had to make a decision without complete information? What was the situation? What risks did you take? Why did you make the decision you made?"
1. **Team player**. Takes feedback well.
    1. "Tell me about a time when you changed your mind about something. What was your thought process behind it?"
    1. "Tell me about a time when you disagreed with your manager. What did you learn from this situation?"
    1. "Tell me about a time when you needed the cooperation of a peer who was resistant. What did you do? What was the outcome?"
    1. "Give me an example of a tough or critical piece of feedback you received. What was it and what did you do about it?"
    1. "If I were to speak with your peers what positive or negative feedback would they have of you?"
1. **Communicator**. Can articulate ideas at different levels.
    1. "What makes a great engineer?"
    1. "Describe to me something you know well."
    1. "You mentioned X in your resume. Explain it to me as if I've never come across it?"
1. **Teacher**. Enjoys growing other engineers. Especially important for senior-level engineers.
    1. "Tell me of a time where you helped someone in your team grow."
1. **Deep diver**. Digs a level deeper to understand what's happening under the hood.
    1. "Tell me about a time you were trying to understand a problem on your team and you had to go down several layers to figure it out."
    1. If you had two weeks, heads down, to learn something new, what's at the top of your list?
1. **Simplifier**. Simplifies problems instead of just hacks at things and adds tech debt. Does the person have a build vs. buy mentality.
    1. "Tell me a about a complex problem that you solved with a simple solution."
1. **Missionary**. Interested in company's mission or technology.
    1. "Explain to me what your current company does and why it's important."
    1. "What interests you working at [COMPANY]?"

What to watch out for:

1. **Short tenure at companies**. If a candidate typically stays at companies for less than a year, ask them why. There might be perfectly valid reasons or it might indicate a pattern that the person is difficult to work with.
    1. Why did you only work at X for less than 1 year?
1. **Menu of technologies**. Resumes that just list technologies used instead of problems solved may indicate person may not be thinking big picture. Also a typical trait of junior engineers.
1. **Lack of curiosity**. Does the person ask questions about the company, product or team?
1. **No career progression**. Does the person have a clear career progression? If not, why?
1. **Role description**. Is this person just describing their job or are they sharing the actual impact they had at the company?
1. **Lack of quantifiable metrics**. Does the person have metrics to show the impact of their work?

Questions to ask yourself about the candidate:

1. **Are they better than the average person on the team?** If not, you're not raising the bar.
2. **Do you admire this person and want to learn from them?** If not, you're not hiring people better than you.

### References

You should take the opportunity to do reference calls. They can tell you a lot about the candidate. Here are some tips: <https://gist.github.com/ksindi/bbade71640bb62c4547348c3bb355739>.

## Onboarding

Having a good onboarding process is crucial to the success of your team. It ensures new members are contributing as early as possible and are assimilated into your processes and culture.

An onboarding process is successful if your new team member can contribute a bug fix on their first day of joining.

Onboarding material:

1. Team mission
    1. How is your team moving the needle for the customer?
1. Team members
    1. Include: name, role/title, email, slack username, github username
1. Repositories and services
    1. Include system diagrams
1. How to communicate within the team
    1. Slack channels
    1. Keeping yourself informed
    1. Communication protocols during and outside of business hours
1. Documentation
    1. Code contributing guidelines
    1. PR review process
    1. Ticketing process
    1. Glossary of terms
    1. Releasing code
    1. How tos (e.g. migrate database, add secrets)
1. Getting started
    1. Installation instructions (e.g. Docker, postgres).
    1. A checklist of all accesses expected (e.g. AWS, PagerDuty)
    1. Running your apps locally
    1. Deploying your first bug fix (tip: label some tickets as "good first bug")
1. New hire meetings. Who should your new team member meet with?

## Managing up

1. Make sure you and your manager are on the same page by sharing a document listing your project priorities, timelines and confidence levels.
1. Your manager also needs to manage up. Proactively update your manager on project timeline changes with brief answers to the following questions:
    1. What is the new timeline?
    1. Why did the timeline change?
    1. How confident are you with the new timeline?
1. Nobody cares for blame or excuses. Own mistakes and document corrective actions you will take to mitigate them going forward.

## Announcing change

1. Examples of change: promotions, reshuffles, restructuring.
1. Acknowledge the difficulty or opportunity of the change.
1. Appeal to emotions by using narrative to explain the why.
    1. Why is this change important now for the company?
    1. Who does this change affect?
1. Appeal to logic by using facts. What metrics will this change achieve?
1. Socialize the change to get buy in. Start with the people who it affects the most.

## Standups

I like to organize standups where on-call engineers lead during Monday, Wednesday and Friday. This gives them a chance to practice public speaking. On Thursdays, the Engineering Manager (EM) or Product Manger (PM) lead the standup and talk about priorities and strategy.

#### Monday (on-call leads)

1. Before Meeting (on-call): Make a list of notable alerts from on-call.
2. Weekend highlights (popcorn style)
3. Review notable monitoring info.
4. Review on-call tickets.
5. Call out any major/risky deployments planned for the week.
6. Priorities: What epics are people working on this week?
7. Review ticket board

#### Wednesday (on-call leads)

1. Review PR Backlog and GitHub dependabot issues
2. Review ticket board

#### Thursday (EM or PM leads)

The Engineering Manager or Product Manager leads the standup to discuss priorities and strategy. This is a good time to discuss any changes to the roadmap. The goal is to make sure everyone is on the same page and aligned.

1. Review priorities for next couple of weeks.
2. Review roadmap and any changes.
3. Discuss feedback from customers or sales.
4. Share any interesting metrics.

#### Friday (on-call leads)

1. Small popcorn retro where everyone talks about highlights and lowlights. What went well? What didn't go well? Could we do anything to make this better (If so, add tickets!)?
2. Demo any new features or improvements.
3. Review ticket board.

## Further reading

Here are some great resources on management:

1. [Manager's Path](https://www.amazon.com/Managers-Path-Leaders-Navigating-Growth/dp/1491973897/): Excellent guide for all levels of management.
1. [97 Things Every Engineering Manager Should Know](https://www.amazon.com/Things-Every-Engineering-Manager-Should-ebook/dp/B081TPX6NS): Collection of management tips from various practitioners.
1. [5 questions every Engineering Manager should be asking themselves](https://www.getclockwise.com/blog/5-questions-every-engineering-manager-should-be-asking-themselves)
1. [The Pendulum or the Ladder](https://charity.wtf/2019/01/04/engineering-management-the-pendulum-or-the-ladder/): On the challenges of being a manager who wants to stay technical.
1. [What You Do Is Who You Are](https://www.amazon.com/What-You-Do-Who-Are/dp/0062871331): Why company culture matters and how to establish one.
1. [How to Hire Smarter than the Market](https://erikbern.com/2020/01/13/how-to-hire-smarter-than-the-market-a-toy-model.html): Berkson's paradox and engineering hiring.
1. [LifeLabs Learning](https://lifelabslearning.com). Great workshop for new and experienced managers. I learned a lot from it on feedback, coaching and 1-1s.
1. [How Software Engineers Can Help Interview Their Future Managers](https://blog.newrelic.com/technology/hiring-software-engineering-managers-interview): A list of questions for engineers to ask managers.
1. [7 Tips for Better Executive Communication](https://medium.com/@joefletcher/7-tips-for-better-communication-32cbe84c8ddf): Tips on how to communicate effectively.
1. [Toxic Meeting Culture](https://erikbern.com/2017/12/29/toxic-meeting-culture.html): How to avoid meeting antipatterns.
