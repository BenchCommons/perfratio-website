# AGENTS.md — website-perfratio

Follow the org-wide rules in [BenchCommons/.github AGENTS.md](https://github.com/BenchCommons/.github/blob/main/AGENTS.md) and the decisions in [.product](https://github.com/BenchCommons/.product). This file only adds what is specific to this repo.

## Role
Site: marketing and documentation for perfratio. It consumes no benchmark data.

## Stack
React 19, vinext (Next-style app router) and Tailwind 4, deployed on Cloudflare Workers. Routes: `/`, `/pt/`, `/docs/`.

## Rules
- Repository links live in `app/config.ts` and should point to `BenchCommons/perfratio` (see issue #1); the site repository itself is `BenchCommons/website-perfratio`.
