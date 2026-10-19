# Embedding in Sakai

The tutor reaches students through one pasted iframe on a Sakai Lessons page; Microsoft says the Demo website is for testing, so use the Custom website (Web app) embed code for students ([Microsoft Learn](https://learn.microsoft.com/en-us/microsoft-copilot-studio/publication-connect-bot-to-web-channels)).

### Embed the tutor (8 minutes live)

1. **Set authentication.** Copilot Studio: Settings → Security → Authentication → **No authentication** → Save. With "Authenticate with Microsoft" the agent works only in Teams and Microsoft 365, not inside Sakai.
2. **Publish.** Wait for the confirmation. Republish after every change to instructions or knowledge.
3. **Copy the embed code.** Channels → **Custom website** (some versions: *Web app*). It looks like `<iframe src="https://copilotstudio.microsoft.com/environments/…/webchat?__version__=2" frameborder="0" style="width: 100%; height: 100%;"></iframe>`.
4. **Fix the height.** Change `height: 100%` to `height: 600px`.
5. **Add it to Lessons.** Course site → Lessons → Add Text → click **Source** in the editor → paste the iframe → Save. Add one line above it: "Your AI study coach. It will guide you, not give you answers. Don't share personal information."
6. **Check as a student.** Use Student View and send one test message.
7. **Fallback if blank or stripped.** Some Sakai setups block iframes. Add the agent link via Resources → Add → Web Links (URLs), or a Lessons link set to open in a new window. Ask CICT to allow copilotstudio.microsoft.com.

### Other Sakai tips from today

| Goal | Sakai tool | How |
| --- | --- | --- |
| Import AI-written MCQs | Tests & Quizzes | Add → *Create using markup text* → paste → Create Assessment or Question Pool → Publish |
| Quick in-class poll | Polls | Add a poll, paste one AI-drafted question and options, set open/close times |
| Full feedback survey | Resources or Lessons link | Build in Microsoft Forms, post the link |
| Share rubrics, cases, slides | Resources / Lessons | Upload the checked file; put the rubric next to the assignment |
| Introduce the tutor | Announcements | Post what it does, what it won't do, and that it can be wrong |
| Turnitin on submissions | Assignments | Enable the Turnitin / content review option when creating the assignment (if IBA's integration is on) |
| Role-play or FAQ agent | Lessons | Same embed steps; one agent per Lessons page, clearly titled |

### Privacy and integrity

- With No authentication, anyone with the link can use the agent and read anything it can quote. Upload only material you'd happily publish.
- Never upload student names, IDs, grades or unreleased exams.
- Every message uses IBA's Copilot Studio capacity; ask CICT about limits before using it with large classes.
- Tell students on day one: what the tutor is for, that it won't do graded work, that conversations may be reviewed to improve it, and that it can be wrong.
- Review transcripts after week one (agent Analytics) and tighten the instructions where it gave too much away.
