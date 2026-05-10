# Personal Experience Review Prompt Template

A structured AI prompt template for conducting in-depth personal experience reviews through a two-phase interview and writing process.

[中文文档](README.zh-CN.md)

## What Is This?

This is a prompt template designed to help you systematically review and reflect on any period of your life — career development, entrepreneurial journey, learning and growth, annual summary, and more.

Instead of asking AI to "help me write a review," this template turns AI into a professional interviewer who asks targeted follow-up questions phase by phase, and then produces a comprehensive review document with three parts:

1. **My Story** — A first-person chronological narrative of your experience
2. **An Observer's Commentary** — An objective third-party analysis of your patterns, strengths, and weaknesses
3. **Issues to Address** — Prioritized problems with actionable next steps

## How It Works

The template follows a two-phase process:

### Phase 1: Interview

You provide a rough starting point (timeline + brief description). The AI then asks follow-up questions to dig deeper into:

- What exactly you did (specific projects, actions, deliverables)
- Why you did it (context, motivation, catalyst)
- What the results were (outcomes, feedback, gains and losses)
- Your subjective feelings and thoughts at the time
- Causal relationships and turning points between events

The AI asks one direction at a time, never overwhelming you. When a period is covered, it moves on to the next.

### Phase 2: Writing

After the full interview, the AI produces a complete review document with the three parts described above.

## Quick Start

1. Go to [`prompt/en.md`](prompt/en.md) (or [`prompt/zh-CN.md`](prompt/zh-CN.md) for Chinese)
2. Copy the **System Instructions** block
3. Paste it at the beginning of a new AI conversation
4. Follow it with your own opening narrative, e.g.:

> I want to review my career development over the past year. The starting point is June 2025. I had just left Company A because... Then I spent two months job hunting... In September, I joined Company B... Start by asking me follow-up questions about these, and after you're done, I'll continue with what happened next.

**Tip:** If you use Claude Projects, paste the System Instructions into the Project's Custom Instructions for automatic application in every new conversation.

## Example Output

See the [`examples/`](examples/) directory for a full example of a review document produced using this template:

- [`examples/en.md`](examples/en.md) — English example
- [`examples/zh-CN.md`](examples/zh-CN.md) — Chinese example

The example covers a university student's AI-era journey from indifference to AI to simultaneously participating in two AI projects, including hackathon wins, internship experiences, and startup involvement.

## File Structure

```
personal-review-prompt/
├── README.md              # English README (this file)
├── README.zh-CN.md        # Chinese README
├── prompt/
│   ├── en.md              # English prompt template
│   └── zh-CN.md           # Chinese prompt template
├── examples/
│   ├── en.md              # English example output
│   └── zh-CN.md           # Chinese example output
└── LICENSE                # MIT License
```

## Design Principles

- **Interview-first approach**: The AI doesn't jump to conclusions — it asks questions first to understand your full story
- **One question at a time**: Never overwhelming, always focused
- **Objective and direct**: No excessive comfort or flattery — honest analysis is the goal
- **Actionable output**: Every identified issue comes with concrete next steps
- **Priority-based problem solving**: Foundational issues > high-leverage issues > specific skill gaps

## Compatible AI Tools

This template works with any AI model that supports system instructions or long-context conversations, including:

- Claude (Anthropic)
- ChatGPT (OpenAI)
- Gemini (Google)
- DeepSeek
- And other similar AI assistants

## License

[MIT](LICENSE) — Feel free to use, modify, and distribute.
