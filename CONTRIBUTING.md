# Contributing to WHY

Thanks for your interest in improving WHY. This is a small project with a clear mission: reduce cognitive debt from AI-assisted development. Contributions that serve that mission are welcome.

## What's Most Useful Right Now

**New question patterns.** The core multiple-choice format works, but there's a roadmap of deeper patterns (Spot the Bug, Predict the Output, Explain It Back). If you've got ideas for question types that force genuine comprehension, open an issue describing the pattern, when it should trigger, and why it's better than MC for that scenario.

**Language/framework coverage.** WHY is designed to be stack-agnostic, but the examples lean toward React/TypeScript. If you work in Python, Rust, Go, infrastructure-as-code, or anything else — and you spot a place where the skill's instructions could better adapt to your stack — PRs are welcome.

**Edge cases.** If you've used WHY and it behaved unexpectedly (wrong trigger, bad question quality, awkward tone), open an issue with the context. The SKILL.md is prompt engineering — real-world failure cases are the most valuable feedback.

**Difficulty scaling ideas.** The current version treats all developers the same. If you have thoughts on how to adapt question difficulty based on score history or code complexity, that's a conversation worth having.

## How to Contribute

1. **Issues first.** Please open an issue before a PR. This keeps effort focused and avoids wasted work.

2. **Fork and branch.** Fork the repo, create a branch from `main`, make your changes.

3. **Keep changes focused.** One concern per PR. A question pattern addition and a README rewording should be separate PRs.

4. **Test your changes.** If you're modifying the SKILL.md, test it in Claude Code (or your agent of choice) with a real code block. Describe what you tested and what happened in the PR description.

5. **Open the PR.** Describe what you changed and why. If it's a new question pattern, include an example of the pattern in action.

## What Won't Be Merged

- Changes that make WHY a gatekeeper (withholding code, blocking workflow).
- Generic textbook-style question templates. Every question must be contextual.
- Dependencies. WHY is a markdown file. Let's keep it that way.
- Aggressive or condescending tone in any user-facing text (be kind to each other)

## Code of Conduct

Be decent. Be kind. Be respectful. This is a learning tool, the same ethos applies to how we work together.

## Questions?

Open an issue or start a discussion. There's no Discord, no Slack, no mailing list. GitHub is the convo starter.
