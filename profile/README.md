![Thinking](thinker_rodin_sculpture.jpg)

# Code is Easy, State is Hard.
Building new applications has never been difficult. The real challenge has always been in performance, continuity and state management. Getting to production is just the beginning of the journey, and the real work lies in keeping the system stable while it grows.

## AI Declaration
LLMs are a force multiplier, not a replacement. My personal workflow relies on local LLM tooling (Pi Harness, Qwen models) to handle scaffolding, transformations and boilerplate. All core logic, architecture, state decisions are my own.

* Development: AI-assisted boilerplate and refactoring.
* Documentation: AI-generated readmes and auto-docs with manual review / edits.
* Insights: Blog posts and articles are my own words; AI is used for summaries and review.

## Portfolio
### [Pi Agent Sandbox](https://github.com/pragmatic-systems/Pragmatic.AgentSandbox)
A hardened, locked-down Docker environment for the Pi agent harness. Designed to provide a secure, reproducible developer tool chain with baked in agent.

### [CakeCI](https://github.com/pragmatic-systems/Pragmatic.CakeCI)
Platform agnostic CI / CD tool chain built in Dotnet Cake that can be run locally, or through GitHub, Jenkins, CircleCI. Dog-foods itself to verify, test and publish its own packages.

### [CQRS](https://github.com/pragmatic-systems/Pragmatic.CQRS)
Sub-set of MediatR functionality re-implemented from the interfaces using a local model. Experimenting with local bot tooling on recursive, generic problems and optimisation. This achieves functional and performance parity with the original, and comes without a license restriction.

### [TemplateApi](https://github.com/pragmatic-systems/Pragmatic.TemplateApi)
Production ready .Net Api + Postgres template, comes with job server and full OIDC / RBAC support, covered by a comprehensive test harness running on Test Containers. Currently just backend services and tooling, but front end is planned.