# About Me

Hey, I'm Niranjan, a junior at Columbia studying Computer Science and Applied Math. I like the layer underneath: runtimes, kernels, storage and the infrastructure makes stuff fast and reliable.

## What I'm Into Right Now

**Agents as programs, not prompts.** Most agent frameworks are a loop around an LLM call with tools bolted on. At [PASTA Lab] I work on ChitChat, an agent-oriented language in Rust. Agent logic is parsed into an AST and run by an evaluator, tools live behind a common trait and registry, custom tools run sandboxed, and model calls go through one provider-agnostic layer. Since agent behavior is a real program, you can inspect it, test it, and reason about it. We're also exploring reflection, so programs can inspect and rewrite their own structure.

**Infrastructure for agent platforms.** At Sarvam AI I worked on the backend of their agent platform: durable workflows on Temporal, a Postgres-backed memory layer for agents, replay testing with a fake LLM so workflow changes can't silently break runs already in flight, and hardening the boundary where users plug in their own MCP servers.

**Kernels.** This semester I'm writing Linux kernel code for my OS class and finally seeing what sits under the syscall boundary.

**Market structure.** I got into this simulating an exchange's pre-open order matching at the National Stock Exchange of India, and it's stuck with me since.

## Other Things I've Built

- **[Chess engine](https://github.com/NiranjanMedi/CubistHackathon)** for a quant hackathon
- **LiveCode**, a multiplayer code editor on CRDTs with sandboxed execution (in progress)
- **SecureUs**, a neighborhood safety app people actually used

## Tools I Reach For

Rust · Python · C/C++ · PostgreSQL · Temporal · Docker · Linux

## Socials

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:niranjan.mediratta@gmail.com)
