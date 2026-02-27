# Agent Setup Guide

## Purpose
This file guides AI agents (e.g., Copilot or Cursor) on repo setup and operations.

## Environment Requirements
- Node.js v18+
- Python 3.10+
- Install dependencies: npm install && pip install -r requirements.txt

## Setup Commands
1. Clone repo: git clone <repo-url>
2. Install: npm ci
3. Run dev server: npm run dev

## Coding Standards
- Use TypeScript for all new code.
- Follow ESLint rules.
- Commit messages: Use conventional commits (feat:, fix:, etc.).

## Testing
- Run tests: npm test
- Coverage threshold: 80%

## Deployment
- Build: npm build
- Deploy to Vercel: vercel deploy

## Agent-Specific Notes
- Always reference this file for context.
- Avoid direct file edits; use PRs.
