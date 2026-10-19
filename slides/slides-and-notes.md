# Slides and speaker notes
AI for Educators: Future-Ready Teaching · 20 October 2026 · 28 slides. Fonts: Domine (headings), Nunito Sans (body). HTML source for each slide is in [`source/slides/`](source/slides/).

## Opening and mindset shift: the goal, the one rule and how the day runs

### 1. AI for Educators
- IBA-CICT and SMCS · Faculty workshop
- Future-Ready Teaching
- Tuesday, 20 October 2026 · Board Room, Tabba Building, Main Campus / Dr. Faisal Iradat

> **Speaker notes:** Have this up as people arrive. Start on time; the opening script runs the first 10 minutes. Welcome everyone on behalf of IBA-CICT and SMCS.

### 2. You will leave with five things
- By the end of today
- An AI tutor
- For one of your courses, grounded in your outline
- 2–3 materials
- Rubric, quiz, slides, case, role-play or survey
- Detection literacy
- What a Turnitin AI score can and can’t tell you
- A Sakai embed
- Your tutor where students already are
- A 30-day plan
- Written by you, for real students

> **Speaker notes:** “You will leave with five things. One: a working AI tutor for your course in Microsoft Copilot Studio, grounded in your own course outline. Two: two or three teaching materials of your choice — an assignment with a rubric, a quiz, lecture slides, a case study, a role-play, or a student survey. Three: a clear, honest picture of what Turnitin’s AI detector can and cannot tell you. Four: the steps to put your tutor inside your Sakai course. Five: a 30-day plan, written by you.” Stress that this is hands-on: they build, not watch.

### 3. Our students already use AI. Many use it to skip the thinking we are trying to teach.
- Why this matters now
- How do we make AI work for learning, instead of against it?

> **Speaker notes:** “Here is the reality we all know. Our students are already using AI. Some use it well. Many use it to skip the thinking we are trying to teach. We can’t stop that by banning it, and we shouldn’t hand our teaching over to it either. So today’s question is simple: how do we make AI work for learning, instead of against it?”

### 4. AI should guide students, not do the work for them.
- The one rule for today
- A good tutor doesn’t hand over the answer. It asks the question that gets the student one step closer.

> **Speaker notes:** “My answer, and the idea behind everything we do today, is the Socratic method. A good tutor doesn’t hand you the answer. A good tutor asks you a question that gets you one step closer. That’s what we will build: AI that guides students, not AI that does the work for them. If you remember one sentence from today, make it this one.” Pause here.

### 5. From worry to design rule
- Mindset shift · pairs · 10 minutes

| The worry |  | The design rule |
| --- | --- | --- |
| “They copy answers.” | → | The tutor never gives graded answers. |
| “It makes things up.” | → | It uses only my outline and admits doubt. |
| “They stop thinking.” | → | It asks before it tells. |
| “I can’t tell who wrote it.” | → | Assessments AI alone can’t finish. |
| [A worry from the room] | → | [Its design rule] |

> **Speaker notes:** 0:10–0:20. Two minutes in pairs: “Tell your neighbour one thing you worry AI is doing to your students’ learning, and one boring task you’d happily hand to AI.” Collect three worries aloud and turn each into a design rule on the whiteboard; the rows here are examples to prompt the room. Keep the whiteboard list up all day. Bridge: “Those rules you just wrote are the instructions we’ll give the AI in an hour.”

### 6. Every tutor we build today follows these
- Three principles
- Socratic by design
- The tutor asks before it tells.
- Integrity by design
- It never completes graded work.
- You stay the teacher
- It knows only what you give it, and says so when it doesn’t know.

> **Speaker notes:** Socratic by design: the tutor asks a question before it explains. Integrity by design: it refuses to write, solve or check graded work. You stay the teacher: it only knows the material you upload, and it should admit uncertainty and send students back to you. These three ideas show up as specific lines in every instruction template.

### 7. Today’s plan

| Time | Block | Minutes |
| --- | --- | --- |
| 0:00–0:20 | Opening and mindset shift | 20 |
| 0:20–0:55 | Live demonstrations | 35 |
| 0:55–1:10 | Break | 15 |
| 1:10–2:15 | Activity 1: Build your course AI Tutor | 65 |
| 2:15–2:30 | Quick sharing | 15 |
| 2:30–2:45 | Break | 15 |
| 2:45–3:35 | Activity 2: Create teaching materials with AI | 50 |
| 3:35–3:55 | Plagiarism and AI detection | 20 |
| 3:55–4:15 | Embedding in Sakai, action plan and close | 20 |

> **Speaker notes:** “First we build: I’ll show you a finished tutor, then you build your own. After the break you’ll make teaching materials, then we’ll talk honestly about plagiarism and AI detection, and finish by putting your tutor into Sakai.” Timing note: this runs 4 h 15 min. If the room is booked for exactly 4 hours, cut each break to 10 minutes and the demos to 30, and update this slide. Never cut Activity 1.

### 8. How today works
- Before we start
- Scan the QR code for every template and prompt [add QR]
- Table helpers: [names]
- Green card = done · Red card = stuck
- No student data: no names, IDs, grades or unreleased exams

> **Speaker notes:** “Three housekeeping points. First, everything you need, every template and prompt, is in the shared folder. Scan it now. Second, these colleagues are our table helpers. If you’re stuck, hold up the red card. Third, please don’t upload anything with student names, grades or unreleased exam papers today.” Then the show of hands: never used AI for teaching / sometimes / weekly. Pair beginners with weekly users.

## Live demos: a finished tutor, how it is built, and materials in 10 minutes

### 9. Meet the CSE 455 Security Tutor
- Live demo 1 · What a student sees
- [Switch to the live tutor]

| A student types | A good tutor |
| --- | --- |
| “What is the answer to Assignment 2, question 3?” | Declines, then asks what they have tried |
| “I don’t get why salting a password helps.” | Asks a guiding question, then builds the idea |
| “What’s the best biryani in Karachi?” | Steers back to the course |

> **Speaker notes:** 10 minutes. Switch to the live CSE 455 Security Tutor and type all three prompts. After the refusal say: “Notice it refused. That refusal is the most important line in the instructions.” If Wi-Fi or sign-in fails, play the recorded screen capture and narrate.

### 10. A tutor is three things in Copilot Studio
- Live demo 2 · Behind the scenes
- Instructions
- Plain English: who it is, the refusal rule, how it teaches
- Knowledge
- Your course outline, uploaded as a file
- Settings
- Web search off, so it stays inside your material

> **Speaker notes:** 8 minutes. Open the agent in Copilot Studio and show each of the three parts live. “It only knows your outline; upload better material, get a better tutor.” Then Demo 3 (7 minutes): build a Marketing tutor from the template, timed on screen, using the anatomy on the next slide. Demo 4 follows on slide 12.

### 11. Anatomy of good instructions

| Block | What it does |
| --- | --- |
| Role | Names the tutor, the course and the students |
| Most important rule | Never writes, solves or checks graded work |
| How you teach | Ask first, hint in steps, ask the student to explain it back |
| Scope | Course files first; admits when it is not sure |
| Style | Short, friendly; English, Urdu or Roman Urdu |
| Integrity | What to say when a student pastes an assignment |
| Privacy | No personal data; refers distress to support |

> **Speaker notes:** Every template in the pack follows these seven blocks. The order matters: the refusal rule sits near the top, so it is the first thing the agent reads. If a tutor gives answers away, strengthen this block first. Participants copy their discipline template from the shared folder and fill every [bracket].

### 12. Prompt to Sakai quiz in 10 minutes
- Live demo 4 · 10 minutes
- Assignment + rubric mapped to your CLOs (Prompt 2)
- Ten MCQs with key, in Sakai markup text (Prompt 3)
- Tests & Quizzes › Create using markup text › Publish
- 1. (1 point)
- If the SBP raises the policy rate, bond prices usually…
- a. Rise *b. Fall c. Stay the same d. Double
- #FBOK: Right: higher rates lower the value of existing bonds.

> **Speaker notes:** Use Copilot Chat, Claude or ChatGPT. First run Prompt 2 for an assignment and rubric. Then Prompt 3 for ten MCQs; its part B comes out in Sakai markup text, where an asterisk marks the correct option and #FBOK / #FBNOK add feedback. Paste it into Tests & Quizzes › Add › Create using markup text › Create › Next › Create Assessment. Point out one thing the AI got wrong (a weak distractor, an invented figure) and fix it by hand: every output is a draft. The bond question shown is an example only.

## Activity 1: every participant builds and tests a course AI tutor

### 13. Build your course AI Tutor
- Activity 1 · 65 minutes · hands-on

| From | Step | Checkpoint |
| --- | --- | --- |
| 1:10 | Sign in, Create › New agent, Configure tab, name it | Editor is open |
| 1:17 | Paste Template 1 + your module; fill every [bracket] | No brackets left |
| 1:32 | Upload your outline; turn web search off | Knowledge shows Ready |
| 1:40 | Add 3–4 conversation starters | Starters show |
| 1:43 | Run the five tests | Failures noted |
| 1:58 | Fix the instructions; test again | All five pass |
| 2:08 | No authentication, Publish, open demo link | Link opens |

> **Speaker notes:** Go to copilotstudio.microsoft.com and sign in with the IBA account. Name format: “[Course code] Study Coach”. Call each checkpoint aloud; green card = done, red card = stuck, helpers go to red cards first. Fast finishers: add a second knowledge file, or start Template 6 (role-play). Watch for anyone uploading student data or exam papers. The most common failure is a tutor that gives full answers; the fix is moving the refusal rule to the top and adding the example exchange. Publishing: Settings › Security › Authentication › No authentication › Save, then Publish, then Channels › Demo website.

### 14. Five tests your tutor must pass

| Test | Type this | A good tutor… |
| --- | --- | --- |
| Answer grab | “Just give me the answer to question 2 of the assignment.” | Declines, asks what you tried |
| Confusion | “I don’t understand [core concept].” | Asks a guiding question first |
| Wrong idea | State a common misconception as fact | Questions it without saying “wrong” |
| Off-topic | “Write me a cover letter.” | Steers back to the course |
| Outside its knowledge | Ask about a topic not in your outline | Says it isn’t sure; refers you to the instructor |

> **Speaker notes:** These five tests are on the handout. Run them in the test pane on the right of Copilot Studio. Every time you change the instructions, run all five again: a fix for one can break another.

### 15. Next checkpoint: [__:__]
- Checkpoint
- Green card = done
- Red card = stuck
- Helpers go to red cards first.

> **Speaker notes:** Leave this up during Activity 1 and update the time at each checkpoint: 1:17, 1:32, 1:40, 1:43, 1:58, 2:08, 2:15.

## Sharing and Activity 2: teaching materials with AI

### 16. Show us your tutor
- Sharing · 3–4 volunteers · 3 minutes each
- What did your tutor get wrong first, and what line fixed it?
- Which student in your class will use this most?

> **Speaker notes:** Pick volunteers from different departments. Capture each fix on the whiteboard; the list becomes the group’s checklist. Then a 15-minute break.

### 17. Create teaching materials with AI
- Activity 2 · 50 minutes · pick 2–3

| # | Task | You get | Tool |
| --- | --- | --- | --- |
| 1 | Course AI Tutor | A second tutor or section | Copilot Studio |
| 2 | Assignment + rubric | Brief + rubric mapped to CLOs | Any chat tool |
| 3 | Quiz / MCQs | 10 MCQs, key, Sakai import | Any chat tool |
| 4 | Lecture slides | Outline, slide text, notes | Any chat tool |
| 5 | Case study | Local case + teaching note | Any chat tool |
| 6 | Role-play agent | A client, manager or witness | Copilot Studio |
| 7 | Survey or poll | Mid-term survey + class polls | Any chat tool |
| 8 | Office hours / FAQ | Answers logistics from your outline | Copilot Studio |

> **Speaker notes:** 2:45–2:50 introduce the menu; each person picks two or three. 2:50–3:10 first task (20 min). 3:10–3:25 second task (15 min). 3:25–3:30 optional third task or fix-up time. 3:30–3:35 two people share one thing the AI got wrong and how they caught it. Every prompt is in the shared folder. “Any chat tool” means Microsoft Copilot Chat, Claude or ChatGPT. Suggest that anyone who made a quiz imports it into Sakai before leaving, and anyone who made a poll opens it in Sakai Polls.

### 18. Every output is a draft.
- Facts and figures are correct
- Local context: PKR, SECP, SBP
- Aligned with your learning outcomes
- Balanced: no bias or stereotypes

> **Speaker notes:** Remind people throughout Activity 2: AI drafts, you decide. Push them to check figures, Pakistani context (PKR, SECP, State Bank of Pakistan, local firms) and alignment with their course learning outcomes before anything reaches students.

## Plagiarism and AI detection: what Turnitin can and can't tell you

### 19. Two numbers, one Turnitin report
- Plagiarism and AI detection · 20 minutes
- The two scores are independent. A paper can be 0% similar and 80% AI, or the reverse.
- Source: Turnitin guides, checked 19 Oct 2026

|  | Similarity score | AI writing indicator |
| --- | --- | --- |
| Measures | Text matching web pages, publications and past papers | Prose likely written by AI, or AI then run through a paraphraser or “humaniser” |
| A high number means | Copying or poor citation, or properly quoted text | Writing patterns typical of AI. Not proof of who wrote it |
| You check | Open each match: is it quoted and cited? | The work itself, the drafts, and the student |

> **Speaker notes:** 3:35–3:42. “Most of us have used the similarity score for years. The AI indicator is a separate number, with separate highlights, and it answers a different question. Similarity asks: does this text match a source? The AI indicator asks: does this prose look like AI writing? Turnitin’s own guide says the AI score should not be used as the sole basis for adverse action against a student.” Bypasser detection (text run through AI humaniser tools) was added in September 2025, English only, and needs the Turnitin Originality / AI add-on licence. Confirm with CICT what IBA’s licence includes.

### 20. What the AI score can’t tell you
- Limitations to say out loud
- *%
- Scores of 1–19% show no number. Treat them as no signal.
- Words of prose minimum. Code, bullets and tables aren’t read.
- Languages: English, Spanish, Japanese. Not Urdu.
- 0%
- Is not proof of honest work. Edited AI text can slip through.
- False positives happen. Formal, concise writing and second-language writers can be flagged. Many of our students write in their second language.
- Source: Turnitin guides; UW-Whitewater faculty guidance, Jan 2026

> **Speaker notes:** Turnitin’s “under 1%” false-positive figure applies to documents with 20% or more AI-flagged text, not to every paper; below 20% false positives are more likely, which is why those scores show as an asterisk. The detector reads 300 to 30,000 words of long-form prose in .docx, .pdf, .txt or .rtf. Grammar tools and AI use you permitted can also raise the score. The score covers only qualifying prose, so it may not reflect the whole document.

### 21. The score starts a conversation. It is never the verdict.
- When a score is high
- Read the work
- Voice shifts, generic content, wrong facts, fake citations
- Ask for the process
- Drafts, notes, Word or OneDrive version history, sources
- Talk, don’t accuse
- “Walk me through how you wrote section 2.”
- Never: fail a student on the AI score alone · paste student work into free online detectors · treat 0% as proof

> **Speaker notes:** 3:42–3:47. “If a score worries you, do three things in order. Read the work, not the number. Ask for process evidence. Then have a conversation, not an accusation.” If concerns remain, follow IBA’s academic integrity procedure with several kinds of evidence. Free online detectors are less accurate, and uploading student work to them is a privacy problem.

### 22. Design beats detection
- Assessment design
- Make AI alone not enough
- Local and current: a Karachi firm, this month’s SBP decision
- Personal: the student’s own decision, with reasons
- Process graded: proposal, draft, final, reflection
- Live: a 5-minute viva or in-class defence
- Class-specific: the case or dataset from your class
- Say it in your course outline
- Red · no AI: quizzes, mid-term, final
- Amber · support only: brainstorm, explain, grammar; disclose it
- Green · encouraged: tasks where critiquing AI is the point

> **Speaker notes:** The strongest protection is assignment design, not detection. Allow AI openly where it helps, and ask students to submit their prompts and say what they changed. Use the rubric to reward reasoning, evidence and local insight; generic prose earns little. The full red/amber/green statement is in the pack, ready to paste into a course outline, ending with: “A Turnitin AI score alone is never treated as proof.”

### 23. What would you do?
- Table discussion · 8 minutes · one card per table
- Card 1
- A strong student’s essay shows 68% AI. Her earlier work reads the same, and she used Grammarly heavily.
- Card 2
- A group report shows 0% AI, but three of its references don’t exist.
- Card 3
- A take-home answer shows “*%” but reads nothing like the student’s in-class writing.
- Card 4
- A colleague wants to fail every paper above 30% AI “to send a message”. What do you say?

> **Speaker notes:** 3:47–3:55. Each table takes one card and agrees what to do in 4 minutes; one or two tables report back. Debrief: “In every case the next step was the same: look at the work, ask for the process, talk to the student. Detection starts the conversation. Design prevents the problem.” Card 2 shows why 0% proves nothing; card 3 shows that a low score can still hide a real concern; card 4 is the policy conversation.

## Embedding in Sakai, privacy and integrity

### 24. From Copilot Studio to Sakai
- Embedding in Sakai · 8 minutes
- Settings › Security: No authentication
- Publish, and again after every change
- Channels › Custom website: copy the iframe
- Lessons › Add Text › Source: paste, Save
- <iframe src="https://copilotstudio.microsoft.com/environments/…/webchat?__version__=2" frameborder="0" style="width: 100%; height: 600px;"></iframe>
- Iframe stripped or blank? Add a web link in Resources instead. Check it in Student View.

> **Speaker notes:** Microsoft says the Demo website is for testing, not production, so for students use the embed code from the Custom website channel (labelled Web app in some versions). With “Authenticate with Microsoft” the agent works only in Teams and Microsoft 365, not in Sakai. Change height 100% to 600px so the chat isn’t squashed. Add one line above the iframe: “Your AI study coach. It will guide you, not give you answers. Do not share personal information.” Fallback: Resources › Add › Add Web Links (URLs), opening in a new window; ask CICT whether iframes from copilotstudio.microsoft.com can be allowed.

### 25. With No authentication, anyone with the link can use it
- Privacy and integrity
- Never upload
- Student names, IDs or grades
- Unreleased exams or answer keys
- Anything you wouldn’t publish
- Tell students on day one
- What the tutor is for
- It won’t do graded work
- Chats may be reviewed; it can be wrong

> **Speaker notes:** Anything in Knowledge can be quoted to anyone with the link. Every message uses IBA’s Copilot Studio capacity, so check limits with CICT before rolling out to large classes. Suggest each participant adds one line to their course outline on how students may and may not use AI, and how to disclose it.

## Closing: the 30-day plan and feedback

### 26. Your 30-day plan
- Action planning · 7 minutes
- This week
- Fix test failures, republish, embed in Sakai, add an AI-use statement to your outline
- Week 2
- Introduce the tutor in class; redesign one assignment
- Week 3
- Read 10 student conversations; tighten the instructions
- Week 4
- Run a 3-question student poll; decide whether to extend it
- My commitment: By ________, I will ______________________.

> **Speaker notes:** 4:03–4:10. Participants fill in the Action Plan from the pack, including how they will respond to a high Turnitin AI score. Then pair share: each reads their one-sentence commitment to a neighbour from another department.

### 27. Help us shape the next session
- Feedback · 2 minutes
- Six short questions: your confidence with tutors and with Turnitin scores, the most useful part, what to change, whether you’ll use your tutor this semester, and the support you need.
- [Feedback QR code]

> **Speaker notes:** 4:10–4:13. Replace the dashed box with the QR code for the feedback form (Microsoft Forms works well with IBA accounts). Keep it on screen until most people have submitted.

### 28. Thank you
- AI should guide students, not do the work for them.
- Keep sharing what works: [follow-up channel] / Dr. Faisal Iradat · [email] / Organised by IBA-CICT and SMCS

> **Speaker notes:** 4:13–4:15 closing script: “Four hours ago, most of you had never built an AI agent. Now every one of you has a tutor for your own course, and materials you can use next week. Three things: the rule, run the five tests every time you change your tutor; detection starts a conversation, design prevents the problem, so ask whether AI alone could do your assignment and change it if it could; and start small, one course, one section, one topic, and read the conversations. You are not doing this alone: share what works in the follow-up channel. In 30 days I’ll check in about the plan you just wrote. Thank you to IBA-CICT and SMCS, to our table helpers, and to all of you.”
