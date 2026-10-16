# Jon Sundin

I build software that makes complex information easier to understand without losing its structure or the context it came from. Right now that means **[Margin Chat](https://github.com/jmsundin/margin-chat)**.

## Margin Chat

**[marginchat.com](https://www.marginchat.com)** · [repo](https://github.com/jmsundin/margin-chat)

An AI notebook built around one idea: chats scroll away, ideas shouldn't. Highlight any passage and ask about it in the margin. The answer opens beside the document as its own note, linked to the exact passage it came from, and the original stays where you left it.

![Highlighting a passage and asking AI about it opens the answer as a side document linked to the passage](https://github.com/jmsundin/margin-chat/raw/main/docs/media/readme/ask-ai-side-document.gif)

What it does today:

- **Branch, don't scroll.** Ask about a passage and get the answer as a linked side document, or add a private margin note next to the line that sparked it.
- **Local-first Markdown vault.** Every document, answer and note is a plain Markdown file with `[[wiki links]]`. Point it at a folder (an Obsidian vault works), sync to the cloud, or import a zip.
- **Map view.** Notes become a graph you can arrange, cluster by links or meaning, and zoom into until the cards are editable documents.
- **Agent mode.** Ask AI can work through your vault on its own: searching by words and meaning, reading pasted pages and PDFs, and showing each step and source it used.
- **MCP server.** Claude Code, Cursor, VS Code and other agents can search, read and add to your cloud vault through the same tools Agent mode uses.
- **Bring your own model.** OpenAI, Anthropic, Gemini, xAI or Hugging Face with your own keys, with a record on each answer of which model ran, why it was picked, and what context it saw.
- **Everywhere you read.** Web app, an Electron desktop app for Mac, Windows and Linux, and a Chrome extension that opens the workspace on top of any page.

Built with React 19, Vite, TypeScript and Tiptap on the front end; Node, Postgres with pgvector and Vercel Blob on the back end; Bun as the monorepo toolchain. I build it with AI coding agents and review, test and ship what they produce; every commit on `main` releases to production once CI passes.

**Next:** an evaluation set for retrieval and answer quality in Agent mode, and a small Python (FastAPI) service over the vault.

## Earlier work on the same problem

- **[Infoverse AI](https://infoverse.ai)**: search Wikipedia and see a topic as an interactive graph, with articles in a split pane. Next.js, TypeScript, D3.
- **Tangible AI**: built a D3.js conversation graph for a chatbot builder (Django/DRF), and earlier did Python NLP work with spaCy, embeddings and NetworkX.
- **AI LA Cerebral Beach GenAI Hackathon**: 1st place, Sports & Media track (Oct 2024).

## Day to day

Full-stack engineer on internal enterprise workflow applications: Angular, TypeScript, Java and Spring Boot, REST, PostgreSQL, and a lot of testing. Before that I was an SDET working in Playwright, Cypress and Rest Assured.

Where I'm heading: applied AI engineering, building agentic applications that handle tool use, context, branching and evaluation well.

## How I work

Learn, plan, act, observe, revise, repeat. And before switching to something new: first do more, then do better, then do new.

## Contact

- LinkedIn: [linkedin.com/in/jonsundin](https://www.linkedin.com/in/jonsundin/)
- X: [@JonSundin](https://x.com/JonSundin)
