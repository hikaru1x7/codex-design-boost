# Codex Design Boost

Fix messy Codex designs with one small, plain-text skill.

**Small instructions. Cleaner designs. No extra machinery.**

Too many boxes. Uneven spacing. Misaligned text. Decoration that gets in the way.

Codex Design Boost gives your agent a short set of design rules: remove visual noise, align related elements, use color consistently, and inspect the actual result—not just the code.

Built to make a noticeable difference without a heavyweight setup. The author created it after repeatedly finding Codex's visual output frustrating, and reports a substantial improvement in their own workflow. That is personal experience, not a controlled benchmark.

An instruction-only AI agent skill for UI design cleanup, frontend polish, typography, spacing, alignment, color consistency, and visual review.

## What it does

- Removes unnecessary decoration without losing useful information.
- Improves spacing, alignment, typography, and color consistency.
- Preserves your content, functionality, and chosen design direction.
- Calls for rendered measurements and visual checks before and after changes.
- Covers interfaces, diagrams, documents, images, and video—not just websites.

One short instruction file. No bundled engine, scripts, templates, or required companion skills. Easy to read before installing, with a small instruction footprint. Rendering, measurements, and visual review still take time and tokens and require suitable tools.

## When to use it

- "Clean up this AI-generated UI without changing its functionality."
- "Fix inconsistent spacing, padding, alignment, and typography."
- "Reduce visual clutter and unnecessary cards or borders."
- "Polish an existing frontend while preserving its design system."
- "Review rendered layouts for clipped text, overlap, and inconsistent spacing."
- "Make diagrams, slides, or reports visually consistent."

Choose this skill for compact, design-system-neutral guidance with rendered checks. It is not a component library, a palette database, a full UX audit, or a replacement for a browser or document renderer. Read the complete [skill instructions](skills/design-quality/SKILL.md) before installing.

## Install

Ask Codex:

```text
Use $skill-installer to install design-quality from
https://github.com/hikaru1x7/codex-design-boost/tree/main/skills/design-quality
```

If you already have a skill named `design-quality`, review it before replacing anything. Avoid installing duplicate copies. If the new skill does not appear, restart Codex. See the [official skill documentation](https://learn.chatgpt.com/docs/build-skills).

## Use

```text
Use $design-quality to clean up this page. Keep the content and functionality,
improve spacing and alignment, remove unnecessary decoration, and inspect
the rendered result at the target screen sizes.
```

The repository is **Codex Design Boost**. The installed skill remains **`design-quality`**. Its design instructions are not tied to a particular model; setup and results in other agents have not been verified.

## Expectations

This is a compact design discipline, not a new model or an automatic quality guarantee. Results depend on the model, task, existing design, and available inspection tools. It does not certify accessibility or claim benchmarked superiority over other agents or skills.

Community project. Not affiliated with or endorsed by OpenAI.

## Free to use

Released under [CC0 1.0 Universal](LICENSE). Use, modify, redistribute, or sell it, including in commercial projects. No attribution required. Provided as-is, without warranties. See the [CC0 summary](https://creativecommons.org/publicdomain/zero/1.0/).
