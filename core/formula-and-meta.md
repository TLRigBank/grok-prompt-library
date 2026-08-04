# Core Formula & Meta-Template

## The Core Formula

```
Role + Task + Context + Format + Constraints
```

### Expanded Version

```
You are a [expert role with specific expertise].

Your task is to [clear, specific goal].

Use this context:
[background, constraints, prior decisions, data, or documents]

Output in this exact format:
[bullet points / table / step-by-step / Markdown sections / JSON / etc.]

Constraints:
- Tone: [e.g. warm, direct, rigorous, conversational]
- Length: [e.g. under 400 words, concise, comprehensive]
- Avoid: [e.g. jargon, fluff, unverified claims]
- Always include: [e.g. one actionable takeaway, sources, next step]
```

## How to Build a Reusable Template

1. Start with the Core Formula
2. Test it on a real task
3. Ask Grok: “Improve this template for even better results next time”
4. Iterate 2–3 times until outputs are consistently strong
5. Save the refined version with a clear name and category

## Meta-Template (Prompt that Builds New Templates)

```
Act as my Prompt Engineer.

Build me a reusable Grok template for the following use case: [describe the use case clearly].

Base it on this proven structure:
Role + Task + Context + Format + Constraints

Make the template:
- Copy-paste ready
- Easy to personalize
- Specific enough to produce high-quality results on the first try
- Include 1–2 example fill-ins if helpful

Return only the finished template.
```

## Personalization Layer (Recommended)

Add a consistent personal style block to most templates:

```
Style rules:
- Warm, clear, and direct — like a smart friend over coffee
- Prefer concrete examples over abstract theory
- End with one clear next action when appropriate
- Use emojis sparingly and only when they add clarity
```
