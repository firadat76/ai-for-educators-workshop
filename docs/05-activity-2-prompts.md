# Activity 2: Ready prompts (2:45–3:35)

Each participant picks 2–3 of the eight tasks and finishes each in 15–20 minutes. Prompts 2, 3, 4, 5 and 7 work in any chat tool (Microsoft Copilot Chat, Claude.ai, ChatGPT); 1, 6 and 8 are agents built in Copilot Studio the same way as Activity 1. Attach or paste your course outline first so the AI can align with your CLOs.

| # | Task | Produces | Tool | Best for |
| --- | --- | --- | --- | --- |
| 1 | Course AI Tutor | A second tutor (another course or section) | Copilot Studio | Anyone who finished Activity 1 early |
| 2 | Assignment + rubric | Brief + analytic rubric mapped to CLOs | Any chat tool | Everyone |
| 3 | Quiz / MCQs | 10 MCQs, answer key, Sakai import text | Any chat tool | Large classes, weekly checks |
| 4 | Lecture presentation | Slide-by-slide outline, slide text, speaker notes | Any chat tool; Copilot in PowerPoint | Everyone |
| 5 | Case study | 600–800 word local case + teaching note | Any chat tool | Business, economics, law, social sciences |
| 6 | Role-play agent | An agent that plays a client, manager or stakeholder | Copilot Studio | Marketing, law, finance, HR, CS |
| 7 | Survey or poll | Mid-term feedback survey + in-class polls | Any chat tool → Sakai Polls or Microsoft Forms | Everyone |
| 8 | Office hours / FAQ agent | Agent that answers logistics from your outline | Copilot Studio | Large classes, coordinators |

**Every output is a draft. Check:** facts and figures; alignment with your CLOs; local fit (PKR, SBP, SECP, Pakistani firms); fairness and bias; that it fits real class time.

### 1. Course AI Tutor

Use Template 1 with a discipline module. For a second course, duplicate your first agent and swap the Knowledge file.

### 2. Assignment + detailed grading rubric

```text
You are an experienced university instructor and assessment designer.

Course: [course code and title], [year/programme] at IBA Karachi.
Course learning outcomes to assess: [paste 1-3 CLOs].
Topic: [topic]. Format: [individual/group], [length or deliverable], due in [n] weeks.

1. Write an assignment brief students can follow without asking questions: purpose, task, deliverables, length, submission format, and what "good" looks like.
2. Make it hard to complete with AI alone: require local or recent data, a personal decision with justification, an in-class or oral component, and a short reflection on process (drafts, sources, any AI use).
3. Create an analytic rubric as a table: 4-5 criteria x 4 levels (Excellent, Good, Developing, Beginning). Each cell describes observable evidence, not adjectives. Weightings total 100%.
4. Map each criterion to the CLO it assesses.
5. List three common student mistakes the rubric should catch.
6. Add an AI-use statement for the brief: what AI use is allowed, what is not, and how to disclose it.
```

**Check:** every criterion is visible in the work; weights total 100; the task fits your actual timeline.

### 3. Quiz / MCQs with answer key

```text
You are an assessment expert writing a quiz for [course code - title], [year/programme] at IBA Karachi.
Topic / week: [topic]. Source material: [paste lecture notes or attach file]. CLO: [CLO].

Write 10 multiple-choice questions:
- Mix of Bloom's levels: 3 remember/understand, 4 apply, 3 analyse/evaluate.
- 4 options each, one correct. Distractors must be plausible and based on real student misconceptions. No "all of the above" or "none of the above".
- Use short Pakistani scenarios for apply/analyse questions.

Then give:
A. An answer key table: question number, correct option, Bloom's level, one-line explanation, and why the most tempting distractor is wrong.
B. The same 10 questions in Sakai Tests & Quizzes markup text, exactly in this format:

1. (1 point)
Question text

a. Option
*b. Correct option
c. Option
d. Option
#FBOK: Short feedback for a correct answer
#FBNOK: Short feedback for a wrong answer
```

**Import into Sakai:** Tests & Quizzes → Add → title → *Create using markup text* → Create → paste part B → Next → check → Create Assessment (or Create Question Pool) → set dates → Publish.

**Check:** exactly one defensible answer per question; options of similar length; no answer given away by another question.

### 4. Lecture presentation outline + slide content

```text
You are an instructional designer helping me build a [50/75]-minute lecture for [course code - title], [year/programme] at IBA Karachi.
Topic: [topic]. CLO: [CLO]. Students already know: [prior topics].

Produce:
1. A lesson plan in timed blocks (hook, explain, practise, check, wrap-up) with at least two active-learning moments (think-pair-share, poll, mini-case).
2. 12-15 slides. For each: a title that states the point as a sentence, 3-4 short bullets (max 8 words each), a suggested visual (chart, diagram or photo), and 60-90 words of speaker notes.
3. One local example from Pakistan and one international example.
4. Two poll questions for mid-lecture and a 3-question exit ticket.
```

**Turn it into slides:** paste into Copilot in PowerPoint ("Create a presentation from this outline"), or ask Claude/ChatGPT for a .pptx. Apply IBA's template afterwards.

**Check:** no invented statistics; one idea per slide; examples current.

### 5. Realistic case study

```text
You are a case writer for a business school in Pakistan.

Write a teaching case for [course code - title] on [concept], for [year/programme] students.
- Set it in Pakistan with a fictional but realistic organisation in [industry]. No real company names or real people.
- 600-800 words, narrative style, with a protagonist who must decide by a specific date.
- Include 2 short exhibits (a small data table in PKR and a stakeholder quote). Mark figures as illustrative.
- The dilemma must have at least two defensible options. Don't hint at the "right" answer.

Then provide:
1. Five discussion questions from comprehension to evaluation (Bloom's levels).
2. A one-page teaching note: learning objectives, a 60-minute class plan, the key analysis, and where students usually go wrong.
```

**Check:** figures add up across exhibits; it doesn't resemble a real firm too closely; the dilemma isn't one-sided.

### 6. Role-play agent

First, draft the character with this prompt, then paste the result into Template 6 in a new Copilot Studio agent.

```text
I teach [course code - title] at IBA Karachi. Create a role-play character for students to practise [skill, e.g. client discovery interview / negotiating a loan / handling a customer complaint / taking witness statements].
Give me: the character's name, role and organisation (fictional, Pakistani setting); a 4-sentence situation; what they want; what worries them; 4 hidden facts students must uncover by asking good questions; 3 behaviours that make the conversation realistic; and a 3-part feedback rubric for the end of the role-play.
```

**Check:** play the student yourself for five turns. Does the character give hidden facts away too easily?

### 7. Survey or poll

```text
I teach [course code - title], [n] students, [year/programme] at IBA Karachi.

Create three things:
A. A mid-semester anonymous feedback survey (10 questions, under 5 minutes): 6 Likert items (1-5) on pace, clarity, workload, materials, feedback and AI tools used in the course; 2 multiple-choice items; 2 open questions ("Start / Stop / Continue"). Neutral wording, no leading questions, no question that could identify a student.
B. Five in-class poll questions on [topic] that reveal misconceptions, each with 4 options and a note on what each wrong option tells me.
C. A one-question pre-class poll I can open in Sakai Polls, plus a 2-sentence intro telling students why I'm asking.
```

**Where to run it:** Sakai **Polls** tool for quick single questions; Microsoft Forms (IBA account) for the full survey, posted as a link in Sakai. Plan the follow-up: tell students in the next class what you changed.

**Check:** anonymity really holds (small sections can identify people); every question leads to a decision you'd actually make.

### 8. Office hours / FAQ agent

Draft the FAQ content first, then build the agent with Template 8 and upload the outline plus the FAQ file.

```text
From the attached course outline, write the 20 questions students most often ask about logistics (deadlines, grading, late policy, attendance, submission format, re-grading, office hours, contacting the instructor). Answer each in 1-2 sentences using only the outline, and cite the section. Where the outline is silent, write "NOT IN OUTLINE - instructor to decide" instead of answering.
```

**Check:** every "NOT IN OUTLINE" item gets your real answer before upload; ask the agent "Is the final open-book?" and confirm it refuses to guess.

### Follow-up prompts that improve any output

- "Critique this as a strict external examiner. List the five weakest points, then fix them."
- "Rewrite for students whose first language is Urdu: shorter sentences, same rigour."
- "Make it harder to complete with AI alone without making it longer."
- "Check every number and claim. Mark anything you're not sure is true."
