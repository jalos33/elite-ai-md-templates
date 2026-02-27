# Deployment Checklist

## Pre-Deployment
- [ ] Run all tests.
- [ ] Build artifacts.
- [ ] Security scan.

## Cloud Setup
- AWS: Use EC2 or Lambda.
- Vercel: npm run deploy.

## Post-Deployment
- [ ] Monitor logs.
- [ ] Rollback plan: Git revert.

## Example Script
Bash deploy script
git push origin main
vercel --prod
## Common Pitfalls
- Env vars missing.
- Port conflicts.
