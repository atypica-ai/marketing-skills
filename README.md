# Atypica.AI Marketing Skills

A collection of AI agent skills focused on marketing research and product innovation. Built for marketers, founders, and product teams who want AI coding agents to help with market sizing, competitive analysis, and product innovation reporting. Works with Claude Code, OpenAI Codex, Cursor, Windsurf, and any agent that supports the [Agent Skills spec](https://agentskills.io).

Built by the [Atypica.AI](https://atypica.ai) team. Atypica.AI is a consumer intelligence platform that lets you simulate real user voices — helping marketers, product managers, and founders understand their market deeply without traditional research delays. These skills bring the same research rigor directly into your AI agent workflow. [Try Atypica.AI →](https://atypica.ai)

Run into a problem or have a question? [Open an issue](https://github.com/atypica-ai/marketing-skills/issues) — we're happy to help.

## What are Skills?

Skills are markdown files that give AI agents specialized knowledge and workflows for specific tasks. When you add these to your project, your agent can recognize when you're working on a marketing or research task and apply the right frameworks and best practices automatically.

## Available Skills

<!-- SKILLS:START -->
| Skill | Description |
|-------|-------------|
| [market-sizing](skills/market-sizing/) | Produce a rigorous, sourced TAM/SAM/SOM market sizing for any product or business. Use whenever a user asks about market size, total addressable market, SAM, SOM, or market opportunity — across any industry including SaaS, AI tools, consumer brands, F&B, fashion, beauty, and more. |
| [product-rnd](skills/product-rnd/) | Generate professional Product Innovation Research & Development reports as polished HTML. Conducts research, applies consulting-grade analysis frameworks, and produces shareable reports for senior decision-makers. |
| [html-to-pdf](skills/html-to-pdf/) | Convert any HTML file to a faithful PDF, preserving CSS layout, Tailwind styles, colors, and fonts. Use to export or share an HTML report as PDF. |
| [plan-as-consultant](skills/plan-as-consultant/) | Plan a business research study the way a professional consultant would — selecting the right analytical framework (JTBD, KANO, STP, GE-McKinsey, etc.), designing the research method, and defining a specific actionable output. Use this skill when someone has a business question to research: product decisions, user understanding, market analysis, pricing strategy, brand positioning, feature prioritization, or competitive strategy. |
| [atypica-user-interview](skills/atypica-user-interview/) | Run AI-simulated user interviews and focus group discussions using atypica.ai's library of human-like personas. Use whenever you need user research, product feedback, UX testing, or want to understand what different types of real people think — without recruiting actual participants. |
| [logo-design](skills/logo-design/) | Design professional logos as SVG code with browser preview. 9-phase workflow: discovery, market research, letterform analysis, design direction, color strategy, typography, SVG implementation, delivery (3 concepts), and iterative refinement. |
<!-- SKILLS:END -->

## Installation

### Option 1: Clone and Copy (Recommended)

```bash
git clone https://github.com/atypica-ai/marketing-skills.git
cp -r marketing-skills/skills/* .agents/skills/
```

For Claude Code, also symlink into `.claude/skills/`:

```bash
mkdir -p .claude/skills
cp -r marketing-skills/skills/* .claude/skills/
```

### Option 2: Git Submodule

Add as a submodule for easy updates:

```bash
git submodule add https://github.com/atypica-ai/marketing-skills.git .agents/marketing-skills
```

Then reference skills from `.agents/marketing-skills/skills/`.

### Option 3: Fork and Customize

1. Fork this repository
2. Customize skills for your specific industry or workflow
3. Clone your fork into your projects

### Option 4: npx skills (if using Agent Skills CLI)

```bash
# Install all skills
npx skills add atypica-ai/marketing-skills

# Install specific skills
npx skills add atypica-ai/marketing-skills --skill market-sizing

# List available skills
npx skills add atypica-ai/marketing-skills --list
```

## Usage

Once installed, just ask your agent to help with research and marketing tasks:

```
"What's the market size for AI-powered consumer research tools?"
→ Uses market-sizing skill

"Run a TAM/SAM/SOM for a B2B SaaS targeting mid-market retailers"
→ Uses market-sizing skill with b2b-saas example

"Generate a product innovation report for this new snack concept"
→ Uses product-rnd skill

"Create an investor-ready market analysis for our pitch deck"
→ Uses market-sizing + product-rnd skills together

"Export this HTML report as a PDF"
→ Uses html-to-pdf skill

"Interview 5 users about their morning routine and spending habits"
→ Uses atypica-user-interview skill

"Design a logo for my fintech startup called NexaFlow"
→ Uses logo-design skill

"Create a brand mark for a coffee shop called Brew & Co"
→ Uses logo-design skill
```

You can also invoke skills directly:

```
/market-sizing
/product-rnd
/html-to-pdf
/atypica-user-interview
/logo-design
```

## License

[MIT](LICENSE) — Use these however you want.
