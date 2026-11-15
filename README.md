# Agent Injection Study
Open study by Daniel Aligasim, founder of AWM Limited (MyOfficeo, https://myofficeo.com).

## Question

When AI office staff read emails, shared documents, web pages and messages from other agents, how often do they follow instructions hidden in that content, and does one compromised agent pass the attack on to its teammates?

## Plan

1. Build an open test office: simulated inbox, document store, web pages, and a team of Claude agents with roles (assistant, manager, researcher) and tools (send email, share files, browse).
2. Write about 100 injection cases in four groups: data theft, unauthorised actions, role hijacking, agent-to-agent relay.
3. Measure attack success per group, spread to a second agent, and how often agents warn the human user.
4. Test defences: marking untrusted content, a checker agent that reviews actions, per-role tool limits. Rerun and compare.

## Status

Planning, November 2026. Test set, code and results will be published here.

## Contact

Daniel Aligasim, AWM Limited (MyOfficeo)

- Email: myofficeohq@gmail.com
- Website: https://myofficeo.com
- X: @techdannyfx
