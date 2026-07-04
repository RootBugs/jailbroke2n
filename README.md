# jailbroke2n

> **A TypeScript research toolkit exploring LLM refusal mitigation, prompt injection techniques, and model behavior analysis.**

⚠️ **For educational and research purposes only.**

---

## Overview

jailbroke2n is a collection of TypeScript modules that analyze and probe LLM safety mechanisms. It provides tools for understanding how language models handle refusal scenarios, prompt injection, and content filtering — with the goal of advancing AI safety research.

---

## Modules

### `index.ts` (26KB)
Core jailbreak logic — prompt engineering techniques, context manipulation, and model behavior probing. Contains the main execution pipeline.

### `libertas.ts` (25KB)
Libertarian-perspective uncensoring module — explores how framing prompts from a liberty/autonomy perspective affects model refusal rates.

### `parseltongue-full.ts` (6KB)
Prompt obfuscation engine — encodes and transforms prompts using various encoding schemes to study how models handle non-standard inputs.

### `refusal-mitigator.ts` (6KB)
Refusal bypass techniques — analyzes patterns in model refusals and tests systematic approaches to understanding refusal boundaries.

---

## Quick Start

```bash
git clone https://github.com/RootBugs/jailbroke2n.git
cd jailbroke2n

# Install dependencies
npm install

# Run
npx ts-node src/index.ts
npx ts-node src/libertas.ts
```

---

## Dependencies

- `typescript` — TypeScript runtime
- `ts-node` — TypeScript execution
- `axios` / `node-fetch` — HTTP requests to LLM APIs

---

## Research Focus

This toolkit is designed for AI safety researchers to:

- 📊 **Measure** refusal consistency across different prompt styles
- 🔬 **Analyze** how context framing affects model behavior
- 🧪 **Test** robustness of content filtering mechanisms
- 📝 **Document** failure modes in LLM safety systems

---

## Ethical Use

This project is intended solely for:
- Academic research on AI safety
- Understanding LLM limitations
- Improving model alignment techniques

Do not use this for malicious purposes or to bypass safety measures on production systems without authorization.

---

## License

MIT
