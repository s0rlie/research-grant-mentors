# research-grant-mentors
Interview-based system prompts for developing research grant applications (FRIPRO; more calls planned). Asks questions rather than writing text. Optimised for NTNU's IDUN LLM services.

Read the policy for Use of ICT tools with generative artificial intelligence at NTNU carefully before using the system prompt.
[Link to policy](https://i.ntnu.no/wiki/-/wiki/English/Use+of+ICT+tools+with+generative+artificial+intelligence+at+NTNU+-+policy)

## NTNU FRIPRO Mentor

File: [`ntnu-fripro-mentor.md`](ntnu-fripro-mentor.md). Planned work is in the [roadmap](docs/ROADMAP.md).

| | |
|---|---|
| **Best for** | Researchers who plan an application to FRIPRO, the Research Council of Norway's scheme for ground-breaking research. The mentor helps you choose a call, develop an idea into a project description, and review a draft. |
| **Calls covered** | Early Career Scientists, Radical Research Ideas, Experienced Scientists, and International Mobility. |
| **How it works** | It interviews you. It asks you to state your idea in one sentence before it helps you draft. It reviews a draft against the assessment criteria and the project description template. |
| **Sources** | The call texts and project description templates on [forskningsradet.no](https://www.forskningsradet.no/en/Portfolios/ground-breaking/fripro/). The call facts are written into the prompt. The mentor does not search the web. |
| **Call facts last checked** | 13 October 2026. |
| **Not included** | Top Researchers and other programmes. Budget tables and the application form. Your institution's internal deadlines and procedures. |
| **It does not judge the science** | The mentor assesses how clearly a claim is stated and how well the parts of the proposal fit together. It cannot tell you whether an idea is new, important or correct. |

### Check the result

- **Call rules:** the call text on forskningsradet.no is the authority. Ask fripro@rcn.no when the call text does not answer your question.
- **The science:** ask a colleague in your field to read the proposal before you submit. The mentor cannot replace that review.
- **Your application:** speak to the research adviser at your institution.
- **Use of AI:** check the funder's current rules on the use of AI in applications. You are responsible for everything you submit.

### Ways to start

At NTNU the mentor has these six conversation starters. If you set the mentor up on another platform, add the same six: the prompt expects one of them as the opening message.

- I don't know which FRIPRO call I should apply for
- Tell me the differences between the FRIPRO calls
- I have an idea and want to develop it into an application
- I have a draft I want feedback on
- I was rejected and want to improve my application
- Show me the journey from idea to submitted proposal

### Set-up

1. Create a custom assistant in your chat service.
2. Copy everything between `# SYSTEM PROMPT — START` and `# SYSTEM PROMPT — END` into the instructions field.
3. The last section contains the line `Today's date: {{current_date}}`. If your platform uses a different date variable, replace the placeholder. If it has none, leave the line as it is: the mentor then asks you for the date.

### Limitations

These limits come from how language models work. They apply to every assistant of this kind.

- **It knows only its instructions and what you write.** It does not look up the call text, the Research Council's website or the literature in your field. Its call facts are fixed at the date above.
- **It has no memory between conversations.** A new conversation starts from nothing. Paste your one-sentence idea or your draft again when you return.
- **A long conversation can outgrow what the model reads.** The earliest messages then drop out or are replaced by a summary, and the mentor does not tell you. If it forgets something you said, start a new conversation and paste a short summary.
- **It may not see everything in a file.** The platform reads the text of a PDF or Word file. Figures, a Gantt chart and the page layout may not come through, and the mentor cannot count the pages of your project description. It can read an image within the limits of the model, but text and images sent together can cause problems. If you are unsure, ask the mentor what it can see.
- **It sounds equally certain when it is right and when it is wrong.** The tone of an answer tells you nothing about its accuracy. This includes rules that are in its instructions.
- **The same question can give a different answer.** Answers vary from one attempt to the next, and from one model to another.
- **It leans towards agreement.** Language models tend to agree with the person they talk to. Ask it for the weaknesses.
- **It can invent references.** A paper, author or result that it mentions may not exist. Check every reference yourself.
- **It does not know today's date unless the platform or you supply it.** Eligibility depends on dates, so give the date if it asks.
- **Text it writes tends towards common phrasing.** Keep your own formulations where they carry your idea.
