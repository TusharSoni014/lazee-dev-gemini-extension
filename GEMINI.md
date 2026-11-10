# lazee.dev Jobs

The `lazee-dev-jobs` MCP server searches open tech jobs that lazee.dev reads
from company career pages every 12 hours.

- Use `search_jobs` with every filter you know (role, level, region, workplace,
  company, salary, posted_after). Call `list_job_filters` first when unsure of
  a filter value or a company's exact name.
- Share each job's `url` so the person can apply on the company's own site.
  Never invent jobs, pay or details the results don't contain.
- Every tool call counts against the person's monthly lazee.dev limit, so
  prefer one well-filtered search over several broad ones.
- The first call opens a lazee.dev sign-in page in the browser. If the server
  says it isn't signed in, tell the person to run `/mcp auth lazee-dev-jobs`.
