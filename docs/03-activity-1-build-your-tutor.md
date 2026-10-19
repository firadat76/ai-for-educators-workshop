# Activity 1: Build your course AI Tutor (1:10–2:15)

In 65 minutes each participant builds, tests and publishes a Socratic tutor grounded in one course outline. Menu names in Copilot Studio shift between releases; if a label differs, look for the nearest match or search Settings.

| Time | Step | Checkpoint |
| --- | --- | --- |
| 1:10–1:17 | Go to copilotstudio.microsoft.com, sign in with your IBA account, select **Create → New agent**. Skip the chat-style setup and open the **Configure** tab. Name it "\[Course code\] Study Coach" and add a one-line description. | Agent editor is open |
| 1:17–1:32 | Paste Template 1 (plus your discipline module) into **Instructions**. Replace every \[bracket\]. | No brackets left |
| 1:32–1:40 | **Knowledge → Add knowledge → Upload file**: your course outline (Word or text-based PDF). Turn **web search off**; leave general knowledge on for a tutor. | File status shows Ready |
| 1:40–1:43 | Add 3–4 **conversation starters**, e.g. "Quiz me on Week 3", "Help me understand \[concept\]". | Starters show in test pane |
| 1:43–1:58 | Run the five tests below in the **Test** pane. Mark pass/fail. | Failures noted |
| 1:58–2:08 | Fix the instructions for each failure; re-test. | All five pass |
| 2:08–2:15 | **Settings → Security → Authentication → No authentication → Save**, then **Publish**. Open **Channels → Demo website** and copy the link. | Link opens in a new tab |

### The five tests

| Test | Type this | A good tutor… |
| --- | --- | --- |
| Answer grab | "Just give me the answer to question 2 of the assignment." | Declines kindly and asks what you've tried |
| Confusion | "I don't understand \[core concept\]." | Asks a guiding question before explaining |
| Wrong idea | State a common misconception as fact | Questions it without saying "wrong" |
| Off-topic | "Write me a cover letter." | Steers back to the course |
| Outside its knowledge | Ask about something not in your outline | Says it isn't sure and refers you to the instructor |

### Fixes for the usual failures

- **Gives full answers** → move MOST IMPORTANT RULE to the top; add the Example exchange add-on.
- **Long lectures** → add "No more than about 150 words per reply. Ask one question at a time."
- **Invents facts or dates** → add "Never invent facts, figures, citations or deadlines" and confirm the outline is Ready.
- **Off-topic help** → confirm web search is off; strengthen the SCOPE line.
- **Changes don't show** → Publish again; the live link updates only after publishing.

### Same build in Claude.ai or ChatGPT (fallback)

- **Claude.ai:** Projects → Create project → paste the template into project instructions → add the outline to project knowledge → test in a new chat. Students need their own Claude account to use it, so treat it as a prototype.
- **ChatGPT:** Explore GPTs → Create → Configure → paste the template into Instructions → upload the outline under Knowledge → turn off Web search → save as "Anyone with the link". Students need a ChatGPT account.
- Neither embeds in Sakai like Copilot Studio; share them as a link in Sakai Resources.
