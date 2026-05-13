# Contributing

Thanks for helping keep this curriculum useful. The two most common contributions are **broken-link fixes** and **course suggestions**.

## Reporting a broken link

1. Check the [open issues](https://github.com/mvillaloboz/open-source-cs-degree/issues) to see if it's already been reported.
2. If not, open a new issue using the "Broken link" template. Include:
   - The current (broken) URL as it appears in the README
   - What happens when you visit it (404, redirect, paywall, etc.)
   - A replacement URL if you have one

## Suggesting a course

A good suggestion meets all of these:

- **Free to audit.** No paywall to access the lecture materials. Optional paid certificates are fine.
- **From a recognized institution** (university, well-established platform). Personal blog tutorials are out of scope.
- **Self-contained.** Lecture videos and/or notes are publicly available — not just a syllabus page that links to an internal LMS.
- **Reasonably current.** Course material updated within the last ~5 years, or a "classic" course that's still considered canonical (e.g. MIT 6.006, Berkeley CS61A).

Open an issue using the "Course suggestion" template, or send a PR directly if you're confident.

## Submitting a PR

1. Fork the repo and create a branch from `main`.
2. Make your change. Keep PRs **small and focused** — one course change per PR is ideal.
3. The link checker runs automatically on every PR. If it flags your link, please fix it before requesting review.
4. In the PR description, link to the issue you're addressing (if any) and explain why the change is an improvement.

## Style

- Course entries follow this format: `> [Institution Course Number](url) *(optional note)*`
- When multiple courses are listed as alternatives, separate them with `> *or*` on its own line.
- Trailing two-space line breaks are intentional — they render as line breaks in GitHub Markdown without inserting paragraph spacing.
- Prefer `https://` over `http://`.

## What this project is not

- It's not a comprehensive list of every free CS course online — it's an opinionated, structured path mirroring a 4-year degree.
- It's not a place for paid bootcamps, tutorial sites, or interview-prep platforms.
- It's not actively maintained by a team — be patient with response times, and feel free to ping if a PR has been sitting for a while.
