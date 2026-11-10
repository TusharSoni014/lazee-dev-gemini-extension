# lazee.dev Jobs for Gemini CLI

Search open tech jobs from Gemini CLI. lazee.dev reads open roles from company
career pages every 12 hours and tags each one by role, seniority, country and
workplace.

This extension connects Gemini CLI to the lazee.dev Jobs MCP server
(`https://lazee.dev/mcp`) and adds a skill for finding jobs that fit what you
ask for.

## Install

```bash
gemini extensions install https://github.com/TusharSoni014/lazee-dev-gemini-extension
```

Then start `gemini` and ask, for example, "Find remote senior backend jobs
posted this week".

## Sign-in

The first time Gemini CLI connects, a lazee.dev page opens in your browser:
sign in with your lazee.dev account and select Allow. No API key needed. To
sign in again, run `/mcp auth lazee-dev-jobs` inside Gemini CLI.

Every tool call counts toward your lazee.dev account's monthly limit (Free 100,
Pro 5,000 calls, reset on the 1st, UTC).

## Tools

- `search_jobs`: filter by role, level, region, remote/hybrid/on-site, company,
  yearly pay range and posting date. Returns up to 25 jobs a page with the
  link to apply on the company's site.
- `get_job`: details of one job.
- `list_job_filters`: every accepted filter value and exact company names.
- `get_job_stats`: how many jobs and companies are tracked and when they were
  last refreshed.

All tools are read-only. The extension can't see your lazee.dev profile,
resumes or applications, and it never applies for you.

## Links

- Docs: https://lazee.dev/mcp-server
- Privacy: https://lazee.dev/privacy
- Terms: https://lazee.dev/terms
- Support: support@lazee.dev
