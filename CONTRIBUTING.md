# Contributing

Thanks for considering a contribution. This is a curated list, so the bar for inclusion is "would I tell a friend to read this?" rather than "does it exist?"

## Adding a Resource

1. **Find the right file.** Resources live in `resources/`, one topic per file. If a link could fit two topics, pick the more specific one.
2. **Match the format.** Each entry follows this shape:

   ```markdown
   - **[Name](URL)** — One-line "why". When would someone reach for this?
   ```

   The "why" matters more than the name. `[Modal](https://modal.com/) — Serverless ML infrastructure` is fine. `[Modal](https://modal.com/) — A platform.` is not.

3. **Don't duplicate.** Search the repo first (`grep -r "modal.com" resources/`) before adding. Links should appear in exactly one file.
4. **Group sensibly.** Keep entries under the right `##` subsection. If your link doesn't fit any existing subsection and you have only one entry for a new one, just add it to the closest subsection rather than creating a one-item group.

## What Doesn't Belong

- Self-promotion of low-effort content.
- Paywalled content where the free version is also good.
- Aggregator pages that mostly link elsewhere (link to the underlying resource instead).
- Anything that competes with an already-listed entry without being meaningfully better.

## Removing Stale Entries

Found a dead link, abandoned project, or resource that's been superseded? Open an issue or PR. The link checker catches outright 404s but not "the project is dead but the homepage still loads."

## PR Process

1. Fork, branch, edit the relevant file in `resources/`.
2. Run the link checker locally if you want: `lychee resources/your-file.md`.
3. Open a PR with a one-line description of what you added or changed.

## Don't Edit These Yourself

- `README.md` — generated/curated; PRs should target `resources/*.md`.
- `mkdocs.yml` navigation — only edit if you're adding a new top-level topic file.

## Code of Conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Short version: be kind, assume good faith, focus on the resources not the people.
