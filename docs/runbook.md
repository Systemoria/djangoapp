# Unknown from repository scan

Operational runbook suggestions:
- Common failures: database connection errors due to misconfigured DBHOST/DBUSER/DBPASS, ALLOWED_HOSTS not set when WEBSITE_HOSTNAME missing
- Diagnostics: check env vars, database connectivity, Django logs, static file storage
- Recovery: verify environment variable values, re-run migrations, restart app service if necessary
- Monitoring hints: log streams, health endpoints, application insights if configured (not present in repo)
