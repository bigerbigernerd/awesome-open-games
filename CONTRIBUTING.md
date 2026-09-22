# Contributing

Thanks for helping grow this list! A few rules keep the quality high.

## What belongs here

- The project must be **open source**: code published under an OSI-approved license
  (MIT, GPL, Apache-2.0, BSD, zlib, …) or an equivalently libre license.
- **Games** must be playable or buildable from source today (no dead prototypes).
- **Engine remakes** that need original commercial assets are OK — mark them with 🧩.
- **Assets** must be under libre terms (CC0 / CC-BY / CC-BY-SA / OFL or similar).
- No broken links, no forks/duplicates of an entry already listed, no spam.

## Entry format

```markdown
- [Name](https://github.com/owner/repo) — One-line description. `Tech` `License`
```

- Keep the description to one line, no hype words ("best", "ultimate").
- Prefer the canonical repo URL (github.com/owner/repo, correct case).
- License tag should match the repo's `LICENSE` file (SPDX-ish short form is fine).

## How to contribute

1. Fork the repo and create a branch.
2. Add your entry in the right section, keeping alphabetical order where it exists.
3. Check your links (CI runs [awesome-lint](https://github.com/sindresorhus/awesome-lint)).
4. Open a pull request describing what the project is and its license.

## Review checklist (for maintainers)

- [ ] Link works, repo is not archived/abandoned without note
- [ ] License verified in the source repo
- [ ] Placed in the correct section, format matches
- [ ] No duplicate of an existing entry
