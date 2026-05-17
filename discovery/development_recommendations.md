# Development Recommendations

- **Tech Stack:** Go 1.23 (backend), PostgreSQL + TimescaleDB (time‑series), React/Next.js (web) + React Native (mobile), Terraform for infra.
- **CI/CD:** GitHub Actions with integration tests; Docker images on GHCR.
- **Modeling:** Use Snowflake or Redshift for analytics; integrate with AI services via OpenAI API.
- **Security:** Employ OWASP API Security Checklist.
