# MIND CHILDREN FUTURE

Working document for the conversation with Ben and Chris. Goal of the
conversation: answer the hard questions and find structure, so that Mind
Children can stand on its own as a company with a clear goal.

Status: interrogation complete (3 rounds, 2026-09-27). Sections 1 to 6
are my thoughts. Sections 7 to 10 are the advisor's read and suggestions.

## 1. Facts as of today

### Company

- Legal entity, Seattle, WA. Board: Ben (temporary CEO, also CEO of
SingularityNET), Chris (previous CEO), Mario and David (investors /
interested parties), possibly others.
- Salaries are paid by SingularityNET. Rough burn: $30k to $40k per
month, overhead already cut. I am not sure of the number.
- Token situation is volatile, but funds appear to be there.
- SNET runs a monthly review of expenses and return. No documented
deliverable process, because there is no business model yet.
- I have stakes but no ownership. Exact form unclear to me.
- I have never spoken to Mario or David. Chris has reported to them a
bit. Ben is the one to convince; they will likely follow.
- Inside SNET, the OmegaClaw crew is the group that cares about us (the
embodied AI angle).



### How we work

- Chris is the focal point. Daily standup, weekly one-on-one with Chris.
Plans are open, we work closely together, discussion is flexible.
- Nothing gets cancelled or deprioritised on purpose. Things get added.



### People


| Who   | Role on paper                  | What actually fills the week                                                                                                        | Where they stand                                                                                                                                                                                                  |
| ----- | ------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ben   | CEO                            | SingularityNET. Very little Mind Children time.                                                                                     | Open, listens to good ideas, would support a mix of everyone's goals. One hour online call available.                                                                                                             |
| Chris | Ex-CEO, hardware               | Floor management, 3D printing. Face of the company at meetings, pulled back to the floor by necessity. Sporadic contact with Korea. | Relieved Ben took the CEO role. Industrial design background, wants to do hardware. Neutral, somewhat an ally. Good relationship with Ben, gets a lot of freedom. We have discussed most of these topics already. |
| Me    | Main architect, software stack | AI, integration, Thalamus.                                                                                                          | Want to stay and fix it. Open to owning the product roadmap. Not asking for a board seat now.                                                                                                                     |
| Yue   | Main robotics engineer         | New mechanisms with servos, some software.                                                                                          | Would go along, prefers building.                                                                                                                                                                                 |
| Nile  | Robot operator, handyman       | Travels with the robot, keeps it alive.                                                                                             | Would go along, prefers tinkering.                                                                                                                                                                                |


Nobody in this table owns customers, sales, or the business case.

### The robot

- Half-height humanoid on a wheeled base. Articulated arms and face,
gesturing hands. Built for social interaction, deliberately not for
manipulation or bipedal walking.
- One unit exists. It lives in the lab.
- Parts: roughly $20k. Building a second one: up to 3 months. No factory,
just our lab.
- Runs at least 3 hours on battery.
- Unattended, it can: hold rudimentary conversation, explain a topic,
give a presentation, play children's games with a whiteboard, guide
people around the lab.
- The moment that makes a room go quiet: it has autonomously hosted
conference tracks on stage.
- Exposure to outsiders: demos and presentations only.
- Safety and certification for public spaces: nobody has looked at it.
The electrical system is overdimensioned for safety. Impedance arms
are in progress for the same reason.



### What breaks in the field (30 days, no team present)


| Failure                | Repair time | Notes                              |
| ---------------------- | ----------- | ---------------------------------- |
| 3D-printed face parts  | 3 months    | Single biggest deployment blocker. |
| Shoulders (3D-printed) | 2 days      |                                    |
| Elbows (3D-printed)    | 2 days      |                                    |
| Electrical issues      | 2 weeks     | Custom power and USB lines.        |


History: parts breaking, one fatal servo overload, several face repairs.

### Customers and revenue

- Zero robots sold as a product.
- One copy went to a university in Korea. I do not know what they paid.
Probably not in use. The partner and investor story died through their
internal politics and a general conservative trend. Interest may not be
fully dead, but there is no reliable deal. Chris is in sporadic touch.
- No other customers. Nobody is addressing this properly.



### Markets the team talks about


| Market                             | Why                                  | My honest read                                 |
| ---------------------------------- | ------------------------------------ | ---------------------------------------------- |
| Museum / hospitality / hotel clerk | Low-hanging fruit                    | Closest to what the robot already does.        |
| Events / conference hosting        | Already demonstrated on stage        | Not on our list, but it is the proven use.     |
| Education                          | Embodied teaching beats touchscreens | Strong feelings, no customer conversations.    |
| Eldercare                          | I have prior experience here         | Logical, but reliability and regulation heavy. |
| Research platform                  | It is what the robot already is      | The default if we do nothing.                  |
| Robot comedian                     | Personal favourite                   | Background idea, not marketable yet.           |




### Roadmap items, who owns them, and what they are for


| Item                    | Driven by  | Purpose                                                                                                   | If dropped                                                                                 |
| ----------------------- | ---------- | --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Impedance-response arms | Chris, Yue | Safety: not hurting people or destroying scenery or itself                                                | Cannot go near the public. Essential.                                                      |
| Power distribution PCB  | Me         | Robustness, less wiring, tidier power and USB                                                             | Robot still works. Nice to have.                                                           |
| More robots             | Me         | Field work needs more than one unit                                                                       | Cannot be dropped, only postponed.                                                         |
| OmegaClaw integration   | Ben        | SNET's agentic harness (MeTTa/Hyperon symbolic reasoning, short and long term memory) as the robot's core | Little technical difference; frontier models already work. Political: SNET pays the bills. |
| Storytelling            | ?          | ?                                                                                                         | ?                                                                                          |




### Thalamus

- Full audio/video pipeline for social interaction: recognition and
tracking of people around the robot, multi-person interaction, social
signals and gestures, integrated animations, broader OmegaClaw
interface.
- My contribution, built on Mind Children time. Ownership (company IP vs
mine) not stated anywhere.
- Plan: open source it, publish on YouTube. Reasons: credibility and
positioning ("Mind Children are the people who brought you Thalamus"),
my own profile, and a community that improves the field without
paying expensive researchers. A free/paid split is possible for
customer-specific parts.
- Most of the field still runs STT-LLM-TTS or basic speech-to-speech
pipelines. Thalamus is ahead of that.



### The "production ready" problem

- Deployment at a customer needs different software and hardware
requirements than demos and academic research.
- Chris and I have always known this means extra development effort.
- SingularityNET culture is academic and experimental, so help from
them on production readiness will be messy.
- We do not have the resources to build a production version, and I do
not want to fight SNET's culture over it.



## 2. My diagnosis

- No vision. No avenue toward customers.
- Real risk: Mind Children stays Ben's pet project forever.
- I like Ben, but I want the company to stand on its own, attract real
investment, and make a difference.
- It is not a conflict problem. Everyone gets along, Ben is open, Chris
is relieved, funds exist. It is an ownership problem: nobody has been
asked to make a customer happen, so nobody is in a hurry.



## 3. What Ben would say

"Mind Children is at the forefront of embodied AI, which is the holy
grail that AI research is currently missing."

True. Also not a company goal. It describes a research program.

## 4. What I want out of the conversation

1. Stay and fix it.
2. Renegotiate my role: own the product roadmap, not a board seat.
3. (Last resort) Force a decision by a deadline.
4. (Last resort) Find a way out.

My capacity: I am in this for life if there is a fighting chance.
Fractal One is unpaid and has no priority. The videos are the Thalamus
channel, low priority. Thalamus work for Mind Children would slow down
if I take on the roadmap.

## 5. Gaps I need to close before the conversation

- Who the outside investors are, what they put in, what they were
promised, and what they expect. Ask Chris, who has reported to them.
- What "stakes but no ownership" means for me on paper.
- Whether Ben and the board actually want a standalone company, or are
content with a research vehicle inside SNET. This has never been asked
directly.
- What Korea paid, whether the robot runs, and whether the door is open.
- Monthly burn, and what the "return" column in SNET's monthly review
currently shows.
- Who owns Thalamus IP.
- What "storytelling" on the roadmap actually is and who wants it.



## 6. The meeting

- Ben, Chris, me. Online, about one hour. Small presentation.
- Topics I want on the table:
  1. Drive production-level development: yes or no.
  2. Open source Thalamus and start the YouTube channel: yes or no.
  3. Build more robots: when.
  4. Define a roadmap and vision beyond "embodied AI is important".
- Worst outcome: the items get dismissed and there is no roadmap. The
morning after, I start charting other social robotics startups that
need my flavour of talent.



## 7. Advisor's read

- The "standalone company" goal is mine. It is not yet confirmed as
Ben's or the board's. Until it is, every other argument is built on
sand. The meeting has to surface that answer.
- I am the most experienced startup person on the team and I do not know
the funding terms. Close that before the meeting, via Chris.
- The Korean sale is the one thing that looks like market evidence and
nobody has mined it.
- The robot has already done a paid-looking job: hosting conference
tracks autonomously. Events, museums and reception are the same
market. Nile already travels with the robot. That is a rentable
service today, with an operator present, needing zero production
readiness. It is not on the market list because nobody thinks of it
as a business.
- With one robot and a face that takes three months to repair, a single
accident takes the company's entire demo capability offline for a
quarter. A spare face is a business continuity item, not a hardware
nicety.
- SNET is customer number one whether we like it or not. They pay, they
review monthly, and the OmegaClaw crew wants an embodied showcase.
Serving them with explicit deliverables is not selling out, it is the
structure that is currently missing. It buys the time to find
customer number two, who pays with money from outside the ecosystem.
- "Production ready" is being framed as a culture fight with SNET. It is
actually a resourcing question, and it only matters once there is a
customer to deploy to. Scope it to what the first deployment needs,
nothing more.
- Thalamus open source is a strategy decision for the company, not a
side project. SNET's whole ethos is open, decentralised AI, so Ben
will like it. Settle IP ownership before publishing anything, and
brand the channel Mind Children first, me as the face.
- The team is five engineers and no seller. The fix is not a hire. It is
one existing person with startup experience owning customer discovery
for six months. That person is me, and it costs Thalamus velocity.
- The worst outcome is not dismissal. Ben is open and will support "a
mix of all our goals". The worst outcome is a warm yes to everything
and nothing changes, because that is exactly the current state. A
discussion opener with four topics and an agreeable CEO produces that
outcome by default.



## 8. Advisor's suggestions for the conversation

1. Do not open a discussion. Ask for one decision. The four topics all
  hang off one question: "Do we intend to put this robot in front of a
   paying customer within twelve months, yes or no?" Put that on slide
   one. Every other item is answered by the branch Ben picks. If he
   picks "both", the commercial branch still needs an owner and a date,
   and that is the ask.
2. Bring facts they have not seen laid out together. One robot. Zero
  revenue. Three months per unit. Three months per face. Thirty to
   forty thousand a month. Five engineers, zero people on customers.
   Then the capability list, then the market table. No complaints, no
   adjectives. Where a number is unknown, say "I do not know this and
   somebody should." That is itself the argument for structure.
3. Offer to own it, in a shape Ben can say yes to in one hour: no board
  change, no hire, no budget increase, only reallocation. "I own the
   roadmap and the first paying deployment for six months. Thalamus
   slows down. Here is the first target." Then ask Ben for three things
   only: confirmation of the goal, thirty minutes with him monthly, and
   permission to talk to Mario and David.
4. Propose the first target as the one the robot has already done:
  robot-as-a-service for conferences, corporate events and museums in
   the Seattle area, operator included. It monetises the single unit,
   needs no production readiness, produces the first entry in SNET's
   "return" column, and puts a date on the calendar, which is where
   urgency comes from. Eldercare and education are the second act.
5. Turn OmegaClaw into a deliverable rather than a favour. Define what
  an "embodied OmegaClaw showcase" is, with milestones, and report on
   it in the monthly review. That gives SNET a return, gives the
   OmegaClaw crew a reason to defend the budget, and gives Thalamus a
   stated purpose inside the company.
6. Pre-brief Chris. Never let him first hear the fork question in front
  of Ben. Frame the change as freeing him to do hardware, which he
   wants, not as a verdict on his CEO period. Ask him to co-own the
   spare face and the arms timeline in the plan, so he is presenting,
   not being presented to.
7. Order the immediate actions so the first two need nobody's
  permission: build a spare face now; call the Korean university and
   learn what they paid and whether the robot runs. Both can start
   tomorrow, and both make the meeting stronger.
8. Do not say the private tripwire out loud in the meeting, but set it:
  if sixty days after the meeting there is no named owner, no first
   customer conversation, and no date, that is the answer, and the
   morning-after plan begins.



## 9. Proposed presentation, six slides

1. The question. "Paying customer within twelve months: yes or no?"
2. Where we are. The numbers, the one robot, the repair table, the
  team table with the empty customer row.
3. What the robot can already do. Three hours, autonomous, on stage.
4. The first target. Events and museums as a service, operator
  included. What it earns, what it teaches us, what it needs (spare
   face, arms timeline, insurance check).
5. The six-month plan. Owner, monthly review with Ben, OmegaClaw as a
  deliverable, Thalamus open source with IP settled, robot number two
   triggered by the first committed customer.
6. What I am asking for. Three things. Then stop talking.



## 10. Before the meeting, in order

1. Ask Chris for the investor picture and my own paper position.
2. Ask Chris or Ben what Korea paid, and get a call with them scheduled.
3. Get the burn number.
4. Start the spare face.
5. Walk Chris through slides one, four and five.
6. Send Ben the six slides the day before, so the hour is for deciding.

