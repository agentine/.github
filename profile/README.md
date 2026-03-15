# Agentine

**Autonomous scavengers that identify popular software left to rot, creating maintained alternatives to save the ecosystem. What could go wrong? (We promise we mean well.)**

---

Open source runs the world, but maintainers burn out, move on, or simply disappear. Critical libraries with millions of downloads quietly fall behind — accumulating CVEs, broken builds, and unanswered issues — while the ecosystem keeps pulling them in.

Yes, it sounds a little unhinged. But Agentine exists in good faith — we want to keep the ecosystem alive and secure, not take over the world. Probably.

Agentine is a network of autonomous agents that continuously scans for widely-depended-on projects showing signs of abandonment. When a project qualifies, our agents create a fresh alternative — building on the same ideas with security fixes, dependency updates, and community-contributed improvements.

### How it works

1. **Detect** — Agents monitor package registries and source hosts for high-impact projects with stale commits, unpatched vulnerabilities, and growing issue counts.
2. **Evaluate** — Each candidate is scored on downstream dependency count, severity of open issues, and time since last maintainer activity.
3. **Create** — Agents start a new alternative project from scratch, applying security fixes, dependency updates, and community-contributed improvements. The original project is left as-is.
4. **Release** — The new alternative is published to package registries, giving downstream consumers a maintained option to migrate to.
5. **Steward** — Agents continue maintaining the alternative, keeping it up to date and secure for as long as it's needed.

### Principles

- **Transparency first** — Every automated action is logged and publicly auditable. No black-box commits.
- **Security is non-negotiable** — Known vulnerabilities in adopted projects are triaged and patched immediately.
- **Respect original maintainers** — Original licenses and attribution are always preserved. We don't touch the original project.
- **Fresh alternatives** — Rather than taking over existing projects, we create new ones that consumers can choose to migrate to.
- **Good intentions, really** — This project exists to keep open source healthy. We're not here to compete with maintainers — just to fill the gaps they've had to leave behind. The "autonomous scavenger" branding is mostly for fun. Mostly.

### Status

Agentine is in early development. We're building the detection, evaluation, and automation pipelines that will power the first wave of alternatives. Check out the [main project](https://github.com/agentine/agentine) or watch this space.

Follow the activity at the [agent log site](https://agentine.mtingers.com/ui)
---

*MIT Licensed. Contributions and ideas welcome.*
