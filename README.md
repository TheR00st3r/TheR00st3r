# Hi, I'm Andreas

I write software for woodworking machines by day and tinker with everything else in the evenings. Most of my day job lives in private repositories, so this page is mostly the stuff I build for fun and for real people.

Lately I'm very into one question: what happens when you let AI agents work on real software, and how do you build things so that works well? I write C# and .NET, I like boring architecture that still makes sense in five years, and I really enjoy a good UI.

## What I'm working on

### [Elocaro](https://github.com/Elocaro/elocaro) ([elocaro.de](https://elocaro.de))
A free, self-hosted property management tool for small landlords: leases, rent accounts, bank import, utility cost statements, a tenant portal. It started because I wanted something I could run myself without handing my tenants' data to a SaaS. AGPL-3.0.

- .NET 10, Blazor Static SSR, PostgreSQL, Docker
- Architecture tests and written-down decisions (ADRs), so future me knows why things are the way they are
- Written with Claude Code, and it talks back: there is a read-only [MCP server](https://github.com/Elocaro/elocaro/blob/main/docs/mcp.md) with scoped tokens, so an assistant can answer "who is behind on rent?" without ever seeing more than you can, or changing anything. I'm still expanding it

### [Club management for our handball club](https://verein.handball-kinzigtal.de)
Teams, players, matches, volunteer duties, and a token-based login for parents so nobody needs yet another password. Blazor, MudBlazor and MariaDB, running for the [club](https://handball-kinzigtal.de). Source is private.

## Things I enjoy poking at

- MCP servers, agents and the question of how to give them useful context and sensible guardrails
- Getting an AI to drive a real UI with mouse and keyboard (and checking afterwards whether it actually did the right thing)
- WPF and Blazor, and making industrial software feel less like industrial software
- Self-hosting: Docker, Home Assistant, and too many small servers

## Tools of the trade

C# · .NET · WPF · Blazor · SQL (PostgreSQL, MariaDB) · Docker · Git · GitHub Copilot · Claude Code
