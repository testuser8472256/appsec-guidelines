# Vulnerability Scanning Policy

## Static Analysis (SAST)
- Use Semgrep to scan all pull requests automatically via Github Actions
- Run full SAST scan on every merge to main branch

## Dynamic Analysis (DAST)
- Use OWASP ZAP to run weekly scans against staging environment
- Any High/Critical findings must be resolved before production deployment
