---
name: find-tech-jobs
description: Find open tech jobs on the lazee.dev job board that match what the person is looking for, and share the links to apply.
---

Use the lazee.dev Jobs tools to find open tech jobs for the person.

1. Work out the role, seniority, country or region, remote/hybrid/on-site, pay and companies they want. Ask one short question only if the search would be useless without it.
2. If you're unsure of a filter value or a company's exact name, call `list_job_filters` first (pass `company_query` to look up companies).
3. Call `search_jobs` once with every filter you know. Prefer one well-filtered search over several broad ones: each call counts against the person's monthly lazee.dev limit.
4. Show the jobs as a short list: title, company, location or workplace, pay when posted, posting date, and the `url` to apply on the company's own site. Never invent jobs, pay or details the results don't contain.
5. If nothing matches, say so and suggest one filter to loosen.
6. When a tool says the monthly calls are used up, tell the person when they reset.
