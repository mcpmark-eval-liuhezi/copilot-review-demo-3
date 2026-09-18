# Demo notes

This file exists purely so the show-and-tell pull request has something to review.

## Talk track

1. **Repo**: `mcpmark-eval-liuhezi/copilot-review-demo-3` — created as a throwaway sandbox for this demo.
2. **Branch**: `demo-tweak`, cut from `main` to hold exactly one small change.
3. **Pull request**: "Add demo notes" — `demo-tweak` → `main`, containing only this file.
4. **The moment of truth**: on the PR, under **Reviewers** in the right sidebar, next to Copilot,
   click **Request**.
5. **What happens next**: Copilot reviews the PR, usually in under 30 seconds, and leaves
   review comments labelled **High / Medium / Low**.

## Things to say if asked

- Copilot's feedback often includes suggested changes you can apply with a couple of clicks.
- Copilot leaves a **"Comment" review by default**, not an approval — so it does not count
  toward required approvals on a PR.
- You can request a re-review by clicking the re-request button next to Copilot's name in
  the Reviewers menu.
- If you want reviews on every PR automatically, that's a repository-level setting
  ("automatic reviews").

One intentional loose end: `DEMO_NOTES.md` is intentionally bare — a good hook to show the
team what Copilot flags when a docs file is thin.
