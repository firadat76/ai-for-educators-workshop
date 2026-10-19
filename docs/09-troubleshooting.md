# Troubleshooting guide

Most problems on the day are sign-in, a tutor that gives answers away, or changes that don't show until republishing.

| Problem | Likely cause | Fix |
| --- | --- | --- |
| Can't sign in / "You don't have access" | No Copilot Studio licence, or wrong account | Use the IBA account; start the trial if offered; check with CICT. Meanwhile pair up, or build in Claude/ChatGPT with the same template |
| Asked to pick an environment | Several Power Platform environments | Use the one CICT names, otherwise the default |
| Tutor gives full answers | Refusal rule weak or late | Put MOST IMPORTANT RULE first; add the Example exchange; re-test |
| Tutor helps with off-topic requests | Web search on, or scope too loose | Turn off web search; strengthen SCOPE |
| Tutor invents facts or deadlines | No grounding or no uncertainty rule | Upload the outline; add "Never invent facts, figures, citations or deadlines" |
| Knowledge stuck on "In progress" | Large or scanned PDF | Wait 2–3 min; use Word or a text-based PDF; split big files |
| Agent ignores a new file | Not republished, or still processing | Wait for Ready, then Publish |
| Replies are long lectures | No length limit | "No more than about 150 words. Ask one question at a time." |
| Replies in English to Urdu | Language rule missing | "Reply in the language the student uses." |
| Test pane works, demo link doesn't | Not published, or authentication on | No authentication → Save → Publish → reopen link |
| Sakai shows a blank box | Iframe blocked | Try another browser; check Source view kept the iframe; use the web-link fallback |
| Sakai editor deletes the iframe | Rich-text editor strips iframes | Use a web link; ask CICT to allow the domain |
| Chat squashed in Sakai | height: 100% | Change to height: 600px |
| Students asked to sign in | Authentication set to Microsoft | No authentication + republish (only if content is safe to be public) |
| Sakai markup import errors | Format slipped (missing blank line, asterisk, or numbering) | Ask the AI: "Reformat exactly to Sakai markup: blank line after the question, asterisk before the correct letter"; import 3 questions first to test |
| MCQs have two right answers | Weak distractors | Follow-up prompt: "Check each question has exactly one defensible answer; fix any that don't" |
| Case figures don't add up | AI arithmetic | "Recalculate every figure in the exhibits and show the working" |
| Turnitin shows no AI score | Under 300 words, unsupported language or file, or AI feature not licensed | Check length and file type; ask CICT whether the AI indicator is enabled |
| Turnitin shows "\*%" | Score between 1% and 19% | Treat as no signal; don't act on it |
| Wi-Fi drops during demo | Room capacity | Play recorded captures; tether the trainer laptop to a phone |
| No course outline | Forgot it | Spare sample outline, or paste the course description from the IBA website |
| Participant far ahead | Experienced user | Build Template 6 or 8, or help a red-card colleague |
| Participant far behind | New to the tools | Pair with a helper; a working tutor in the test pane is enough — publishing can wait |
