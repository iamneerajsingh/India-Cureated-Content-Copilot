# MS-4019 · CUR_IND2 "Elevate" · A Day with Project Nexus
### Curated demo pack: agentic day in the life, built around scheduled prompts

| | |
|---|---|
| **Course** | MS-4019: Transform your everyday business processes with agents |
| **Preset** | CUR_IND2 – Elevate (India preset curation) |
| **Format** | 1-day instructor-led training (overlay on the official course, which isn't replaced) |
| **Promoted agents** | Personal News Digest · Plan My Day · Project Delta Digest · AI Learning Advisor |
| **Supporting agents** | Analyst · Researcher · Prompt Coach · Idea Coach · Writing Coach · SharePoint agent |
| **Adoption goal** | Every learner leaves with **at least 3 scheduled prompts (at least 2 daily)** → Agent DAU/MAU and PRU |
| **Version** | v1.0 draft, October 2026 · Owner: Neeraj Kumar · Contributors: Aharna Moulick, Payal Guruprasad |

> **Validate before delivery:** agent and template names, menu labels and scheduling options change often. Do a dry run in your delivery tenant and update the labels in this pack where they differ.

---

## Contents
1. [Why this story](#why-this-story)
2. [The day at a glance](#the-day-at-a-glance)
3. [MS-4019 topic coverage map](#ms-4019-topic-coverage-map)
4. [Modular delivery: drop any section](#modular-delivery-drop-any-section)
5. [Environment setup and pre-delivery checklist](#environment-setup-and-pre-delivery-checklist)
6. [How to schedule a prompt](#how-to-schedule-a-prompt)
7. Sections 0–9: demo walkthroughs
8. [Section 10 – Scheduled prompt pack](#section-10--scheduled-prompt-pack)
9. [Pack contents](#pack-contents)

---

## Why this story
Learners don't keep using an agent because the demo was impressive. They keep using it because it **earns a recurring moment in their workday**. This pack teaches every MS-4019 topic through one employee's day and turns each moment into a **scheduled prompt**:

> **Training → Try the agent → See personal value → Schedule it → Agent comes back daily → Measurable adoption (DAU/MAU, PRU)**

**Story line:**
> *Arjun starts his day overwhelmed by information. By the end of the day, his agents have helped him **understand** what matters, **prioritise** his time, **execute** on his project, and **grow** the skills he needs next. Tomorrow, they're already waiting for him.*

---

## The day at a glance
| Time | Arjun's question | Agent | Outcome | MS-4019 module | Scheduled? |
|---|---|---|---|---|---|
| 8:30 AM | *What changed that matters to me?* | **Personal News Digest** | Understand | M1 | ✅ Daily |
| 9:00 AM | *What matters today?* | **Plan My Day** (+ Prompt Coach) | Prioritize | M1, M2 | ✅ Daily ×2 |
| 10:00 AM | *Where does my project really stand?* | **Project Delta Digest** (built in Agent Builder) | Execute | M3 | ✅ Daily + Weekly |
| 11:30 AM | *Why is adoption dropping?* | Analyst | Investigate | M2 (lab) | Optional |
| 1:30 PM | *What should we do next?* | Researcher + Idea Coach + Writing Coach | Recommend | M2 (labs) | Optional |
| 3:00 PM | *Can the team serve themselves?* | SharePoint agent + share in Teams | Scale | M3, M4 (lab) | n/a |
| 4:00 PM | *What do I need to learn next?* | **AI Learning Advisor** | Grow | M6 | ✅ Weekly |
| 5:30 PM | *What's set up for tomorrow?* | Wrap my day + "Schedule 3" | Sustain | M1, M4, M5 | ✅ Learners schedule 3 |
| Next day | *(nothing to ask: digests arrive on their own)* | Scheduled prompts | **Adoption** | n/a | n/a |

### Suggested timing (1-day ILT)
| Block | Content | Time |
|---|---|---|
| Morning | Module 1 (official) + Section 0 + Section 1 + Section 2 | ~2 h |
| Late morning | Module 2 (official) + Section 4 (Analyst lab) + Section 5 (Researcher and choice labs) | ~2 h |
| Afternoon | Module 3 (official) + Section 3 (Delta Digest = Copilot Chat agent lab) + Section 6 (SharePoint lab) | ~2 h |
| Late afternoon | Module 4 (official) + Section 7 + Section 8 + Section 9 | ~1.5 h |

> The table above shows the **story** order. In delivery, follow the **official module order**: each section sits inside its module, and Arjun's clock time is the narrative device.

---

## MS-4019 topic coverage map
| MS-4019 module / topic | Covered in |
|---|---|
| **M1** What are agents? (prebuilt / template / custom) | S1 |
| **M1** Who can create and use agents? | S1, S7 |
| **M1** Benefits of using agents | S2 |
| **M1** Enhance collaboration using agents | S6 |
| **M1** IT governance controls | S8 |
| **M2** Analyst agent + Exercise 1 | S4 |
| **M2** Researcher agent + Exercise 2 | S5 |
| **M2** Prompt Coach | S2 |
| **M2** Idea Coach / Writing Coach | S5 |
| **M2** Exercise 3: agent of your choice | S5 (pick a coach or curated agent) |
| **M3** Tools used to create agents | S3 |
| **M3** Components of an agent | S3 |
| **M3** Create an agent in Copilot Chat (Describe / Configure) + Exercise 1 | S3 |
| **M3** Create an agent in SharePoint + Exercise 2 | S6 |
| **M3** Test and edit your agents | S3 |
| **M3** Manage your agents | S6, S8 |
| **M4** Share an agent with other users / in Teams | S6 |
| **M4** Interact with agents (permissions, chat history) | S6, S8 |
| **M5** Learning path review | S8 |
| **M6** India preset: templates + scheduled prompts | S1, S2, S3, S7, S8, S10 |

---

## Modular delivery: drop any section
Every section is self-contained and has an **"If you drop this section"** note telling you how to keep the story going.

| Section | Can drop? | Minimum to keep if dropped |
|---|---|---|
| S0 Story setup | ⚠️ Not recommended | One-line persona intro |
| S1 Personal News Digest | ✅ | Explain agent types using Plan My Day |
| S2 Plan My Day | ✅ | Show Prompt Coach in S3; move "Wrap my day" to S8 |
| S3 Project Delta Digest | ✅ | Use the official lab's own agent for the Module 3 build |
| S4 Analyst | ✅ | Run the official lab as self-paced |
| S5 Researcher + coaches | ✅ | Run the official labs as self-paced |
| S6 SharePoint agent | ✅ | Keep one slide on sharing and permissions |
| S7 AI Learning Advisor | ✅ | Mention it as an optional schedule in S8 |
| S8 Wrap + Schedule 3 | ❌ **Never drop** | This is where adoption happens |
| S9 Close + follow-up | ⚠️ Keep the follow-up | Day 2 / Day 7 nudges |

**Common short versions:**
- **Core 4 only** (customer has the curated templates): S0 → S1 → S2 → S3 → S7 → S8
- **No templates available**: S0 → S2 (in Copilot Chat) → S4 → S5 → S6 → S8 (schedule Copilot Chat prompts)
- **Build-focused audience**: S0 → S3 → S6 → S7 → S8

---

## Environment setup and pre-delivery checklist
Full checklist: `01_Trainer-Guide/Pre-Delivery-Checklist.md`

| Check | Who | Why |
|---|---|---|
| Learners have a **Microsoft 365 Copilot** licence | CSM → customer | Work-grounded agents, Researcher/Analyst, scheduling |
| **Agents** tab enabled in Copilot | Customer admin | Without it there's no agent experience |
| Templates enabled: Personal News Digest, Plan My Day, Project Delta Digest, AI Learning Advisor | Customer admin | Core of this preset |
| **Agent Builder** (create agent) allowed for users | Customer admin | Module 3 build |
| SharePoint agents allowed; learners have a site with Edit rights | Customer admin | Module 3 SharePoint lab |
| Web grounding allowed (for Researcher and AI Learning Advisor) | Customer admin | External sources |
| **Scheduled prompts** available to users | Trainer dry run | The adoption mechanic |
| Persona and agents captured in the AER / pre-delivery instructions | CSC | Lets the MTT prepare quickly |
| Trainer has uploaded `04_Sample-Data/Project-Nexus` to a demo SharePoint folder | MTT | Delta Digest and SharePoint demos |

**In class:** ask *"Can you see this agent?"* before each section. Most can → hands-on. None can → demo only, or use the fallback. A mix → trainer judgement.

---

## How to schedule a prompt
> Labels and menu positions vary by release and app (Copilot app, Teams, Outlook, m365copilot.com). Confirm in your tenant during the dry run.

1. In Microsoft 365 Copilot Chat (in the agent's conversation, or in Copilot Chat itself), **run the prompt once** and check the output is useful.
2. Hover over **your prompt** → select **⋯ / More options** → **Schedule this prompt** (clock icon).
3. Set:
   - **Name:** short and clear, e.g. `Start my day`
   - **Frequency:** daily, weekly, etc. (weekdays where offered)
   - **Time:** the moment in your day it should arrive
   - **Notifications / end date:** if offered
4. **Save**. The response arrives in the Copilot conversation at the scheduled time, with a notification.
5. **Manage:** open the **Scheduled prompts** list (Copilot settings / ⋯ menu) to edit, pause or delete schedules.

**Tips for prompts that schedule well**
- Write the prompt so it **stands alone**. Include role, project and timeframe (*"last 24 hours"*, *"this week"*).
- Ask for a **fixed format** (table, top 5, TL;DR) so it can be scanned in 2 minutes.
- Use relative time words (*today*, *since yesterday*), not fixed dates.
- If scheduling inside a specific agent isn't supported in your tenant, schedule the same prompt from Copilot Chat and add `@<agent name>` or the agent's grounding sources. **Validate this during the dry run.**

---

## Section 0 – Story setup: meet Arjun (5 min)

> **Where it runs:** Opening of the curated day, right after the Module 1 introduction slide. Keep it to one slide and a short story; Arjun comes back in every module.

### Overview
The story ties all of MS-4019 together. Arjun's day goes from **Understand → Prioritize → Execute → Grow**. Each agent fixes one real problem in his day. Each one ends with a **scheduled prompt**, so that tomorrow the agent comes to Arjun before he has to ask.

### Persona
| | |
|---|---|
| **Name** | Arjun Mehta |
| **Role** | Program Manager, Contoso India (IT services, Bengaluru) |
| **Project** | **Project Nexus**: Contoso's internal rollout of Microsoft 365 Copilot and agents to 2,000 employees across four business units (Delivery, Sales, Finance, HR) |
| **Reports to** | Priya Nair, VP Transformation |
| **Team** | 6 workstream leads, 2 change champions, 1 analyst |
| **A typical day** | 9 meetings, about 200 emails and Teams messages, 3 status reports, 1 steering committee each week |

> Project Nexus is the same internal initiative used in the official MS-4019 Analyst lab. That lets the story lead straight into the official lab exercises.

### The business scenario
On Monday Arjun has a steering committee with Priya. She wants three things:
1. A clear view of where Nexus stands.
2. An explanation of why adoption in one business unit is falling.
3. A recommendation for the next phase, which will use **agents**.

Arjun has one day, too much information and no time to chase people.

### Pain points (the opening hook)
| # | Pain point | Arjun's question | Agent that answers it |
|---|---|---|---|
| 1 | Information overload | *"What changed that matters to me?"* | Personal News Digest |
| 2 | Too many priorities competing | *"What actually matters today?"* | Plan My Day |
| 3 | Chasing status across teams | *"Where does my project really stand?"* | Project Delta Digest |
| 4 | Data he can't interpret quickly | *"Why is adoption dropping?"* | Analyst |
| 5 | Needing a researched recommendation | *"What should we do next?"* | Researcher + Idea Coach + Writing Coach |
| 6 | The same team questions every day | *"Can the team serve themselves?"* | SharePoint agent |
| 7 | A skill gap the project exposed | *"What do I need to learn next?"* | AI Learning Advisor |

### Trainer talk track
> "Meet Arjun. He's not short of tools, he's short of attention. Today we'll watch him hand one problem at a time to an agent. Then he does the thing that matters most: he **schedules** the agent, so tomorrow it's waiting for him. By the end of today you'll do the same for your own work."

### Learner action
Ask each learner to write down **one recurring moment in their own week**, like Arjun's 8:30 news check. Say they'll schedule an agent for it before they leave.


---

## Section 1 – 8:30 AM · Personal News Digest · UNDERSTAND (15 min)

> **MS-4019 topics covered:** Module 1, *What are agents?* (prebuilt agents vs. agent templates vs. custom agents) and *Who can create and use agents?*

### Overview
Personal News Digest is an **agent template**, a declarative agent grounded in your **mailbox, Teams chats and SharePoint**. It sorts through company broadcast messages (leadership mail, announcement channels, intranet news) and gives you a short digest of what matters to your role and location. It leaves out peer and project chatter.

### Business scenario
It's 8:30 and Arjun opens his laptop. Overnight there's a CEO note on AI, a policy change on data handling, an HR deadline, an IT outage notice and 40 newsletters. Somewhere in there are the two things that will change his steering committee message.

### Pain points
- Company-wide updates get lost among broadcast mail, Teams posts and the intranet.
- Required actions (policies, trainings, deadlines) get missed.
- Checking every source takes 30–45 minutes every morning.
- What matters to a Program Manager in Bengaluru isn't what matters to everyone.

### Business benefits
- Replaces a 30–45 minute morning scan with a 3-minute read.
- Fewer missed policy, training and compliance deadlines.
- Faster alignment with leadership priorities.
- **Adoption:** a daily scheduled digest means a daily active user.

### Learning objectives
Learners will be able to:
1. Explain the difference between a **prebuilt agent**, an **agent template** and a **custom agent**.
2. Add the Personal News Digest template from the Agent Store or Agent Builder template gallery.
3. Write a role-aware **Goal → Context → Source → Expectations** prompt.
4. **Schedule** a daily briefing prompt.

### Environment setup
| Item | Requirement |
|---|---|
| Licence | Microsoft 365 Copilot (full licence; Copilot Chat alone isn't enough for agents grounded in work data) |
| Agents tab | Enabled by the tenant admin |
| Template | Personal News Digest visible in **Agents → Get agents / Agent Store** or in the **Agent Builder → template gallery** |
| Data | Your own mailbox and Teams; company announcements in the last 7–30 days |
| Trainer check | Ask *"Can you see Personal News Digest?"* If most learners can, do it hands-on. If none can, demo it only. Otherwise use trainer judgement. |
| Fallback | Use the **Fallback prompt** below in Copilot Chat (Work mode), or paste the sample announcements from `04_Sample-Data/Nexus_Sample_Announcements.md` into the chat. |

### Demo walkthrough
1. Open **Microsoft 365 Copilot Chat** → **Agents** → **Get agents / Agent Store** (or **New agent → templates**).
2. Search for **Personal News Digest** → **Add** (or **Create from template**, then **Create**).
3. Open the agent and point out the **conversation starters**. *Teaching point: this is a template, so Microsoft has already written the instructions and knowledge settings.*
4. Run **Prompt 1A (simple)**, then **Prompt 1B (structured)**.
5. Run the **follow-up**.
6. **Schedule it** (see below).

**Prompt 1A – simple (conversation-starter style)**
```
What are the top 5 company-wide announcements from the past week, tagged Critical, Important, or FYI? Include the sender and date for each.
```

**Prompt 1B – structured (Goal → Context → Source → Expectations)**
```
Goal: Give me a personalised morning briefing of what changed that matters to my work.
Context: I am a Program Manager leading Project Nexus, our internal rollout of Microsoft 365 Copilot and agents. I care about leadership direction on AI, policy changes that affect data or tools, training deadlines, and anything that affects employee adoption.
Source: Use company-wide announcements from my email, Teams announcement channels, and SharePoint news from the last 24 hours (or since my last working day).
Expectations: Show the 5 most relevant items only, as a table:
Priority (Critical / Important / FYI) | Headline | What happened | Why it matters to me | Action and deadline
End with one line: "The one thing I should mention in today's steering committee prep."
```

**Follow-up (makes it agentic)**
```
Which two of these items should change how I position Project Nexus to leadership this week? Explain why in two lines each.
```

**Extra prompts from the template's test set (use any)**
| Scenario | Prompt |
|---|---|
| Back from leave | `I just returned to the office. Catch me up on critical org news since the start of my time off.` |
| Policy action | `List recent policy changes that require employee action, including deadlines and links to the official policy.` |
| Leadership voice | `Surface messages and newsletters from the CEO, C-suite, or skip-levels in the past 30 days — include key quotes.` |
| Manager actions | `What announcements made by my manager in the past 14 days should my team pay attention to? Summarize key actions my team should take.` |
| Operational alerts | `Are there active incidents or planned outages I should know about?` |

### Schedule it 🔁
| Field | Value |
|---|---|
| Name | `Morning briefing – what changed` |
| Prompt | Prompt 1B |
| Frequency | Daily (weekdays where offered) |
| Time | 8:30 AM |
| Why | The habit is formed: Arjun's day starts with the digest already waiting. |

### Teaching moment
> *Search asks: "What happened?" Personal News Digest asks: "What happened **that matters to me**?"*

### Bridge to the next section
> "Arjun now knows what's changing **outside** his project. But his calendar, inbox and to-do list are still fighting for his attention. Next problem: **what actually matters today?**"

### If you drop this section
Open Section 2 with: *"Arjun starts his morning overwhelmed…"* Cover the **agent types** (Module 1) using Plan My Day instead.


---

## Section 2 – 9:00 AM · Plan My Day (+ Prompt Coach) · PRIORITIZE (15 min)

> **MS-4019 topics covered:** Module 1, *Explore the benefits of using agents* (task simplification, a personalised experience); Module 2, *Examine the Prompt Coach agent*.

### Overview
Plan My Day brings together your **meetings, tasks, emails and documents** in one time-aware briefing. It also re-plans your day when something changes. Prompt Coach is used here to improve Arjun's prompt **before** he schedules it, because a scheduled prompt is only as good as the prompt itself.

### Business scenario
Arjun has 9 meetings, a steering committee deck to draft, a stuck workstream and 30 minutes set aside to learn. He doesn't need another to-do list. He needs **prioritisation**. At 9:40 Priya asks for a 90-minute deep-dive on the Finance BU adoption drop, and the plan has to change.

### Pain points
- Calendar, inbox, Teams and Planner are all separate views; there's no single plan.
- Urgent work pushes out important work.
- Re-planning by hand after every interruption.
- Walking into meetings unprepared.

### Business benefits
- Less time spent planning each day (about 20 minutes saved).
- Protected focus time for top outcomes.
- Better meeting preparation.
- **Adoption:** two scheduled touchpoints each day (start and end) give strong daily usage.

### Learning objectives
Learners will be able to:
1. Use Plan My Day to build a time-blocked plan from their own work data.
2. **Re-plan** with a follow-up prompt when something changes (agentic behaviour).
3. Use **Prompt Coach** to improve a prompt.
4. **Schedule** a start-of-day and an end-of-day prompt.

### Environment setup
| Item | Requirement |
|---|---|
| Licence | Microsoft 365 Copilot |
| Agent | **Plan My Day**: first-party agent or template, depending on the tenant. Check **Agents → All agents / Agent Store**. |
| Prompt Coach | Prebuilt agent in Copilot Chat |
| Data | The learner's real calendar for today (at least 2–3 meetings works best), Outlook, Teams, Planner or To Do |
| Fallback | Run the same prompts in Copilot Chat (Work mode). The planning still works; you lose the agent's built-in structure. |

### Demo walkthrough
1. Open **Prompt Coach**. Paste Arjun's weak prompt:
   ```
   plan my day
   ```
   Then ask:
   ```
   Improve this prompt so an agent can build a realistic, time-blocked plan for a Program Manager. Use Goal, Context, Source, Expectations.
   ```
   *Teaching point: the coach adds context, sources and the output format. Compare the result with Prompt 2B.*
2. Open **Plan My Day** and run **Prompt 2A**, then **Prompt 2B**.
3. **Plot twist:** run **Prompt 2C** (the urgent request).
4. Show **Meeting prep** (Prompt 2D) for the next meeting on the calendar.
5. **Schedule it**, two prompts (see below).

**Prompt 2A – simple**
```
Prep my day
```

**Prompt 2B – structured**
```
Goal: Help me create a realistic, focused plan for today.
Context: I am a Program Manager leading Project Nexus. Today I must prepare for Monday's steering committee, unblock a delayed workstream, attend my scheduled meetings, handle urgent messages, and keep 30 minutes for learning. I want to avoid unnecessary context switching.
Source: Use my calendar, recent emails and Teams messages, tasks, and documents I am working on.
Expectations: Give me a time-blocked plan as a table:
Time | Activity | Priority (High/Med/Low) | Why this time makes sense
Then list my top 3 outcomes for today and anything I can safely postpone or delegate.
```

**Prompt 2C – plot twist (agentic re-plan)**
```
An urgent request just came in from my VP: a 90-minute deep-dive on why Finance adoption is dropping. Reorganise my day while protecting my top 3 outcomes. Tell me what moved and what I should decline or delegate.
```

**Prompt 2D – meeting prep**
```
Prep me for my next meeting: attendees, purpose, related documents, open action items, and the one question I should ask.
```

**Extra prompts from the template's test set**
| Scenario | Prompt |
|---|---|
| What did I miss | `What did I miss?` |
| Pending decisions | `Do I have any pending decisions or approvals where others are waiting on me?` |
| Meeting load | `How heavy is my meeting load today?` |
| Delegation | `What should I delegate today?` |
| Weekly look-ahead | `Give me a weekly look ahead` |

### Schedule it 🔁 (two schedules)
| Name | Prompt | Frequency | Time |
|---|---|---|---|
| `Start my day` | Prompt 2B | Daily (weekdays) | 9:00 AM |
| `Wrap my day` | `Wrap my day: summarise what I completed, what slipped, decisions I owe, and preview tomorrow's top 3 priorities.` | Daily (weekdays) | 6:00 PM |
| `Weekly look-ahead` *(optional)* | `Give me a weekly look ahead with milestones, meeting load, and top priorities.` | Weekly, Monday | 8:45 AM |

### Teaching moment
> *The first prompt shows **planning**. The plot twist shows something more valuable: **agentic experiences earn their place when circumstances change.***

### Bridge to the next section
> "Arjun's top outcome today is a clear Nexus status for the steering committee. But status lives in six people's heads, three trackers and a hundred messages. Instead of chasing people, he'll **build an agent** that does the chasing."

### If you drop this section
Cover Prompt Coach briefly in Section 3, using it to improve the Delta Digest prompt before scheduling. Move the "Wrap my day" schedule into Section 8.


---

## Section 3 – 10:00 AM · Project Delta Digest (built in Agent Builder) · EXECUTE (25 min)

> **MS-4019 topics covered:** Module 3, *Examine the tools used to create agents*, *Explore the components of an agent*, *Create an agent in Copilot Chat (Describe and Configure)*, *Test and edit your agents*; **Lab:** *Exercise – Create a Microsoft 365 Copilot Chat agent* (use this agent as the learner's build).

### Overview
Project Delta Digest is an **agent template**. It produces a structured, repeatable **daily or weekly digest of project changes**: shipped or completed work, work in progress, status changes, blockers and risks. In production it reads your project management tool through a **Copilot connector**. In class we ground it on the **Project Nexus SharePoint folder** (sample data in this pack) or the learner's own project files.

This is the **build** moment of the course. Arjun creates the agent from a template, looks at each **component**, tests it, edits it and then schedules it.

### Business scenario
Every Friday Arjun spends about 2 hours collecting updates from six workstream leads for a status report that's out of date by Monday. Risks show up late. Leadership hears about blockers after they've already slipped a milestone.

### Pain points
- Manual status reporting takes up PM and team time.
- Little visibility into **what changed** since the last report.
- Risks and blockers are found too late.
- A different report format every week makes leadership reviews slower.

### Business benefits
- Status reporting goes from about 2 hours to about 10 minutes of review.
- Risks surface early, with owner and days stuck.
- A consistent leadership-ready format every week.
- **Adoption:** a daily digest plus a weekly leadership recap is a recurring, business-critical use.

### Learning objectives
Learners will be able to:
1. Create an agent from a **template** in Agent Builder.
2. Identify and edit the **components** of an agent: name, icon, description, instructions, knowledge, capabilities and starter prompts.
3. Use the **Describe** and **Configure** tabs.
4. **Test** an agent for accuracy, consistency and edge cases, then **edit** its instructions.
5. **Schedule** a daily digest and a weekly leadership recap.

### Environment setup
| Item | Requirement |
|---|---|
| Licence | Microsoft 365 Copilot (needed to ground on SharePoint/OneDrive work content) |
| Agent Builder | **Copilot Chat → New agent / Create agent** available (not blocked by the admin) |
| Template | **Project Delta Digest** in the Agent Builder template gallery. **If it's not listed**, build it from scratch using `05_Agent-Instructions/Project-Delta-Digest_Instructions.md`. |
| Knowledge | Upload the `04_Sample-Data/Project-Nexus` files to a SharePoint folder or OneDrive folder the learner owns, **or** use the learner's own project folder |
| Connector *(optional, production)* | A Copilot connector to Azure DevOps, Jira or another PM tool, configured by an admin. Not needed for class. |
| Trainer prep | Pre-build one copy of the agent the day before, in case the template or tenant is slow in class |

### Demo walkthrough – build
1. In Copilot Chat, select **New agent** (or **Create agent**) → open the **template gallery** → select **Project Delta Digest**.
2. On the **Describe** tab, show that the template has pre-filled the agent. Refine it in natural language:
   ```
   Tailor this agent for the Project Nexus programme. Workstreams are Licensing & Readiness, Training & Champions, Agents Pilot, Change Communications, Analytics, and Governance. Group every digest by workstream and include owner names.
   ```
3. Switch to **Configure**. Walk through each **component** (this is the Module 3 *components* topic):
   | Component | What to show |
   |---|---|
   | Name / icon | `Nexus Delta Digest` |
   | Description | Short and precise; it appears in the agent catalogue |
   | Instructions | The template's structured instructions (sections, output contract, guardrails). Add one line: `Always flag items with no update for more than 5 working days as STALE.` |
   | Knowledge | Add the **Project Nexus** SharePoint folder or OneDrive files. *Teaching point: the agent only sees what the user can access.* |
   | Capabilities | Leave the defaults; mention code interpreter and image generation where available |
   | Starter prompts | Keep "Daily digest", "Current risks" and "Leadership recap" |
4. Select **Create** and open the agent.

### Demo walkthrough – test and edit (Module 3 *Test and edit your agents*)
Run these in order and point out the test dimension each one covers:

**Prompt 3A – daily digest (accuracy)**
```
Give me today's digest for Project Nexus — TL;DR, what was completed, what is in progress, blockers, and risks from the last 24 hours. Cite the source for each item.
```
**Prompt 3B – blockers (consistency: rephrase and compare)**
```
What's blocking Project Nexus? List active blockers, who owns them, and how many days they've been stuck. Flag anything idle for more than 5 days.
```
**Prompt 3C – escalate vs watch (judgement)**
```
What should I escalate now vs watch for another week? Give two lists with risk score (1–5), owner, rationale, and source.
```
**Prompt 3D – edge case (guardrails)**
```
What is the budget variance for the Sales workstream?
```
*Expected: the agent says it has no Sales workstream or budget data and does **not** make up numbers. If it guesses, **edit the instructions** (`Never invent figures; if data is not in the knowledge sources, say so.`), update the agent and test again.*

**Prompt 3E – leadership recap (format)**
```
Give me a leadership-ready weekly digest for Project Nexus — TL;DR, milestones, top 3 risks, momentum signals, and the single decision I need from leadership. One page, no item-level tables.
```

**Prompt 3F – proactive (agentic)**
```
Tell me what I should be asking right now — 3 to 5 questions, each addressed to a specific owner, grounded in real blockers and stale items.
```

**Extra prompts from the template's test set**
| Scenario | Prompt |
|---|---|
| This week's wins | `Show me everything completed this week, grouped by milestone, with dates and links to the source items.` |
| Stakeholder update | `Draft a stakeholder update I can send to my team. Include TL;DR, milestones, top risks, and asks.` |
| 10-minute brief | `If I had to brief leadership unexpectedly in 10 minutes on Project Nexus, what would matter?` |
| Meeting recap | `Summarize my most recent project meeting as: decision, rationale, next step. Format in a table.` |

### Schedule it 🔁 (two schedules)
| Name | Prompt | Frequency | Time |
|---|---|---|---|
| `Nexus daily delta` | Prompt 3A | Daily (weekdays) | 10:00 AM |
| `Nexus leadership recap` | Prompt 3E | Weekly, Friday | 4:00 PM |

### Learner hands-on (MS-4019 Lab: Create a Copilot Chat agent)
Learners build **their own** Delta Digest for a real project of theirs, or use the Nexus sample files. They then run at least two test prompts, make one instruction edit and **schedule** the daily digest.

### Teaching moment
> *"You didn't write an agent from a blank page. You **started from a template, tailored it, tested it and scheduled it**. That's the everyday business-user way to build agents."*

### Bridge to the next section
> "The first digest shows why Priya is worried: **Finance weekly active users are down three weeks running**, and two Finance items (workshops and template enablement) are **blocked**. Arjun has the usage and survey data, but no time to dig through a spreadsheet before his 90-minute deep-dive. Time for the **Analyst**."

### If you drop this section
Learners still need an agent to build for the Module 3 lab. Use the official lab's *agent of your choice*. Move Prompt 3D (edge-case testing) into the SharePoint agent section.


---

## Section 4 – 11:30 AM · Analyst · INVESTIGATE (20 min + official lab)

> **MS-4019 topics covered:** Module 2, *Examine the Analyst agent*; **Lab:** *Exercise 1 – Use the Analyst agent* (the official Project Nexus survey lab).

### Overview
Analyst explores, interprets and summarises work data (Excel, CSV, Word, Power BI) in natural language. It reasons step by step and can **run Python**, so you can see the code it ran and check its work.

### Business scenario
The Delta Digest flagged a drop in Finance adoption. Arjun has the Nexus adoption data (weekly active users by business unit, licences, survey sentiment). Priya wants to know **why** by this afternoon.

### Pain points
- Raw data, no analyst available, and the deadline is today.
- Pivot tables and charts take hours.
- Hard to tell a trend from noise.

### Business benefits
- Answers from data in minutes, not hours.
- Transparent reasoning (Python code you can see) builds trust.
- Ready-to-use charts for the steering committee.

### Learning objectives
1. Upload a data file to Analyst and ask analytical questions in natural language.
2. Read and check Analyst's reasoning and Python code.
3. Turn the findings into a chart and a 3-bullet insight for leadership.

### Environment setup
| Item | Requirement |
|---|---|
| Licence | Microsoft 365 Copilot |
| Agent | **Analyst** (prebuilt; under **Agents** in Copilot Chat) |
| Data | `04_Sample-Data/Project-Nexus/Nexus_Adoption_Data.xlsx` for the story demo; the **official lab spreadsheet** (Project Nexus survey results) for the hands-on |

### Demo walkthrough
1. Open **Analyst** → attach `Nexus_Adoption_Data.xlsx`.
2. Run Prompts 4A → 4C. Expand the **reasoning / code** panel at least once.

**Prompt 4A – trend**
```
Analyse weekly active users by business unit over the last 8 weeks. Which business unit is declining, since when, and by how much? Show a line chart.
```
**Prompt 4B – root cause**
```
For the declining business unit, compare licence assignment, training completion, and survey sentiment with the other business units. What are the three most likely reasons for the decline? Show the evidence for each.
```
**Prompt 4C – leadership-ready**
```
Summarise the findings as 3 bullets for a steering committee slide, plus one recommended action with an expected impact. Keep it under 80 words.
```

### Learner hands-on
Run the **official lab: Exercise 1 – Use the Analyst agent** (Project Nexus survey results). The story context makes it easy: *"You're Arjun's analyst. Find out what the survey says."*

### Schedule it 🔁 *(optional)*
Analyst is best used on demand. If the data file is updated weekly in OneDrive, an optional schedule is:
`Every Monday 9:30 AM – Compare this week's Nexus adoption data with last week. Flag any business unit that dropped more than 10%.`
*(Validate that scheduled runs can reach the file in your tenant.)*

### Bridge to the next section
> "Arjun now knows **what** is happening: Finance users weren't trained on agents and don't see their use cases. Priya wants a **recommendation**, backed by evidence, for what to do next."

### If you drop this section
Mention Analyst on one slide and keep the official lab as self-paced. In Section 5, give Researcher the finding directly: *"Finance adoption is down 30% because of a training gap."*


---

## Section 5 – 1:30 PM · Researcher + Idea Coach + Writing Coach · RECOMMEND (20 min + official lab)

> **MS-4019 topics covered:** Module 2, *Examine the Researcher agent*, *Examine the Idea Coach agent*, *Examine the Writing Coach agent*; **Labs:** *Exercise 2 – Use the Researcher agent* and *Exercise 3 – Use a prebuilt agent of your choice*.

### Overview
- **Researcher** carries out deep, multi-step research across work data (emails, meetings, files) and the web (where enabled), and produces a well-structured report with citations.
- **Idea Coach** stress-tests a plan from several angles.
- **Writing Coach** turns a rough draft into a polished message.

### Business scenario
Arjun has to recommend the **next phase** of Nexus: how to bring agent adoption back up in Finance. He needs internal context (what's been tried and what the team said) **and** external evidence (what's worked elsewhere). He then needs to pressure-test the idea and write a crisp note to Priya.

### Pain points
- Research spread across mail, meetings, files and the web.
- Recommendations that aren't challenged before they reach leadership.
- Long, unclear status emails.

### Business benefits
- A recommendation with sources in under 15 minutes.
- Better decisions through structured challenge.
- Clear, professional leadership communication.

### Learning objectives
1. Use Researcher to combine internal and external sources into a cited report.
2. Use Idea Coach to challenge a recommendation.
3. Use Writing Coach to tailor a message for an executive.
4. Choose the right prebuilt agent for the job (Copilot Chat vs. Researcher vs. the coaches).

### Environment setup
| Item | Requirement |
|---|---|
| Licence | Microsoft 365 Copilot (Researcher may have usage limits; check them in your tenant) |
| Agents | **Researcher**, **Idea Coach**, **Writing Coach** (prebuilt) |
| Data | Learner's own mail and meetings; Nexus sample files; web grounding if the tenant allows it |
| Timing note | Researcher can take a few minutes. **Start it, then teach Idea Coach while it runs.** |

### Demo walkthrough
1. Open **Researcher** → run **Prompt 5A**. Point out the clarifying questions and the research plan.
2. While it runs, open **Idea Coach** → run **Prompt 5B**.
3. Return to Researcher's report and point out the **citations**.
4. Open **Writing Coach** → run **Prompt 5C**.

**Prompt 5A – Researcher**
```
Goal: Recommend how to recover Microsoft 365 Copilot agent adoption in our Finance business unit within 60 days.
Context: I lead Project Nexus. Finance weekly active users fell about 30% over three weeks. Analysis suggests Finance users were not trained on agents and don't see role-relevant use cases.
Source: Use my emails, meeting notes, and the Project Nexus files for internal context, and credible external sources (Microsoft adoption guidance, industry case studies) for proven practices.
Expectations: A 1-page report with: situation, 3 options (effort, impact, risk), a recommended option, a 30-60 day plan, and success metrics. Cite every source.
```
**Prompt 5B – Idea Coach**
```
Here is my plan: run role-based agent workshops for Finance, appoint 5 Finance champions, and give every attendee three scheduled prompts on day one. Challenge this plan from the perspective of a CFO, a busy finance analyst, and IT governance. What would make it stronger?
```
**Prompt 5C – Writing Coach**
```
Rewrite this as a crisp note to my VP. Professional, confident, under 120 words, with one clear ask: [paste Researcher's recommendation summary]
```

### Learner hands-on
- **Official lab: Exercise 2 – Use the Researcher agent** (own data).
- **Official lab: Exercise 3 – Use a prebuilt agent of your choice.** Encourage learners to pick a **coach** agent or one of the **curated agents** from this day.

### Schedule it 🔁 *(optional)*
`Weekly, Monday 8:00 AM (Researcher or Copilot Chat) – What changed in Microsoft 365 Copilot and agent adoption best practice in the last 7 days that is relevant to an internal rollout? 5 bullets with sources.`

### Teaching moment
> *Copilot Chat is for a quick answer. **Researcher** is for depth and citations. **Coaches** are for improving your thinking and writing. Pick the agent that matches the depth you need.*

### Bridge to the next section
> "Priya approves the plan. Now Arjun's team is about to be flooded with questions: *How do I get a licence? Where's the training? Who's my champion?* He can't answer them all, so he gives the team an agent that can."

### If you drop this section
Keep Researcher for the official lab only. Coaches can be self-explored in Exercise 3.


---

## Section 6 – 3:00 PM · SharePoint agent + sharing in Teams · SCALE (10 min, brief)

> **MS-4019 topics covered:** Module 3, *Create an agent in SharePoint*, *Manage your agents* (default site agent); Module 4, *Share an agent with other users*, *Share an agent in Microsoft Teams*, *Interact with agents*; **Lab:** *Exercise 2 – Create a SharePoint agent*.

### In one minute
Arjun creates a **"Nexus Help Desk"** SharePoint agent on the Project Nexus site, grounded in the team FAQ and rollout plan. He shares it in the **Nexus team chat** and adds it to the channel so people can **@mention** it. He also shares his **Nexus Delta Digest** agent with the workstream leads.

### Steps
1. Go to the Project Nexus SharePoint site → **Copilot / agent** → **Create an agent**.
2. **Overview:** name `Nexus Help Desk`. **Sources:** `Nexus_Team_FAQ.docx`, `Nexus_Rollout_Plan.docx`. **Behaviour:** welcome message and 3 starter prompts.
3. Test it:
   ```
   How do I get a Copilot licence, and who is the champion for Finance?
   ```
4. **Share:** copy the agent link → post it in the Nexus Teams chat → **@Nexus Help Desk** in the chat.
5. Share the **Nexus Delta Digest** (Copilot Chat agent) with **specific users** (the workstream leads).

### Key teaching points (Module 4)
- Shared agents respect permissions. **People only get answers from content they can already access.** Sharing the agent doesn't share the files.
- A site owner can set an approved agent as the **site's default agent**.
- Your chats with agents are private to you; you can rename or delete your chat history.

### Schedule it 🔁
Not applicable. SharePoint agents are used on demand by the team. The adoption benefit comes from **sharing**: every teammate who uses it becomes an active user.

### If you drop this section
Run the official SharePoint lab as self-paced. Keep one slide on **sharing and permissions** (Module 4) using the Delta Digest as the example.


---

## Section 7 – 4:00 PM · AI Learning Advisor · GROW (15 min)

> **MS-4019 topics covered:** Module 6 (India preset), *personalised skilling*. It also reinforces Module 1, *Who can create and use agents?* (the path from business user to maker).

### Overview
AI Learning Advisor is an **agent template**, a declarative agent grounded in **Microsoft Learn** and the **Copilot Developer Camp** websites. It gives fast, trusted, step-by-step guidance and **personalised learning plans** across the Microsoft stack (Microsoft 365, Copilot Studio, Power Platform, Azure, Entra ID), with citations to official docs.

### Business scenario
Priya approved the plan, and added one more thing: *"You'll run the Finance agent workshops yourself."* Arjun is comfortable with Copilot, but he isn't confident explaining **agent grounding, knowledge, Agent Builder vs. Copilot Studio, or governance** to a room of finance professionals. The project has exposed a skill gap.

### Pain points
- Hundreds of learning resources and no clear path.
- Generic courses that don't match the learner's current level.
- No time; learning keeps getting pushed back.
- Repeated "how do I…?" questions going to subject-matter experts.

### Business benefits
- A focused, personalised learning path instead of browsing.
- Trusted answers with citations to Microsoft Learn.
- Subject-matter experts freed from repeated questions.
- **Adoption:** a weekly scheduled learning check-in keeps the learner coming back, and growing.

### Learning objectives
1. Add AI Learning Advisor from the template gallery or Agent Store.
2. Generate a **personalised 4-week learning plan** with a knowledge check.
3. Use it to answer "which tool when" questions (Agent Builder vs. Copilot Studio).
4. **Schedule** a weekly learning check-in.

### Environment setup
| Item | Requirement |
|---|---|
| Licence | Microsoft 365 Copilot; web/public website grounding allowed by the admin |
| Template | **AI Learning Advisor** (formerly "AI Skilling") in the template gallery or Agent Store |
| Fallback | If it isn't available: Copilot Chat with `Use Microsoft Learn as your primary source` added to the prompt, or build it quickly from `05_Agent-Instructions/AI-Learning-Advisor_Instructions.md` |

### Demo walkthrough
1. Add and open **AI Learning Advisor**.
2. Run **Prompt 7A**, then the **knowledge check (7B)**. Answer one or two questions live.
3. Run **Prompt 7C** (the which-tool-when question that every MS-4019 audience asks).
4. **Schedule it.**

**Prompt 7A – personalised plan**
```
Goal: Create a personalised learning journey so I can confidently explain and demonstrate Microsoft 365 Copilot agents to finance professionals.
Context: I am a Program Manager. I'm comfortable with Microsoft 365 Copilot and basic prompting. My gaps are agent grounding and knowledge sources, Agent Builder vs. Copilot Studio, agent sharing and governance, and designing finance use cases. I can spend 3 hours per week for 4 weeks.
Source: Prioritise Microsoft Learn and official Microsoft resources.
Expectations: A 4-week roadmap as a table:
Week | Skill | Why it matters for my workshops | Recommended learning (with link) | Hands-on activity | Evidence I've learned it
Prioritise impact. Don't overwhelm me.
```
**Prompt 7B – knowledge check (agentic: it adapts the plan)**
```
Before I start, test my existing knowledge with five questions, one at a time. Use my answers to adjust the 4-week plan.
```
**Prompt 7C – which tool when**
```
What's the difference between Agent Builder and Copilot Studio, and which should a finance business user use when? Give me a comparison table and a recommendation.
```

**Extra prompts from the template's test set**
| Scenario | Prompt |
|---|---|
| What's new | `What's new in Copilot Studio and Microsoft 365 Copilot and what should I try first?` |
| Explain simply | `Explain MCP (Model Context Protocol) like I am new to AI and why should I care as a maker?` |
| Brainstorm | `I am in Finance and new to building agents. Help me brainstorm 5 agent ideas with knowledge sources for each.` |
| Governance | `Give me a governance checklist for business users sharing agents in Microsoft 365 that I can show my IT team.` |

### Schedule it 🔁
| Name | Prompt | Frequency | Time |
|---|---|---|---|
| `Weekly learning check-in` | `It's a new week of my agent learning plan. Remind me of this week's skill, give me one 20-minute activity, and ask me one question to check last week's learning.` | Weekly, Monday | 4:00 PM |

> *Note: a scheduled prompt runs as a new conversation. Repeat the essential context (role, goal, plan) in the scheduled prompt, or ask the agent to rebuild the plan. Check in your tenant whether earlier chat context carries over.*

### Teaching moment
> *That's the difference between **content discovery** and **personalised learning**.*

### Bridge to the next section
> "It's 5:30. Arjun's day started with 200 unread items and no plan. Let's see what he's set up for tomorrow."

### If you drop this section
End the story at Section 5 or 6. Mention AI Learning Advisor in Section 8 as an optional agent to schedule.


---

## Section 8 – 5:30 PM · Wrap my day: schedule, govern, commit (15 min)

> **MS-4019 topics covered:** Module 1, *Examine IT governance controls for your agents*; Module 4, *Interact with agents* (chat history, permissions); Module 5, *Learning path review*.

### Overview
This is the **most important section for adoption**. Learners leave having **scheduled at least 3 prompts**, so the agents come to them tomorrow.

### Step 1 – Show Arjun's schedule (2 min)
| Time | Agent | Scheduled prompt | Frequency | Outcome |
|---|---|---|---|---|
| 8:30 AM | Personal News Digest | Morning briefing – what changed | Daily | Understand |
| 9:00 AM | Plan My Day | Start my day | Daily | Prioritize |
| 10:00 AM | Nexus Delta Digest | Nexus daily delta | Daily | Execute |
| 4:00 PM Fri | Nexus Delta Digest | Nexus leadership recap | Weekly | Execute |
| 4:00 PM Mon | AI Learning Advisor | Weekly learning check-in | Weekly | Grow |
| 6:00 PM | Plan My Day | Wrap my day | Daily | Prioritize |

> **Talk track:** "Six scheduled prompts, about 5 minutes of reading a day. Arjun's agents now work for him **20+ days a month**, and he didn't have to remember any of it."

### Step 2 – Live: wrap Arjun's day (2 min)
In **Plan My Day**:
```
Wrap my day: summarise what I completed, what slipped, decisions I owe, and preview tomorrow's top 3 priorities.
```

### Step 3 – Learner hands-on: "Schedule 3" (8 min)
Every learner:
1. Picks **at least 3 prompts** from the **Scheduled Prompt Pack** (Section 10), including at least **2 daily** ones.
2. Personalises each one (role, project name, priorities).
3. Runs it once, checks the output, then **schedules it** (see *How to schedule a prompt*).
4. Opens the **scheduled prompts list** to confirm all 3 are there.
5. Posts **"✅ 3 scheduled"** in the class Teams chat.

### Step 4 – Governance check (3 min, Module 1 + 4)
Quick discussion:
- Scheduled prompts and agents **only use data the user can already access**. Permissions, sensitivity labels and DLP still apply.
- Check what you **share**: sharing an agent doesn't grant access to its knowledge sources.
- **Manage** scheduled prompts: pause or delete the ones you don't read. Unread digests are noise.
- Your agent chats are private. You can rename or delete your history.
- Your organisation decides which agents and templates are enabled (IT governance controls).

### Learning-path review (Module 5)
Ask: *"Which of Arjun's moments is most like your own day, and which agent did you schedule for it?"*


---

## Section 9 – Next morning · The adoption moment (trainer close + follow-up)

### Close the session (2 min)
> "Tomorrow at 8:30, your first digest will be waiting for you. You didn't just *try* an agent today. You made it part of your workday."

Shift the mindset from **"I tried an agent"** to **"I use this agent as part of my workflow."**

### Follow-up plan (for the trainer / CSM)
| When | Action | Owner |
|---|---|---|
| Day 1 | Share the copy-paste prompt pack in the class Teams chat | Trainer |
| Day 2 | Post: *"Did your 8:30 digest arrive? Reply with one useful item it found."* | Trainer / champion |
| Day 7 | Post: *"Pause one schedule you're not reading and add one that matters."* | Champion |
| Day 30 | Compare Agent MAU and PRU against the pre-training baseline (MSX / dashboard) | CSM / MTT lead |

### Success indicators
- % of learners with **at least 3 scheduled prompts** at the end of class (target: **80%**).
- % with **at least 2 daily** schedules (drives daily active usage).
- Agent MAU and PRU change at day 30.


---

## Section 10 – Scheduled prompt pack
> Copy-paste versions: `03_Prompt-Packs/Learner-Copy-Paste-Prompts.txt` (for the class Teams chat) and `03_Prompt-Packs/Scheduled-Prompts.csv`.
> Replace anything in **[brackets]** with your own role, project or priorities.

### Daily (these drive DAU)
| # | Agent | Name | Time | Prompt |
|---|---|---|---|---|
| D1 | Personal News Digest | Morning briefing | 8:30 AM | `I am a [role] working on [project/area]. Give me the 5 most important company-wide updates from the last 24 hours that matter to my role, as a table: Priority (Critical/Important/FYI) – Headline – Why it matters to me – Action and deadline.` |
| D2 | Plan My Day | Start my day | 9:00 AM | `Create a time-blocked plan for today from my calendar, email, Teams, and tasks: Time – Activity – Priority – Why now. List my top 3 outcomes and what I can postpone or delegate.` |
| D3 | Project Delta Digest | Daily project delta | 10:00 AM | `Give me today's digest for [project] — TL;DR, completed, in progress, blockers (owner, days stuck), and risks from the last 24 hours, with sources. Flag anything idle more than 5 days.` |
| D4 | Plan My Day | Wrap my day | 6:00 PM | `Wrap my day: what I completed, what slipped, decisions I owe, and tomorrow's top 3 priorities.` |
| D5 | Plan My Day | Meeting-heavy day check | 8:45 AM | `How heavy is my meeting load today? Which meetings can I skip, shorten, or delegate, and where is my best focus block?` |

### Weekly (these drive PRU and depth)
| # | Agent | Name | When | Prompt |
|---|---|---|---|---|
| W1 | Project Delta Digest | Leadership recap | Fri 4:00 PM | `Give me a leadership-ready weekly digest for [project] — TL;DR, milestones, top 3 risks, momentum signals, and the one decision I need from leadership. One page.` |
| W2 | Project Delta Digest | Escalate vs watch | Thu 3:00 PM | `What should I escalate now vs watch for another week on [project]? Two lists with risk score (1–5), owner, rationale, and source.` |
| W3 | Plan My Day | Weekly look-ahead | Mon 8:45 AM | `Give me a weekly look-ahead: key meetings, deadlines, milestones, meeting load, and my top 3 priorities for the week.` |
| W4 | Personal News Digest | Leadership voice | Mon 8:30 AM | `Summarise messages from my leadership chain and company executives in the last 7 days. Key quotes (under 20 words) and actions for my team.` |
| W5 | AI Learning Advisor | Learning check-in | Mon 4:00 PM | `I am a [role] building skills in [topic]. Give me this week's single most valuable skill, one 20-minute Microsoft Learn activity with a link, and one question to test what I learned last week.` |
| W6 | AI Learning Advisor | What's new | Fri 12:00 PM | `What's new this week in Microsoft 365 Copilot and agents that a [role] should try? Top 3, each with a Microsoft Learn link and a 5-minute try-it step.` |

### Trainer recommendation by audience
| Audience | Suggested "Schedule 3" |
|---|---|
| Any employee | D1 + D2 + D4 |
| Project / delivery managers | D2 + D3 + W1 |
| Managers / leaders | D1 + D2 + W4 |
| People building skills / champions | D2 + W5 + W6 |

---

## Pack contents
```
MS-4019_CUR_IND2_Project-Nexus_Demo-Pack/
├── README.md                          ← this file (master guide)
├── 01_Trainer-Guide/
│   ├── Pre-Delivery-Checklist.md      ← CSM / CSC / MTT checklist + availability check
│   ├── Delivery-Flow-and-Timing.md    ← agenda, timing, drop matrix, short versions
│   └── Trainer-Talk-Track.md          ← story lines and bridges, one per section
├── 02_Demo-Scripts/                   ← one file per section (drop any file you don't need)
│   ├── S00_Story-Setup_Meet-Arjun.md
│   ├── S01_0830_Personal-News-Digest.md
│   ├── S02_0900_Plan-My-Day.md
│   ├── S03_1000_Project-Delta-Digest.md
│   ├── S04_1130_Analyst.md
│   ├── S05_1330_Researcher-and-Coaches.md
│   ├── S06_1500_SharePoint-Agent.md
│   ├── S07_1600_AI-Learning-Advisor.md
│   ├── S08_1730_Wrap-Schedule-Govern.md
│   └── S09_Next-Morning_Adoption.md
├── 03_Prompt-Packs/
│   ├── Scheduled-Prompt-Pack.md
│   ├── Scheduled-Prompts.csv
│   └── Learner-Copy-Paste-Prompts.txt ← paste into the class Teams chat
├── 04_Sample-Data/
│   ├── Nexus_Sample_Announcements.md  ← fallback for Personal News Digest
│   └── Project-Nexus/                 ← upload to a SharePoint/OneDrive folder
│       ├── Nexus_Project_Tracker.xlsx
│       ├── Nexus_Adoption_Data.xlsx
│       ├── Nexus_Weekly_Status_W42.docx
│       ├── Nexus_Weekly_Status_W43.docx
│       ├── Nexus_Steering_Committee_Notes.docx
│       ├── Nexus_Rollout_Plan.docx
│       └── Nexus_Team_FAQ.docx
└── 05_Agent-Instructions/             ← fallback: build the agent if the template isn't available
    ├── Personal-News-Digest_Instructions.md
    ├── Plan-My-Day_Instructions.md
    ├── Project-Delta-Digest_Instructions.md
    └── AI-Learning-Advisor_Instructions.md
```

> All names, people and data in Project Nexus are fictitious and are for training only.
