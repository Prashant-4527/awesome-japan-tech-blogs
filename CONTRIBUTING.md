# Contributing to Awesome Japan Tech Blogs

First off — thank you! This list grows better with every contribution.  
Below is everything you need to know to add a blog, fix an entry, or suggest an improvement.

---

## 📋 Table of Contents

- [What belongs here](#-what-belongs-here)
- [What doesn't belong here](#-what-doesnt-belong-here)
- [How to contribute](#-how-to-contribute)
- [Adding a new company blog](#-adding-a-new-company-blog)
- [Adding a specific article](#-adding-a-specific-article)
- [Formatting rules](#-formatting-rules)
- [Review process](#-review-process)

---

## ✅ What belongs here

- **Engineering blogs** from Japan-based tech companies, startups, or research labs
- Content on: backend, ML/AI, LLMs, data engineering, mobile, devops, or related areas
- Blogs that are (or were) actively maintained — no abandoned side projects
- Both English and Japanese blogs are welcome (clearly labeled with 🇬🇧 / 🇯🇵)

---

## ❌ What doesn't belong here

- Marketing or product announcement blogs with no technical depth
- Personal blogs (unless they're the official channel of a Japanese tech company)
- Blogs not related to software engineering
- Paywalled content

---

## 🚀 How to contribute

### Option A — Open an Issue (easiest)

Use the [Add Blog issue template](https://github.com/Prashant-4527/awesome-japan-tech-blogs/issues/new?template=add-blog.md) and fill in the fields.  
A maintainer will review and add it.

### Option B — Submit a Pull Request

1. **Fork** this repo
2. **Edit** `README.md` following the formatting rules below
3. **Open a PR** with the title: `Add: [Company Name] Engineering Blog`
4. Wait for review — usually within a few days

---

## 📝 Adding a new company blog

Find the right category in `README.md` and add a new section using this template:

```markdown
#### Company Name `🟢` `🇬🇧` `🇯🇵`
> One-line description of the company and what makes their blog worth following.

🔗 https://their.blog.url/

| Title | Topic | Date |
|-------|-------|------|
| [Article Title](https://link.to/article) | Topic Tag | Mon YYYY |
```

**Rules for the section header:**
- Status badge: `🟢` Active (posts in last 12 months), `🟡` Occasional, `🔴` Archived
- Language badges: include only the languages available on that blog

---

## 📝 Adding a specific article

If you want to add an article to an existing company section, add a new row to that company's table:

```markdown
| [Descriptive Article Title](https://direct.link/to/article) | Topic / Subtopic | Mon YYYY |
```

**Article inclusion criteria:**
- The article should be technically substantial (not a press release or job posting)
- Link directly to the article, not the blog homepage
- Use the actual month + year, not "TBA" or "Ongoing"

---

## 🎨 Formatting rules

| Rule | Example |
|------|---------|
| Company names in `####` headers | `#### Mercari Engineering` |
| Recommended tag for top-tier blogs | `⭐` after company name |
| Blog URL on its own line with 🔗 | `🔗 https://...` |
| Tables for article listings | see template above |
| Index table updated for every new company | add row to the Company Blog Index |

**Status badges explained:**
- `🟢` — Posted in last 12 months
- `🟡` — 1–3 years since last post
- `🔴` — Archived or no posts in 3+ years

---

## 🔍 Review process

All PRs are reviewed for:

1. **Accuracy** — Does the blog exist and match the description?
2. **Engineering quality** — Is the content genuinely technical?
3. **Format** — Does the PR follow the template?
4. **Duplicates** — Is the blog already in the list?

We aim to review within **3–5 days**. If your PR sits longer than a week without feedback, ping us in the issue thread.

---

Thank you for making this list better! 🇯🇵
