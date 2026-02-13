# Knowledge Base Index

## Purpose

This index keeps the marketing knowledge base searchable and maintainable as a documentation-only repository.

## Document Catalog

| Domain | File |
| --- | --- |
| Recruitment | `Barbara Bruno-High‑Tech High‑Touch Recru.md` |
| Recruitment | `Geoff Smart and Randy Street’s Who-The A Method for Hiring.md` |
| Recruitment | `Jeff Hyman’s Recruit Rockstars.md` |
| Recruitment | `Katrina Collier_ The Robot‑Proof Recruiter.md` |
| Recruitment | `Laszlo Bock-Work Rulesmd.md` |
| Recruitment | `Mark Murphy-Hiring for Attitude.md` |
| Marketing | `Building-a-StoryBrand-Donald-Miller.md` |
| Marketing | `Marketing-Management-Philip-Kotler.md` |
| Marketing | `Ogilvy-on-Advertising-David-Ogilvy.md` |
| Marketing | `Positioning-Al-Ries-and-Jack-Trout.md` |
| Marketing | `Purple-Cow-Seth-Godin.md` |
| Marketing | `The-Brand-Gap-Marty-Neumeier.md` |
| Marketing | `The-Lawyer-Marketing-Book-Matt-Staroscia.md` |
| Marketing | `The-Tipping-Point-Malcolm-Gladwell.md` |
| Marketing | `This-Is-Marketing-Seth-Godin.md` |
| Strategy | `All_books.md` |
| Strategy | `How Brands Grow (Vol 1 & 2) – by Byron S.md` |
| Strategy | `Scaling-Startups-Jason-Quey.md` |
| Strategy | `The-E-Myth-Attorney-Gerber.md` |
| Strategy | `The-Next-CMO-Operational-Excellence.md` |
| Strategy | `Traction-Weinberg-Mares.md` |

## Naming Rules

- Use `Title-Author.md` format for new summaries.
- Keep one topic per file.
- Prefer ASCII punctuation in filenames for cross-platform compatibility.

## Validation

The CI workflow runs markdown link checks. Run locally with:

```bash
lychee --offline --accept 200,429 --no-progress '*.md'
```
