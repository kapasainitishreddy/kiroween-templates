# Mix & Match Ideas

## Cross-category combinations
1. **Sloot UI in Costume Contest style** — Take the compression pipeline and skin it with the haunted terminal aesthetic.
2. **Hop protocol as Skeleton Crew App 2** — Use the Lamarr hopping visualizer as one of the two demo apps on the necro-template.
3. **Neural seed + hopping visualization** — Frankenstein entry that encodes messages into seeds that hop frequencies.
4. **Shared UI package** — Extract the best components from Costume Contest or Resurrection into the Skeleton Crew `packages/ui`.

## Quick repo creation commands (run locally)
```bash
# Resurrection
mkdir sloot-reborn && cp -r kiroween-templates/resurrection-sloot/. sloot-reborn/
cd sloot-reborn && git init && npx create-next-app@latest . --typescript --tailwind --app --src-dir --import-alias "@/*"

# Frankenstein
mkdir lamarr-link && cp -r kiroween-templates/frankenstein-lamarr/. lamarr-link/
# then create-next-app

# Skeleton Crew (monorepo)
mkdir necro-template && cp -r kiroween-templates/skeleton-crew/. necro-template/
cd necro-template && pnpm create turbo@latest

# Costume Contest
mkdir haunted-terminal && cp -r kiroween-templates/costume-contest/. haunted-terminal/
# then create-next-app
```

## Kiro first prompts to paste
- "Read the specs in specs/ and implement the compression pipeline according to the design."
- "Follow the steering files in .kiro/steering/ and build the hop visualizer."
- "Create the monorepo structure from structure.md and implement both demo apps."
