# Repository Guidelines

This repository tracks public content across the web that mentions or uses JuiceFS. The `README.md` file is the canonical catalog. Keep all catalog entries and descriptions in English, even when the linked content is in another language.

## Scope

Include public material that meaningfully mentions JuiceFS, especially:

- Articles, blog posts, case studies, tutorials, announcements, and news.
- Academic papers, technical reports, benchmarks, and research infrastructure writeups.
- Videos, conference talks, demos, podcasts, and livestream recordings.
- Social media posts from X, LinkedIn, Reddit, Hacker News, company forums, and similar platforms.
- Project pages, documentation, GitHub repositories, and release notes when they show a real JuiceFS use case.

Do not add private content, inaccessible links, pure SEO spam, or pages that only contain an incidental keyword match with no useful JuiceFS context.

Do not add content hosted on `juicefs.com`; it is official project content and should not be cataloged here.

## README Structure

Keep `README.md` as the primary human-readable list. Use these top-level sections when adding matching content:

- `Articles`
- `Papers`
- `Videos`
- `Podcasts`
- `Projects`
- `Reports and Benchmarks`
- `Mentions in social media`

Within each section, keep entries in reverse chronological order when a publication date is available. If no date is available, place the entry after dated entries in the most relevant section.

## Entry Format

Prefer one bullet per item:

```markdown
- Mon YYYY, [Title](https://example.com), short neutral description explaining who published it and how it relates to JuiceFS
```

For videos, include the channel or speaker and publication date when available:

```markdown
- [Title](https://example.com) from [Channel](https://example.com/channel), published at Month YYYY. Short description of the JuiceFS relevance.
```

For social posts, include the author, platform, and link:

```markdown
- Author, role or organization, mentioned JuiceFS on Platform: [short context](https://example.com/post). Short description of why it is useful.
```

Use concise descriptions. One sentence is usually enough; two sentences are acceptable when the content needs context. Avoid hype, sales copy, and unsupported claims.

## Quality Rules

- Write entries in English.
- Preserve the original title of linked content, including non-English titles.
- Prefer the original source over mirrors, reposts, summaries, or scraped copies.
- Exclude official JuiceFS project content hosted on `juicefs.com`.
- Verify that each link is reachable before adding it.
- Verify publication month and year when possible.
- Explain the JuiceFS relevance directly. Do not add links where JuiceFS is only a weak or ambiguous keyword match.
- Avoid duplicates. Search `README.md` for the URL, title, author, and organization before adding a new item.
- Fix obvious typos in nearby touched lines, but avoid unrelated rewrites.
- Keep personal notes rare and clearly marked, following the existing `Me:` style only when the note adds useful context.

## Update Workflow

When adding content manually or through Codex:

1. Read the relevant section of `README.md` first.
2. Check whether the item already exists by URL, title, author, organization, and topic.
3. Open or search the source when needed to confirm the title, date, publisher, and JuiceFS context.
4. Add the item to the best section using the established style.
5. Keep the list sorted by publication date within that section.
6. Run a quick diff review before finishing.

For larger updates, group related additions in a single pass and keep descriptions consistent across entries.

## Automation Guidance

Automations may periodically search the web for new public JuiceFS mentions. Useful search patterns include:

- `JuiceFS`
- `"JuiceFS" blog -site:juicefs.com`
- `"JuiceFS" Kubernetes -site:juicefs.com`
- `"JuiceFS" AI -site:juicefs.com`
- `"JuiceFS" training -site:juicefs.com`
- `"JuiceFS" benchmark -site:juicefs.com`
- `"JuiceFS" site:youtube.com`
- `"JuiceFS" site:x.com`
- `"JuiceFS" site:linkedin.com`
- `"JuiceFS" site:arxiv.org`
- `"JuiceFS" site:github.com`

Automation output should be treated as candidates, not as final catalog entries. Before editing `README.md`, verify each candidate, remove duplicates, and discard low-signal matches. If a candidate is useful but incomplete, prefer adding it only after the missing date, source, or JuiceFS relevance can be confirmed.

## Commit Hygiene

Keep commits small and topic-focused. A typical update should only touch `README.md` and, when process rules change, `AGENTS.md`. Do not reformat the whole README while adding a few entries.
