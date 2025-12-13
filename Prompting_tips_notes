## Notes for poscast

### State-Of-The-Art Prompting For AI Agents

- Good prompts include (example: https://parahelp.com/blog/prompt-design):
  - A role
  - A logical breakdown and step-by-step plan for the task, with specifics: what to do in step one, step two, etc.
  - Important details, such as which behaviors are undesired and which details must be present
  - The structure of the output (how many sections in total, what the first section is, what the second section is, etc.)
  - An example of the desired output
- A good prompt needs to clearly lay out the logical structure of the task.
- Metaprompting: feed the AI your prompt plus examples where existing prompts performed poorly, and ask the AI to improve the prompt itself.
- When a task is very complex, you can improve output quality by providing many examples.
- To avoid hallucinations, add something like this into the prompt: “If you do not have enough information, don’t make things up. Stop and ask me.”
- Add a debug section: tell the AI to include, in its output, a part that tells humans what needs to be improved or further clarified, presented as a todo list.
- You can also inspect the model’s chain-of-thought (its reasoning process) to discover weaknesses in your prompt.
- If the prompt becomes very long, you can write it into a document, then feed that document to the AI and have the AI edit/produce a refined version.

---

### AI Prompt Engineering: A Deep Dive  
(Repeated points are already bolded above)

- (Contrary to some existing advice) do not give the model a “role”; instead, treat the model as a colleague. If the model already understands a concept, you can directly ask it to do the concrete task without assigning a persona.
- Do not rely on analogy to a similar task; it’s better to describe the current task clearly and directly.
- The best method is to use clear natural language to describe the task.
- Provide a defined output for unknown inputs (may be less relevant in personal use cases). For example, if you have an agent that only works with text and Excel files, you can tell the model that if it encounters an unknown input type (e.g., an image), it should simply output “unknown.”
- You can also let the AI write the prompt: give the AI some context/content and ask it to draft a prompt for the task.
- Tips for improving your prompt-writing skills:
  - Use prompts frequently: write and test many of them.
  - Carefully read the model’s outputs and (when available) its reasoning process.
  - Keep iterating: write a prompt, look at the model’s output, analyze it, refine the prompt, and repeat.
  - Describe your needs as clearly and directly as possible.
  - Ask the model for feedback—have it tell you whether your prompt is clear.

---

### Resources

- YC podcast（State-Of-The-Art Prompting For AI Agents）：https://youtu.be/DL82mGde6wo?si=c_R5cClWW2tQVv1e
- Anthropic podcast（AI prompt engineering: A deep dive ）：https://youtu.be/T9aRN5JkmL8?si=WGJt4gYrsjrAqp_v
- Anthropic workshop（Prompting 101 | Code w/ Claude）：https://youtu.be/ysPbXH0LpIE?si=H6lR0BcKlhz8QH3O
- Dan Koe (How To Use AI Better Than 99% Of People) : https://youtu.be/xgpLjLHB5sA?si=7z42s5FMBjSmw7WO
- Dan Koe's Meta prompt (prompt about prompt): https://docs.google.com/document/d/1T5dPX1tpivAwnKgKgqW7tkHA20c9GGegPgm6mSADpS8/edit?usp=sharing
