# junaid-tutor

A Claude Code plugin that turns Claude into a personal tutor for **The AI Agent Factory** (agentfactory.panaversity.org).

It bundles two things:

- **Skill** (`skills/zia-tutor-ai`): how the tutor teaches. One concept at a time, quizzes before moving on, and it keeps your learner record up to date.
- **MCP server** (`.mcp.json`): connects to `https://zia-tutor-ai.panaversity.org/mcp` for the book content and your learner record. It signs in with OAuth the first time you use it.

## Install

At the prompt of a Claude Code terminal session:

```
/plugin install junaid-tutor --marketplace mjunaidca/junaid-tutor
```

From a shell:

```
claude plugin install junaid-tutor --marketplace mjunaidca/junaid-tutor
```

In the desktop app: click **+** next to the prompt box, then **Plugins**, **Add marketplace** with `mjunaidca/junaid-tutor`, then **Add plugin**.

## Use

After installing, run `/mcp` and sign in to the tutor server. Then just ask, for example: "I'm new to AI, where do I start?" or "Continue where I left off."

## License

MIT
